# ADR-0001 — FlowLab como prova de conceito obrigatória

- Status: Accepted
- Data: 2026-10-01

## Contexto

Foi proposta uma arquitetura futura composta por DevMethod Lab, FlowLab Core e EVE. Implementar tudo imediatamente criaria risco de overengineering.

## Decisão

Construir primeiro apenas o FlowLab.

DevMethod Lab e EVE não serão implementados até a conclusão do FlowLab Validation Gate e aprovação explícita.

## Consequências positivas

- reduz escopo;
- reduz risco;
- testa o método em situação real;
- produz evidências antes de expandir;
- mantém custo inicial em R$ 0,00.

## Consequências negativas

- recursos de acompanhamento de crescimento e validação avançada ficam adiados;
- parte da arquitetura poderá ser descartada se o FlowLab reprovar.

## Critério de revisão

Revisar após a primeira versão estável e retrospectiva.
