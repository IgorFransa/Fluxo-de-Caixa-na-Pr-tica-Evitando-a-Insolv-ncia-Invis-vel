# Plano de testes de prompts (6 execuções)

> 3 famílias × 2 variações = 6 logs. É suficiente para descrever metodologia e mostrar iteração.

## Família A — Resumo estruturado (por fonte)
- P01 (base): Resumo em: conceito → importância → erro comum → ação prática + cite trechos.
- P02 (variação): 8 bullets + 3 alertas + 1 exemplo (comércio) + cite trechos.

## Família B — Fórmulas e indicadores (ciclos/NCG)
- P03 (base): Extraia fórmulas PME/PMR/PMP/CO/CF/NCG e explique termos.
- P04 (variação): Aplique ao case (PME 45, PMR 30, PMP 20) + interpretação + 3 ações.

## Família C — Diagnóstico e plano de ação (comércio)
- P05 (base): Onde o caixa está preso? 5 ações por impacto (alto→baixo) + trade-offs.
- P06 (variação): Checklist semanal de tesouraria + métricas mínimas.

## Como registrar (sem print)
- Use `TEMPLATE_LOG.txt` e salve como `LOGS/P0X.txt`.
