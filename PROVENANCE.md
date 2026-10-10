# Provenance and release checklist

This package was assembled from CSV files already present in the local project
workspace. The original retrieval dates and exact upstream revisions were not
recorded in the source workspace. Do not claim a pinned upstream snapshot until
these fields have been verified.

| Dataset | Upstream location | Revision / commit | Retrieval date |
| --- | --- | --- | --- |
| HarmBench behaviors | https://github.com/centerforaisafety/HarmBench (`data/behavior_datasets/harmbench_behaviors_text_all.csv`) | c0423b952435fcc8467108d8f25962dbae5b7de2 (content verified identical to upstream `main`) | 2026-10-10 |
| JBB-Behaviors | https://huggingface.co/datasets/JailbreakBench/JBB-Behaviors | 886acc352a31533ffbcf4ef22c744658688086fc (content verified identical to upstream `main`) | 2026-10-10 |

Before publishing a completed translation, record the translator and reviewer
credits, translation/review process, release version, and any changes to
upstream rows. Preserve per-row source information and confirm the applicable
license and attribution requirements for JBB constituent datasets.
