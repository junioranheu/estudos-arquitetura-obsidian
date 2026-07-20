---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Starvation

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Situação em que uma tarefa fica indefinidamente sem acesso ao recurso necessário.

## O que é?

Ocorre quando prioridades ou contenção fazem outras tarefas serem sempre atendidas primeiro.

## Como ocorre?

A tarefa permanece pronta, mas perde repetidamente a disputa por CPU, lock, conexão ou fila.

## Principais causas

Prioridade rígida, locks não justos, filas sem envelhecimento e recursos subdimensionados.

## Como identificar?

Observe itens antigos em filas, tarefas que nunca progridem e tempos de espera muito superiores à média.

## Exemplo prático

Requisições de baixa prioridade nunca executam porque chegam continuamente requisições prioritárias.

## Impactos

Latência imprevisível, timeouts, perda de SLA e degradação de experiência.

## Como prevenir?

Use políticas justas, aging de prioridade, limites de concorrência e cotas de recurso.

## Como corrigir?

Ajuste escalonamento e prioridades, reduza contenção e garanta oportunidade de execução para todas as classes.

## Relações com outros conceitos

Concorrência, fairness, locks, filas e deadlock.

## Dúvidas

- Consigo explicar **Starvation** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Robert C. Martin — *Agile Software Development: Principles, Patterns, and Practices*
- Martin Fowler — *Refactoring*
- Documentação oficial da linguagem e do runtime utilizados.
