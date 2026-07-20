---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Objetos ricos e objetos anêmicos

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Objetos ricos combinam estado e regras; anêmicos carregam dados e delegam comportamento.

## Conceitos comparados

O modelo rico protege invariantes nas entidades; o anêmico usa entidades semelhantes a DTOs.

## Principais diferenças

No rico, comandos são métodos do domínio; no anêmico, serviços manipulam propriedades.

## Exemplo prático

Pedido.AdicionarItem(...) versus pedido.Itens.Add(...) seguido de validações externas.

## Quando cada abordagem faz sentido?

Rico em domínios complexos; anêmico em CRUD simples.

## Vantagens e desvantagens

- Benefícios: Rico localiza invariantes; anêmico é simples inicialmente.
- Custos: Rico exige design; anêmico pode espalhar regras.

## Critérios de decisão

- Complexidade do domínio.
- Frequência e risco das mudanças.
- Necessidade de consistência, escala e operação.

## Relações com outros conceitos

DDD, encapsulamento, entidades e CRUD.

## Dúvidas

- Consigo explicar **Objetos ricos e objetos anêmicos** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Robert C. Martin — *Agile Software Development: Principles, Patterns, and Practices*
- Martin Fowler — *Refactoring*
- Documentação oficial da linguagem e do runtime utilizados.
