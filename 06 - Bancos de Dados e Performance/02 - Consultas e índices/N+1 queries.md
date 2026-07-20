---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# N+1 queries

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Uma consulta inicial dispara outra consulta para cada item retornado.

## O que é?

Surge frequentemente por lazy loading ou acesso a relacionamentos em loops.

## Como ocorre?

A aplicação busca N registros e consulta dependências individualmente.

## Principais causas

Lazy loading, serialização automática de navegações e consultas dentro de loops.

## Como identificar?

Habilite logs SQL ou tracing e conte quantas consultas são executadas por requisição.

## Exemplo prático

Buscar 100 pedidos e consultar o cliente de cada um gera 101 queries.

## Impactos

Muitos round trips, alta latência, pressão no pool de conexões e sobrecarga do banco.

## Como prevenir?

Use projeções, joins ou Include adequados, carregamento em lote e DataLoader.

## Como corrigir?

Reescreva o acesso para buscar somente os dados necessários em uma ou poucas consultas.

## Relações com outros conceitos

ORM, eager loading, projeção, joins e DataLoader.

## Dúvidas

- Consigo explicar **N+1 queries** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Markus Winand — *SQL Performance Explained*
- Documentação oficial do SGBD utilizado.
