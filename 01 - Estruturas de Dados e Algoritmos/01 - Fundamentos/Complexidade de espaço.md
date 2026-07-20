---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Complexidade de espaço

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Medida de quanto uso adicional de memória cresce em relação ao tamanho da entrada.

## O que é?

Considera memória auxiliar, estruturas temporárias, pilha de chamadas e, dependendo da análise, a própria entrada.

## Por que é importante?

Um algoritmo rápido pode ser inviável se exigir memória demais, principalmente em grandes volumes ou ambientes limitados.

## Como funciona?

A análise identifica as alocações que crescem com n e mantém apenas o termo dominante.

## Complexidade típica

| Exemplo | Espaço auxiliar |
|---|---|
| Variáveis fixas | O(1) |
| Cópia de n itens | O(n) |
| Matriz n × n | O(n²) |

## Exemplo em C#

```csharp
int Somar(ReadOnlySpan<int> valores)
{
    int total = 0; // espaço adicional O(1)
    foreach (var valor in valores) total += valor;
    return total;
}
```

## Quando usar?

Ao processar coleções grandes, arquivos, matrizes, grafos e algoritmos recursivos.

## Quando evitar ou ter cuidado?

Evite criar cópias desnecessárias e observe recursão profunda, buffers e materialização de consultas.

## Relações com outros conceitos

- [[Big O]]
- [[Recursão]]
- [[Array dinâmico]]
- [[Merge Sort]]

## Dúvidas para revisão

- Consigo explicar **Complexidade de espaço** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
