---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Array dinâmico

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Array que cresce automaticamente ao atingir sua capacidade.

## O que é?

Mantém um array interno e cria outro maior quando precisa acomodar mais elementos.

## Por que é importante?

Combina acesso rápido por índice com tamanho flexível e é a coleção sequencial padrão em muitos cenários.

## Como funciona?

Adicionar ao final normalmente é O(1) amortizado; ocasionalmente ocorre uma realocação O(n).

## Complexidade típica

| Operação | Custo |
|---|---|
| Acesso por índice | O(1) |
| Adição ao final | O(1) amortizado |
| Inserção/remoção no meio | O(n) |

## Exemplo em C#

```csharp
var nomes = new List<string>();
nomes.Add("Ana");
nomes.Add("Bruno");
```

## Quando usar?

Para coleções ordenadas por posição com muitas leituras e adições ao final.

## Quando evitar ou ter cuidado?

Tenha cuidado com grandes expansões, inserções no início e remoções frequentes no meio.

## Relações com outros conceitos

- [[Array]]
- [[Lista encadeada]]
- [[List vs LinkedList]]

## Dúvidas para revisão

- Consigo explicar **Array dinâmico** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
