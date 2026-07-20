---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Builder

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Intenção

Permitir a construção gradual e validada de objetos complexos.

## Problema

Evita construtores telescópicos e torna criação legível.

## Estrutura e participantes

Builder, ConcreteBuilder, produto, cliente e, opcionalmente, Director.

## Como funciona?

O cliente configura o builder e solicita Build; um director pode coordenar sequências.

## Exemplo prático

PedidoBuilder.ComCliente(...).AdicionarItem(...).Build().

## Quando usar?

Objetos complexos, imutáveis ou com muitas combinações.

## Quando evitar?

Evite para objetos simples com poucos parâmetros.

## Vantagens

Construção clara e validação centralizada.

## Desvantagens e trade-offs

Mais classes e possível duplicação.

## Padrões relacionados

Factory Method, Abstract Factory e Fluent Interface.

## Dúvidas

- Consigo explicar **Builder** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Fowler — *Refactoring*
- Robert C. Martin — *Clean Code*
- Gamma et al. — *Design Patterns*.
