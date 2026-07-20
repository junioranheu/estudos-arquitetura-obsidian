---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Busca binária

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Busca que divide repetidamente uma coleção ordenada ao meio.

## O que é?

Compara o alvo com o elemento central e elimina metade do espaço de busca.

## Por que é importante?

Reduz uma busca em milhões de elementos para poucas dezenas de comparações.

## Como funciona?

Mantém limites inferior e superior até encontrar o valor ou esvaziar o intervalo.

## Complexidade típica

| Métrica | Custo |
|---|---:|
| Tempo | O(log n) |
| Espaço iterativo | O(1) |

## Exemplo em C#

```csharp
int indice = Array.BinarySearch(valoresOrdenados, procurado);
```

## Quando usar?

Para dados ordenados com acesso por índice e muitas consultas.

## Quando evitar ou ter cuidado?

Não funciona corretamente em dados não ordenados; ordenar apenas para uma busca pode custar mais que busca linear.

## Relações com outros conceitos

- [[Array]]
- [[Big O]]
- [[Busca linear]]
- [[Árvore binária de busca]]

## Dúvidas para revisão

- Consigo explicar **Busca binária** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
