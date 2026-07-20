---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Busca linear

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Busca que verifica os elementos um a um até encontrar o alvo.

## O que é?

Não exige que os dados estejam ordenados.

## Por que é importante?

É simples, tem baixo custo de preparação e funciona em qualquer sequência.

## Como funciona?

Percorre a coleção desde o início e compara cada elemento com o valor procurado.

## Complexidade típica

| Caso | Tempo |
|---|---:|
| Melhor | O(1) |
| Médio/pior | O(n) |
| Espaço | O(1) |

## Exemplo em C#

```csharp
int indice = Array.IndexOf(valores, procurado);
```

## Quando usar?

Para coleções pequenas, buscas ocasionais ou dados não ordenados.

## Quando evitar ou ter cuidado?

Se as buscas forem frequentes, considere ordenar, indexar ou usar tabela hash.

## Relações com outros conceitos

- [[Array]]
- [[Busca binária]]
- [[Tabela hash]]

## Dúvidas para revisão

- Consigo explicar **Busca linear** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
