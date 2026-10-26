# Financial news sentiment

[Benchmark index](../README.md) | [Shared protocol](../protocol.md)

**Role:** principal task. **Coverage:** 11,931 inputs per condition.

## Input structure

- `text`
- `label`

## Output and measures

Output: Bearish; Bullish; Neutral.

Measures: sentiment distribution; classification accuracy.

## Construction and scope

Classify the retained financial headline texts using the saved task label mapping.

This is the News task named in the appendix; it is separate from FOMC stance classification.

## Original source

[Upstream project or dataset](https://huggingface.co/datasets/zeroshot/twitter-financial-news-sentiment)

Obtain source material from the linked provider under its terms. The source corpus and the selected SPACE panel are different resources.
