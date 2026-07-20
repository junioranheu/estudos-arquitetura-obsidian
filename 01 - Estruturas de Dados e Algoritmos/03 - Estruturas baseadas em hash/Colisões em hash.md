---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Colisões em hash

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Situação em que chaves diferentes resultam no mesmo bucket ou código hash.

## O que é?

Colisões são inevitáveis porque o espaço de chaves costuma ser maior que o espaço de buckets.

## Por que é importante?

Entender colisões explica por que tabelas hash têm O(1) médio, mas não garantem O(1) no pior caso.

## Como funciona?

Implementações resolvem colisões por encadeamento, endereçamento aberto ou estratégias equivalentes, além de redimensionar a tabela.

## Complexidade típica

| Cenário | Efeito |
|---|---|
| Boa distribuição | Poucos candidatos por bucket |
| Muitas colisões | Busca se aproxima de O(n) |

## Exemplo em C#

```csharp
var mapa = new Dictionary<MinhaChave, string>(new MeuComparador());
```

## Quando usar?

Ao implementar tipos usados como chave e ao analisar degradação de desempenho.

## Quando evitar ou ter cuidado?

Implemente Equals e GetHashCode de forma consistente e evite chaves mutáveis enquanto estiverem no dicionário.

## Relações com outros conceitos

- [[Função hash]]
- [[Tabela hash]]
- [[Map e Dictionary]]

## Dúvidas para revisão

- Consigo explicar **Colisões em hash** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
