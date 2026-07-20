---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: []
---

# Chaves estrangeiras

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Restrições que ligam uma coluna a uma chave de outra tabela.

## O que é?

Garantem integridade referencial entre registros relacionados.

## Papel na modelagem

Impede referências órfãs e documenta relações.

## Como funciona?

O banco valida inserções, atualizações e exclusões conforme a ação configurada.

## Exemplo SQL

```sql
ALTER TABLE pedido
ADD CONSTRAINT fk_pedido_cliente
FOREIGN KEY (cliente_id) REFERENCES cliente(id);
```

## Regras e restrições

A coluna referenciada deve ser PRIMARY KEY ou UNIQUE. Ações comuns: RESTRICT, CASCADE, SET NULL e NO ACTION.

## Impactos de performance

Indexe FKs usadas em joins e exclusões; muitas validações aumentam o custo de escrita.

## Erros comuns

Referenciar coluna não única, usar CASCADE sem avaliar impacto e não indexar a FK.

## Relações com outros conceitos

PK, constraints, cardinalidade e índices.

## Dúvidas

- Consigo explicar **Chaves estrangeiras** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Markus Winand — *SQL Performance Explained*
- Documentação oficial do SGBD utilizado.
