---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Merge Sort

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Algoritmo de ordenação que divide a coleção, ordena as partes e as intercala.

## O que é?

Segue divide and conquer e garante O(n log n) no pior caso.

## Por que é importante?

É estável e previsível, sendo adequado para listas encadeadas e ordenação externa.

## Como funciona?

Divide até obter partes unitárias e então combina duas sequências ordenadas por vez.

## Complexidade típica

| Métrica | Custo |
|---|---:|
| Tempo | O(n log n) |
| Espaço típico em arrays | O(n) |
| Estável | Sim |

## Exemplo em C#

```csharp
// Implementação conceitual:
var esquerda = valores[..meio];
var direita = valores[meio..];
// Ordenar as partes e intercalar.
```

## Quando usar?

Quando estabilidade e pior caso previsível são importantes.

## Quando evitar ou ter cuidado?

Em arrays, exige memória auxiliar; para pequenos conjuntos, algoritmos simples podem ter menor overhead.

## Relações com outros conceitos

- [[Ordenação]]
- [[Divide and conquer]]
- [[Complexidade de espaço]]

## Dúvidas para revisão

- Consigo explicar **Merge Sort** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
