# FlowLab

FlowLab é a prova de conceito inicial da metodologia de engenharia definida para validar, em um projeto real e pequeno, se o processo agrega valor antes de qualquer evolução para **DevMethod Lab** ou **EVE**.

## Objetivo

Validar na prática um ciclo completo e enxuto:

`Discover → Define → Design → Build → Test → Release → Observe → Review`

O FlowLab deve provar que requisitos, ADRs, RFCs, Issues, Pull Requests, testes, CI/CD, observabilidade, releases e retrospectivas ajudam o desenvolvimento sem criar burocracia excessiva.

## Regra principal

> DevMethod Lab e EVE não estão aprovados antecipadamente.

Só poderão ser considerados após o **FlowLab Validation Gate** e aprovação explícita do proprietário do projeto.

## Zero-Cost Guard

Durante toda a fase de validação:

- custo recorrente máximo: **R$ 0,00**;
- serviços pagos: bloqueados;
- cobrança automática: bloqueada;
- usage-based billing: bloqueado;
- APIs pagas de IA: bloqueadas;
- upgrades automáticos: bloqueados;
- free tiers com risco de cobrança sem hard cap: não permitidos.

Qualquer exceção futura precisa de aprovação explícita e decisão registrada.

## Escopo do MVP

O produto inicial será um rastreador simples de solicitações com:

- criação de solicitação;
- título e descrição;
- status;
- prioridade;
- histórico de alterações;
- listagem e filtros;
- dashboard básico;
- persistência local;
- testes automatizados;
- health check;
- logging;
- documentação de decisões;
- pipeline de CI apenas quando mantido sem risco de custo.

## Stack proposta

- ASP.NET Core 8
- SQLite
- HTML/CSS/JavaScript
- xUnit
- Playwright somente se necessário e sustentável
- Git/GitHub
- GitHub Actions dentro das condições de custo zero
- Logging nativo ou Serilog
- Health Checks

## Gate de continuidade

Ao final da primeira versão estável, o projeto receberá uma decisão:

- **GO** — método validado; pode-se avaliar DevMethod Lab + EVE;
- **ITERATE** — método tem valor, mas precisa de ajustes;
- **STOP** — o overhead não se justifica.

A decisão deve ser baseada em evidências e aprovação humana, não em opinião isolada de IA.
