---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# ISP - Princípio da Segregação de Interfaces

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Clientes não devem depender de métodos que não utilizam.

## O que o princípio diz?

Clientes não devem depender de métodos que não utilizam. Contratos devem ser pequenos e focados nas capacidades necessárias.

## Qual problema evita?

Reduz dependências acidentais e implementações vazias.

## Como aplicar?

Interfaces amplas são divididas conforme consumidores reais.

## Exemplo prático

Separar ILeitorArquivo de IGravadorArquivo.

## Sinais de violação

- Responsabilidades misturadas ou dependências rígidas.
- Contratos que forçam comportamento inadequado ou surpreendem o consumidor.

## Benefícios

Contratos claros e mudanças localizadas.

## Limitações e trade-offs

Mais interfaces para nomear e compor.

## Relações com outros conceitos

SRP, coesão, contratos e DIP.

## Dúvidas

- Consigo explicar **ISP - Princípio da Segregação de Interfaces** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Robert C. Martin — *Agile Software Development: Principles, Patterns, and Practices*
- Martin Fowler — *Refactoring*
- Documentação oficial da linguagem e do runtime utilizados.
