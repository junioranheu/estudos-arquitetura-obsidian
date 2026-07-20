---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos, arvores]
---

# AVL

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Árvore binária de busca balanceada em que as alturas das subárvores diferem no máximo por um.

## O que é?

Mantém um fator de balanceamento para cada nó e executa rotações após alterações.

## Por que é importante?

Oferece buscas muito previsíveis por manter balanceamento mais rígido.

## Como funciona?

Inserções e remoções atualizam alturas e aplicam rotações simples ou duplas.

## Complexidade típica

| Operação | Custo |
|---|---:|
| Buscar | O(log n) |
| Inserir | O(log n) |
| Remover | O(log n) |

## Exemplo em C#

```csharp
// A BCL não expõe uma AVL pronta.
// SortedDictionary<TKey,TValue> oferece comportamento ordenado com árvore balanceada.
```

## Quando usar?

Quando buscas são muito frequentes e um balanceamento rígido é desejável.

## Quando evitar ou ter cuidado?

Pode executar mais rotações que uma Red-Black Tree em cargas com muitas escritas.

## Relações com outros conceitos

- [[Árvore balanceada]]
- [[Red-Black Tree]]
- [[Árvore binária de busca]]

## Dúvidas para revisão

- Consigo explicar **AVL** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
