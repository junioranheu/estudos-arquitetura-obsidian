---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Docker

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Plataforma para construir, distribuir e executar containers.

## O que é?

Fornece Dockerfile, imagens, runtime, registry e composição.

## Componentes principais

Dockerfile gera camadas; runtime cria containers.

## Como funciona?

Dockerfile gera camadas; runtime cria containers.

## Exemplo prático

docker build cria imagem e docker run inicia a API.

## Quando usar?

Desenvolvimento local, CI/CD e deploy.

## Quando evitar?

Evite imagens gigantes, root e segredos em camadas.

## Vantagens

Ecossistema maduro e fluxo simples.

## Limitações e trade-offs

Tuning, segurança e armazenamento.

## Boas práticas

- Mantenha responsabilidades claras e configuração versionada.
- Automatize validação e observabilidade.
- Documente limites, falhas e operação.

## Relações com outros conceitos

Containers, OCI, Compose, registry e Kubernetes.

## Referências

- Google — *Site Reliability Engineering*
- Nicole Forsgren, Jez Humble e Gene Kim — *Accelerate*
- Documentação oficial de Docker, Kubernetes e OpenTelemetry.
