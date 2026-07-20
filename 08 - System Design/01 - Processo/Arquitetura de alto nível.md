---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Arquitetura de alto nível

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Objetivo

Traduzir requisitos em componentes e interações compreensíveis.

## Entradas necessárias

Requisitos funcionais e não funcionais, volume, restrições e integrações.

## Perguntas que devem ser feitas

Quem usa, quais fluxos são críticos, onde ficam os dados e quais falhas importam?

## Como executar?

Parte de requisitos e define limites, componentes, armazenamento e comunicação.

## Exemplo prático

Cliente → API Gateway → serviço de pedidos → banco e fila.

## Saídas esperadas

Diagrama, responsabilidades, fluxos, decisões e riscos.

## Trade-offs

Pode esconder detalhes críticos se for abstrata demais.

## Erros comuns

- Escolher tecnologia antes de entender o problema.
- Ignorar volume, falhas ou operação.
- Não registrar hipóteses e consequências.

## Relações com outros conceitos

C4, system context, requisitos e trade-offs.

## Dúvidas

- Consigo explicar **Arquitetura de alto nível** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Alex Xu — *System Design Interview*
- Google — *Site Reliability Engineering*.
