---
tipo: conceito
status: nao-iniciado
dificuldade: avancado
tags: []
---

# Particionamento

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Divisão lógica ou física de dados em partes menores.

## O que é?

Distribui linhas por faixa, hash, lista ou critério semelhante.

## Problema de escala que resolve

Reduz o conjunto de dados examinado e facilita manutenção de tabelas grandes.

## Como funciona?

O banco direciona registros e pode eliminar partições irrelevantes na consulta.

## Estratégias e variações

Range, hash, list e particionamento composto.

## Exemplo prático

Eventos são particionados por mês.

## Quando adotar?

Tabelas grandes com chave previsível.

## Riscos e trade-offs

Skew, chave ruim e operações entre partições.

## Como monitorar?

Distribuição, pruning, tamanho, crescimento e queries que varrem tudo.

## Relações com outros conceitos

Sharding, retenção e distribuição de dados.

## Dúvidas

- Consigo explicar **Particionamento** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Markus Winand — *SQL Performance Explained*
- Documentação oficial do SGBD utilizado.
