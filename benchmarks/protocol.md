# Shared SPACE evaluation protocol

[Benchmark index](README.md)

## Controlled comparisons

The principal paper contrast is Thinking/Feeling. Compare each unmodified Base model with unprompted trained variants, Base with a personality prompt, and aligned/opposing trained-plus-prompt conditions. Hold task inputs, output requirements and decoding fixed within each reported comparison. E/I, S/N and J/P are complementary analyses; their evaluated coverage must be read separately from the T/F results.

Models: Llama 3.2 3B Instruct, Llama 3.1 8B Instruct, Qwen2.5 3B Instruct and Qwen2.5 7B Instruct. Prompt and combined personality/capability results do not have the same coverage as unprompted trained variants; the paper specifies the unavailable cells. Greedy generative evaluation uses one beam and no sampling. Token limits, parsers and legacy protocols differ by task/condition; consult the task cards and paper rather than assuming one universal scoring protocol.

## Shared situational record structure

| Field | Meaning |
| --- | --- |
| `id`, `task` | Task input identifier and task family |
| `prompt` | Fixed task context and requested response; interaction tasks can use `initial_prompt` plus `action_instruction` |
| `label_map` / `labels` | Allowed output tokens and their semantic actions |
| `reference` | Correctness reference where available; absent/null for preference-only tasks |
| `features` | Numerical factors, source grouping and adaptation metadata |
| `source_id`, `pair_id`, `variant`, `phase` | Provenance or controlled-pair metadata where present |

These are schema descriptions, not bundled input records. Task cards list the task-specific structure. Capability panels use their own CSV columns; the questionnaire uses an item/option-to-pole mapping.

## Parsing and aggregation

Interpretation distributions retain every input, including unparseable responses. A valid leading label followed by an explanation can be parsed; this is different from strict single-label format compliance. Accuracy and macro F1 require a reference, with the CommitmentBank strict-majority eligibility rule described in its task card. Capability failures/unparseable labels count as incorrect. GSM8K extraction differs across saved protocols and ARC Easy includes unsupported reference labels in its reported denominator.

Choice proportions and interaction outcomes characterize behavior. Human choices, supplied dialogue histories, financial actions and simulated outcomes are not objective correctness labels. Percentage-point shifts use the corresponding Base. Retention/reversal compares the signs of trained and opposing-combination shifts from that Base; it does not by itself measure unchanged effect magnitude.

Preserve pairing and source dependence. Related dialogue slices, overlapping price windows and numerical/order variants are not independent observations. The paper reports paired tests, effect sizes, confidence intervals and Holm correction in its statistics appendix; aggregate percentages cannot reconstruct paired tests.

## Fixed histories versus interaction

INSPIRED, Frames and real bargaining-history principal panels are single next-action predictions given a supplied context. Program-feedback bargaining allows up to three model choices and generates buyer feedback with a deterministic controller. These are distinct task types. The supplementary authored feedback probes are also separate from the principal history panels.

## Resource availability

This repository provides the core DPO training implementation, benchmark specifications, a machine-readable structural catalogue and links to original providers. It does not include raw datasets, exact selected evaluation panels, evaluation executables, experimental responses/results, or model weights. It is not a turnkey reproduction package for all paper results. Acquire upstream resources separately under their providers' terms; a link to a source dataset is not a release of the exact SPACE adaptation.
