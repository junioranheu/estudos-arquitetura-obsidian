---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Lista circular

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Lista em que o último nó aponta novamente para o primeiro.

## O que é?

Pode ser simplesmente ou duplamente encadeada e não possui um final nulo natural.

## Por que é importante?

Representa ciclos de forma direta, como escalonamento round-robin.

## Como funciona?

A navegação continua retornando ao início; por isso, a condição de parada deve ser explícita.

## Complexidade típica

| Operação | Custo |
|---|---|
| Percorrer n elementos | O(n) |
| Inserir/remover com nó conhecido | O(1) |

## Exemplo em C#

```csharp
// LinkedList<T> não é circular por padrão.
// A circularidade normalmente é implementada controlando manualmente o próximo nó.
```

## Quando usar?

Para rotação contínua de participantes, buffers circulares e agendadores.

## Quando evitar ou ter cuidado?

Tenha cuidado com loops infinitos, referências inválidas e condições de parada.

## Relações com outros conceitos

- [[Lista encadeada]]
- [[Fila]]
- [[Deque]]

## Dúvidas para revisão

- Consigo explicar **Lista circular** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
