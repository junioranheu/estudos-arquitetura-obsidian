---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Abstract Factory

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Intenção

Fornecer uma interface para criar famílias de produtos compatíveis.

## Problema

Mantém consistência entre produtos e isola a escolha de variante.

## Estrutura e participantes

AbstractFactory, ConcreteFactory, AbstractProduct, ConcreteProduct e cliente.

## Como funciona?

O cliente usa uma fábrica abstrata; cada fábrica concreta cria produtos que funcionam juntos.

## Exemplo prático

Fábrica Windows cria BotaoWindows e JanelaWindows; fábrica macOS cria equivalentes.

## Quando usar?

Alternância entre famílias inteiras de objetos.

## Quando evitar?

Evite quando há apenas um produto simples.

## Vantagens

Consistência e desacoplamento de concretos.

## Desvantagens e trade-offs

Novo tipo de produto exige alterar todas as fábricas.

## Padrões relacionados

Factory Method, Builder, Prototype e DI.

## Dúvidas

- Consigo explicar **Abstract Factory** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Fowler — *Refactoring*
- Robert C. Martin — *Clean Code*
- Gamma et al. — *Design Patterns*.
