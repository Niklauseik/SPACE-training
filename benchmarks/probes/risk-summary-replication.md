# Risk summary replication

[Benchmark index](../README.md) | [Shared protocol](../protocol.md)

**Role:** supplementary probe suite. **Coverage:** 160 inputs per condition.

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

[Direct URL for this specification](https://github.com/Niklauseik/SPACE-training/blob/main/benchmarks/probes/risk-summary-replication.md)

This page documents the task; no dataset download is included.

## Subtask structures

| Subtask | Inputs | Outputs | Controlled fields |
| --- | ---: | --- | --- |
| `risk_means` | 160 | LOTTERY, CERTAIN | probability_high, ev_gap, frame, means_provided, expected_final_wealth_lottery, expected_final_wealth_certain, final_wealth_lottery_low, final_wealth_lottery_high, pair_id, order |
