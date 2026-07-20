---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: []
---

# Classes abstratas

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Classes não instanciáveis que fornecem contrato e implementação compartilhada.

## O que é?

Definem membros comuns e podem exigir que subclasses implementem partes específicas.

## Por que é importante?

Reutiliza comportamento quando existe especialização real.

## Como funciona?

Subclasses herdam estado e comportamento base e completam pontos abstratos.

## Exemplo prático

FormaPagamento define Validar e exige Processar; Pix e Cartão implementam.

## Aplicações

Tipos com estado e comportamento comum estável.

## Limitações e cuidados

Aumenta acoplamento por herança.

Evite hierarquias profundas ou herança só para reaproveitar código.

## Relações com outros conceitos

Herança, interfaces, Template Method e polimorfismo.

## Dúvidas

- Consigo explicar **Classes abstratas** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Robert C. Martin — *Agile Software Development: Principles, Patterns, and Practices*
- Martin Fowler — *Refactoring*
- Documentação oficial da linguagem e do runtime utilizados.
