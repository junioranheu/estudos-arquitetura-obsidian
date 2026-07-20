---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos, arvores]
---

# Heap

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Árvore quase completa em que cada pai respeita uma relação de prioridade com os filhos.

## O que é?

Em min-heap, o menor elemento fica na raiz; em max-heap, o maior fica na raiz.

## Por que é importante?

Permite consultar e remover rapidamente o item de maior prioridade.

## Como funciona?

Normalmente é armazenado em array; os índices calculam pai e filhos sem referências explícitas.

## Complexidade típica

| Operação | Custo |
|---|---:|
| Consultar raiz | O(1) |
| Inserir | O(log n) |
| Remover raiz | O(log n) |
| Construir heap | O(n) |

## Exemplo em C#

```csharp
var heap = new PriorityQueue<string, int>();
heap.Enqueue("normal", 10);
heap.Enqueue("urgente", 1);
```

## Quando usar?

Para filas de prioridade, top K, agendamento e algoritmos de caminho mínimo.

## Quando evitar ou ter cuidado?

Heap não mantém todos os elementos globalmente ordenados e não é ideal para buscar um item arbitrário.

## Relações com outros conceitos

- [[Fila de prioridade]]
- [[Heap Sort]]
- [[Dijkstra]]

## Dúvidas para revisão

- Consigo explicar **Heap** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
