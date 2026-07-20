---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: []
---

# Composição

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Relação todo-parte forte em que o todo controla o ciclo de vida das partes.

## O que é?

A parte pertence ao todo e normalmente não faz sentido isoladamente.

## Por que é importante?

Expressa invariantes e ownership forte.

## Como funciona?

O objeto composto cria, coordena e descarta suas partes.

## Exemplo prático

Pedido é composto por ItensPedido; removido o pedido, os itens deixam de existir naquele contexto.

## Aplicações

Quando as partes não têm identidade útil fora do todo.

## Limitações e cuidados

Pode concentrar responsabilidade demais no objeto raiz.

Evite quando a parte precisa ser compartilhada ou sobreviver sozinha.

## Relações com outros conceitos

Agregação, associação, agregados e encapsulamento.

## Dúvidas

- Consigo explicar **Composição** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Robert C. Martin — *Agile Software Development: Principles, Patterns, and Practices*
- Martin Fowler — *Refactoring*
- Documentação oficial da linguagem e do runtime utilizados.
