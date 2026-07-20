---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Lista encadeada

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Sequência de nós em que cada nó guarda um valor e uma referência para o próximo.

## O que é?

Os elementos não precisam estar em posições contíguas de memória.

## Por que é importante?

Permite inserir ou remover nós conhecidos sem deslocar todos os demais elementos.

## Como funciona?

A navegação começa em um nó inicial e segue referências até encontrar o elemento desejado.

## Complexidade típica

| Operação | Custo |
|---|---|
| Acesso por posição | O(n) |
| Busca | O(n) |
| Inserção/remoção com nó conhecido | O(1) |

## Exemplo em C#

```csharp
var lista = new LinkedList<int>();
var no = lista.AddLast(10);
lista.AddAfter(no, 20);
```

## Quando usar?

Quando há muitas inserções ou remoções em posições já localizadas.

## Quando evitar ou ter cuidado?

Evite para acesso aleatório por índice; o overhead por nó e a baixa localidade de cache podem torná-la mais lenta que List<T>.

## Relações com outros conceitos

- [[Lista duplamente encadeada]]
- [[Array dinâmico]]
- [[List vs LinkedList]]

## Dúvidas para revisão

- Consigo explicar **Lista encadeada** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
