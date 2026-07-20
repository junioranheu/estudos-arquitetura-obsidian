---
tipo: conceito
status: nao-iniciado
dificuldade: iniciante
tags: [estruturas-de-dados, algoritmos]
---

# Função hash

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Função que transforma uma chave em um valor numérico usado para localizar um bucket.

## O que é?

Produz um código determinístico para distribuir chaves em uma tabela hash.

## Por que é importante?

Uma boa distribuição reduz colisões e mantém operações próximas de O(1) em média.

## Como funciona?

Chaves consideradas iguais devem produzir o mesmo hash; chaves diferentes podem produzir hashes iguais.

## Complexidade típica

| Operação | Custo |
|---|---|
| Calcular hash | Geralmente O(1) ou O(tamanho da chave) |

## Exemplo em C#

```csharp
int hash = StringComparer.OrdinalIgnoreCase.GetHashCode("Usuario");
```

## Quando usar?

Em dicionários, conjuntos, caches e particionamento por chave.

## Quando evitar ou ter cuidado?

Nunca use apenas o hash para afirmar igualdade. O hash pode colidir e pode variar entre processos dependendo da implementação.

## Relações com outros conceitos

- [[Tabela hash]]
- [[Colisões em hash]]
- [[Map e Dictionary]]
- [[Set]]

## Dúvidas para revisão

- Consigo explicar **Função hash** sem consultar a nota?
- Consigo justificar sua complexidade de tempo e espaço?
- Consigo reconhecer quando outra estrutura seria mais adequada?

## Referências

- Thomas H. Cormen et al. — *Introduction to Algorithms*
- Robert Sedgewick e Kevin Wayne — *Algorithms*
- Documentação oficial do .NET para as coleções utilizadas.
