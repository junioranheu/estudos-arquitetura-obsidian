---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# SRP - Princípio da Responsabilidade Única

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Em uma frase

Um módulo deve ter um único motivo relevante para mudar.

## O que o princípio diz?

Um módulo deve ter um único motivo relevante para mudar. Separa responsabilidades de atores, políticas ou ritmos de mudança diferentes.

## Qual problema evita?

Reduz efeitos colaterais e melhora coesão.

## Como aplicar?

Comportamentos que mudam juntos ficam juntos; os demais são separados.

## Exemplo prático

PedidoService não deve calcular preço, gerar PDF, enviar e-mail e persistir tudo.

## Sinais de violação

- Responsabilidades misturadas ou dependências rígidas.
- Contratos que forçam comportamento inadequado ou surpreendem o consumidor.

## Benefícios

Testes menores e manutenção localizada.

## Limitações e trade-offs

Separação excessiva gera classes anêmicas.

## Relações com outros conceitos

Coesão, SoC e bounded contexts.

## Dúvidas

- Consigo explicar **SRP - Princípio da Responsabilidade Única** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Robert C. Martin — *Agile Software Development: Principles, Patterns, and Practices*
- Martin Fowler — *Refactoring*
- Documentação oficial da linguagem e do runtime utilizados.
