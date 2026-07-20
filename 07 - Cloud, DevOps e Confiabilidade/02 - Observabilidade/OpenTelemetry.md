---
tipo: conceito
status: nao-iniciado
dificuldade: avancado
tags: []
---

# OpenTelemetry

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Padrão e ferramentas para gerar, coletar e exportar telemetria.

## O que é?

Fornece APIs, SDKs, instrumentações, OTLP e Collector.

## Componentes principais

Aplicações propagam contexto e enviam sinais ao Collector.

## Como funciona?

Aplicações propagam contexto e enviam sinais ao Collector.

## Exemplo prático

API .NET exporta spans HTTP e SQL via OTLP.

## Quando usar?

Sistemas distribuídos e múltiplas linguagens.

## Quando evitar?

Evite instrumentação sem sampling e governança.

## Vantagens

Portabilidade e contexto distribuído.

## Limitações e trade-offs

Configuração, volume e cobertura desigual.

## Boas práticas

- Mantenha responsabilidades claras e configuração versionada.
- Automatize validação e observabilidade.
- Documente limites, falhas e operação.

## Relações com outros conceitos

Tracing, métricas, logs, OTLP e W3C Trace Context.

## Referências

- Google — *Site Reliability Engineering*
- Nicole Forsgren, Jez Humble e Gene Kim — *Accelerate*
- Documentação oficial de Docker, Kubernetes e OpenTelemetry.
