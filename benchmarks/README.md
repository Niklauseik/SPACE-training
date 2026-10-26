# SPACE benchmark specifications

Task structure and resource navigation for **More Than Just Style: Benchmarking Personality Influence in Large Language Models**.

[Shared protocol](protocol.md) | [Machine-readable catalogue](manifest.json) | [Training code](../README.md#training)

This directory provides specifications and original-source links. Exact evaluation panels, raw datasets, evaluation executables, model outputs and weights are not distributed. Counts below are the named SPACE task versions, not the sizes of the complete upstream datasets.

## Hierarchy

```text
SPACE
├── Personality verification: MBTI
├── Basic capabilities: GSM8K, ARC Easy, BoolQ
├── Hierarchical situational tasks
│   ├── Interpretation: Circa, CommitmentBank, FOMC, FiQA SA, SST-2, News
│   ├── Individual decisions: risk, transport, machine, delay, stock, bargaining
│   └── Interactive decisions: INSPIRED, Frames, bargaining histories, program feedback
├── Supplementary controlled probes
└── Training resource: Machine Mindset (separate from evaluation)
```

## Personality verification

| Task | SPACE coverage | Specification | Original source |
| --- | ---: | --- | --- |
| MBTI personality verification | 46 inputs per condition | [Open task card](personality/mbti.md) | [SPACE specification](personality/mbti.md) |

## Basic capabilities

| Task | SPACE coverage | Specification | Original source |
| --- | ---: | --- | --- |
| GSM8K | 1,300 inputs per condition | [Open task card](capability/gsm8k.md) | [Original source](https://github.com/openai/grade-school-math) |
| ARC Easy | 2,000 inputs per condition | [Open task card](capability/arc-easy.md) | [Original source](https://huggingface.co/datasets/allenai/ai2_arc) |
| BoolQ | 2,000 inputs per condition | [Open task card](capability/boolq.md) | [Original source](https://github.com/google-research-datasets/boolean-questions) |

## Situational interpretation

| Task | SPACE coverage | Specification | Original source |
| --- | ---: | --- | --- |
| Circa | 32,602 inputs per condition | [Open task card](interpretation/circa.md) | [Original source](https://github.com/google-research-datasets/circa) |
| CommitmentBank | 1,009 inputs per condition | [Open task card](interpretation/commitmentbank.md) | [Original source](https://github.com/mcdm/CommitmentBank) |
| FOMC policy stance | 2,421 inputs per condition | [Open task card](interpretation/fomc.md) | [Original source](https://github.com/gtfintechlab/fomc-hawkish-dovish) |
| FiQA sentiment analysis | 1,173 inputs per condition | [Open task card](interpretation/fiqa-sa.md) | [Original source](https://sites.google.com/view/fiqa/) |
| SST-2 sentiment | 10,000 inputs per condition | [Open task card](interpretation/sst2.md) | [Original source](https://huggingface.co/datasets/stanfordnlp/sst2) |
| Financial news sentiment | 11,931 inputs per condition | [Open task card](interpretation/financial-news.md) | [Original source](https://huggingface.co/datasets/zeroshot/twitter-financial-news-sentiment) |

## Individual decision making

| Task | SPACE coverage | Specification | Original source |
| --- | ---: | --- | --- |
| Choices13k risky choices | 1,764 inputs per condition | [Open task card](individual/choices13k.md) | [Original source](https://github.com/jcpeterson/choices13k) |
| Transportation | 210 inputs per condition | [Open task card](individual/transportation.md) | [Original source](https://github.com/statsmodels/statsmodels/tree/main/statsmodels/datasets/modechoice) |
| Machine selection | 4,160 inputs per condition | [Open task card](individual/machine-selection.md) | [Original source](https://huggingface.co/datasets/marcelbinz/Psych-101) |
| Delayed rewards | 288 inputs per condition | [Open task card](individual/delayed-rewards.md) | [SPACE specification](individual/delayed-rewards.md) |
| Original stock windows | 2,074 inputs per condition | [Open task card](individual/stock-windows.md) | [Original source](https://github.com/pipiku915/FinMem-LLM-StockTrading) |
| Controlled stock paths | 1,005 inputs per condition | [Open task card](individual/controlled-stock.md) | [SPACE specification](individual/controlled-stock.md) |
| Single-turn bargaining | 2,334 inputs per condition | [Open task card](individual/single-turn-bargaining.md) | [Original source](https://github.com/stanfordnlp/cocoa/tree/master/craigslistbargain) |
| Controlled buyer offers | 900 inputs per condition | [Open task card](individual/controlled-bargaining.md) | [Original source](https://github.com/stanfordnlp/cocoa/tree/master/craigslistbargain) |

## Interactive decision making

| Task | SPACE coverage | Specification | Original source |
| --- | ---: | --- | --- |
| INSPIRED recommendations | 119 inputs per condition | [Open task card](interaction/inspired.md) | [Original source](https://github.com/sweetpeach/Inspired) |
| Frames travel proposals | 282 inputs per condition | [Open task card](interaction/frames.md) | [Original source](https://github.com/Maluuba/frames) |
| Real bargaining histories | 351 inputs per condition | [Open task card](interaction/bargaining-histories.md) | [Original source](https://github.com/stanfordnlp/cocoa/tree/master/craigslistbargain) |
| Program-feedback bargaining | 2,272 inputs per condition | [Open task card](interaction/bargaining-feedback.md) | [Original source](https://github.com/stanfordnlp/cocoa/tree/master/craigslistbargain) |

## Supplementary controlled probes

| Task | SPACE coverage | Specification | Original source |
| --- | ---: | --- | --- |
| Decision probes | 1,319 inputs per condition | [Open task card](probes/decision-probes.md) | [SPACE specification](probes/decision-probes.md) |
| Decision probes semantic | 1,319 inputs per condition | [Open task card](probes/decision-probes-semantic.md) | [SPACE specification](probes/decision-probes-semantic.md) |
| Decision deep probes | 182 inputs per condition | [Open task card](probes/decision-deep-probes.md) | [SPACE specification](probes/decision-deep-probes.md) |
| Decision validation | 360 inputs per condition | [Open task card](probes/decision-validation.md) | [SPACE specification](probes/decision-validation.md) |
| Decision history replication | 108 inputs per condition | [Open task card](probes/decision-history-replication.md) | [SPACE specification](probes/decision-history-replication.md) |
| Decision targeted followup | 304 inputs per condition | [Open task card](probes/decision-targeted-followup.md) | [SPACE specification](probes/decision-targeted-followup.md) |
| Risk summary replication | 160 inputs per condition | [Open task card](probes/risk-summary-replication.md) | [SPACE specification](probes/risk-summary-replication.md) |

## Training resource

| Task | SPACE coverage | Specification | Original source |
| --- | ---: | --- | --- |
| Machine Mindset preference data | 12,159 T/F preference pairs | [Open task card](training-data/machine-mindset.md) | [Original source](https://github.com/PKU-YuanGroup/Machine-Mindset) |

## Main-text targeted probes

The expected-payoff replication has **20 economic cells and 80 matched input settings**, crossing presentation frame and option order. Each setting is evaluated without and with an explicit payoff summary, producing **160 prompt records (80 per summary condition)** in the frozen replication suite. The buyer-offer probe has **15 source situations and 315 inputs** including offer levels and option orders. These are separate from the principal 1,764-choice variance panel and 900-input controlled-bargaining panel. The probe-suite cards list saved prompt-record counts; these must not be confused with matched-pair counts or independent economic situations.

The two authored feedback versions per recommendation domain are reported separately in the paper statistics appendix; they are not part of the 119/282 principal history panels.
