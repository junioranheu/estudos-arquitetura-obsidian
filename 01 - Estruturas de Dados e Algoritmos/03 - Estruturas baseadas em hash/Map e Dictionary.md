---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Map e Dictionary

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Estrutura que associa uma chave única a um valor.

## O que é?

Map é o conceito geral; Dictionary<TKey,TValue> é a implementação hash mais comum no .NET.

## Por que é importante?

Permite localizar valores diretamente por uma chave significativa.

## Como funciona?

Cada chave é convertida em hash, localizada em um bucket e comparada por igualdade.

## Complexidade típica

| Operação | Médio |
|---|---:|
| Buscar por chave | O(1) |
| Inserir/atualizar | O(1) amortizado |
| Remover | O(1) |

## Exemplo em C#

```csharp
var precos = new Dictionary<string, decimal>(StringComparer.OrdinalIgnoreCase)
{
    ["cafe"] = 8.50m
};
decimal preco = precos["CAFÉ".Normalize()];
```

## Quando usar?

Para índices em memória, agrupamentos, contadores e lookup por ID.

## Quando evitar ou ter cuidado?

Evite indexar diretamente sem verificar existência quando a chave pode faltar; use TryGetValue.

## Relações com outros conceitos

- [[Tabela hash]]
- [[Função hash]]
- [[Dictionary, SortedDictionary e ConcurrentDictionary]]

## Dúvidas para revisão

- Consigo explicar **Map e Dictionary** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
