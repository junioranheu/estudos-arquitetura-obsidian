---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Tracing

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Rastreamento do caminho e duração de uma operação distribuída.

## O que é?

Um trace é composto por spans relacionados por contexto.

## Que perguntas responde?

Por onde a operação passou, quanto tempo cada etapa levou e em qual componente ocorreu a falha?

## Como coletar?

Propague trace context e crie spans nas entradas, saídas e operações relevantes, com sampling adequado.

## Exemplo prático

Trace mostra latência concentrada no serviço de estoque.

## Boas práticas

- Mantenha responsabilidades claras e configuração versionada.
- Automatize validação e observabilidade.
- Documente limites, falhas e operação.

## Limitações e riscos

Um trace é composto por spans relacionados por contexto.

trace_id é propagado e cada serviço registra seus spans.

## Relação entre logs, métricas e traces

Métricas mostram tendências e alertam; traces mostram o caminho de uma operação; logs fornecem detalhes discretos. A correlação entre os três reduz o tempo de diagnóstico.

## Dúvidas

- Consigo explicar **Tracing** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Google — *Site Reliability Engineering*
- Nicole Forsgren, Jez Humble e Gene Kim — *Accelerate*
- Documentação oficial de Docker, Kubernetes e OpenTelemetry.
