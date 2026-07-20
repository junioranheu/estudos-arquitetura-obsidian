---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Domínio rico vs CRUD

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Domínio rico modela regras; CRUD prioriza operações simples sobre dados.

## Conceitos comparados

CRUD é adequado com poucas regras; domínio rico coloca decisões em entidades e value objects.

## Principais diferenças

No CRUD, serviços manipulam registros; no rico, métodos preservam invariantes.

## Exemplo prático

Atualizar status diretamente versus Pedido.Cancelar(motivo).

## Quando cada abordagem faz sentido?

CRUD em cadastros simples; rico em capacidades estratégicas.

## Vantagens e desvantagens

- Benefícios: Complexidade proporcional ao problema.
- Custos: Rico exige design; CRUD pode espalhar regras quando cresce.

## Critérios de decisão

- Complexidade do domínio.
- Frequência e risco das mudanças.
- Necessidade de consistência, escala e operação.

## Relações com outros conceitos

DDD, objetos ricos, serviços e transações.

## Dúvidas

- Consigo explicar **Domínio rico vs CRUD** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Eric Evans — *Domain-Driven Design*
- Vaughn Vernon — *Implementing Domain-Driven Design*
- Vaughn Vernon — *Domain-Driven Design Distilled*.
