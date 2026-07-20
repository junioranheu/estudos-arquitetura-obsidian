---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Factory Method

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Intenção

Definir um ponto de criação substituível para produtos relacionados.

## Problema

Isola criação e facilita extensão de produtos.

## Estrutura e participantes

Creator, ConcreteCreator, Product e ConcreteProduct.

## Como funciona?

O fluxo chama um método fábrica implementado por criadores concretos.

## Exemplo prático

Uma importação seleciona CsvParser ou JsonParser por fábrica.

## Quando usar?

Criação variável dentro de um fluxo maior.

## Quando evitar?

Evite quando a construção direta é simples e estável.

## Vantagens

Menor acoplamento e extensão controlada.

## Desvantagens e trade-offs

Pode gerar hierarquias e classes adicionais.

## Padrões relacionados

Abstract Factory, Simple Factory e Template Method.

## Dúvidas

- Consigo explicar **Factory Method** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Fowler — *Refactoring*
- Robert C. Martin — *Clean Code*
- Gamma et al. — *Design Patterns*.
