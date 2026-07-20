---
tipo: conceito
status: nao-iniciado
dificuldade: avancado
tags: []
---

# Explique Event-Driven Architecture

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Resposta em 30 segundos

Componentes reagem a fatos publicados como eventos.

Permite integração assíncrona e absorção de picos.

## Resposta completa

Desacopla produtores e consumidores no tempo e no espaço.

Produtor publica fato; broker ou event bus entrega a consumidores independentes.

Principal cuidado: Consistência eventual, duplicidade, ordem e observabilidade.

## Exemplo prático

PedidoCriado dispara estoque, cobrança e notificação.

## Principais benefícios

Baixo acoplamento, escala e extensibilidade.

## Trade-offs e limitações

Consistência eventual, duplicidade, ordem e observabilidade.

## Quando faz sentido?

Fluxos assíncronos e integração entre domínios.

## Erros comuns na resposta

- Definir somente por pastas ou ferramentas.
- Ignorar contexto e trade-offs.
- Não apresentar exemplo concreto.

## Perguntas de aprofundamento

- Consigo explicar **Explique Event-Driven Architecture** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Conceitos relacionados

Mensageria, pub/sub, outbox, idempotência e CQRS.

## Referências

- Consulte a nota principal do conceito neste vault.
- Revise os livros e documentações indicados na respectiva área.
