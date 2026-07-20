---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Deadlock

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Bloqueio permanente causado por tarefas que aguardam recursos mantidos umas pelas outras.

## O que é?

Ocorre quando duas ou mais execuções formam um ciclo de espera e nenhuma consegue continuar.

## Como ocorre?

Normalmente envolve exclusão mútua, posse e espera, falta de preempção e espera circular.

## Principais causas

Ordem inconsistente de aquisição de locks, locks aninhados, transações longas e recursos compartilhados em excesso.

## Como identificar?

Analise thread dumps, lock graphs, sessões bloqueadas, timeouts e métricas de espera.

## Exemplo prático

A thread A segura X e espera Y; a thread B segura Y e espera X.

## Impactos

Travamento, aumento de latência, filas acumuladas e indisponibilidade parcial ou total.

## Como prevenir?

Adote uma ordem global de aquisição de locks, mantenha regiões críticas curtas, use timeout e reduza estado compartilhado.

## Como corrigir?

Interrompa uma das operações, libere recursos e elimine o ciclo de dependência no código ou nas transações.

## Relações com outros conceitos

Concorrência, locks, transações, isolamento e starvation.

## Dúvidas

- Consigo explicar **Deadlock** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Robert C. Martin — *Agile Software Development: Principles, Patterns, and Practices*
- Martin Fowler — *Refactoring*
- Documentação oficial da linguagem e do runtime utilizados.
