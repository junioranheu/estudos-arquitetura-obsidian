---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Explique Clean Architecture

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Resposta em 30 segundos

Mantém regras de negócio independentes de frameworks e infraestrutura.

Preserva regras e melhora testabilidade diante de mudanças tecnológicas.

## Resposta completa

Separa entidades, casos de uso, adaptadores e detalhes, com dependências apontando para dentro.

O núcleo define políticas e contratos; camadas externas adaptam e implementam detalhes.

Principal cuidado: Cerimônia, mapeamentos e abstrações demais.

## Exemplo prático

CriarPedido depende de IRepositorioPedido implementado com EF Core.

## Principais benefícios

Independência, testes rápidos e fronteiras explícitas.

## Trade-offs e limitações

Cerimônia, mapeamentos e abstrações demais.

## Quando faz sentido?

Sistemas com regras relevantes e longa vida.

## Erros comuns na resposta

- Definir somente por pastas ou ferramentas.
- Ignorar contexto e trade-offs.
- Não apresentar exemplo concreto.

## Perguntas de aprofundamento

- Consigo explicar **Explique Clean Architecture** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Conceitos relacionados

Hexagonal, Onion, DIP, DDD e camadas.

## Referências

- Consulte a nota principal do conceito neste vault.
- Revise os livros e documentações indicados na respectiva área.
