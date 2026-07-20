---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Autenticação

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Processo de verificar quem é o usuário, serviço ou dispositivo.

## O que é?

Valida identidade usando credenciais e fatores apropriados.

## Objetivo de segurança

Comprovar a identidade com nível de confiança proporcional ao risco da operação.

## Como funciona?

O sujeito apresenta prova; o provedor valida e emite sessão ou token.

## Fluxo prático

Usuário entra com senha e MFA e recebe sessão segura.

## Mecanismos e padrões

Senhas com hash forte, MFA, passkeys, certificados, sessões, tokens e federação via OpenID Connect.

## Vulnerabilidades e ameaças

Credential stuffing, brute force, phishing, session fixation, roubo de token e recuperação de conta insegura.

## Boas práticas

Use MFA, rate limiting, cookies seguros, expiração, revogação, hashing forte e fluxos padronizados.

## Diferença para conceitos relacionados

Autenticação responde “quem é?”. Autorização responde “o que essa identidade pode fazer?”.

## Dúvidas

- Consigo explicar **Autenticação** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- OWASP Application Security Verification Standard
- OWASP Cheat Sheet Series
- Documentação oficial de OAuth 2.0 e OpenID Connect.
