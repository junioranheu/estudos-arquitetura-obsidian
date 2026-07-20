---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: []
---

# Polimorfismo

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Capacidade de tratar implementações diferentes por um mesmo contrato.

## O que é?

A mesma operação produz comportamentos distintos conforme o tipo concreto.

## Por que é importante?

Substitui condicionais extensas e permite extensão.

## Como funciona?

O consumidor usa interface ou tipo base e o despacho seleciona a implementação.

## Exemplo prático

Checkout chama IMetodoPagamento.Processar sem saber se é Pix ou cartão.

## Aplicações

Comportamentos variáveis sob um contrato comum.

## Limitações e cuidados

Mais indireção e fluxo menos óbvio.

Evite quando há só uma implementação ou diferenças essenciais são ocultadas.

## Relações com outros conceitos

Interfaces, herança, OCP, LSP e Strategy.

## Dúvidas

- Consigo explicar **Polimorfismo** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Robert C. Martin — *Agile Software Development: Principles, Patterns, and Practices*
- Martin Fowler — *Refactoring*
- Documentação oficial da linguagem e do runtime utilizados.
