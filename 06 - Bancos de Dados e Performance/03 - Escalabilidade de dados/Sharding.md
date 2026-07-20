---
tipo: conceito
status: nao-iniciado
dificuldade: avancado
tags: []
---

# Sharding

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Distribuição horizontal de dados entre bancos independentes.

## O que é?

Cada shard armazena uma parte definida por uma chave de shard.

## Problema de escala que resolve

Distribui volume e carga além da capacidade de uma máquina.

## Como funciona?

Um roteador calcula o destino e envia a operação.

## Estratégias e variações

Range, hash, diretório e geo-sharding.

## Exemplo prático

Clientes são distribuídos por hash de cliente_id.

## Quando adotar?

Volumes ou throughput que não cabem verticalmente.

## Riscos e trade-offs

Rebalanceamento, hotspots e operações cross-shard.

## Como monitorar?

Skew, hotspots, tamanho por shard, roteamento e rebalanceamento.

## Relações com outros conceitos

Particionamento, consistent hashing e bancos distribuídos.

## Dúvidas

- Consigo explicar **Sharding** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Markus Winand — *SQL Performance Explained*
- Documentação oficial do SGBD utilizado.
