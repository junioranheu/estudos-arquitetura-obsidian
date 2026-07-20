---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: []
---

# Encapsulamento

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Proteção do estado interno por uma interface controlada de operações.

## O que é?

Impede alterações arbitrárias e garante que mudanças respeitem regras do objeto.

## Por que é importante?

Preserva consistência e reduz dependência de detalhes internos.

## Como funciona?

Campos ficam protegidos e métodos expressam operações válidas.

## Exemplo prático

Conta.Sacar valida saldo e limite em vez de permitir editar Saldo diretamente.

## Aplicações

Objetos com regras sobre mudança de estado.

## Limitações e cuidados

Ocultação excessiva pode dificultar integração.

Evite setters públicos que quebram invariantes.

## Relações com outros conceitos

Abstração, invariantes, objetos ricos e information hiding.

## Dúvidas

- Consigo explicar **Encapsulamento** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Robert C. Martin — *Agile Software Development: Principles, Patterns, and Practices*
- Martin Fowler — *Refactoring*
- Documentação oficial da linguagem e do runtime utilizados.
