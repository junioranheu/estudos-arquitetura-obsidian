---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Gerenciamento de segredos

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Armazenamento seguro de credenciais, chaves e tokens.

## O que é?

Protege com criptografia, acesso, auditoria e rotação.

## Componentes principais

Aplicações obtêm segredos em runtime por identidade.

## Como funciona?

Aplicações obtêm segredos em runtime por identidade.

## Exemplo prático

API usa managed identity para ler Key Vault.

## Quando usar?

Toda aplicação com recursos protegidos.

## Quando evitar?

Evite segredos em Git, logs ou imagens.

## Vantagens

Governança, auditoria e menor vazamento.

## Limitações e trade-offs

Dependência do cofre e bootstrap seguro.

## Boas práticas

- Mantenha responsabilidades claras e configuração versionada.
- Automatize validação e observabilidade.
- Documente limites, falhas e operação.

## Relações com outros conceitos

Vault, KMS, identidade, rotação e least privilege.

## Referências

- Google — *Site Reliability Engineering*
- Nicole Forsgren, Jez Humble e Gene Kim — *Accelerate*
- Documentação oficial de Docker, Kubernetes e OpenTelemetry.
