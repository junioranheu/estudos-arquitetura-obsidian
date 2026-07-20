---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# DIP - Princípio da Inversão de Dependência

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Políticas devem depender de abstrações, não de detalhes concretos.

## O que o princípio diz?

Políticas devem depender de abstrações, não de detalhes concretos. Módulos de alto nível e baixo nível se conectam por contratos estáveis.

## Qual problema evita?

Evita que regras mudem por causa de banco, framework ou mensageria.

## Como aplicar?

O núcleo declara interfaces; implementações externas são injetadas.

## Exemplo prático

Caso de uso depende de IRepositorioPedido; EF Core implementa na infraestrutura.

## Sinais de violação

- Responsabilidades misturadas ou dependências rígidas.
- Contratos que forçam comportamento inadequado ou surpreendem o consumidor.

## Benefícios

Testabilidade e independência tecnológica.

## Limitações e trade-offs

Mais tipos, configuração e indireção.

## Relações com outros conceitos

DI, Clean Architecture, interfaces e Hexagonal.

## Dúvidas

- Consigo explicar **DIP - Princípio da Inversão de Dependência** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Robert C. Martin — *Agile Software Development: Principles, Patterns, and Practices*
- Martin Fowler — *Refactoring*
- Documentação oficial da linguagem e do runtime utilizados.
