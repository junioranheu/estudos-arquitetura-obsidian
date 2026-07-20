---
tipo: conceito
status: nao-iniciado
dificuldade: avancado
tags: []
---

# Microsserviços

## Meu entendimento

> [!note] Meu resumo
> Escreva aqui, com suas palavras, o que você entendeu depois de estudar este tema.

## Visão geral

Serviços autônomos alinhados a capacidades de negócio.

Cada serviço possui responsabilidade, dados e ciclo de implantação próprios.

## Problema que busca resolver

Busca autonomia, escala independente e isolamento de mudanças.

## Princípios e características

- Serviços autônomos alinhados a capacidades de negócio.
- Cada serviço possui responsabilidade, dados e ciclo de implantação próprios.

## Componentes e responsabilidades

Serviços autônomos, APIs e eventos, dados por serviço, gateway, observabilidade e plataforma de entrega.

## Fluxo de execução

A requisição entra por gateway ou serviço; os serviços colaboram por chamadas ou eventos e mantêm seus dados.

## Exemplo prático

Pedidos, pagamentos e estoque são serviços separados.

## Quando adotar?

Domínios grandes, equipes múltiplas e operação madura.

## Quando evitar?

Evite em equipes pequenas ou domínio pouco conhecido.

## Vantagens

Autonomia, isolamento e escala por capacidade.

## Desvantagens e trade-offs

Rede, consistência distribuída e alto custo operacional.

## Comparação com outras arquiteturas

A diferença principal está em como responsabilidades, dependências e implantação são organizadas.

Monólito modular, EDA, DDD e sistemas distribuídos.

A escolha deve ser guiada pelos requisitos e pelos custos operacionais.

## Dúvidas

- Consigo explicar **Microsserviços** sem termos vagos?
- Quais sinais justificam seu uso?
- Quais custos e falhas devo considerar em produção?

## Referências

- Mark Richards e Neal Ford — *Fundamentals of Software Architecture*
- Neal Ford et al. — *Software Architecture: The Hard Parts*
- Simon Brown — C4 Model.
