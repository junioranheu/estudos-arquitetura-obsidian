---
tipo: conceito
status: nao-iniciado
dificuldade: avancado
tags: []
---

# Serverless Architecture

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Visão geral

Usa funções e serviços gerenciados sem administrar servidores diretamente.

Transfere provisionamento, escala e parte da operação ao provedor.

## Problema que busca resolver

Reduz esforço operacional e cobra conforme uso em cargas adequadas.

## Princípios e características

- Usa funções e serviços gerenciados sem administrar servidores diretamente.
- Transfere provisionamento, escala e parte da operação ao provedor.

## Componentes e responsabilidades

Funções, gatilhos, API gateway, filas, storage, bancos gerenciados e observabilidade.

## Fluxo de execução

Um evento ativa a função; a plataforma provisiona a execução, processa e encerra conforme a demanda.

## Exemplo prático

Upload em object storage dispara função de processamento.

## Quando adotar?

Cargas event-driven, intermitentes e automações.

## Quando evitar?

Evite execução longa, estado local forte ou latência extrema.

## Vantagens

Escala automática e menor administração.

## Desvantagens e trade-offs

Cold start, limites do provedor e lock-in.

## Comparação com outras arquiteturas

A diferença principal está em como responsabilidades, dependências e implantação são organizadas.

FaaS, event-driven, cloud-native e containers.

A escolha deve ser guiada pelos requisitos e pelos custos operacionais.

## Dúvidas

- Consigo explicar **Serverless Architecture** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Mark Richards e Neal Ford — *Fundamentals of Software Architecture*
- Neal Ford et al. — *Software Architecture: The Hard Parts*
- Simon Brown — C4 Model.
