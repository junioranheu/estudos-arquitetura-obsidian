---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Routing Key

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Chave usada pelo RabbitMQ para decidir o roteamento.

## O que é?

É comparada aos bindings de exchanges direct ou topic.

## Papel no fluxo de mensageria

Permite roteamento sem conhecer filas.

## Como funciona?

Producer envia a chave; exchange aplica igualdade ou padrões * e #.

## Exemplo prático

pedido.criado combina com pedido.*.

## Decisões de configuração

- Contrato e versionamento.
- Durabilidade, confirmação, retry e timeout.
- Idempotência e observabilidade.

## Garantias e limitações

Convenções ruins geram mensagens não roteadas.

## Falhas e cuidados

Convenções ruins geram mensagens não roteadas.

Evite regras complexas ou dados sensíveis na chave.

## Relações com outros conceitos

Exchange, binding, topic e direct.

## Dúvidas

- Consigo explicar **Routing Key** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Gregor Hohpe e Bobby Woolf — *Enterprise Integration Patterns*
- Ben Stopford — *Designing Event-Driven Systems*
- Documentação oficial do RabbitMQ.
