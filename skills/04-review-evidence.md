---
name: market-entry-04-review-evidence
description: "Use in a separate, review-only task to check a market-entry draft: open the sources behind the 3 to 5 claims that drive the recommendation and write decision/review-findings.md with verdicts. Do not use in the task that wrote the draft, do not edit the draft, and never mark anything human-verified."
---

# Skill 04: Review evidence

## Purpose

Perform a review-only quality check of the decision draft and the 3–5 claims that materially drive its recommendation.

## Required inputs

- `decision/market-entry-draft.md`
- `decision/evidence-ledger.md`
- `decision-brief.md` (or your own completed decision brief)
- Company context or `decision/company-context-summary.md`
- Original cited external sources

## Run in a separate task

Run this skill in a new task that contains only the inputs above. Do not run it in the task that wrote the draft: the author is the weakest reviewer of its own work. If this conversation produced the draft, stop and ask the participant to start a new review-only task.

A new task is an additional check, not a guarantee of independence from the original model. Human verification is still required.

## Review method

1. Name any missing or unreadable input; stop if an essential item is unavailable.
2. Identify the 3–5 claims that materially drive the recommendation.
3. Open each cited external source.
4. Check whether it supports the exact claim, number/unit, population, geography, and observation period.
5. Distinguish an old publication date from an old observation period. Flag stale evidence without automatically rejecting an older applicable source.
6. Quote only a short relevant passage and give a location such as section, table, page, paragraph, or article.
7. If a source cannot be accessed, label it `Source unavailable`; do not invent a passage.
8. Find contradictions, hidden assumptions, unsupported claims, and company goals presented as facts.
9. Check that market attractiveness and company fit remain separate and that postponement/no-go is considered where relevant.

## Verdict labels

Use only:

- `Supported`
- `Partly supported`
- `Unsupported`
- `Source unavailable`

## Output

Create `decision/review-findings.md` using this table:

| Claim | Source URL | Supporting passage/location | Verdict | Limitation | Effect on recommendation |
|---|---|---|---|---|---|

Then list the top issues a human must resolve.

## Do not

- Do not improve the draft prose.
- Do not revise the recommendation.
- Do not label any AI check as human-verified.
- Do not issue an approved verdict.

## Human gate

Wait for actual reviewer findings or explicit instruction to revise.
