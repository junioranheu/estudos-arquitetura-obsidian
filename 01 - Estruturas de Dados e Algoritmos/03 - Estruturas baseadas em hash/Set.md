---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Set

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Coleção de elementos únicos sem acesso por índice.

## O que é?

Um conjunto representa pertencimento e elimina duplicidades.

## Por que é importante?

Oferece verificações de existência e operações matemáticas como união e interseção.

## Como funciona?

Normalmente usa tabela hash; também pode ser implementado com árvore ordenada.

## Complexidade típica

| Operação em HashSet | Médio |
|---|---:|
| Add | O(1) |
| Contains | O(1) |
| Remove | O(1) |

## Exemplo em C#

```csharp
var ids = new HashSet<int> { 1, 2, 2, 3 };
bool novo = ids.Add(4);
ids.IntersectWith(new[] { 2, 3, 5 });
```

## Quando usar?

Para deduplicar, validar pertencimento e comparar grupos.

## Quando evitar ou ter cuidado?

Evite quando precisa preservar duplicatas ou acessar pela posição.

## Relações com outros conceitos

- [[Tabela hash]]
- [[Map e Dictionary]]
- [[HashSet]]

## Dúvidas para revisão

- Consigo explicar **Set** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
