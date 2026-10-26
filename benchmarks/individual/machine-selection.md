# Machine selection

[Benchmark index](../README.md) | [Shared protocol](../protocol.md)

**Role:** principal task. **Coverage:** 4,160 inputs per condition.

## Input structure

- `ordered reward observations`
- `source-to-model machine mapping`
- `one or six choices remaining`

## Output and measures

Output: A; B; mapped to less_observed / more_observed.

Measures: fewer-observed choice proportion.

## Construction and scope

Extract unequal-information decision points from the feng2021dynamics/exp1.csv experiment in Psych-101: one observation of one machine and three of the other.

Use the preserved reward history, not just a means summary. Repeated decision points from a participant/game are related observations.

## Original source

[Upstream project or dataset](https://huggingface.co/datasets/marcelbinz/Psych-101)

Obtain source material from the linked provider under its terms. The source corpus and the selected SPACE panel are different resources.
