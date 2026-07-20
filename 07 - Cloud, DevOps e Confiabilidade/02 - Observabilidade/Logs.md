---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Logs

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Registros estruturados de eventos discretos.

## O que é?

Capturam contexto de operações, decisões e falhas.

## Que perguntas responde?

O que aconteceu, em qual operação, com quais dados de contexto e em que sequência?

## Como coletar?

Use logging estruturado, níveis consistentes, correlação por request ou trace e centralização em uma plataforma.

## Exemplo prático

Erro inclui request_id, pedido_id e código.

## Boas práticas

- Mantenha responsabilidades claras e configuração versionada.
- Automatize validação e observabilidade.
- Documente limites, falhas e operação.

## Limitações e riscos

Capturam contexto de operações, decisões e falhas.

Aplicações emitem timestamp, nível, mensagem e campos correlacionáveis.

## Relação entre logs, métricas e traces

Métricas mostram tendências e alertam; traces mostram o caminho de uma operação; logs fornecem detalhes discretos. A correlação entre os três reduz o tempo de diagnóstico.

## Dúvidas

- Consigo explicar **Logs** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Google — *Site Reliability Engineering*
- Nicole Forsgren, Jez Humble e Gene Kim — *Accelerate*
- Documentação oficial de Docker, Kubernetes e OpenTelemetry.
