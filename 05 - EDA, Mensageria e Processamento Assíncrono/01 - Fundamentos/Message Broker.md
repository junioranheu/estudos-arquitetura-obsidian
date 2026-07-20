---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Message Broker

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Infraestrutura que recebe, armazena, roteia e entrega mensagens.

## O que é?

Desacopla produtores e consumidores e oferece filas e pub/sub.

## Papel no fluxo de mensageria

Absorve picos e desacopla ritmos.

## Como funciona?

Produtores publicam em destinos; o broker persiste e encaminha.

## Exemplo prático

RabbitMQ roteia evento para faturamento e notificações.

## Decisões de configuração

- Contrato e versionamento.
- Durabilidade, confirmação, retry e timeout.
- Idempotência e observabilidade.

## Garantias e limitações

Operação adicional, latência e duplicidade.

## Falhas e cuidados

Operação adicional, latência e duplicidade.

Evite em fluxo simples que exige resposta imediata.

## Relações com outros conceitos

Queue, exchange, RabbitMQ, Kafka e delivery semantics.

## Dúvidas

- Consigo explicar **Message Broker** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Gregor Hohpe e Bobby Woolf — *Enterprise Integration Patterns*
- Ben Stopford — *Designing Event-Driven Systems*
- Documentação oficial do RabbitMQ.
