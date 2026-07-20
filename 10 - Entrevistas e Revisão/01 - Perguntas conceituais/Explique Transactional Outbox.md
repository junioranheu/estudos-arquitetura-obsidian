---
tipo: conceito
status: nao-iniciado
dificuldade: avancado
tags: []
---

# Explique Transactional Outbox

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Resposta em 30 segundos

Persiste mudança de negócio e mensagem na mesma transação local.

Evita perder mensagem após mudança confirmada.

## Resposta completa

Evita dual write entre banco e broker ao registrar mensagens em uma outbox.

A aplicação salva agregado e outbox; um worker publica e marca o item.

Principal cuidado: At-least-once, idempotência, limpeza e monitoramento.

## Exemplo prático

Confirmar pedido grava PedidoConfirmado junto com o novo status.

## Principais benefícios

Confiabilidade e desacoplamento.

## Trade-offs e limitações

At-least-once, idempotência, limpeza e monitoramento.

## Quando faz sentido?

Integração assíncrona confiável sem transação distribuída.

## Erros comuns na resposta

- Definir somente por pastas ou ferramentas.
- Ignorar contexto e trade-offs.
- Não apresentar exemplo concreto.

## Perguntas de aprofundamento

- Consigo explicar **Explique Transactional Outbox** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Conceitos relacionados

Eventos, inbox, CDC, idempotência e mensageria.

## Referências

- Consulte a nota principal do conceito neste vault.
- Revise os livros e documentações indicados na respectiva área.
