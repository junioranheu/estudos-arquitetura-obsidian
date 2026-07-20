---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Fail Fast

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Detectar e comunicar erros cedo e perto da origem.

## O que o princípio diz?

Detectar e comunicar erros cedo e perto da origem. Interrompe a operação assim que uma condição inválida é encontrada.

## Qual problema evita?

Reduz propagação de estado incorreto.

## Como aplicar?

Valida entradas e invariantes antes de trabalho caro ou persistência.

## Exemplo prático

API rejeita identificador inválido antes de consultar dependências.

## Sinais de violação

- Responsabilidades misturadas ou dependências rígidas.
- Contratos que forçam comportamento inadequado ou surpreendem o consumidor.

## Benefícios

Erros claros e menor desperdício.

## Limitações e trade-offs

Falha sem contexto ou recuperação pode reduzir disponibilidade.

## Relações com outros conceitos

Defensive Programming, validação e observabilidade.

## Dúvidas

- Consigo explicar **Fail Fast** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Robert C. Martin — *Agile Software Development: Principles, Patterns, and Practices*
- Martin Fowler — *Refactoring*
- Documentação oficial da linguagem e do runtime utilizados.
