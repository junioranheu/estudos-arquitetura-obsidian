---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos, arvores]
---

# Árvore binária

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Árvore em que cada nó possui no máximo dois filhos.

## O que é?

Os filhos são normalmente chamados de esquerdo e direito.

## Por que é importante?

É a base para BSTs, heaps, árvores de expressão e várias técnicas de busca.

## Como funciona?

Pode ser percorrida em pré-ordem, em ordem, pós-ordem ou por nível.

## Complexidade típica

| Operação | Custo |
|---|---|
| Percorrer | O(n) |
| Buscar sem regra de ordenação | O(n) |

## Exemplo em C#

```csharp
public sealed class BinaryNode<T>
{
    public required T Value { get; init; }
    public BinaryNode<T>? Left { get; set; }
    public BinaryNode<T>? Right { get; set; }
}
```

## Quando usar?

Para expressões, decisões e como base de árvores de busca e heaps.

## Quando evitar ou ter cuidado?

Ser binária não implica estar ordenada ou balanceada.

## Relações com outros conceitos

- [[Árvore]]
- [[Árvore binária de busca]]
- [[Heap]]

## Dúvidas para revisão

- Consigo explicar **Árvore binária** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
