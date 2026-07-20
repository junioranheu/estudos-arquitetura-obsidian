---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Arquitetura em camadas

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Visão geral

Organiza o sistema em camadas com responsabilidades definidas.

Separa apresentação, aplicação, domínio e persistência ou variações equivalentes.

## Problema que busca resolver

Reduz mistura de preocupações e oferece estrutura familiar.

## Princípios e características

- Organiza o sistema em camadas com responsabilidades definidas.
- Separa apresentação, aplicação, domínio e persistência ou variações equivalentes.

## Componentes e responsabilidades

Apresentação, aplicação ou serviços, domínio e infraestrutura ou persistência.

## Fluxo de execução

Entrada na apresentação, orquestração na aplicação, regras no domínio e acesso externo na infraestrutura.

## Exemplo prático

Controller chama serviço de aplicação, que usa domínio e repositório.

## Quando adotar?

Sistemas pequenos e médios com implantação única.

## Quando evitar?

Evite camadas pass-through e dependências circulares.

## Vantagens

Simplicidade, organização e onboarding fácil.

## Desvantagens e trade-offs

Pode espalhar uma feature por muitas camadas.

## Comparação com outras arquiteturas

A diferença principal está em como responsabilidades, dependências e implantação são organizadas.

Clean Architecture, Vertical Slice e monólito.

A escolha deve ser guiada pelos requisitos e pelos custos operacionais.

## Dúvidas

- Consigo explicar **Arquitetura em camadas** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Mark Richards e Neal Ford — *Fundamentals of Software Architecture*
- Neal Ford et al. — *Software Architecture: The Hard Parts*
- Simon Brown — C4 Model.
