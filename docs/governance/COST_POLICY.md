# Zero-Cost Guard

## Política global

```text
MAX_MONTHLY_COST = R$ 0,00
ALLOW_PAID_SERVICES = false
ALLOW_AUTO_UPGRADE = false
ALLOW_USAGE_BASED_BILLING = false
ALLOW_PAID_AI_API = false
ALLOW_REQUIRED_CREDIT_CARD = false
```

## Regra de bloqueio

Se uma dependência ou serviço puder gerar cobrança:

1. marcar como `COST_BLOCKED`;
2. não implementar;
3. procurar alternativa local, open source ou gratuita sem risco de cobrança;
4. documentar a decisão;
5. somente liberar mediante aprovação explícita.

## Free tier

Um free tier só é aceitável quando não houver risco de cobrança automática ou quando existir um hard cap tecnicamente garantido.

## Evidências mínimas por serviço externo

- nome;
- finalidade;
- modelo de cobrança;
- limite gratuito;
- comportamento ao exceder limite;
- existência de hard cap;
- necessidade de cartão;
- decisão: `ALLOWED | COST_BLOCKED`.
