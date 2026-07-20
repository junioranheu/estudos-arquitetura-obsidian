---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Array

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Coleção de tamanho fixo com elementos armazenados em posições contíguas e acessados por índice.

## O que é?

É uma das estruturas mais básicas e oferece acesso direto a qualquer posição.

## Por que é importante?

Tem baixo overhead, boa localidade de memória e acesso por índice em tempo constante.

## Como funciona?

O endereço de um elemento é calculado a partir do início do array, do índice e do tamanho do tipo.

## Complexidade típica

| Operação | Custo |
|---|---|
| Acesso por índice | O(1) |
| Busca não ordenada | O(n) |
| Inserção/remoção no meio | O(n) |

## Exemplo em C#

```csharp
int[] valores = { 10, 20, 30 };
int segundo = valores[1];
```

## Quando usar?

Quando o tamanho é conhecido ou muda pouco e o acesso por índice é frequente.

## Quando evitar ou ter cuidado?

Evite quando inserções e remoções no meio forem muito frequentes ou o tamanho for altamente variável.

## Relações com outros conceitos

- [[Array dinâmico]]
- [[Busca binária]]
- [[Complexidade de espaço]]

## Dúvidas para revisão

- Consigo explicar **Array** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
