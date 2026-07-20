---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Command Query Separation

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Uma operação deve alterar estado ou retornar dados, sem misturar efeitos de forma surpreendente.

## O que o princípio diz?

Uma operação deve alterar estado ou retornar dados, sem misturar efeitos de forma surpreendente. Separa comandos que mudam estado de consultas que apenas observam.

## Qual problema evita?

Torna efeitos previsíveis e melhora testes.

## Como aplicar?

Métodos de escrita explicitam efeitos; leituras não alteram o sistema.

## Exemplo prático

ObterSaldo lê; Debitar altera.

## Sinais de violação

- Responsabilidades misturadas ou dependências rígidas.
- Contratos que forçam comportamento inadequado ou surpreendem o consumidor.

## Benefícios

Contratos claros e menos efeitos ocultos.

## Limitações e trade-offs

Aplicação rígida pode criar chamadas extras.

## Relações com outros conceitos

CQRS, comandos, consultas e imutabilidade.

## Dúvidas

- Consigo explicar **Command Query Separation** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Robert C. Martin — *Agile Software Development: Principles, Patterns, and Practices*
- Martin Fowler — *Refactoring*
- Documentação oficial da linguagem e do runtime utilizados.
