---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Testabilidade

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Facilidade de controlar entradas, observar saídas e verificar comportamento.

## O que é?

Código testável tem dependências explícitas, efeitos isoláveis e resultados determinísticos.

## Por que é importante?

Feedback rápido reduz regressões e permite refatorar.

## Como funciona?

Entradas são injetadas e infraestrutura fica atrás de limites substituíveis.

## Exemplo prático

Serviço recebe IClock e IRepositorio para simular tempo e persistência.

## Aplicações

Regras de negócio e componentes com risco de mudança.

## Limitações e cuidados

Abstrações criadas só para mocks podem piorar o design.

Evite expor detalhes internos apenas para testes.

## Relações com outros conceitos

DI, determinismo, testes automatizados e arquitetura.

## Dúvidas

- Consigo explicar **Testabilidade** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Fowler — *Refactoring*
- Robert C. Martin — *Clean Code*
- Gamma et al. — *Design Patterns*.
