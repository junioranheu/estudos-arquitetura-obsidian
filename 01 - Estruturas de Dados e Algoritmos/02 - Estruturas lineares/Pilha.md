---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Pilha

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Estrutura LIFO: o último elemento inserido é o primeiro removido.

## O que é?

Oferece principalmente as operações empilhar, consultar o topo e desempilhar.

## Por que é importante?

Modela naturalmente chamadas, desfazer ações, parsing e busca em profundidade.

## Como funciona?

Todas as operações principais ocorrem em uma única extremidade chamada topo.

## Complexidade típica

| Operação | Custo |
|---|---|
| Push | O(1) amortizado |
| Pop | O(1) |
| Peek | O(1) |

## Exemplo em C#

```csharp
var pilha = new Stack<string>();
pilha.Push("A");
pilha.Push("B");
string topo = pilha.Pop(); // B
```

## Quando usar?

Para desfazer/refazer, validação de símbolos, DFS iterativa e avaliação de expressões.

## Quando evitar ou ter cuidado?

Evite quando a ordem necessária for FIFO ou quando for preciso acessar itens arbitrários.

## Relações com outros conceitos

- [[Fila]]
- [[Recursão]]
- [[DFS]]

## Dúvidas para revisão

- Consigo explicar **Pilha** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
