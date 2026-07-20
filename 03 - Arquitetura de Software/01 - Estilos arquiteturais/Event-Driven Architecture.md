---
tipo: conceito
status: nao-iniciado
dificuldade: avancado
tags: []
---

# Event-Driven Architecture

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Visão geral

Componentes reagem a fatos publicados como eventos.

Desacopla produtores e consumidores no tempo e no espaço.

## Problema que busca resolver

Permite integração assíncrona e absorção de picos.

## Princípios e características

- Componentes reagem a fatos publicados como eventos.
- Desacopla produtores e consumidores no tempo e no espaço.

## Componentes e responsabilidades

Produtores, eventos, broker ou event bus, consumidores, contratos e observabilidade.

## Fluxo de execução

O produtor confirma sua mudança, publica o evento e consumidores independentes atualizam seus próprios estados.

## Exemplo prático

PedidoCriado dispara estoque, cobrança e notificação.

## Quando adotar?

Fluxos assíncronos e integração entre domínios.

## Quando evitar?

Evite quando consistência imediata e fluxo síncrono simples são centrais.

## Vantagens

Baixo acoplamento, escala e extensibilidade.

## Desvantagens e trade-offs

Consistência eventual, duplicidade, ordem e observabilidade.

## Comparação com outras arquiteturas

A diferença principal está em como responsabilidades, dependências e implantação são organizadas.

Mensageria, pub/sub, outbox, idempotência e CQRS.

A escolha deve ser guiada pelos requisitos e pelos custos operacionais.

## Dúvidas

- Consigo explicar **Event-Driven Architecture** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Mark Richards e Neal Ford — *Fundamentals of Software Architecture*
- Neal Ford et al. — *Software Architecture: The Hard Parts*
- Simon Brown — C4 Model.
