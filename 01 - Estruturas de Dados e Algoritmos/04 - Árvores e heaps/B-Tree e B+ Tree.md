---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos, arvores]
---

# B-Tree e B+ Tree

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Árvores balanceadas de alta ramificação projetadas para reduzir acessos a disco.

## O que é?

Armazenam várias chaves por nó; em B+ Tree, os dados ou ponteiros finais ficam nas folhas encadeadas.

## Por que é importante?

São fundamentais em índices de bancos de dados e sistemas de arquivos.

## Como funciona?

Nós grandes correspondem a páginas; cada acesso elimina uma grande faixa de chaves e reduz I/O.

## Complexidade típica

| Operação | Custo |
|---|---:|
| Buscar | O(log n) |
| Inserir | O(log n) |
| Remover | O(log n) |

## Exemplo em C#

```csharp
// No código de aplicação, normalmente a B+ Tree é usada indiretamente
// por meio de índices do banco de dados.
```

## Quando usar?

Para índices persistentes, consultas por faixa e armazenamento em blocos.

## Quando evitar ou ter cuidado?

Não costuma ser implementada manualmente em aplicações comuns; detalhes de página, concorrência e persistência são complexos.

## Relações com outros conceitos

- [[Árvore balanceada]]
- [[Índices]]
- [[Plano de execução]]

## Dúvidas para revisão

- Consigo explicar **B-Tree e B+ Tree** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
