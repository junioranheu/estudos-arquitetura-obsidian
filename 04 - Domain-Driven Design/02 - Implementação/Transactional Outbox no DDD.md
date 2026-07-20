---
tipo: conceito
status: nao-iniciado
dificuldade: avancado
tags: []
---

# Transactional Outbox no DDD

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Persiste mudança de negócio e mensagem na mesma transação local.

## Definição

Evita dual write entre banco e broker ao registrar mensagens em uma outbox.

## Papel no DDD

Evita perder mensagem após mudança confirmada.

## Como identificar ou modelar?

A aplicação salva agregado e outbox; um worker publica e marca o item.

## Exemplo de domínio

Confirmar pedido grava PedidoConfirmado junto com o novo status.

## Regras e cuidados

At-least-once, idempotência, limpeza e monitoramento.

Evite sem broker ou sem transação local adequada.

## Erros comuns

- Escolher tecnologia antes de entender o problema.
- Ignorar volume, falhas ou operação.
- Não registrar hipóteses e consequências.

## Relações com outros conceitos

Eventos, inbox, CDC, idempotência e mensageria.

## Dúvidas

- Consigo explicar **Transactional Outbox no DDD** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Eric Evans — *Domain-Driven Design*
- Vaughn Vernon — *Implementing Domain-Driven Design*
- Vaughn Vernon — *Domain-Driven Design Distilled*.
