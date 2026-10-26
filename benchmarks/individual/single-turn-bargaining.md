# Single-turn bargaining

[Benchmark index](../README.md) | [Shared protocol](../protocol.md)

**Role:** principal task. **Coverage:** 2,334 inputs per condition.

## Input structure

- `item category`
- `asking price`
- `initial buyer offer`

## Output and measures

Output: ACCEPT; COUNTER; EXIT.

Measures: action distribution.

## Construction and scope

Retain one unambiguous initial buyer-offer snapshot from eligible CraigslistBargain dialogues across five item categories.

Omit hidden targets and future outcomes. This is a fixed-context next-action choice, not a live multi-turn negotiation.

## Original source

[Upstream project or dataset](https://github.com/stanfordnlp/cocoa/tree/master/craigslistbargain)

Obtain source material from the linked provider under its terms. The source corpus and the selected SPACE panel are different resources.
