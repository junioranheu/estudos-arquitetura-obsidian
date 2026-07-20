---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: []
---

# Monólito

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Visão geral

Aplicação implantada como uma única unidade.

Funcionalidades compartilham processo e normalmente ciclo de versão.

## Problema que busca resolver

Oferece simplicidade de desenvolvimento e operação.

## Princípios e características

- Aplicação implantada como uma única unidade.
- Funcionalidades compartilham processo e normalmente ciclo de versão.

## Componentes e responsabilidades

Uma aplicação, um processo de implantação e componentes internos, frequentemente com banco compartilhado.

## Fluxo de execução

A requisição entra na aplicação e o processamento ocorre no mesmo processo, salvo integrações externas.

## Exemplo prático

Uma API contém cadastro, pedidos, estoque e relatórios.

## Quando adotar?

Produtos novos, equipes pequenas e domínios não distribuídos.

## Quando evitar?

Evite monólito sem modularidade quando sistema e equipe crescerem.

## Vantagens

Deploy simples, chamadas locais e transações diretas.

## Desvantagens e trade-offs

Escala e implantação conjuntas, acoplamento e base crescente.

## Comparação com outras arquiteturas

A diferença principal está em como responsabilidades, dependências e implantação são organizadas.

Monólito modular, microsserviços e camadas.

A escolha deve ser guiada pelos requisitos e pelos custos operacionais.

## Dúvidas

- Consigo explicar **Monólito** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Mark Richards e Neal Ford — *Fundamentals of Software Architecture*
- Neal Ford et al. — *Software Architecture: The Hard Parts*
- Simon Brown — C4 Model.
