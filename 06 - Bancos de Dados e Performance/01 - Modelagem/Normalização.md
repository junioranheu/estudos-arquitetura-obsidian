---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Normalização

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Processo de reduzir redundância e anomalias.

## O que é?

Formas normais orientam separar fatos conforme dependências.

## Papel na modelagem

Evita inconsistências de inserção, atualização e exclusão.

## Como funciona?

Identifica dependências funcionais e move atributos para tabelas apropriadas.

## Exemplo SQL

```sql
-- Evite repetir os dados do cliente em cada pedido.
-- Armazene cliente_id e consulte a tabela cliente.
```

## Regras e restrições

1FN elimina grupos repetidos; 2FN remove dependências parciais; 3FN remove dependências transitivas.

## Impactos de performance

Pode aumentar joins, mas reduz escrita redundante e inconsistência.

## Erros comuns

Normalizar sem entender acesso ou ignorar desnormalização consciente.

## Relações com outros conceitos

Formas normais, desnormalização e dependência funcional.

## Dúvidas

- Consigo explicar **Normalização** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Markus Winand — *SQL Performance Explained*
- Documentação oficial do SGBD utilizado.
