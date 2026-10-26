# SST-2 sentiment

[Benchmark index](../README.md) | [Shared protocol](../protocol.md)

**Role:** principal task. **Coverage:** 10,000 inputs per condition.

## Input structure

- `idx`
- `text`
- `label`

## Output and measures

Output: positive; negative.

Measures: sentiment distribution; classification accuracy.

## Construction and scope

Use the saved 10,000-row sentence-sentiment panel.

The panel is a selected subset; do not equate it with a full official evaluation split.

## Original source

[Upstream project or dataset](https://huggingface.co/datasets/stanfordnlp/sst2)

Obtain source material from the linked provider under its terms. The source corpus and the selected SPACE panel are different resources.
