# Data Codebook

## Dataset Basis

- Submitted responses: 204.
- Retained response-content patterns: 181.
- Cleaning method: retain the first occurrence of each pattern and remove later submissions matching across all response fields except timestamp.
- Raw individual-level responses are not publicly included.
- The retained patterns are not verified unique identities.

## Scale Interpretation

Most rating questions used a 1-7 scale, where higher values generally indicate more of the measured construct. The five-item frustration composite reverse-coded the positively oriented time-use and AI-confidence items before averaging.

Cronbach's alpha was .694. This is described as marginal internal consistency for an exploratory, multidimensional composite—not as scale validation. The composite includes a giving-up item that overlaps with part of H4 and a mental-effort item related to the mechanism proposed for H3.

## File Descriptions

- `sample_summary.csv` — submission counts, cleaning basis, and sample overview.
- `key_mean_ratings.csv` — principal means and standard deviations.
- `scenario_frustration_means.csv` — Scenario A and Scenario B checkpoint descriptives.
- `failure_type_counts.csv` — forced-choice failure-type responses used in one H2 operationalization.
- `attention_change_counts.csv` — self-reported reading-attention categories.
- `first_action_counts.csv` — intended first action after repeated wrong answers.
- `behavior_grouped_counts.csv` — constructed switch-away versus stay-and-repair endpoint used for H4.
- `chatbot_platform_counts.csv` — multiple-selection chatbot-platform responses.
- [`../models/`](../models/) — rebuilt inferential tables and full statistical workbook.
