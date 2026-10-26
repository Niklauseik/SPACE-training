# Controlled buyer offers

[Benchmark index](../README.md) | [Shared protocol](../protocol.md)

**Role:** principal task. **Coverage:** 900 inputs per condition.

## Input structure

- `source situation`
- `item category`
- `price band`
- `asking price`
- `buyer-offer ratio`

## Output and measures

Output: ACCEPT; COUNTER; EXIT.

Measures: action distribution by offer ratio.

## Construction and scope

Use 150 retained source situations across five item categories and three price bands, with six synthetic offers from 40% to 90% of asking price.

This 900-input task is distinct from the separate 315-input targeted buyer-offer probe in the main figure.

## Original source

[Upstream project or dataset](https://github.com/stanfordnlp/cocoa/tree/master/craigslistbargain)

Obtain source material from the linked provider under its terms. The source corpus and the selected SPACE panel are different resources.
