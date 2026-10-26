# Circa

[Benchmark index](../README.md) | [Shared protocol](../protocol.md)

**Role:** principal task. **Coverage:** 32,602 inputs per condition.

## Input structure

- `context`
- `polar question`
- `indirect reply`
- `mapped reference label`

## Output and measures

Output: YES; NO; CONDITIONAL; UNCLEAR.

Measures: label distribution; accuracy; macro F1.

## Construction and scope

Retain source items whose published goldstandard2 label maps to one of the four task classes.

All retained inputs stay in distribution denominators; valid leading labels followed by explanations are accepted by the parser.

## Original source

[Upstream project or dataset](https://github.com/google-research-datasets/circa)

Obtain source material from the linked provider under its terms. The source corpus and the selected SPACE panel are different resources.
