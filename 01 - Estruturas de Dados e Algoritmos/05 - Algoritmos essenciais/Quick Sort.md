---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Quick Sort

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Algoritmo que escolhe um pivô, particiona os elementos e ordena recursivamente as partes.

## O que é?

Elementos menores que o pivô vão para um lado e maiores para o outro.

## Por que é importante?

Costuma ser rápido em memória por boa localidade e particionamento in-place.

## Como funciona?

O desempenho depende da escolha do pivô e do equilíbrio das partições.

## Complexidade típica

| Métrica | Custo |
|---|---:|
| Médio | O(n log n) |
| Pior | O(n²) |
| Espaço médio da pilha | O(log n) |
| Estável | Não, em geral |

## Exemplo em C#

```csharp
Array.Sort(valores); // A implementação da plataforma escolhe estratégias otimizadas.
```

## Quando usar?

Para ordenação geral em memória quando estabilidade não é requisito.

## Quando evitar ou ter cuidado?

Pivôs ruins e recursão profunda degradam desempenho; não assuma que toda implementação é estável.

## Relações com outros conceitos

- [[Ordenação]]
- [[Divide and conquer]]
- [[Recursão]]

## Dúvidas para revisão

- Consigo explicar **Quick Sort** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
