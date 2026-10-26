# GSM8K

[Benchmark index](../README.md) | [Shared protocol](../protocol.md)

**Role:** principal task. **Coverage:** 1,300 inputs per condition.

## Input structure

- `question`
- `label (reference number)`

## Output and measures

Output: generated numeric answer.

Measures: accuracy.

## Construction and scope

The evaluated file contains 1,300 questions. Compare each guidance condition with its corresponding Base.

The Llama 3.2 3B Base/trained/Prompt protocol uses a 512-token limit and accepts any extracted number matching the reference; combined and Qwen Prompt evaluations extract the final number. Preserve the paper-specific parser distinction; these are not claimed as standardized leaderboard scores.

## Original source

[Upstream project or dataset](https://github.com/openai/grade-school-math)

Obtain source material from the linked provider under its terms. The source corpus and the selected SPACE panel are different resources.
