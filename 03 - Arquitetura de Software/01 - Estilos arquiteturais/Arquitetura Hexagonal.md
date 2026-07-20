---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Arquitetura Hexagonal

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Visão geral

Protege o núcleo por portas e adaptadores.

Ports and Adapters trata UI, banco e mensageria como detalhes externos.

## Problema que busca resolver

Permite testar o núcleo e trocar tecnologias nas bordas.

## Princípios e características

- Protege o núcleo por portas e adaptadores.
- Ports and Adapters trata UI, banco e mensageria como detalhes externos.

## Componentes e responsabilidades

Núcleo de aplicação/domínio, portas de entrada e saída, adaptadores primários e secundários.

## Fluxo de execução

Um adaptador de entrada chama uma porta; o núcleo executa e usa portas de saída implementadas externamente.

## Exemplo prático

API REST chama porta de entrada; PostgreSQL implementa porta de saída.

## Quando adotar?

Domínios com integrações variadas.

## Quando evitar?

Evite cerimônia excessiva em CRUD simples.

## Vantagens

Testabilidade e limites claros.

## Desvantagens e trade-offs

Mais interfaces, mapeamentos e decisões.

## Comparação com outras arquiteturas

A diferença principal está em como responsabilidades, dependências e implantação são organizadas.

Clean Architecture, Onion, DIP e camadas.

A escolha deve ser guiada pelos requisitos e pelos custos operacionais.

## Dúvidas

- Consigo explicar **Arquitetura Hexagonal** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Mark Richards e Neal Ford — *Fundamentals of Software Architecture*
- Neal Ford et al. — *Software Architecture: The Hard Parts*
- Simon Brown — C4 Model.
