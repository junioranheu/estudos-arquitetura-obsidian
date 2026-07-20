---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Feature Flags

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Chaves que ativam funcionalidades sem novo deploy.

## O que é?

Separam implantação de liberação e permitem segmentação e rollback.

## Componentes principais

O código consulta a flag; a plataforma controla valores por ambiente ou público.

## Como funciona?

O código consulta a flag; a plataforma controla valores por ambiente ou público.

## Exemplo prático

Liberar novo checkout para 5% dos usuários.

## Quando usar?

Mudanças grandes, kill switch e experimentos.

## Quando evitar?

Evite flags permanentes e combinações explosivas.

## Vantagens

Rollback rápido e entrega contínua.

## Limitações e trade-offs

Dívida de flags e testes combinatórios.

## Boas práticas

- Mantenha responsabilidades claras e configuração versionada.
- Automatize validação e observabilidade.
- Documente limites, falhas e operação.

## Relações com outros conceitos

Canary, A/B testing, configuração e CI/CD.

## Referências

- Google — *Site Reliability Engineering*
- Nicole Forsgren, Jez Humble e Gene Kim — *Accelerate*
- Documentação oficial de Docker, Kubernetes e OpenTelemetry.
