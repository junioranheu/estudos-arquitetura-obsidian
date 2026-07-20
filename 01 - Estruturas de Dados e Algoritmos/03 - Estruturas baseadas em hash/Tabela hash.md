---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Tabela hash

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Estrutura que associa chaves a buckets usando uma função hash.

## O que é?

Armazena pares chave-valor ou apenas chaves para permitir busca rápida.

## Por que é importante?

É uma das melhores escolhas para consultas frequentes por identificador sem necessidade de ordenação.

## Como funciona?

Calcula o hash da chave, escolhe um bucket e verifica igualdade entre os candidatos daquele bucket.

## Complexidade típica

| Operação | Médio | Pior caso |
|---|---:|---:|
| Buscar | O(1) | O(n) |
| Inserir | O(1) amortizado | O(n) |
| Remover | O(1) | O(n) |

## Exemplo em C#

```csharp
var usuarios = new Dictionary<int, string>();
usuarios[42] = "Ana";
bool existe = usuarios.ContainsKey(42);
```

## Quando usar?

Para lookup por chave, deduplicação, caches e contadores.

## Quando evitar ou ter cuidado?

Evite quando os dados precisam permanecer ordenados por chave ou quando uma função hash confiável não está disponível.

## Relações com outros conceitos

- [[Função hash]]
- [[Colisões em hash]]
- [[Map e Dictionary]]
- [[Set]]

## Dúvidas para revisão

- Consigo explicar **Tabela hash** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
