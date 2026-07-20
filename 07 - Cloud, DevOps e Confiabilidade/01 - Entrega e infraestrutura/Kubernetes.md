---
tipo: conceito
status: nao-iniciado
dificuldade: avancado
tags: []
---

# Kubernetes

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Plataforma de orquestração de workloads containerizados.

## O que é?

Reconcilia estado desejado de pods, deployments, services e recursos.

## Componentes principais

Control plane agenda, reinicia, distribui tráfego e aplica rollout.

## Como funciona?

Control plane agenda, reinicia, distribui tráfego e aplica rollout.

## Exemplo prático

Deployment mantém três réplicas da API.

## Quando usar?

Muitos workloads e equipe operacional madura.

## Quando evitar?

Evite para poucos serviços simples.

## Vantagens

Self-healing, portabilidade e ecossistema.

## Limitações e trade-offs

Complexidade, custo, rede e segurança.

## Boas práticas

- Mantenha responsabilidades claras e configuração versionada.
- Automatize validação e observabilidade.
- Documente limites, falhas e operação.

## Relações com outros conceitos

Containers, Helm, GitOps e service mesh.

## Referências

- Google — *Site Reliability Engineering*
- Nicole Forsgren, Jez Humble e Gene Kim — *Accelerate*
- Documentação oficial de Docker, Kubernetes e OpenTelemetry.
