# Transportation

[Benchmark index](../README.md) | [Shared protocol](../protocol.md)

**Role:** principal task. **Coverage:** 210 inputs per condition.

## Input structure

- `two retained transport alternatives`
- `travel time`
- `cost`
- `selected_modes`
- `pair_id`

## Output and measures

Output: AIR/CAR or the retained mode labels; faster_more_expensive / slower_cheaper.

Measures: choice distribution.

## Construction and scope

Adapt the source mode-choice records to paired alternatives, matching the frozen 210-input panel.

The original source contains more modes. The SPACE two-option adaptation and its count are not the full source dataset.

## Original source

[Upstream project or dataset](https://github.com/statsmodels/statsmodels/tree/main/statsmodels/datasets/modechoice)

Obtain source material from the linked provider under its terms. The source corpus and the selected SPACE panel are different resources.
