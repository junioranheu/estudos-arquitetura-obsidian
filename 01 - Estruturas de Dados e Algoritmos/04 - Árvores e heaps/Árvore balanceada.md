---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos, arvores]
---

# Árvore balanceada

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Árvore de busca que limita sua altura para manter operações próximas de O(log n).

## O que é?

Usa rotações ou regras estruturais para evitar ramos excessivamente profundos.

## Por que é importante?

Evita que entradas ordenadas degradem uma árvore de busca para O(n).

## Como funciona?

Após inserções e remoções, a árvore verifica invariantes e reorganiza nós quando necessário.

## Complexidade típica

| Operação | Custo esperado |
|---|---:|
| Buscar | O(log n) |
| Inserir | O(log n) |
| Remover | O(log n) |

## Exemplo em C#

```csharp
var mapaOrdenado = new SortedDictionary<int, string>();
mapaOrdenado[10] = "dez";
```

## Quando usar?

Para coleções ordenadas com alterações frequentes e busca previsível.

## Quando evitar ou ter cuidado?

Possui maior complexidade de implementação e overhead que uma tabela hash.

## Relações com outros conceitos

- [[Árvore binária de busca]]
- [[AVL]]
- [[Red-Black Tree]]

## Dúvidas para revisão

- Consigo explicar **Árvore balanceada** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
