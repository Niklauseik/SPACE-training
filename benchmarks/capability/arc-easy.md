# ARC Easy

[Benchmark index](../README.md) | [Shared protocol](../protocol.md)

**Role:** principal task. **Coverage:** 2,000 inputs per condition.

## Input structure

- `question`
- `choices`
- `label`

## Output and measures

Output: selected answer label.

Measures: accuracy.

## Construction and scope

The evaluated file contains 2,000 multiple-choice questions from ARC Easy.

The full denominator includes 87 reference labels not recognized by the A-D parser. Unparseable answers are incorrect, as reported in the appendix.

## Original source

[Upstream project or dataset](https://huggingface.co/datasets/allenai/ai2_arc)

Obtain source material from the linked provider under its terms. The source corpus and the selected SPACE panel are different resources.
