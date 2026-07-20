---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Vertical Slice Architecture

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Visão geral

Organiza código por caso de uso completo.

Cada slice reúne entrada, validação, lógica e acesso a dados necessários.

## Problema que busca resolver

Reduz mudanças espalhadas por camadas.

## Princípios e características

- Organiza código por caso de uso completo.
- Cada slice reúne entrada, validação, lógica e acesso a dados necessários.

## Componentes e responsabilidades

Slices por caso de uso, contratos, handlers, validações e infraestrutura necessária.

## Fluxo de execução

A entrada vai diretamente ao slice responsável, que executa o caso de uso completo.

## Exemplo prático

CriarPedido contém command, validator, handler e testes.

## Quando adotar?

APIs e aplicações orientadas a features.

## Quando evitar?

Evite duplicação inconsciente e padrões inconsistentes.

## Vantagens

Alta coesão por feature e entrega incremental.

## Desvantagens e trade-offs

Possível duplicação entre slices.

## Comparação com outras arquiteturas

A diferença principal está em como responsabilidades, dependências e implantação são organizadas.

CQRS, feature folders, modularidade e camadas.

A escolha deve ser guiada pelos requisitos e pelos custos operacionais.

## Dúvidas

- Consigo explicar **Vertical Slice Architecture** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Mark Richards e Neal Ford — *Fundamentals of Software Architecture*
- Neal Ford et al. — *Software Architecture: The Hard Parts*
- Simon Brown — C4 Model.
