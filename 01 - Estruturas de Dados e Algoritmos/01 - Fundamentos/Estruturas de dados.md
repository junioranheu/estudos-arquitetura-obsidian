---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Estruturas de dados

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Formas de organizar dados para executar operações com custos previsíveis.

## O que é?

Uma estrutura de dados define como valores são armazenados, relacionados e acessados na memória.

## Por que é importante?

A estrutura escolhida afeta desempenho, consumo de memória, clareza do código e facilidade de manutenção.

## Como funciona?

Cada estrutura favorece certas operações, como acesso por índice, busca por chave, ordenação, prioridade, hierarquia ou conectividade.

## Complexidade típica

| Operação | Custo |
|---|---|
| Depende da estrutura | De O(1) a O(n) ou mais |

## Exemplo em C#

```csharp
var numeros = new List<int> { 10, 20, 30 };
var porId = new Dictionary<int, string> { [1] = "Ana" };
```

## Quando usar?

Sempre que o modo de armazenar e acessar dados influenciar a solução.

## Quando evitar ou ter cuidado?

Evite escolher por hábito. Considere volume, ordem, unicidade, frequência de leitura e frequência de escrita.

## Relações com outros conceitos

- [[Big O]]
- [[Complexidade de espaço]]
- [[Array]]
- [[Tabela hash]]
- [[Árvore]]
- [[Grafo]]

## Dúvidas para revisão

- Consigo explicar **Estruturas de dados** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
