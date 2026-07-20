---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Cache

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Camada temporária que reduz latência e carga da origem.

## O que é?

Pode existir no cliente, CDN, gateway, aplicação ou banco.

## Papel na arquitetura

Acelerador entre consumidor e origem.

## Como funciona?

Consulta cache; no miss, acessa origem e atualiza a cópia.

## Exemplo de fluxo

Redis armazena perfis populares por cinco minutos.

## Quando usar?

Leituras repetidas e dados tolerantes a defasagem.

## Decisões de projeto

Localização, chave, TTL, invalidação, eviction, replicação e fallback.

## Vantagens

Baixa latência e menor carga.

## Riscos e trade-offs

Stale data, stampede e memória.

## Alternativas

Otimização da origem, índices, materialized views ou réplicas.

## Dúvidas

- Consigo explicar **Cache** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Alex Xu — *System Design Interview*
- Google — *Site Reliability Engineering*.
