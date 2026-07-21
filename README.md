# Human Patience and AI Frustration

A student-led research project examining how repeated hypothetical AI chatbot errors relate to reported frustration, trust, reading attention, and intended next actions.

> **Analysis status:** Revised July 2026. The public results use 181 retained response-content patterns after an exact-content duplicate rule removed 23 later submissions from 204 collected submissions. These patterns are not verified unique identities.

## Overview

AI chatbots are widely used for school, work, and everyday problem-solving, but they can also produce inaccurate or conflicting responses. This cross-sectional, scenario-based survey examined respondents' ratings and intended reactions after fixed sequences of imagined chatbot errors. It did not observe behavior in a live chatbot task and does not establish causal effects.

## Research Question

What is the relationship between repeated AI chatbot mistakes and reported user frustration, trust, reading attention, and behavior such as rephrasing, switching tools, or giving up?

## Methods

The study used a Google Forms scenario survey. Respondents completed trust and expected-accuracy items, two fixed error scenarios, attention and intended-action items, a five-item exploratory frustration composite, and demographic questions.

The rebuilt analysis used:

- Friedman tests and Holm-adjusted paired Wilcoxon tests for repeated frustration ratings.
- An exact binomial comparison and paired final-checkpoint sensitivity analysis for H2.
- Binary logistic regression with odds ratios and 95% confidence intervals for H3 and H4.
- Spearman and Kruskal-Wallis sensitivity analyses for directional attention and action-category differences.

## Rebuilt Findings

| Hypothesis | Rebuilt conclusion | Key result |
|---|---|---|
| H1: frustration rises across repeated errors | **Supported** | Scenario A: Friedman chi-square(3) = 374.60, Kendall's W = .690; Scenario B: chi-square(2) = 275.12, W = .760; both p < .001. |
| H2: inconsistent errors are more frustrating | **Mixed evidence** | Exclusive forced choice favored Scenario B, 60 vs. 35, exact p = .013, but the paired final rating was slightly lower for B than A, mean difference = -0.182, Wilcoxon p = .0095. |
| H3: frustration predicts an attention change toward verification | **Partially supported** | The composite model for any attention change did not reach .05, OR = 1.39, 95% CI [0.97, 1.98], p = .069. Directional results did not establish a shift toward more-careful verification. |
| H4: frustration predicts grouped switch-away intentions | **Not supported** | OR = 1.08, 95% CI [0.84, 1.38], p = .565. External search, switching AI tools, and giving up should be modeled separately. |

Repeated-error ratings show a strong frustration pattern. The proposed "verification shift" is retained only as a conceptual interpretation for future live-task research—not as an observed mechanism demonstrated by this survey.

## Repository Contents

- [`paper/`](paper/) — revised paper PDF and exact revision change log.
- [`models/`](models/) — rebuilt H1-H4 workbook, public result tables, and descriptive figures.
- [`survey/`](survey/) — survey-question summary.
- [`data/`](data/) — aggregate public summaries for the 181-pattern analysis basis.
- [`transparency/`](transparency/) — AI-use, ethics/privacy, and limitations notes.

## Data and Ethics Note

Raw respondent-level data are not publicly shared because the source contains timestamps, demographic combinations, duplicate submissions, and optional written responses. The retained data include 24 records selecting "Under 18." The supplied materials did not document the applicable consent, assent, parental-permission, or institutional/school ethics determination; that procedure should be documented before presenting the project as completed human-subjects research.

## Author

Steven Pham

## AI Use Statement

AI tools assisted with outlining, drafting, charts, statistical explanations, rebuilt-model validation, and revision formatting. The student researcher remains responsible for reviewing the source data, model specifications, paper language, and reported conclusions.
