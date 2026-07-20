---
tipo: conceito
status: estudando
dificuldade: iniciante
tags: []
---
 
# Concorrência

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Execução de várias tarefas com progresso sobreposto.

## O que é?

Organização de múltiplas unidades de trabalho que disputam tempo de CPU, memória ou recursos compartilhados.

## Por que é importante?

Melhora responsividade e utilização de recursos.

## Como funciona?

O sistema intercala tarefas, usa threads ou operações assíncronas e coordena o acesso ao estado compartilhado.

## Exemplo prático

Uma API atende várias requisições enquanto aguarda banco de dados e serviços externos.

## Aplicações

Servidores, interfaces responsivas, I/O e processamento de múltiplos fluxos.

## Limitações e cuidados

Condições de corrida, deadlocks e testes mais difíceis.

Evite quando a carga é pequena ou o custo de sincronização supera o ganho.

## Relações com outros conceitos

Paralelismo, assincronicidade, threads, locks e idempotência.

## Dúvidas

- Consigo explicar **Concorrência** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Robert C. Martin — *Agile Software Development: Principles, Patterns, and Practices*
- Martin Fowler — *Refactoring*
- Documentação oficial da linguagem e do runtime utilizados.
