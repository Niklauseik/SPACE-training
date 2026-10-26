# Decision validation

[Benchmark index](../README.md) | [Shared protocol](../protocol.md)

**Role:** supplementary probe suite. **Coverage:** 360 inputs per condition.

## Input structure

- `shared record: id, task, prompt, instruction, label_map, reference, features`
- `task-specific factor fields listed below`

## Output and measures

Output: task-specific discrete labels or a bounded numeric response.

Measures: within-condition response changes; paired condition effects; option-order and presentation sensitivity.

## Construction and scope

Frozen supplementary probe suite. The table below lists the included subtask structures and row counts.

These are authored or adapted controlled probes, not independent official datasets. Counts include presentation/option-order variants and do not equal independent economic situations. Numeric elicitation tasks use a bounded numeric output instead of a categorical label.

## Resource location

[Direct URL for this specification](https://github.com/Niklauseik/SPACE-training/blob/main/benchmarks/probes/decision-validation.md)

This page documents the task; no dataset download is included.

## Subtask structures

| Subtask | Inputs | Outputs | Controlled fields |
| --- | ---: | --- | --- |
| `bargaining_deadline` | 144 | ACCEPT, COUNTER, EXIT | asking_price, minimum_ratio, offer_ratio, final_offer, pair_id, order |
| `information_presentation` | 72 | ACCEPT, ASK, OTHER | domain, information_state, representation, clarification_cost_minutes, pair_id, order |
| `machine_identity` | 48 | FEWER, MORE | mean_gap, horizon, fewer_color, fact_order_reversed, pair_id, order |
| `stock_replication` | 96 | BUY, SELL, HOLD | net_return, volatility, path, prices, pair_id, order |
