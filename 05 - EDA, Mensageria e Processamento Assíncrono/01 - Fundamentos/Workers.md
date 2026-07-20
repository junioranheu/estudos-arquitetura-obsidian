---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Workers

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Processos que executam tarefas fora do atendimento principal.

## O que é?

São unidades contínuas ou sob demanda ligadas a filas ou agendadores.

## Que problema operacional resolve?

Isola trabalho pesado e permite escala independente.

## Como funciona?

Buscam trabalho, controlam concorrência, processam e confirmam.

## Exemplo prático

Worker redimensiona imagens de uma fila.

## Execução, retries e idempotência

Registre estado durável, limite tentativas, use backoff e torne a operação idempotente.

Retries, shutdown e observabilidade.

## Monitoramento

Monitore duração, sucesso, falhas, retries, backlog e idade do trabalho.

## Falhas e cuidados

Retries, shutdown e observabilidade.

Evite para lógica que precisa da mesma transação da requisição.

## Quando usar?

Jobs demorados, importações e integrações.

## Quando evitar?

Evite para lógica que precisa da mesma transação da requisição.

## Relações com outros conceitos

Background jobs, consumer, queue e scheduler.

## Referências

- Gregor Hohpe e Bobby Woolf — *Enterprise Integration Patterns*
- Ben Stopford — *Designing Event-Driven Systems*
- Documentação oficial do RabbitMQ.
