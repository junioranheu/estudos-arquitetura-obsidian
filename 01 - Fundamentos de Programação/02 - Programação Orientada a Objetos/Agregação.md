---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: []
---

# Agregação

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Relação todo-parte em que a parte pode existir independentemente do todo.

## O que é?

É uma associação em que o objeto reúne partes sem controlar necessariamente seu ciclo de vida.

## Por que é importante?

Modela pertencimento fraco sem impor ciclo de vida.

## Como funciona?

O agregador mantém referências a partes que podem sobreviver ou ser compartilhadas.

## Exemplo prático

Um Time agrega Jogadores; o jogador existe antes e depois do time.

## Aplicações

Quando a parte possui identidade e existência próprias.

## Limitações e cuidados

Pode ser confundida com associação ou composição.

Evite usar agregação para qualquer referência sem semântica todo-parte.

## Relações com outros conceitos

Associação, composição, entidades e agregados de DDD.

## Dúvidas

- Consigo explicar **Agregação** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Robert C. Martin — *Agile Software Development: Principles, Patterns, and Practices*
- Martin Fowler — *Refactoring*
- Documentação oficial da linguagem e do runtime utilizados.
