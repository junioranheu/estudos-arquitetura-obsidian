---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Big O

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Notação que descreve como o custo de um algoritmo cresce conforme a entrada aumenta.

## O que é?

Big O representa um limite assintótico superior e normalmente é usado para comparar crescimento de tempo ou espaço.

## Por que é importante?

Permite prever escalabilidade sem depender de uma máquina, linguagem ou tempo medido específico.

## Como funciona?

Ignora constantes e termos menos relevantes para destacar o comportamento dominante quando n cresce.

## Complexidade típica

| Ordem | Interpretação |
|---|---|
| O(1) | Constante |
| O(log n) | Logarítmica |
| O(n) | Linear |
| O(n log n) | Linearítmica |
| O(n²) | Quadrática |

## Exemplo em C#

```csharp
bool contem = numeros.Contains(30); // Em List<T>, busca linear: O(n)
int valor = numeros[0];              // Acesso por índice: O(1)
```

## Quando usar?

Para comparar algoritmos e justificar escolhas de estruturas.

## Quando evitar ou ter cuidado?

Big O não substitui medição real. Cache, alocação, constantes e padrão dos dados também importam.

## Relações com outros conceitos

- [[Complexidade de espaço]]
- [[Busca binária]]
- [[Ordenação]]
- [[Tabela hash]]

## Dúvidas para revisão

- Consigo explicar **Big O** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
