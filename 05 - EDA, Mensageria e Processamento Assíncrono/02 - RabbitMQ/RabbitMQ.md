---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# RabbitMQ

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Broker orientado a filas e roteamento.

## O que é?

Implementa AMQP e oferece exchanges, queues, bindings, ack e dead-lettering.

## Papel no fluxo de mensageria

Adequado para work queues e roteamento flexível.

## Como funciona?

Producers publicam em exchanges; mensagens chegam a filas e consumers.

## Exemplo prático

API publica job; workers processam com ack e DLQ.

## Decisões de configuração

- Contrato e versionamento.
- Durabilidade, confirmação, retry e timeout.
- Idempotência e observabilidade.

## Garantias e limitações

Operação de cluster, tuning e duplicidade.

## Falhas e cuidados

Operação de cluster, tuning e duplicidade.

Evite como histórico longo de eventos ou analytics massivo.

## Relações com outros conceitos

AMQP, exchange, queue, Kafka e DLQ.

## Dúvidas

- Consigo explicar **RabbitMQ** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Gregor Hohpe e Bobby Woolf — *Enterprise Integration Patterns*
- Ben Stopford — *Designing Event-Driven Systems*
- Documentação oficial do RabbitMQ.
