---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Explique CQRS

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Resposta em 30 segundos

Separa modelos de escrita e leitura conforme suas necessidades.

Evita deformar o modelo de domínio para atender relatórios.

## Resposta completa

Comandos alteram agregados; consultas usam modelos otimizados, sem exigir o mesmo formato.

Handlers carregam agregados e preservam invariantes; projeções atendem leituras.

Principal cuidado: Consistência eventual e duplicação de modelos.

## Exemplo prático

ConfirmarPedido altera o agregado; uma projeção lista pedidos por cliente.

## Principais benefícios

Modelos focados e consultas eficientes.

## Trade-offs e limitações

Consistência eventual e duplicação de modelos.

## Quando faz sentido?

Escrita rica e leitura muito diferente.

## Erros comuns na resposta

- Definir somente por pastas ou ferramentas.
- Ignorar contexto e trade-offs.
- Não apresentar exemplo concreto.

## Perguntas de aprofundamento

- Consigo explicar **Explique CQRS** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Conceitos relacionados

DDD, comandos, projeções, eventos e Event Sourcing.

## Referências

- Consulte a nota principal do conceito neste vault.
- Revise os livros e documentações indicados na respectiva área.
