# Program-feedback bargaining

[Benchmark index](../README.md) | [Shared protocol](../protocol.md)

**Role:** principal task. **Coverage:** 2,272 inputs per condition.

## Input structure

- `initial situation`
- `asking price`
- `initial buyer offer`
- `action instructions`
- `controller budget/profile`
- `maximum model turns`

## Output and measures

Output: ACCEPT; COUNTER; EXIT at each model turn.

Measures: turn/action distributions; agreement and final interaction outcomes.

## Construction and scope

Exclude 62 initial offers at or above asking price, then allow at most three model choices with program-generated buyer feedback.

This is the model-in-the-loop interaction task. Buyer responses come from a deterministic program, not a second language model; keep it separate from fixed-context history tasks.

## Original source

[Upstream project or dataset](https://github.com/stanfordnlp/cocoa/tree/master/craigslistbargain)

Obtain source material from the linked provider under its terms. The source corpus and the selected SPACE panel are different resources.
