---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: []
---

# Entidades e relacionamentos

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Modelagem de objetos relevantes e suas ligações.

## O que é?

Entidades possuem identidade; relacionamentos descrevem associação e cardinalidade.

## Papel na modelagem

Traduz o domínio para estrutura coerente.

## Como funciona?

Mapeia um-para-um, um-para-muitos e muitos-para-muitos em tabelas e chaves.

## Exemplo SQL

```sql
CREATE TABLE pedido (
  id bigint PRIMARY KEY,
  cliente_id bigint NOT NULL REFERENCES cliente(id)
);
```

## Regras e restrições

Explicite cardinalidade, opcionalidade, ownership e ações de exclusão.

## Impactos de performance

Relacionamentos influenciam joins, índices e padrões de acesso.

## Erros comuns

Relações muitos-para-muitos sem entidade associativa e cascatas indevidas.

## Relações com outros conceitos

ER, cardinalidade, normalização, PK e FK.

## Dúvidas

- Consigo explicar **Entidades e relacionamentos** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Markus Winand — *SQL Performance Explained*
- Documentação oficial do SGBD utilizado.
