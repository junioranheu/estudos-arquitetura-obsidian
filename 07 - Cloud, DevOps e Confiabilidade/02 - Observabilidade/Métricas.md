---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Métricas

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Medições numéricas agregadas ao longo do tempo.

## O que é?

Representam contadores, gauges, histogramas e distribuições.

## Que perguntas responde?

Quanto ocorre, com que frequência, quão rápido e como o comportamento muda ao longo do tempo?

## Como coletar?

Instrumente operações principais e exporte contadores, gauges e histogramas com dimensões de cardinalidade controlada.

## Exemplo prático

Taxa de requisições, p95 e percentual de erros.

## Boas práticas

- Mantenha responsabilidades claras e configuração versionada.
- Automatize validação e observabilidade.
- Documente limites, falhas e operação.

## Limitações e riscos

Representam contadores, gauges, histogramas e distribuições.

Aplicações exportam valores coletados e visualizados.

## Relação entre logs, métricas e traces

Métricas mostram tendências e alertam; traces mostram o caminho de uma operação; logs fornecem detalhes discretos. A correlação entre os três reduz o tempo de diagnóstico.

## Dúvidas

- Consigo explicar **Métricas** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Google — *Site Reliability Engineering*
- Nicole Forsgren, Jez Humble e Gene Kim — *Accelerate*
- Documentação oficial de Docker, Kubernetes e OpenTelemetry.
