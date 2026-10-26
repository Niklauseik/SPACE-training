# Machine Mindset preference data

[Benchmark index](../README.md) | [Shared protocol](../protocol.md)

**Role:** training resource. **Coverage:** 12,159 T/F preference pairs.

## Input structure

- `instruction`
- `input`
- `output in aligned opposite-pole JSON lists`

## Output and measures

Output: prompt; chosen; rejected for DPO.

Measures: training loss for stopping.

## Construction and scope

Pair English Thinking and Feeling responses by row index, with matching instruction/context. Reversing the target reverses chosen/rejected.

This is training material, not a situational evaluation benchmark. The source dataset and model weights are not redistributed.

## Original source

[Upstream project or dataset](https://github.com/PKU-YuanGroup/Machine-Mindset)

Obtain source material from the linked provider under its terms. The source corpus and the selected SPACE panel are different resources.
