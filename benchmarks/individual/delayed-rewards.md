# Delayed rewards

[Benchmark index](../README.md) | [Shared protocol](../protocol.md)

**Role:** principal task. **Coverage:** 288 inputs per condition.

## Input structure

- `sooner_amount`
- `later_amount`
- `front_delay_days`
- `delay_gap_days`
- `amount_ratio`

## Output and measures

Output: A = SOONER; B = LATER.

Measures: later-payment choice proportion.

## Construction and scope

Construct a fixed amount/delay grid with both payments guaranteed.

SPACE-authored task adaptation. There is no separate upstream dataset download for this grid; this specification is its public resource page. Choices are preferences, not accuracy.

## Resource location

[Direct URL for this specification](https://github.com/Niklauseik/SPACE-training/blob/main/benchmarks/individual/delayed-rewards.md)

This page documents the task; no dataset download is included.
