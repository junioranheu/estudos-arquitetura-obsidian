---
tipo: conceito
status: nao-iniciado
dificuldade: avancado
tags: []
---

# Explique Saga

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Resposta em 30 segundos

Transação distribuída como sequência de transações locais e compensações.

Viabiliza workflows distribuídos longos.

## Resposta completa

Mantém consistência eventual sem bloquear todos os serviços.

Cada etapa confirma localmente e aciona a próxima; falhas compensam quando possível.

Principal cuidado: Estados intermediários e compensações imperfeitas.

## Exemplo prático

Pedido reserva estoque, cobra e agenda entrega; falha de cobrança libera estoque.

## Principais benefícios

Autonomia e ausência de locks distribuídos longos.

## Trade-offs e limitações

Estados intermediários e compensações imperfeitas.

## Quando faz sentido?

Processos entre serviços com etapas independentes.

## Erros comuns na resposta

- Definir somente por pastas ou ferramentas.
- Ignorar contexto e trade-offs.
- Não apresentar exemplo concreto.

## Perguntas de aprofundamento

- Consigo explicar **Explique Saga** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Conceitos relacionados

Orquestração, coreografia, outbox e idempotência.

## Referências

- Consulte a nota principal do conceito neste vault.
- Revise os livros e documentações indicados na respectiva área.
