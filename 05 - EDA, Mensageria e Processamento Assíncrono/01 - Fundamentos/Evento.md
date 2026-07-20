---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Evento

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Mensagem imutável que registra um fato ocorrido.

## O que é?

Informa algo no passado e pode interessar a zero ou vários consumidores.

## Papel no fluxo de mensageria

Desacopla reações e permite extensão.

## Como funciona?

Produtor publica sem conhecer reações; consumidores processam independentemente.

## Exemplo prático

PedidoConfirmado informa que o pedido foi confirmado.

## Decisões de configuração

- Contrato e versionamento.
- Durabilidade, confirmação, retry e timeout.
- Idempotência e observabilidade.

## Garantias e limitações

Consistência eventual, versão, ordem e duplicidade.

## Falhas e cuidados

Consistência eventual, versão, ordem e duplicidade.

Evite eventos genéricos ou usados como RPC disfarçado.

## Relações com outros conceitos

Comando, pub/sub, event sourcing e integration event.

## Dúvidas

- Consigo explicar **Evento** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Gregor Hohpe e Bobby Woolf — *Enterprise Integration Patterns*
- Ben Stopford — *Designing Event-Driven Systems*
- Documentação oficial do RabbitMQ.
