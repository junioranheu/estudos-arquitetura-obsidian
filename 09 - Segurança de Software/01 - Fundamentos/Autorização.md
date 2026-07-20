---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Autorização

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Decisão sobre o que uma identidade pode fazer.

## O que é?

Aplica políticas por papel, atributo, permissão, contexto e ownership.

## Objetivo de segurança

Permitir cada ação somente ao sujeito adequado, no recurso e contexto corretos.

## Como funciona?

Após autenticar, o sistema avalia política antes da ação.

## Fluxo prático

Só proprietário ou administrador cancela pedido.

## Mecanismos e padrões

RBAC, ABAC, ACL, scopes, policies e verificação de propriedade do recurso.

## Vulnerabilidades e ameaças

IDOR/BOLA, elevação de privilégio, confused deputy e permissões excessivas.

## Boas práticas

Negue por padrão, valide no backend, aplique least privilege e teste cenários negativos.

## Diferença para conceitos relacionados

Autorização usa a identidade autenticada para decidir acesso; ela não comprova a identidade.

## Dúvidas

- Consigo explicar **Autorização** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- OWASP Application Security Verification Standard
- OWASP Cheat Sheet Series
- Documentação oficial de OAuth 2.0 e OpenID Connect.
