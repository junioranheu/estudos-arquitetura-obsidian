---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Invariantes

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Condições que devem permanecer verdadeiras durante a vida válida de um objeto.

## O que é?

São regras de consistência que nenhuma operação permitida pode violar.

## Por que é importante?

Protegem o domínio contra estados impossíveis.

## Como funciona?

Construtores e métodos validam condições antes de alterar o estado.

## Exemplo prático

Um Pedido finalizado não pode receber novos itens.

## Aplicações

Entidades, value objects, agregados e transações.

## Limitações e cuidados

Invariantes distribuídas exigem consistência eventual.

Evite depender apenas da validação da interface.

## Relações com outros conceitos

Encapsulamento, agregados, validação e transações.

## Dúvidas

- Consigo explicar **Invariantes** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Robert C. Martin — *Agile Software Development: Principles, Patterns, and Practices*
- Martin Fowler — *Refactoring*
- Documentação oficial da linguagem e do runtime utilizados.
