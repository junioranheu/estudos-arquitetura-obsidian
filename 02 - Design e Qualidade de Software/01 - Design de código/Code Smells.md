---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Code Smells

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Sinais que sugerem problemas de design, embora não sejam defeitos por si só.

## O que é?

Estruturas difíceis de entender, alterar ou testar, como métodos longos, duplicação e classes com responsabilidades demais.

## Como ocorre?

São percebidos em revisão, métricas e dificuldade recorrente durante mudanças.

## Principais causas

Crescimento sem refatoração, duplicação, responsabilidades misturadas e pressão contínua por prazo.

## Como identificar?

Procure métodos longos, classes com muitas responsabilidades, condicionais extensas, nomes vagos e mudanças espalhadas.

## Exemplo prático

Método com dezenas de condicionais e parâmetros sugere responsabilidades misturadas.

## Impactos

Maior custo de mudança, testes difíceis, mais regressões e entendimento lento.

## Como prevenir?

Faça revisão de código, refatoração contínua, testes e definição clara de responsabilidades.

## Como corrigir?

Aplique técnicas específicas, como extrair método, mover responsabilidade, remover duplicação e substituir condicionais por polimorfismo quando adequado.

## Relações com outros conceitos

Refatoração, dívida técnica, Clean Code e coesão.

## Dúvidas

- Consigo explicar **Code Smells** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Fowler — *Refactoring*
- Robert C. Martin — *Clean Code*
- Gamma et al. — *Design Patterns*.
