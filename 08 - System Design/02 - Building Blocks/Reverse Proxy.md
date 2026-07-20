---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Reverse Proxy

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Intermediário que recebe requisições e encaminha a backends.

## O que é?

Oculta servidores internos e pode aplicar TLS, cache e roteamento.

## Papel na arquitetura

Fachada de rede diante dos servidores de origem.

## Como funciona?

Cliente conecta ao proxy, que escolhe backend e devolve resposta.

## Exemplo de fluxo

Nginx termina HTTPS e encaminha /api.

## Quando usar?

Publicação web, TLS e roteamento.

## Decisões de projeto

TLS, headers, timeout, buffering, cache, rotas e HA.

## Vantagens

Segurança, flexibilidade e otimização de rede.

## Riscos e trade-offs

Ponto de falha e configuração complexa.

## Alternativas

API Gateway, ingress ou load balancer L7.

## Dúvidas

- Consigo explicar **Reverse Proxy** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Alex Xu — *System Design Interview*
- Google — *Site Reliability Engineering*.
