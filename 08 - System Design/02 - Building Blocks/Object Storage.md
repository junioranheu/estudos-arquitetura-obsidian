---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Object Storage

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Armazenamento de objetos por chave em grande escala.

## O que é?

Guarda payload e metadados em buckets, sem filesystem tradicional.

## Papel na arquitetura

Camada durável para blobs e arquivos.

## Como funciona?

Clientes usam API HTTP; o serviço garante durabilidade.

## Exemplo de fluxo

Imagens e backups ficam em S3 ou Azure Blob.

## Quando usar?

Mídia, documentos, backups e data lakes.

## Decisões de projeto

Chaves, buckets, acesso, criptografia, versionamento, lifecycle e multipart.

## Vantagens

Durabilidade, escala e custo.

## Riscos e trade-offs

Latência e custo de transferência.

## Alternativas

Filesystem, block storage ou banco de dados.

## Dúvidas

- Consigo explicar **Object Storage** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Martin Kleppmann — *Designing Data-Intensive Applications*
- Alex Xu — *System Design Interview*
- Google — *Site Reliability Engineering*.
