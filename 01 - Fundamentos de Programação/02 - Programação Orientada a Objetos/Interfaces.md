---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: []
---

# Interfaces

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Contratos que descrevem capacidades sem definir uma implementação concreta.

## O que é?

Declaram membros que tipos diferentes podem implementar de formas próprias.

## Por que é importante?

Reduz dependência de concretos e melhora testes.

## Como funciona?

Consumidores dependem do contrato e recebem implementações por composição ou DI.

## Exemplo prático

INotificador possui Enviar; EmailNotifier e SmsNotifier implementam.

## Aplicações

Múltiplas implementações ou fronteiras explícitas.

## Limitações e cuidados

Interfaces excessivas aumentam indireção.

Evite criar interface para toda classe sem motivo.

## Relações com outros conceitos

DIP, ISP, polimorfismo e injeção de dependência.

## Dúvidas

- Consigo explicar **Interfaces** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Robert C. Martin — *Agile Software Development: Principles, Patterns, and Practices*
- Martin Fowler — *Refactoring*
- Documentação oficial da linguagem e do runtime utilizados.
