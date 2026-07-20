---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# DNS

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Sistema distribuído que traduz nomes em endereços e registros.

## O que é?

Organiza hierarquia de zonas e resolvedores com cache por TTL.

## Papel na arquitetura

Camada de localização por nomes.

## Como funciona?

Cliente consulta resolver, que obtém resposta autoritativa.

## Exemplo de fluxo

api.exemplo.com resolve para o load balancer.

## Quando usar?

Todo serviço acessível por nome.

## Decisões de projeto

Tipos de registro, TTL, authoritative DNS, geo-routing e health checks.

## Vantagens

Escala global e flexibilidade.

## Riscos e trade-offs

Propagação, cache e ataques.

## Alternativas

Service discovery interno ou configuração estática.

## Dúvidas

- Consigo explicar **DNS** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Alex Xu — *System Design Interview*
- Google — *Site Reliability Engineering*.
