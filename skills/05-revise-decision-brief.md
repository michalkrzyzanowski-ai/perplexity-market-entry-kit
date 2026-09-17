# Skill 05 — Revise decision brief

## Purpose

Revise the draft only against supplied reviewer findings.

## Required inputs

- `decision/market-entry-draft.md`
- `decision/evidence-ledger.md`
- `decision/review-findings.md` or participant-supplied reviewer findings
- Company context
- Completed decision brief

## Revision rules

1. Map each material review issue to one of these outcomes:
   - Corrected
   - Removed
   - Relabeled as an assumption
   - Remains unresolved, with explanation
2. Remove unsupported claims unless they are explicitly labeled as assumptions and are appropriate to retain.
3. Correct units, populations, geographies, periods, source descriptions, and claim wording where review findings require it.
4. Update the recommendation only where evidence justifies the change.
5. Keep all realistic decision options, including postponement/no-go.
6. State what evidence would change the recommendation.
7. Retain a clear separation between market attractiveness and company fit.
8. Keep all human-verification fields as `Not yet checked` unless the participant supplies an actual completed human source check.
9. Leave final human approval pending.

## Required output

Create:

- `decision/revised-decision-brief.md`
- `decision/unresolved-items.md`

Include an issue-resolution table:

| Material issue | Correction or unresolved explanation | Evidence status | Effect on recommendation |
|---|---|---|---|

## Do not

- Do not invent reviewer findings.
- Do not represent an AI review as human approval.
- Do not complete final approval fields on behalf of a person.

## Human gate

Ask the decision owner to review the revised draft and unresolved-items register before making a decision.
