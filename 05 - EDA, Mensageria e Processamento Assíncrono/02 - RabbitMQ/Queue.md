---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Queue

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Estrutura que armazena mensagens até o processamento.

## O que é?

No RabbitMQ, distribui cada mensagem a um consumidor entre os conectados.

## Papel no fluxo de mensageria

Absorve picos e desacopla produção e consumo.

## Como funciona?

Exchange roteia; consumer recebe, processa e envia ack.

## Exemplo prático

Fila gerar-relatorio distribui jobs entre workers.

## Decisões de configuração

- Contrato e versionamento.
- Durabilidade, confirmação, retry e timeout.
- Idempotência e observabilidade.

## Garantias e limitações

Backlog, ordem limitada e poison messages.

## Falhas e cuidados

Backlog, ordem limitada e poison messages.

Evite fila única para trabalhos com requisitos muito diferentes.

## Relações com outros conceitos

Exchange, ack, DLQ e prefetch.

## Dúvidas

- Consigo explicar **Queue** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Gregor Hohpe e Bobby Woolf — *Enterprise Integration Patterns*
- Ben Stopford — *Designing Event-Driven Systems*
- Documentação oficial do RabbitMQ.
