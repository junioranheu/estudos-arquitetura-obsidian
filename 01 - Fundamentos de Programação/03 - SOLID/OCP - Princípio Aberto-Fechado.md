---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# OCP - Princípio Aberto-Fechado

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Permitir extensão sem modificar repetidamente código estável.

## O que o princípio diz?

Permitir extensão sem modificar repetidamente código estável. Isola pontos de variação por contratos, composição e polimorfismo.

## Qual problema evita?

Reduz regressão em áreas estáveis.

## Como aplicar?

Novas regras entram como implementações em vez de crescer switches centrais.

## Exemplo prático

Adicionar Boleto como nova implementação de IMetodoPagamento.

## Sinais de violação

- Responsabilidades misturadas ou dependências rígidas.
- Contratos que forçam comportamento inadequado ou surpreendem o consumidor.

## Benefícios

Extensão segura e impacto menor.

## Limitações e trade-offs

Abstrações prematuras e mais indireção.

## Relações com outros conceitos

Polimorfismo, Strategy, plugins e DIP.

## Dúvidas

- Consigo explicar **OCP - Princípio Aberto-Fechado** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Robert C. Martin — *Agile Software Development: Principles, Patterns, and Practices*
- Martin Fowler — *Refactoring*
- Documentação oficial da linguagem e do runtime utilizados.
