---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Índices compostos

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Índices formados por duas ou mais colunas em ordem específica.

## O que é?

Atendem filtros, joins e ordenações que usam seu prefixo.

## Como afeta a performance?

A ordem das colunas é decisiva; igualdade costuma vir antes de intervalo e ordenação.

## Como identificar?

Analise planos, consultas frequentes e índices existentes.

## Exemplo prático

INDEX(cliente_id, data_criacao) atende pedidos de um cliente por data.

## Estratégias de otimização

Escolha a menor combinação que atende filtros e ordenação.

## Trade-offs

Mais custo de escrita e armazenamento.

## Erros comuns

Inverter a ordem sem critério ou duplicar prefixos.

## Relações com outros conceitos

Seletividade, leftmost prefix e covering index.

## Dúvidas

- Consigo explicar **Índices compostos** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Markus Winand — *SQL Performance Explained*
- Documentação oficial do SGBD utilizado.
