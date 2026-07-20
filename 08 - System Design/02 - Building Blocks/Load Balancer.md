---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Load Balancer

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Distribui tráfego entre instâncias saudáveis.

## O que é?

Melhora disponibilidade e capacidade usando algoritmos e health checks.

## Papel na arquitetura

Distribuidor de conexões entre backends.

## Como funciona?

Recebe conexões e encaminha por round-robin, least connections ou hash.

## Exemplo de fluxo

Distribui requisições entre quatro réplicas.

## Quando usar?

Serviços com múltiplas réplicas.

## Decisões de projeto

Camada 4 ou 7, algoritmo, health check, TLS, afinidade e HA.

## Vantagens

Alta disponibilidade e escala.

## Riscos e trade-offs

Health checks ruins e latência adicional.

## Alternativas

DNS load balancing, client-side balancing ou anycast.

## Dúvidas

- Consigo explicar **Load Balancer** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Alex Xu — *System Design Interview*
- Google — *Site Reliability Engineering*.
