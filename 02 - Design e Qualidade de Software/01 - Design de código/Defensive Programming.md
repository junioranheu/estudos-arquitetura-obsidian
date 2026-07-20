---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Defensive Programming

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Prática de antecipar entradas inválidas, estados inesperados e falhas externas.

## O que é?

Adiciona validações, contratos, limites e tratamento para impedir propagação de erros.

## Por que é importante?

Aumenta robustez em ambientes não totalmente confiáveis.

## Como funciona?

Valida dados nas bordas, protege invariantes e trata dependências de forma explícita.

## Exemplo prático

Validar tamanho e formato de arquivo antes do processamento e limitar retries.

## Aplicações

APIs públicas, integrações, parsing e operações críticas.

## Limitações e cuidados

Mais verbosidade e risco de esconder bugs.

Evite validações redundantes e captura silenciosa de exceções.

## Relações com outros conceitos

Fail Fast, validação, resiliência e segurança.

## Dúvidas

- Consigo explicar **Defensive Programming** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Fowler — *Refactoring*
- Robert C. Martin — *Clean Code*
- Gamma et al. — *Design Patterns*.
