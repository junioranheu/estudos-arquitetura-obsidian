---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Deque

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Fila de duas pontas que permite inserir e remover no início e no fim.

## O que é?

Combina comportamentos de pilha e fila em uma única estrutura.

## Por que é importante?

É útil em janelas deslizantes, algoritmos de busca e buffers com operações nas duas extremidades.

## Como funciona?

Mantém acesso eficiente às duas pontas, geralmente com buffer circular ou lista duplamente encadeada.

## Complexidade típica

| Operação | Custo |
|---|---|
| Inserir/remover nas pontas | O(1) amortizado |
| Busca interna | O(n) |

## Exemplo em C#

```csharp
// O .NET não possui uma coleção Deque<T> geral na BCL.
// Pode ser implementada com buffer circular ou biblioteca específica.
```

## Quando usar?

Quando o algoritmo precisa operar eficientemente nas duas extremidades.

## Quando evitar ou ter cuidado?

Evite improvisar com List<T>.RemoveAt(0), pois isso desloca os elementos e custa O(n).

## Relações com outros conceitos

- [[Fila]]
- [[Pilha]]
- [[Lista duplamente encadeada]]

## Dúvidas para revisão

- Consigo explicar **Deque** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
