---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Producer e Consumer

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Producer publica mensagens; consumer recebe e processa.

## O que é?

São papéis separados por um canal ou broker.

## Papel no fluxo de mensageria

Permite escala e evolução independentes.

## Como funciona?

Producer serializa e envia; consumer valida, executa e confirma.

## Exemplo prático

Pedidos publica PedidoCriado; Estoque consome e reserva.

## Decisões de configuração

- Contrato e versionamento.
- Durabilidade, confirmação, retry e timeout.
- Idempotência e observabilidade.

## Garantias e limitações

Contratos, retries, ordem e observabilidade.

## Falhas e cuidados

Contratos, retries, ordem e observabilidade.

Evite consumers não idempotentes e producers acoplados a consumidores.

## Relações com outros conceitos

Broker, ack, consumer group e idempotência.

## Dúvidas

- Consigo explicar **Producer e Consumer** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Gregor Hohpe e Bobby Woolf — *Enterprise Integration Patterns*
- Ben Stopford — *Designing Event-Driven Systems*
- Documentação oficial do RabbitMQ.
