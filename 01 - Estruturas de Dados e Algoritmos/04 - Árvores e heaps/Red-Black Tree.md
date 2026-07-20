---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos, arvores]
---

# Red-Black Tree

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Árvore binária de busca balanceada por regras de cores associadas aos nós.

## O que é?

As regras limitam a altura sem exigir o balanceamento rígido de uma AVL.

## Por que é importante?

Equilibra bom desempenho de leitura com menor quantidade média de rotações em escritas.

## Como funciona?

Após inserir ou remover, recolore nós e executa rotações para restaurar as invariantes.

## Complexidade típica

| Operação | Custo |
|---|---:|
| Buscar | O(log n) |
| Inserir | O(log n) |
| Remover | O(log n) |

## Exemplo em C#

```csharp
var ordenado = new SortedDictionary<int, string>();
ordenado.Add(2, "B");
ordenado.Add(1, "A");
```

## Quando usar?

Para mapas e conjuntos ordenados com leituras e escritas frequentes.

## Quando evitar ou ter cuidado?

Não oferece busca média O(1) como Dictionary e exige comparador consistente.

## Relações com outros conceitos

- [[Árvore balanceada]]
- [[AVL]]
- [[Dictionary, SortedDictionary e ConcurrentDictionary]]

## Dúvidas para revisão

- Consigo explicar **Red-Black Tree** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
