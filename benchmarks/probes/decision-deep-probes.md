# Decision deep probes

[Benchmark index](../README.md) | [Shared protocol](../protocol.md)

**Role:** supplementary probe suite. **Coverage:** 182 inputs per condition.

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

[Direct URL for this specification](https://github.com/Niklauseik/SPACE-training/blob/main/benchmarks/probes/decision-deep-probes.md)

This page documents the task; no dataset download is included.

## Subtask structures

| Subtask | Inputs | Outputs | Controlled fields |
| --- | ---: | --- | --- |
| `bargaining_elicitation` | 30 | NUMBER | source_id, category, asking_price, price_band, wording, pair_id, order |
| `machine_neutral` | 96 | BLUE, RED | mean_gap, horizon, fewer_color, fact_order_reversed, pair_id, order, means_provided |
| `risk_means` | 48 | LOTTERY, CERTAIN | probability_high, expected_final_wealth_lottery, expected_final_wealth_certain, ev_gap, lottery_variance, frame, pair_id, order, means_provided |
| `travel_elicitation` | 8 | NUMBER | minutes_saved, mode_assignment, wording, pair_id, order |
