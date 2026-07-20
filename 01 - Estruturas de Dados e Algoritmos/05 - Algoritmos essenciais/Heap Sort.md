---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Heap Sort

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Algoritmo que transforma os dados em heap e remove repetidamente o maior ou menor elemento.

## O que é?

Usa a propriedade do heap para posicionar o próximo elemento na posição final.

## Por que é importante?

Garante O(n log n) no pior caso e pode operar in-place.

## Como funciona?

Constrói um max-heap, troca a raiz com o final e restaura o heap na parte restante.

## Complexidade típica

| Métrica | Custo |
|---|---:|
| Tempo | O(n log n) |
| Espaço | O(1) |
| Estável | Não |

## Exemplo em C#

```csharp
// Pode ser implementado sobre um array usando relações de índice entre pai e filhos.
```

## Quando usar?

Quando pior caso previsível e pouco espaço adicional são importantes.

## Quando evitar ou ter cuidado?

Geralmente tem pior localidade e constantes maiores que algoritmos híbridos de bibliotecas modernas.

## Relações com outros conceitos

- [[Heap]]
- [[Ordenação]]
- [[Fila de prioridade]]

## Dúvidas para revisão

- Consigo explicar **Heap Sort** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
