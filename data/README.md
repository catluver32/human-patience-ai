# Data

This folder contains aggregate summary data from the research project.

The public files use 181 retained response-content patterns, not all 204 Google Forms submissions. Exact-content deduplication retained the first occurrence of each response pattern and removed 23 later submissions matching an earlier submission across every response field except timestamp.

The retained patterns are not verified unique people because the supplied dataset does not include respondent identifiers, device/IP markers, or sufficient completion-time metadata.

Raw respondent-level data are not included because they may contain timestamps, demographic combinations, duplicate submissions, and optional written responses that could raise privacy concerns.

Inferential results are available in [`../models/`](../models/).
