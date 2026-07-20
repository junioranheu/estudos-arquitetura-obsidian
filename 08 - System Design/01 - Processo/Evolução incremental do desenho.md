---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Evolução incremental do desenho

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Objetivo

Adicionar complexidade somente quando um requisito ou gargalo justificar.

## Entradas necessárias

Requisitos priorizados, restrições, métricas e riscos.

## Perguntas que devem ser feitas

Qual é a solução mais simples, onde ela falha e qual mudança resolve o limite?

## Como executar?

Desenha fluxo básico e adiciona cache, fila, réplica ou sharding conforme limites.

## Exemplo prático

Começar com banco único e depois adicionar réplica de leitura.

## Saídas esperadas

Etapas de evolução, gatilhos, trade-offs e plano de migração.

## Trade-offs

Mudanças tardias podem exigir migração.

## Erros comuns

- Escolher tecnologia antes de entender o problema.
- Ignorar volume, falhas ou operação.
- Não registrar hipóteses e consequências.

## Relações com outros conceitos

KISS, YAGNI, arquitetura evolutiva e gargalos.

## Dúvidas

- Consigo explicar **Evolução incremental do desenho** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Alex Xu — *System Design Interview*
- Google — *Site Reliability Engineering*.
