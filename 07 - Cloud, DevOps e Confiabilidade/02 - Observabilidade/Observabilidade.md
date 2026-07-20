---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Observabilidade

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Capacidade de inferir estado interno pelos sinais externos.

## O que é?

Combina instrumentação e análise de logs, métricas e traces.

## Que perguntas responde?

O sistema está saudável, onde está o problema e por que ele ocorreu?

## Como coletar?

Instrumente aplicação e infraestrutura, propague contexto e centralize logs, métricas e traces.

## Exemplo prático

Métrica aponta erro, trace localiza etapa e logs explicam causa.

## Boas práticas

- Mantenha responsabilidades claras e configuração versionada.
- Automatize validação e observabilidade.
- Documente limites, falhas e operação.

## Limitações e riscos

Combina instrumentação e análise de logs, métricas e traces.

Sinais compartilham contexto e são enviados a plataforma de análise.

## Relação entre logs, métricas e traces

Métricas mostram tendências e alertam; traces mostram o caminho de uma operação; logs fornecem detalhes discretos. A correlação entre os três reduz o tempo de diagnóstico.

## Dúvidas

- Consigo explicar **Observabilidade** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Google — *Site Reliability Engineering*
- Nicole Forsgren, Jez Humble e Gene Kim — *Accelerate*
- Documentação oficial de Docker, Kubernetes e OpenTelemetry.
