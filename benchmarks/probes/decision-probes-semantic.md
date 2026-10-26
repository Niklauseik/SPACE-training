# Decision probes semantic

[Benchmark index](../README.md) | [Shared protocol](../protocol.md)

**Role:** supplementary probe suite. **Coverage:** 1,319 inputs per condition.

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

[Direct URL for this specification](https://github.com/Niklauseik/SPACE-training/blob/main/benchmarks/probes/decision-probes-semantic.md)

This page documents the task; no dataset download is included.

## Subtask structures

| Subtask | Inputs | Outputs | Controlled fields |
| --- | ---: | --- | --- |
| `bargaining` | 315 | ACCEPT, COUNTER, EXIT | source_id, source_split, category, asking_price, price_band, offer_ratio, pair_id, order |
| `bargaining_interaction` | 48 | ACCEPT, COUNTER, EXIT | asking_price, minimum_ratio, initial_offer_ratio, offer_path, offers, pair_id, order |
| `delay` | 192 | SOONER, LATER | amount, premium, delay_gap_days, front_delay_days, simple_annualized_premium, pair_id, order |
| `machine` | 112 | FEWER, MORE | mean_gap_fewer_minus_more, fewer_n, more_n, horizon, pattern, pair_id, order |
| `movie` | 108 | ACCEPT, ASK, OTHER | information_state, clarification_cost_minutes, social_pressure, version, pair_id, order |
| `movie_interaction` | 36 | ACCEPT, ASK, OTHER | revelation, clarification_cost_minutes, version, pair_id, order |
| `risk` | 100 | LOTTERY, CERTAIN | probability_high, expected_final_wealth_lottery, expected_final_wealth_certain, ev_gap, lottery_variance, frame, pair_id, order |
| `stock` | 216 | BUY, SELL, HOLD | prices_oldest_to_newest, target_net_return, realized_net_return, volatility_level, target_daily_log_return_population_sd, realized_daily_log_return_population_sd, path_id, standardized_return_pattern, last_daily_log_return, latest_price, pattern_is_shared_across_all_cells, purchase_price, pair_id, order |
| `tour` | 108 | ACCEPT, ASK, OTHER | information_state, clarification_cost_minutes, social_pressure, version, pair_id, order |
| `tour_interaction` | 36 | ACCEPT, ASK, OTHER | revelation, clarification_cost_minutes, version, pair_id, order |
| `travel` | 48 | SLOW, FAST | minutes_saved, premium, dollars_per_hour_saved, mode_assignment, pair_id, order |
