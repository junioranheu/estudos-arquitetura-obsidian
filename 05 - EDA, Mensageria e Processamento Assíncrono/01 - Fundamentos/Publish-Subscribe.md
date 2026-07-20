---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Publish-Subscribe

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Uma publicação é entregue a múltiplos assinantes.

## O que é?

Separa publicador de assinantes e permite fan-out de eventos.

## Papel no fluxo de mensageria

Permite novas reações sem mudar o produtor.

## Como funciona?

Publicador envia a tópico ou exchange; cada assinatura recebe sua cópia.

## Exemplo prático

PedidoCriado chega a estoque, analytics e notificações.

## Decisões de configuração

- Contrato e versionamento.
- Durabilidade, confirmação, retry e timeout.
- Idempotência e observabilidade.

## Garantias e limitações

Mais consumidores e falhas independentes.

## Falhas e cuidados

Mais consumidores e falhas independentes.

Evite quando apenas um trabalhador deve processar cada tarefa.

## Relações com outros conceitos

Queue, topic, exchange, eventos e fan-out.

## Dúvidas

- Consigo explicar **Publish-Subscribe** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Gregor Hohpe e Bobby Woolf — *Enterprise Integration Patterns*
- Ben Stopford — *Designing Event-Driven Systems*
- Documentação oficial do RabbitMQ.
