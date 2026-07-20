---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Lista duplamente encadeada

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Lista em que cada nó referencia tanto o próximo quanto o anterior.

## O que é?

É uma variação da lista encadeada que permite percorrer nos dois sentidos.

## Por que é importante?

Facilita remoções e navegação reversa quando o nó atual é conhecido.

## Como funciona?

Cada nó armazena valor, referência anterior e referência seguinte.

## Complexidade típica

| Operação | Custo |
|---|---|
| Busca | O(n) |
| Inserção/remoção com nó conhecido | O(1) |
| Navegação anterior/próximo | O(1) |

## Exemplo em C#

```csharp
var lista = new LinkedList<string>();
var atual = lista.AddLast("B");
lista.AddBefore(atual, "A");
lista.AddAfter(atual, "C");
```

## Quando usar?

Para históricos navegáveis, filas internas, editores e estruturas LRU.

## Quando evitar ou ter cuidado?

Consome mais memória por nó e continua sem acesso O(1) por índice.

## Relações com outros conceitos

- [[Lista encadeada]]
- [[Deque]]
- [[Cache]]

## Dúvidas para revisão

- Consigo explicar **Lista duplamente encadeada** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
