---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Alertas

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Notificações acionáveis sobre condições que ameaçam usuários ou objetivos.

## Objetivo

Permite resposta antes de ampliar impacto.

## Sinais e condições de alerta

Disponibilidade, latência, taxa de erros, saturação, backlog, consumo de recursos e indicadores críticos do negócio.

## Como definir limiares?

Prefira SLOs, janelas de tempo e taxas de mudança. Evite valores instantâneos escolhidos sem dados históricos.

## Exemplo prático

Alertar quando erro viola o SLO por janela sustentada.

## Severidade e escalonamento

Associe severidade ao impacto e à urgência, com responsável, canal e tempo esperado de resposta.

## Redução de falsos positivos

Use duração mínima, deduplicação, agrupamento, silenciamento em manutenção e revisão periódica das regras.

## Boas práticas

- Mantenha responsabilidades claras e configuração versionada.
- Automatize validação e observabilidade.
- Documente limites, falhas e operação.

## Erros comuns

- Escolher tecnologia antes de entender o problema.
- Ignorar volume, falhas ou operação.
- Não registrar hipóteses e consequências.

## Relações com outros conceitos

Observabilidade, SLO, incident response e on-call.

## Referências

- Google — *Site Reliability Engineering*
- Nicole Forsgren, Jez Humble e Gene Kim — *Accelerate*
- Documentação oficial de Docker, Kubernetes e OpenTelemetry.
