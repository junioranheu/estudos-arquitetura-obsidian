---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Onion Architecture

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Visão geral

Organiza o sistema em anéis com o domínio no centro.

Dependências apontam para dentro, preservando o núcleo de detalhes externos.

## Problema que busca resolver

Mantém políticas independentes de tecnologia.

## Princípios e características

- Organiza o sistema em anéis com o domínio no centro.
- Dependências apontam para dentro, preservando o núcleo de detalhes externos.

## Componentes e responsabilidades

Domínio no centro, serviços de domínio, aplicação e infraestrutura nos anéis externos.

## Fluxo de execução

Chamadas entram pelas bordas e avançam para dentro; dependências de código apontam ao núcleo.

## Exemplo prático

Domínio define IRepositorioCliente; infraestrutura implementa com SQL.

## Quando adotar?

Sistemas orientados a domínio.

## Quando evitar?

Evite excesso de anéis em aplicações simples.

## Vantagens

Testabilidade e isolamento do domínio.

## Desvantagens e trade-offs

Indireção e sobreposição com outras arquiteturas limpas.

## Comparação com outras arquiteturas

A diferença principal está em como responsabilidades, dependências e implantação são organizadas.

Clean Architecture, Hexagonal, DIP e DDD.

A escolha deve ser guiada pelos requisitos e pelos custos operacionais.

## Dúvidas

- Consigo explicar **Onion Architecture** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Mark Richards e Neal Ford — *Fundamentals of Software Architecture*
- Neal Ford et al. — *Software Architecture: The Hard Parts*
- Simon Brown — C4 Model.
