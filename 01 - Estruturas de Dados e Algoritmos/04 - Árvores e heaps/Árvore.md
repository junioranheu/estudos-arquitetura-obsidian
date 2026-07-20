---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos, arvores]
---

# Árvore

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Estrutura hierárquica formada por nós ligados por relações de pai e filho.

## O que é?

Possui uma raiz, subárvores e folhas; normalmente não contém ciclos.

## Por que é importante?

Representa hierarquias de forma natural e permite buscas, ordenação e divisão recursiva.

## Como funciona?

Cada nó mantém referências aos filhos; a profundidade indica a distância até a raiz e a altura mede o maior caminho até uma folha.

## Complexidade típica

| Operação | Custo |
|---|---|
| Percorrer todos os nós | O(n) |
| Buscar | Depende do tipo e da altura |

## Exemplo em C#

```csharp
public sealed class Node<T>
{
    public required T Value { get; init; }
    public List<Node<T>> Children { get; } = [];
}
```

## Quando usar?

Para menus, sistemas de arquivos, organogramas, ASTs e hierarquias de domínio.

## Quando evitar ou ter cuidado?

Ciclos acidentais podem causar recursão infinita; árvores profundas podem estourar a pilha.

## Relações com outros conceitos

- [[Árvore binária]]
- [[Grafo]]
- [[Recursão]]

## Dúvidas para revisão

- Consigo explicar **Árvore** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
