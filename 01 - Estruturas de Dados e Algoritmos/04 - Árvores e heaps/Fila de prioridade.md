---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos, arvores]
---

# Fila de prioridade

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Coleção que remove primeiro o elemento de maior prioridade, e não necessariamente o mais antigo.

## O que é?

É uma abstração normalmente implementada com heap.

## Por que é importante?

Permite agendar tarefas, eventos e caminhos candidatos de acordo com custo ou urgência.

## Como funciona?

Cada item recebe uma prioridade; a estrutura mantém o melhor candidato na raiz.

## Complexidade típica

| Operação | Custo com heap |
|---|---:|
| Enqueue | O(log n) |
| Dequeue | O(log n) |
| Peek | O(1) |

## Exemplo em C#

```csharp
var fila = new PriorityQueue<string, int>();
fila.Enqueue("baixa", 100);
fila.Enqueue("alta", 1);
string proxima = fila.Dequeue(); // alta
```

## Quando usar?

Para schedulers, simulações, Dijkstra e processamento por urgência.

## Quando evitar ou ter cuidado?

Prioridades iguais podem não preservar ordem de chegada; adicione um critério de desempate se estabilidade for necessária.

## Relações com outros conceitos

- [[Heap]]
- [[Fila]]
- [[Dijkstra]]

## Dúvidas para revisão

- Consigo explicar **Fila de prioridade** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
