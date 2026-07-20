---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Plano de execução

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Estratégia escolhida pelo otimizador para executar SQL.

## O que é?

Descreve scans, seeks, joins, sorts e estimativas de linhas.

## Como afeta a performance?

Operadores, estimativas e acesso físico determinam I/O, CPU e memória.

## Como identificar?

Use EXPLAIN ou plano real e compare estimado com realizado.

## Exemplo prático

Plano revela table scan em tabela grande por falta de índice.

## Estratégias de otimização

Atualize estatísticas, ajuste consulta, tipos, filtros e índices.

## Trade-offs

Planos variam com dados, parâmetros e estatísticas.

## Erros comuns

Otimizar só pelo custo estimado ou criar índice para cada consulta.

## Relações com outros conceitos

Índices, estatísticas, cardinalidade e joins.

## Dúvidas

- Consigo explicar **Plano de execução** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Markus Winand — *SQL Performance Explained*
- Documentação oficial do SGBD utilizado.
