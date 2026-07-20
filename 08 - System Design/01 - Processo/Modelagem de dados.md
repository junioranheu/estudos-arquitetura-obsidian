---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Modelagem de dados

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Objetivo

Criar modelo que preserve regras e atenda os padrões de acesso.

## Entradas necessárias

Entidades, invariantes, volume, consultas, retenção e consistência.

## Perguntas que devem ser feitas

Quais dados, chaves, relações, consultas e requisitos de distribuição?

## Como executar?

Identifica chaves, padrões de leitura/escrita e armazenamento adequado.

## Exemplo prático

Timeline armazena posts por autor e projeções por seguidor.

## Saídas esperadas

Esquema, índices, chave de partição, políticas e evolução.

## Trade-offs

Desnormalização e distribuição aumentam complexidade.

## Erros comuns

- Escolher tecnologia antes de entender o problema.
- Ignorar volume, falhas ou operação.
- Não registrar hipóteses e consequências.

## Relações com outros conceitos

SQL, NoSQL, normalização, partição e consistência.

## Dúvidas

- Consigo explicar **Modelagem de dados** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Alex Xu — *System Design Interview*
- Google — *Site Reliability Engineering*.
