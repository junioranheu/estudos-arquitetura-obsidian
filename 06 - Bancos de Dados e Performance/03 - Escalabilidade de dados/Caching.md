---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Caching

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Armazenamento temporário para evitar recomputação ou acesso repetido.

## O que é?

Mantém cópias com política de expiração e invalidação.

## Problema de escala que resolve

Reduz pressão sobre banco, serviços e CPU ao reutilizar resultados.

## Como funciona?

Consulta cache; no miss, busca origem, armazena e retorna.

## Estratégias e variações

Cache-aside, read-through, write-through, write-behind, TTL e invalidação por evento.

## Exemplo prático

Catálogo popular fica no Redis por alguns minutos.

## Quando adotar?

Dados caros, frequentes e tolerantes a defasagem.

## Riscos e trade-offs

Stale data, stampede, invalidação e memória.

## Como monitorar?

Hit rate, miss rate, latência, evictions, memória e idade dos dados.

## Relações com outros conceitos

Redis, CDN, cache-aside, TTL e consistência.

## Dúvidas

- Consigo explicar **Caching** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Markus Winand — *SQL Performance Explained*
- Documentação oficial do SGBD utilizado.
