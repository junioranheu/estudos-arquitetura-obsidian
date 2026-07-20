---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: []
---

# Chaves primárias

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Colunas que identificam unicamente cada linha.

## O que é?

São únicas e não nulas, formando a identidade relacional do registro.

## Papel na modelagem

Permite referências e operações determinísticas.

## Como funciona?

O banco cria restrição e normalmente índice para garantir unicidade.

## Exemplo SQL

```sql
CREATE TABLE cliente (
  id bigint GENERATED ALWAYS AS IDENTITY PRIMARY KEY,
  nome text NOT NULL
);
```

## Regras e restrições

Deve ser única, não nula e preferencialmente imutável.

## Impactos de performance

Chaves estreitas reduzem índices; valores sequenciais tendem a favorecer inserções em B-tree.

## Erros comuns

Usar dado mutável, chave larga ou GUID aleatório sem avaliar o SGBD.

## Relações com outros conceitos

FK, chave natural, substituta e UNIQUE.

## Dúvidas

- Consigo explicar **Chaves primárias** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Markus Winand — *SQL Performance Explained*
- Documentação oficial do SGBD utilizado.
