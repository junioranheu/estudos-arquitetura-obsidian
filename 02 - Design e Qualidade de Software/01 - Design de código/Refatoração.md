---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Refatoração

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Mudança da estrutura interna sem alterar comportamento observável.

## O que é?

Melhora design, legibilidade e capacidade de mudança preservando resultados.

## Objetivos

Reduz dívida e prepara o código para novas mudanças.

## Quando refatorar?

Ao encontrar smells, antes de novas features ou durante manutenção.

## Técnicas comuns

Extrair método, renomear, mover método, introduzir objeto-parâmetro, remover duplicação e substituir condicional por polimorfismo quando houver variação real.

## Exemplo antes e depois

Extrair regra de desconto de um método grande para um componente testável.

## Como refatorar com segurança?

Proteja o comportamento com testes, faça mudanças pequenas, execute a suíte continuamente e mantenha commits reversíveis.

## Sinais de alerta

Métodos longos, classe Deus, duplicação, nomes vagos, comentários compensatórios e mudanças espalhadas.

## Limitações e trade-offs

Consome tempo sem valor funcional imediato.

## Relações com outros conceitos

Testes, code smells, dívida técnica e melhoria contínua.

## Referências

- Martin Fowler — *Refactoring*
- Robert C. Martin — *Clean Code*
- Gamma et al. — *Design Patterns*.
