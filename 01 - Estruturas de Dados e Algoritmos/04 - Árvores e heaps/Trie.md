---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos, arvores]
---

# Trie

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Árvore de prefixos em que cada caminho representa caracteres ou partes de uma chave.

## O que é?

Compartilha prefixos entre palavras e permite pesquisar por prefixo.

## Por que é importante?

É eficiente para autocomplete, dicionários e roteamento baseado em prefixos.

## Como funciona?

Cada nível representa uma posição da chave; uma marca indica o fim de uma palavra válida.

## Complexidade típica

| Operação | Custo |
|---|---:|
| Inserir palavra | O(k) |
| Buscar palavra/prefixo | O(k) |

*k é o tamanho da chave.*

## Exemplo em C#

```csharp
public sealed class TrieNode
{
    public Dictionary<char, TrieNode> Children { get; } = [];
    public bool IsWord { get; set; }
}
```

## Quando usar?

Para autocomplete, validação de prefixos, busca textual e roteamento.

## Quando evitar ou ter cuidado?

Pode consumir muita memória quando o alfabeto é grande ou há pouco compartilhamento de prefixos.

## Relações com outros conceitos

- [[Árvore]]
- [[Map e Dictionary]]
- [[Busca por prefixo]]

## Dúvidas para revisão

- Consigo explicar **Trie** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
