---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Containers

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Unidades isoladas que empacotam aplicação e dependências.

## O que é?

Compartilham o kernel do host com isolamento de processos, filesystem e recursos.

## Componentes principais

Imagem imutável é executada como container com configuração e volumes externos.

## Como funciona?

Imagem imutável é executada como container com configuração e volumes externos.

## Exemplo prático

API .NET usa a mesma imagem em dev, QA e produção.

## Quando usar?

Serviços, jobs e aplicações empacotáveis.

## Quando evitar?

Evite estado durável no filesystem efêmero.

## Vantagens

Portabilidade, densidade e inicialização rápida.

## Limitações e trade-offs

Segurança, rede, imagens e operação.

## Boas práticas

- Mantenha responsabilidades claras e configuração versionada.
- Automatize validação e observabilidade.
- Documente limites, falhas e operação.

## Relações com outros conceitos

Docker, OCI, Kubernetes, volumes e namespaces.

## Referências

- Google — *Site Reliability Engineering*
- Nicole Forsgren, Jez Humble e Gene Kim — *Accelerate*
- Documentação oficial de Docker, Kubernetes e OpenTelemetry.
