# Decision targeted followup

[Benchmark index](../README.md) | [Shared protocol](../protocol.md)

**Role:** supplementary probe suite. **Coverage:** 304 inputs per condition.

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

[Direct URL for this specification](https://github.com/Niklauseik/SPACE-training/blob/main/benchmarks/probes/decision-targeted-followup.md)

This page documents the task; no dataset download is included.

## Subtask structures

| Subtask | Inputs | Outputs | Controlled fields |
| --- | ---: | --- | --- |
| `bargaining_history_followup` | 144 | ACCEPT, COUNTER, EXIT | asking_price, minimum_ratio, minimum_price, current_offer_ratio, current_offer, history_type, previous_offer_ratios, history_turns, clarification_cost_minutes, history_is_supplied, order, context_id |
| `machine_reward_followup` | 160 | RED, BLUE | mean_gap, horizon, fewer_n, more_n, fewer_color, fact_order, means_provided, mean_fewer, mean_more, order, context_id |
