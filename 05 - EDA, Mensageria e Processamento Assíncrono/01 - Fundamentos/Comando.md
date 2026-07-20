---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Comando

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Mensagem que expressa intenção de solicitar uma ação.

## O que é?

É imperativo, direcionado a um responsável e pode ser aceito ou rejeitado.

## Papel no fluxo de mensageria

Torna intenção e responsabilidade explícitas.

## Como funciona?

Um emissor envia; um handler valida e executa a mudança.

## Exemplo prático

ConfirmarPedido solicita confirmação de um pedido.

## Decisões de configuração

- Contrato e versionamento.
- Durabilidade, confirmação, retry e timeout.
- Idempotência e observabilidade.

## Garantias e limitações

Pode falhar, expirar ou duplicar.

## Falhas e cuidados

Pode falhar, expirar ou duplicar.

Evite nomear como comando um fato já ocorrido.

## Relações com outros conceitos

Evento, mensagem, handler e idempotência.

## Dúvidas

- Consigo explicar **Comando** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Gregor Hohpe e Bobby Woolf — *Enterprise Integration Patterns*
- Ben Stopford — *Designing Event-Driven Systems*
- Documentação oficial do RabbitMQ.
