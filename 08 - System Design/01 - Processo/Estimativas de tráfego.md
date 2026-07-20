---
tipo: conceito
status: nao-iniciado
dificuldade: avancado
tags: []
---

# Estimativas de tráfego

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Objetivo

Obter ordem de grandeza suficiente para orientar decisões.

## Entradas necessárias

Usuários, frequência, payload, retenção, picos e crescimento.

## Perguntas que devem ser feitas

Qual média, pico, proporção de leitura e escrita e tamanho do payload?

## Como executar?

Usa usuários, frequência, payload, sazonalidade e fator de pico.

## Exemplo prático

10 milhões de ações por dia são cerca de 116 por segundo em média.

## Saídas esperadas

QPS, throughput, bandwidth, armazenamento e hipóteses.

## Trade-offs

Hipóteses erradas super ou subdimensionam.

## Erros comuns

- Escolher tecnologia antes de entender o problema.
- Ignorar volume, falhas ou operação.
- Não registrar hipóteses e consequências.

## Relações com outros conceitos

QPS, throughput, bandwidth, storage e Little’s Law.

## Dúvidas

- Consigo explicar **Estimativas de tráfego** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Alex Xu — *System Design Interview*
- Google — *Site Reliability Engineering*.
