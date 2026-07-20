---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Arquitetura orientada a componentes

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Visão geral

Estrutura o sistema como componentes independentes com interfaces explícitas.

Cada componente encapsula implementação e expõe contratos para composição.

## Problema que busca resolver

Favorece reutilização, substituição e evolução modular.

## Princípios e características

- Estrutura o sistema como componentes independentes com interfaces explícitas.
- Cada componente encapsula implementação e expõe contratos para composição.

## Componentes e responsabilidades

Componentes, interfaces providas e requeridas, composição e comunicação.

## Fluxo de execução

Um componente recebe a solicitação por sua interface e colabora apenas por contratos publicados.

## Exemplo prático

Módulos de catálogo, pedidos e pagamentos expõem APIs internas.

## Quando adotar?

Produtos com capacidades claramente separáveis.

## Quando evitar?

Evite componentes minúsculos ou contratos instáveis.

## Vantagens

Modularidade, ownership e testes isolados.

## Desvantagens e trade-offs

Coordenação de versões e dependências.

## Comparação com outras arquiteturas

A diferença principal está em como responsabilidades, dependências e implantação são organizadas.

Monólito modular, microsserviços e encapsulamento.

A escolha deve ser guiada pelos requisitos e pelos custos operacionais.

## Dúvidas

- Consigo explicar **Arquitetura orientada a componentes** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Mark Richards e Neal Ford — *Fundamentals of Software Architecture*
- Neal Ford et al. — *Software Architecture: The Hard Parts*
- Simon Brown — C4 Model.
