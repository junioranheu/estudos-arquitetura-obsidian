---
tipo: conceito
status: nao-iniciado
dificuldade: avancado
tags: []
---

# Publicação de eventos de domínio

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Propagação de fatos relevantes ocorridos no domínio.

## Definição

Eventos de domínio registram que uma regra foi executada e algo significativo aconteceu.

## Papel no DDD

Desacopla efeitos secundários da regra principal.

## Como identificar ou modelar?

O agregado cria o evento; após a transação, handlers locais ou integração o processam.

## Exemplo de domínio

PedidoConfirmado atualiza projeção e prepara mensagem externa.

## Regras e cuidados

Ordem, duplicidade e falha de publicação.

Evite publicar antes da transação ou eventos irrelevantes.

## Erros comuns

- Escolher tecnologia antes de entender o problema.
- Ignorar volume, falhas ou operação.
- Não registrar hipóteses e consequências.

## Relações com outros conceitos

Eventos de domínio, integration events e outbox.

## Dúvidas

- Consigo explicar **Publicação de eventos de domínio** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Eric Evans — *Domain-Driven Design*
- Vaughn Vernon — *Implementing Domain-Driven Design*
- Vaughn Vernon — *Domain-Driven Design Distilled*.
