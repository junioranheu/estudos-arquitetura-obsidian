---
tipo: conceito
status: nao-iniciado
dificuldade: avancado
tags: []
---

# Replicação de banco

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Manutenção de cópias de dados em múltiplas instâncias.

## O que é?

Copia alterações do primário para réplicas de forma síncrona ou assíncrona.

## Problema de escala que resolve

Distribui leituras e remove ponto único de falha; líder único não aumenta escrita.

## Como funciona?

Escritas vão ao líder e logs são aplicados nas réplicas.

## Estratégias e variações

Síncrona, assíncrona, física, lógica, leader-follower e multi-leader.

## Exemplo prático

Réplica de leitura atende relatórios.

## Quando adotar?

Redundância, leitura escalável e DR.

## Riscos e trade-offs

Lag, failover, conflitos e operação.

## Como monitorar?

Replication lag, erros, logs, capacidade e failover.

## Relações com outros conceitos

Leader-follower, quorum, consistência e backup.

## Dúvidas

- Consigo explicar **Replicação de banco** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Markus Winand — *SQL Performance Explained*
- Documentação oficial do SGBD utilizado.
