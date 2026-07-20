---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Ordenação

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Processo de reorganizar elementos segundo uma chave ou comparador.

## O que é?

Algoritmos de ordenação diferem em tempo, memória, estabilidade e comportamento com dados parcialmente ordenados.

## Por que é importante?

Dados ordenados permitem busca binária, apresentação previsível e algoritmos mais eficientes.

## Como funciona?

O comparador define a ordem; o algoritmo rearranja os elementos respeitando esse critério.

## Complexidade típica

| Algoritmo | Médio | Pior | Espaço | Estável |
|---|---:|---:|---:|---|
| Merge Sort | O(n log n) | O(n log n) | O(n) | Sim |
| Quick Sort | O(n log n) | O(n²) | O(log n) médio | Não, em geral |
| Heap Sort | O(n log n) | O(n log n) | O(1) | Não |

## Exemplo em C#

```csharp
Array.Sort(valores);
var ordenados = pessoas.OrderBy(p => p.Nome).ToList();
```

## Quando usar?

Quando a ordem beneficia buscas, relatórios, agrupamentos ou processamento posterior.

## Quando evitar ou ter cuidado?

Não ordene repetidamente sem necessidade; considere manter estrutura ordenada ou ordenar apenas na fronteira de apresentação.

## Relações com outros conceitos

- [[Merge Sort]]
- [[Quick Sort]]
- [[Heap Sort]]
- [[Busca binária]]

## Dúvidas para revisão

- Consigo explicar **Ordenação** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
