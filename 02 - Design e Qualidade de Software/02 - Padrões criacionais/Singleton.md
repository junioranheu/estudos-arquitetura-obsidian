---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Singleton

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Intenção

Controlar para que apenas uma instância exista no escopo definido.

## Problema

Útil quando uma instância única representa legitimamente o recurso.

## Estrutura e participantes

Singleton e seus consumidores; em DI, o container controla a instância.

## Como funciona?

A classe restringe construção ou o container de DI gerencia o ciclo singleton.

## Exemplo prático

Configuração imutável compartilhada por toda a aplicação.

## Quando usar?

Configuração, caches controlados e serviços thread-safe.

## Quando evitar?

Evite como estado global mutável ou service locator.

## Vantagens

Economia de recursos e identidade única.

## Desvantagens e trade-offs

Acoplamento global, testes difíceis e concorrência.

## Padrões relacionados

DI, Service Locator, escopos e estado global.

## Dúvidas

- Consigo explicar **Singleton** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Fowler — *Refactoring*
- Robert C. Martin — *Clean Code*
- Gamma et al. — *Design Patterns*.
