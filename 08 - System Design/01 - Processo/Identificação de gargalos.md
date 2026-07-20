---
tipo: conceito
status: nao-iniciado
dificuldade: avancado
tags: []
---

# Identificação de gargalos

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Objetivo

Localizar o limite dominante e confirmar sua causa com dados.

## Entradas necessárias

Métricas, traces, profiling, planos SQL, filas e testes de carga.

## Perguntas que devem ser feitas

Qual recurso está saturado, onde cresce a espera e qual é o caminho crítico?

## Como executar?

Mede filas, utilização, latência e caminho crítico antes de otimizar.

## Exemplo prático

CPU da API baixa, mas pool de conexões do banco esgotado.

## Saídas esperadas

Hipótese validada, impacto, correção e nova medição.

## Trade-offs

O gargalo muda após cada melhoria.

## Erros comuns

- Escolher tecnologia antes de entender o problema.
- Ignorar volume, falhas ou operação.
- Não registrar hipóteses e consequências.

## Relações com outros conceitos

Observabilidade, saturação, profiling e capacity planning.

## Dúvidas

- Consigo explicar **Identificação de gargalos** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Alex Xu — *System Design Interview*
- Google — *Site Reliability Engineering*.
