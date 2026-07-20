---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: []
---

# Modelagem relacional

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Representação de dados em relações, chaves e restrições.

## O que é?

Organiza fatos em tabelas e usa operações relacionais para consultar e combinar.

## Papel na modelagem

Oferece integridade e consultas flexíveis.

## Como funciona?

Identifica entidades, atributos, chaves, cardinalidades e dependências.

## Exemplo SQL

```sql
CREATE TABLE pedido_item (
  pedido_id bigint REFERENCES pedido(id),
  produto_id bigint REFERENCES produto(id),
  quantidade int CHECK (quantidade > 0),
  PRIMARY KEY (pedido_id, produto_id)
);
```

## Regras e restrições

Modele fatos e dependências antes de otimizar para consultas.

## Impactos de performance

Tipos, chaves e índices devem refletir cardinalidade e acesso.

## Erros comuns

Misturar conceitos em uma tabela ou armazenar listas em texto sem necessidade.

## Relações com outros conceitos

Normalização, SQL, constraints e índices.

## Dúvidas

- Consigo explicar **Modelagem relacional** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Markus Winand — *SQL Performance Explained*
- Documentação oficial do SGBD utilizado.
