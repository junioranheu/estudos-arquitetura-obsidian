---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos, arvores]
---

# Árvore binária de busca

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Árvore binária ordenada em que valores menores ficam à esquerda e maiores à direita.

## O que é?

A propriedade de ordenação permite descartar metade de uma subárvore a cada comparação quando a árvore está equilibrada.

## Por que é importante?

Suporta busca, inserção, remoção e iteração ordenada.

## Como funciona?

Cada operação segue esquerda ou direita até encontrar a chave ou uma posição vazia.

## Complexidade típica

| Operação | Média balanceada | Pior caso degenerado |
|---|---:|---:|
| Buscar | O(log n) | O(n) |
| Inserir | O(log n) | O(n) |
| Remover | O(log n) | O(n) |

## Exemplo em C#

```csharp
var ordenado = new SortedSet<int> { 30, 10, 20 };
foreach (int valor in ordenado) Console.WriteLine(valor);
```

## Quando usar?

Quando precisa manter dados ordenados e realizar consultas por faixa.

## Quando evitar ou ter cuidado?

Uma BST simples pode virar uma lista encadeada; prefira implementações balanceadas em produção.

## Relações com outros conceitos

- [[Árvore binária]]
- [[Árvore balanceada]]
- [[Red-Black Tree]]

## Dúvidas para revisão

- Consigo explicar **Árvore binária de busca** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
