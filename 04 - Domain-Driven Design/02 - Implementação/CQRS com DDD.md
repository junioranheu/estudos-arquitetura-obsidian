---
tipo: conceito
status: nao-iniciado
dificuldade: avancado
tags: []
---

# CQRS com DDD

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Separa modelos de escrita e leitura conforme suas necessidades.

## Definição

Comandos alteram agregados; consultas usam modelos otimizados, sem exigir o mesmo formato.

## Papel no DDD

Evita deformar o modelo de domínio para atender relatórios.

## Como identificar ou modelar?

Handlers carregam agregados e preservam invariantes; projeções atendem leituras.

## Exemplo de domínio

ConfirmarPedido altera o agregado; uma projeção lista pedidos por cliente.

## Regras e cuidados

Consistência eventual e duplicação de modelos.

Evite em CRUD simples ou quando um modelo atende bem ambos.

## Erros comuns

- Escolher tecnologia antes de entender o problema.
- Ignorar volume, falhas ou operação.
- Não registrar hipóteses e consequências.

## Relações com outros conceitos

DDD, comandos, projeções, eventos e Event Sourcing.

## Dúvidas

- Consigo explicar **CQRS com DDD** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Eric Evans — *Domain-Driven Design*
- Vaughn Vernon — *Implementing Domain-Driven Design*
- Vaughn Vernon — *Domain-Driven Design Distilled*.
