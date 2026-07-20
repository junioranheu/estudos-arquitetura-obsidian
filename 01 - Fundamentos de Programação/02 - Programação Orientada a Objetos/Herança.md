---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: []
---

# Herança

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Mecanismo pelo qual um tipo especializado reutiliza e estende um tipo base.

## O que é?

Modela relação “é um” e permite substituição compatível.

## Por que é importante?

Representa taxonomias estáveis e habilita polimorfismo.

## Como funciona?

A subclasse recebe membros do tipo base e pode adicionar ou sobrescrever comportamento permitido.

## Exemplo prático

Cachorro herda de Animal e implementa EmitirSom.

## Aplicações

Quando existe substituição válida e comportamento comum.

## Limitações e cuidados

Hierarquias frágeis e violações de LSP.

Evite herança apenas para reutilização; prefira composição quando não há “é um”.

## Relações com outros conceitos

Polimorfismo, classes abstratas, LSP e composição.

## Dúvidas

- Consigo explicar **Herança** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Robert C. Martin — *Agile Software Development: Principles, Patterns, and Practices*
- Martin Fowler — *Refactoring*
- Documentação oficial da linguagem e do runtime utilizados.
