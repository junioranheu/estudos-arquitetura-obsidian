---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Mensagem

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Envelope de dados transportado entre componentes.

## O que é?

Pode representar comando, evento, resposta ou documento.

## Papel no fluxo de mensageria

Padroniza comunicação assíncrona.

## Como funciona?

Possui payload e metadados como id, tipo, timestamp, correlação e versão.

## Exemplo prático

JSON do tipo PedidoConfirmado publicado no broker.

## Decisões de configuração

- Contrato e versionamento.
- Durabilidade, confirmação, retry e timeout.
- Idempotência e observabilidade.

## Garantias e limitações

Serialização, versionamento e duplicidade.

## Falhas e cuidados

Serialização, versionamento e duplicidade.

Evite payloads enormes, contratos implícitos e dados sensíveis.

## Relações com outros conceitos

Comando, evento, broker e contrato.

## Dúvidas

- Consigo explicar **Mensagem** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Gregor Hohpe e Bobby Woolf — *Enterprise Integration Patterns*
- Ben Stopford — *Designing Event-Driven Systems*
- Documentação oficial do RabbitMQ.
