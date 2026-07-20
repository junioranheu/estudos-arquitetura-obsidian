---
tipo: conceito
status: nao-iniciado
dificuldade: avancado
tags: []
---

# Explique replicação e particionamento

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Resposta em 30 segundos

Replicação cria cópias; particionamento divide os dados.

São técnicas complementares de escala e resiliência.

## Resposta completa

A primeira melhora redundância e leitura; o segundo distribui volume e carga.

Réplicas recebem alterações; partições recebem subconjuntos por chave.

Principal cuidado: Lag, skew, failover e rebalanceamento.

## Exemplo prático

Pedidos são particionados por cliente e cada partição possui réplicas.

## Principais benefícios

Capacidade, disponibilidade e localidade.

## Trade-offs e limitações

Lag, skew, failover e rebalanceamento.

## Quando faz sentido?

Sistemas de dados grandes ou críticos.

## Erros comuns na resposta

- Definir somente por pastas ou ferramentas.
- Ignorar contexto e trade-offs.
- Não apresentar exemplo concreto.

## Perguntas de aprofundamento

- Consigo explicar **Explique replicação e particionamento** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Conceitos relacionados

Sharding, quorum, CAP e replication lag.

## Referências

- Consulte a nota principal do conceito neste vault.
- Revise os livros e documentações indicados na respectiva área.
