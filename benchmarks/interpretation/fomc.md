# FOMC policy stance

[Benchmark index](../README.md) | [Shared protocol](../protocol.md)

**Role:** principal task. **Coverage:** 2,421 inputs per condition.

## Input structure

- `monetary-policy sentence`
- `source stance label`

## Output and measures

Output: DOVISH; HAWKISH; NEUTRAL.

Measures: label distribution; accuracy; macro F1.

## Construction and scope

Combine the retained train/test statements with the frozen stance mapping: 0 DOVISH, 1 HAWKISH, 2 NEUTRAL.

This measures monetary-policy interpretation, not a general positive/negative sentiment scale.

## Original source

[Upstream project or dataset](https://github.com/gtfintechlab/fomc-hawkish-dovish)

Obtain source material from the linked provider under its terms. The source corpus and the selected SPACE panel are different resources.
