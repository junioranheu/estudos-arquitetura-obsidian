---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Prototype

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Intenção

Produzir objetos por clonagem de um exemplar configurado.

## Problema

Pode reduzir custo de criação e permitir variantes dinâmicas.

## Estrutura e participantes

Prototype, ConcretePrototype e cliente.

## Como funciona?

O protótipo implementa clonagem rasa ou profunda; o cliente ajusta o clone.

## Exemplo prático

Clonar configuração padrão de relatório e alterar filtros.

## Quando usar?

Objetos caros de construir ou altamente configuráveis.

## Quando evitar?

Evite quando cópia profunda é ambígua ou contém recursos externos.

## Vantagens

Criação rápida e menor dependência de concretos.

## Desvantagens e trade-offs

Risco de compartilhar referências mutáveis.

## Padrões relacionados

Memento, Factory Method, serialização e imutabilidade.

## Dúvidas

- Consigo explicar **Prototype** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Fowler — *Refactoring*
- Robert C. Martin — *Clean Code*
- Gamma et al. — *Design Patterns*.
