---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# CI e CD

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Objetivo

Reduz risco e torna releases frequentes e previsíveis.

## Etapas principais

Build, testes, análise estática, empacotamento, publicação de artefato, deploy, verificação e promoção.

## Como funciona?

Commits acionam build, testes, análise, artefato e promoção entre ambientes.

## Exemplo prático

Push executa testes .NET, cria imagem Docker e promove para QA.

## Automação e ferramentas

GitHub Actions, Azure Pipelines, GitLab CI, Jenkins, registries, infraestrutura como código e ferramentas de deployment.

## Boas práticas

- Mantenha responsabilidades claras e configuração versionada.
- Automatize validação e observabilidade.
- Documente limites, falhas e operação.

## Riscos e falhas comuns

Pipelines frágeis, segredos e custo.

## Métricas de acompanhamento

Deployment frequency, lead time for changes, change failure rate e mean time to restore.

## Relações com outros conceitos

Trunk-based, testes, IaC, feature flags e DORA.

## Dúvidas

- Consigo explicar **CI e CD** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Google — *Site Reliability Engineering*
- Nicole Forsgren, Jez Humble e Gene Kim — *Accelerate*
- Documentação oficial de Docker, Kubernetes e OpenTelemetry.
