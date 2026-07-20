---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# LSP - Princípio da Substituição de Liskov

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Subtipos devem substituir o tipo base sem quebrar expectativas.

## O que o princípio diz?

Subtipos devem substituir o tipo base sem quebrar expectativas. Exige compatibilidade de contrato, pré-condições, pós-condições e invariantes.

## Qual problema evita?

Evita hierarquias corretas na sintaxe, mas erradas na semântica.

## Como aplicar?

A subclasse preserva as promessas do tipo base.

## Exemplo prático

Se Ave.Voar é obrigatório, Pinguim não é subtipo válido desse contrato.

## Sinais de violação

- Responsabilidades misturadas ou dependências rígidas.
- Contratos que forçam comportamento inadequado ou surpreendem o consumidor.

## Benefícios

Polimorfismo confiável.

## Limitações e trade-offs

Pode exigir remodelar hierarquias.

## Relações com outros conceitos

Herança, contratos e Design by Contract.

## Dúvidas

- Consigo explicar **LSP - Princípio da Substituição de Liskov** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Robert C. Martin — *Agile Software Development: Principles, Patterns, and Practices*
- Martin Fowler — *Refactoring*
- Documentação oficial da linguagem e do runtime utilizados.
