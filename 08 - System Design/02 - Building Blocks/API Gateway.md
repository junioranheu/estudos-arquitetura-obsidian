---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# API Gateway

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Ponto de entrada que aplica políticas e encaminha APIs.

## O que é?

Centraliza roteamento, autenticação, limites, transformação e observabilidade.

## Papel na arquitetura

Fachada de APIs para consumidores externos.

## Como funciona?

Cliente chama o gateway, que valida e seleciona backends.

## Exemplo de fluxo

App chama /pedidos e gateway encaminha após validar token.

## Quando usar?

Múltiplos serviços e políticas transversais.

## Decisões de projeto

Roteamento, autenticação, rate limit, timeout, cache, transformação e alta disponibilidade.

## Vantagens

Segurança central e roteamento.

## Riscos e trade-offs

Latência adicional e possível gargalo.

## Alternativas

Reverse proxy simples, BFF ou chamadas diretas controladas.

## Dúvidas

- Consigo explicar **API Gateway** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Alex Xu — *System Design Interview*
- Google — *Site Reliability Engineering*.
