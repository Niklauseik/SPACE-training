# Controlled movie/travel feedback probes

[Benchmark index](../README.md) | [Shared protocol](../protocol.md)

**Coverage:** two authored scenario versions per domain (movie and travel). These are controlled feedback probes, separate from the 119 INSPIRED and 282 Frames supplied-history panels.

## Input structure

Each controlled setting specifies the domain, scenario version, clarification cost and option order. Interaction history and turn index determine the current decision context. These are logical task fields, not a claim that a new input-file format or evaluation executable is included in this release.

## Output and measures

Movie actions are ACCEPT, REJECT and ASK_MORE; travel actions are ACCEPT, ASK_DETAILS and SEARCH_OTHER. The reported second-turn comparisons use only common records where Base, T and F all reach turn two. Costs and option orders remain matched within each authored version.

## Analysis scope

The paper reports descriptive paired effects and discrete tests across 72 comparisons. None survives Holm correction. Nominal bootstrap confidence intervals are withheld because only two scenario versions are available. Conditioning on the common second-turn cohort means these are not unconditional causal effects.

## Related principal tasks

- [INSPIRED supplied-history task](../interaction/inspired.md)
- [Frames supplied-history task](../interaction/frames.md)

This specification documents the authored probes; raw scenario records and evaluation executables are not distributed.
