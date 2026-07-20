---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Explique Vertical Slice

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Resposta em 30 segundos

Organiza código por caso de uso completo.

Reduz mudanças espalhadas por camadas.

## Resposta completa

Cada slice reúne entrada, validação, lógica e acesso a dados necessários.

A requisição vai ao handler do caso de uso com modelos e dependências próprios.

Principal cuidado: Possível duplicação entre slices.

## Exemplo prático

CriarPedido contém command, validator, handler e testes.

## Principais benefícios

Alta coesão por feature e entrega incremental.

## Trade-offs e limitações

Possível duplicação entre slices.

## Quando faz sentido?

APIs e aplicações orientadas a features.

## Erros comuns na resposta

- Definir somente por pastas ou ferramentas.
- Ignorar contexto e trade-offs.
- Não apresentar exemplo concreto.

## Perguntas de aprofundamento

- Consigo explicar **Explique Vertical Slice** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Conceitos relacionados

CQRS, feature folders, modularidade e camadas.

## Referências

- Consulte a nota principal do conceito neste vault.
- Revise os livros e documentações indicados na respectiva área.
