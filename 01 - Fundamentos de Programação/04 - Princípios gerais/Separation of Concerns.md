---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Separation of Concerns

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Separar o sistema conforme preocupações distintas.

## O que o princípio diz?

Separar o sistema conforme preocupações distintas. Evita misturar negócio, apresentação, persistência, segurança e infraestrutura.

## Qual problema evita?

Permite evolução e testes independentes.

## Como aplicar?

Cada preocupação recebe limite e responsabilidade próprios.

## Exemplo prático

Controller trata HTTP, caso de uso orquestra e repositório acessa dados.

## Sinais de violação

- Responsabilidades misturadas ou dependências rígidas.
- Contratos que forçam comportamento inadequado ou surpreendem o consumidor.

## Benefícios

Clareza e isolamento de mudanças.

## Limitações e trade-offs

Mais fronteiras e mapeamentos.

## Relações com outros conceitos

SRP, arquitetura em camadas e cross-cutting concerns.

## Dúvidas

- Consigo explicar **Separation of Concerns** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Robert C. Martin — *Agile Software Development: Principles, Patterns, and Practices*
- Martin Fowler — *Refactoring*
- Documentação oficial da linguagem e do runtime utilizados.
