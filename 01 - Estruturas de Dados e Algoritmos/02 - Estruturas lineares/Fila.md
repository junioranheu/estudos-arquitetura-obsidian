---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Fila

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Estrutura FIFO: o primeiro elemento inserido é o primeiro removido.

## O que é?

Representa uma sequência de atendimento ou processamento por ordem de chegada.

## Por que é importante?

É útil em processamento assíncrono, buffers, BFS e controle de tarefas.

## Como funciona?

Itens entram no final e saem no início.

## Complexidade típica

| Operação | Custo |
|---|---|
| Enqueue | O(1) amortizado |
| Dequeue | O(1) |
| Peek | O(1) |

## Exemplo em C#

```csharp
var fila = new Queue<string>();
fila.Enqueue("primeiro");
fila.Enqueue("segundo");
string item = fila.Dequeue();
```

## Quando usar?

Para processar itens pela ordem de chegada e implementar BFS.

## Quando evitar ou ter cuidado?

Uma fila em memória não substitui um broker durável quando é preciso persistência, retry ou distribuição.

## Relações com outros conceitos

- [[Pilha]]
- [[Deque]]
- [[BFS]]
- [[Fila]]

## Dúvidas para revisão

- Consigo explicar **Fila** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
