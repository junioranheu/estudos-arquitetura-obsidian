---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Estruturas lineares e não lineares

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Estruturas lineares organizam elementos em sequência; não lineares representam hierarquias ou redes.

## O que é?

Arrays, listas, pilhas e filas são lineares; árvores e grafos são não lineares.

## Por que é importante?

A classificação ajuda a escolher uma representação compatível com as relações reais do problema.

## Como funciona?

Na estrutura linear, cada posição possui uma ordem principal. Na não linear, um elemento pode se relacionar com vários outros.

## Complexidade típica

| Categoria | Exemplos |
|---|---|
| Linear | Array, lista, pilha, fila |
| Não linear | Árvore, heap, trie, grafo |

## Exemplo em C#

```csharp
var fila = new Queue<string>();
var grafo = new Dictionary<int, List<int>>();
```

## Quando usar?

Use estruturas lineares para sequências e não lineares para hierarquias, dependências e conexões.

## Quando evitar ou ter cuidado?

Não force dados hierárquicos em listas planas quando isso tornar consultas e regras confusas.

## Relações com outros conceitos

- [[Array]]
- [[Lista encadeada]]
- [[Árvore]]
- [[Grafo]]

## Dúvidas para revisão

- Consigo explicar **Estruturas lineares e não lineares** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
