---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Exchange

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Componente do RabbitMQ que recebe mensagens e as roteia para filas.

## O que é?

Não armazena mensagens; aplica bindings conforme seu tipo.

## Papel no fluxo de mensageria

Desacopla producers dos nomes das filas.

## Como funciona?

Producer publica com routing key; bindings determinam filas.

## Exemplo prático

Topic exchange envia pedido.criado para pedido.*.

## Decisões de configuração

- Contrato e versionamento.
- Durabilidade, confirmação, retry e timeout.
- Idempotência e observabilidade.

## Garantias e limitações

Configuração errada pode descartar mensagens.

## Falhas e cuidados

Configuração errada pode descartar mensagens.

Evite topologia complexa sem documentação.

## Relações com outros conceitos

Queue, binding, routing key e RabbitMQ.

## Dúvidas

- Consigo explicar **Exchange** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Gregor Hohpe e Bobby Woolf — *Enterprise Integration Patterns*
- Ben Stopford — *Designing Event-Driven Systems*
- Documentação oficial do RabbitMQ.
