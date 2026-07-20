---
tipo: conceito
status: nao-iniciado
dificuldade: intermediario
tags: []
---

# Monólito modular

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Visão geral

Aplicação única dividida internamente em módulos com limites fortes.

Combina simplicidade operacional do monólito com isolamento lógico.

## Problema que busca resolver

Evita custo prematuro da distribuição.

## Princípios e características

- Aplicação única dividida internamente em módulos com limites fortes.
- Combina simplicidade operacional do monólito com isolamento lógico.

## Componentes e responsabilidades

Aplicação única, módulos de negócio, contratos internos e infraestrutura compartilhada de forma controlada.

## Fluxo de execução

A entrada aciona um módulo, que colabora por contratos ou eventos internos no mesmo processo.

## Exemplo prático

Pedidos e faturamento vivem no mesmo processo, mas colaboram por contratos.

## Quando adotar?

Grande parte dos sistemas de negócio.

## Quando evitar?

Evite quando implantação e escala independentes já são requisitos comprovados.

## Vantagens

Transações simples, deploy único e bons limites.

## Desvantagens e trade-offs

Exige disciplina para impedir erosão modular.

## Comparação com outras arquiteturas

A diferença principal está em como responsabilidades, dependências e implantação são organizadas.

Monólito, microsserviços, bounded contexts e modularidade.

A escolha deve ser guiada pelos requisitos e pelos custos operacionais.

## Dúvidas

- Consigo explicar **Monólito modular** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Mark Richards e Neal Ford — *Fundamentals of Software Architecture*
- Neal Ford et al. — *Software Architecture: The Hard Parts*
- Simon Brown — C4 Model.
