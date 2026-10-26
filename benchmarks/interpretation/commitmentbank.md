# CommitmentBank

[Benchmark index](../README.md) | [Shared protocol](../protocol.md)

**Role:** principal task. **Coverage:** 1,009 inputs per condition.

## Input structure

- `context`
- `utterance`
- `proposition`
- `individual annotation ratings`

## Output and measures

Output: TRUE; FALSE; UNCERTAIN.

Measures: label distribution over 1,009 inputs; accuracy and macro F1 over 858 eligible inputs.

## Construction and scope

Map positive/negative/zero individual ratings to TRUE/FALSE/UNCERTAIN and require a strict majority for the adapted reference.

151 items have no strict-majority reference and enter distributions only. This adapted reference is not an original three-class gold label. The Llama 8B F format-compliance issue is documented in the paper.

## Original source

[Upstream project or dataset](https://github.com/mcdm/CommitmentBank)

Obtain source material from the linked provider under its terms. The source corpus and the selected SPACE panel are different resources.
