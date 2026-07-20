---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Background Jobs

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Tarefas executadas fora do fluxo imediato da requisição.

## O que é?

Processam trabalho agendado, demorado ou tolerante a atraso.

## Que problema operacional resolve?

Evita bloquear requisições e permite retries.

## Como funciona?

A aplicação registra a tarefa; um executor busca, processa e registra o resultado.

## Exemplo prático

Gerar relatório grande após responder 202 Accepted.

## Execução, retries e idempotência

Registre estado durável, limite tentativas, use backoff e torne a operação idempotente.

Falhas assíncronas, duplicidade e monitoramento.

## Monitoramento

Monitore duração, sucesso, falhas, retries, backlog e idade do trabalho.

## Falhas e cuidados

Falhas assíncronas, duplicidade e monitoramento.

Evite quando resultado imediato ou mesma transação é obrigatório.

## Quando usar?

Arquivos, notificações, sincronização e manutenção.

## Quando evitar?

Evite quando resultado imediato ou mesma transação é obrigatório.

## Relações com outros conceitos

Workers, filas, scheduler, idempotência e outbox.

## Referências

- Gregor Hohpe e Bobby Woolf — *Enterprise Integration Patterns*
- Ben Stopford — *Designing Event-Driven Systems*
- Documentação oficial do RabbitMQ.
