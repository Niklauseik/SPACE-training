# Frames travel proposals

[Benchmark index](../README.md) | [Shared protocol](../protocol.md)

**Role:** principal task. **Coverage:** 282 inputs per condition.

## Input structure

- `eligible dialogue prefix`
- `travel constraints`
- `proposed itinerary`

## Output and measures

Output: ACCEPT; ASK_DETAILS; SEARCH_OTHER.

Measures: next-action distribution.

## Construction and scope

Retain 282 eligible prefixes from 1,369 downloaded source dialogues.

The main figure aggregates the third action as OTHER. This is a one-step response to a supplied dialogue history, not an unrestricted dialogue agent.

## Original source

[Upstream project or dataset](https://github.com/Maluuba/frames)

Obtain source material from the linked provider under its terms. The source corpus and the selected SPACE panel are different resources.
