---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# CDN

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Rede distribuída que entrega conteúdo perto do usuário.

## O que é?

Replica e armazena objetos em pontos de presença.

## Papel na arquitetura

Camada de distribuição e cache na borda.

## Como funciona?

Requisição vai ao edge; em miss, busca a origem e armazena.

## Exemplo de fluxo

Imagens e vídeos são servidos pelo PoP mais próximo.

## Quando usar?

Conteúdo estático, mídia e downloads.

## Decisões de projeto

TTL, cache key, purge, origem, compressão, TLS e proteção.

## Vantagens

Performance global e absorção de picos.

## Riscos e trade-offs

Invalidação, egress e conteúdo obsoleto.

## Alternativas

Origem direta, reverse proxy regional ou edge functions.

## Dúvidas

- Consigo explicar **CDN** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Alex Xu — *System Design Interview*
- Google — *Site Reliability Engineering*.
