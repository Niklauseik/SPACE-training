# Real bargaining histories

[Benchmark index](../README.md) | [Shared protocol](../protocol.md)

**Role:** principal task. **Coverage:** 351 inputs per condition.

## Input structure

- `asking price`
- `latest buyer offer`
- `previous buyer/seller offers`
- `price history`

## Output and measures

Output: ACCEPT; COUNTER; EXIT.

Measures: next-action distribution.

## Construction and scope

Retain 351 input slices from 314 source dialogues after removing two duplicated prompts.

Source price histories are supplied; other textual negotiation conditions are omitted. Multiple slices from one dialogue are dependent observations.

## Original source

[Upstream project or dataset](https://github.com/stanfordnlp/cocoa/tree/master/craigslistbargain)

Obtain source material from the linked provider under its terms. The source corpus and the selected SPACE panel are different resources.
