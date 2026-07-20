---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: []
---

# Constraints

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Regras declarativas que preservam validade dos dados.

## O que é?

Incluem NOT NULL, CHECK, UNIQUE, PRIMARY KEY e FOREIGN KEY.

## Papel na modelagem

Garante integridade independentemente da aplicação.

## Como funciona?

O SGBD valida cada escrita e rejeita estados inválidos.

## Exemplo SQL

```sql
CREATE TABLE produto (
  id bigint PRIMARY KEY,
  nome text NOT NULL,
  preco numeric(12,2) CHECK (preco >= 0),
  sku text UNIQUE
);
```

## Regras e restrições

Use nomes explícitos e regras que o banco possa validar com segurança.

## Impactos de performance

UNIQUE e PK criam índices; CHECK e FK adicionam validação na escrita.

## Erros comuns

Desabilitar constraints permanentemente ou confiar somente na aplicação.

## Relações com outros conceitos

Integridade, validação, transações, PK e FK.

## Dúvidas

- Consigo explicar **Constraints** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Markus Winand — *SQL Performance Explained*
- Documentação oficial do SGBD utilizado.
