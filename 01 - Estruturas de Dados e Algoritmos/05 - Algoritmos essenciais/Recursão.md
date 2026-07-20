---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Recursão

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Técnica em que uma função resolve um problema chamando a si mesma com uma entrada menor.

## O que é?

Exige um caso base e uma redução que aproxime a execução desse caso.

## Por que é importante?

Expressa naturalmente árvores, divide and conquer, backtracking e definições recursivas.

## Como funciona?

Cada chamada cria um frame na pilha até atingir o caso base e então retorna na ordem inversa.

## Complexidade típica

| Métrica | Custo |
|---|---|
| Tempo | Depende da quantidade de chamadas |
| Espaço | Depende da profundidade da pilha |

## Exemplo em C#

```csharp
static int Fatorial(int n)
{
    if (n <= 1) return 1;
    return n * Fatorial(n - 1);
}
```

## Quando usar?

Para árvores, DFS, backtracking e problemas naturalmente divisíveis.

## Quando evitar ou ter cuidado?

Entradas profundas podem causar StackOverflowException; prefira iteração quando a profundidade não for controlável.

## Relações com outros conceitos

- [[Pilha]]
- [[DFS]]
- [[Divide and conquer]]
- [[Árvore]]

## Dúvidas para revisão

- Consigo explicar **Recursão** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
