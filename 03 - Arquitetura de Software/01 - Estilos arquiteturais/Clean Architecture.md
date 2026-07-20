---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Clean Architecture

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Visão geral

Mantém regras de negócio independentes de frameworks e infraestrutura.

Separa entidades, casos de uso, adaptadores e detalhes, com dependências apontando para dentro.

## Problema que busca resolver

Preserva regras e melhora testabilidade diante de mudanças tecnológicas.

## Princípios e características

- Mantém regras de negócio independentes de frameworks e infraestrutura.
- Separa entidades, casos de uso, adaptadores e detalhes, com dependências apontando para dentro.

## Componentes e responsabilidades

Entidades, casos de uso, adaptadores de interface e frameworks ou drivers.

## Fluxo de execução

A entrada é adaptada para um caso de uso; o núcleo executa regras e acessa detalhes por abstrações.

## Exemplo prático

CriarPedido depende de IRepositorioPedido implementado com EF Core.

## Quando adotar?

Sistemas com regras relevantes e longa vida.

## Quando evitar?

Evite todas as camadas em funcionalidades triviais.

## Vantagens

Independência, testes rápidos e fronteiras explícitas.

## Desvantagens e trade-offs

Cerimônia, mapeamentos e abstrações demais.

## Comparação com outras arquiteturas

A diferença principal está em como responsabilidades, dependências e implantação são organizadas.

Hexagonal, Onion, DIP, DDD e camadas.

A escolha deve ser guiada pelos requisitos e pelos custos operacionais.

## Dúvidas

- Consigo explicar **Clean Architecture** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Mark Richards e Neal Ford — *Fundamentals of Software Architecture*
- Neal Ford et al. — *Software Architecture: The Hard Parts*
- Simon Brown — C4 Model.
