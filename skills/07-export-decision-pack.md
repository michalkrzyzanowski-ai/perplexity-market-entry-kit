---
name: market-entry-07-export-decision-pack
description: "Use at the end of the market-entry decision sprint to package all decision/ artifacts into decision/decision-pack-index.md with their status and verification state. Do not alter source content and do not mark the decision approved."
---

# Skill 07: Export decision pack

## Purpose

Package the workflow outputs into a reusable, reviewable Markdown decision record.

## Required inputs

- `decision/company-context-summary.md`
- `decision/context-and-gaps.md`
- `decision/assumptions-and-unknowns.md`
- `decision/data-request-register.md`
- `decision/research-plan.md`
- `decision/evidence-ledger.md`
- `decision/market-entry-draft.md` and/or `decision/revised-decision-brief.md`
- `decision/review-findings.md`
- `decision/unresolved-items.md`
- `decision/executive-deck-outline.md`

## Package rules

1. Produce an index that links each artifact to its purpose and status.
2. Preserve source URLs, company-file citations, dates, periods, geographies, limitations, and verification statuses.
3. Keep source facts, goals, assumptions, AI interpretations, recommendations, and unknowns distinct.
4. State whether the pack is draft, reviewed, or awaiting human decision.
5. Do not imply that a human approved any item unless an actual human approval is recorded.

## Output

Create `decision/decision-pack-index.md` containing:

- Decision title and owner
- Current workflow stage
- Artifact inventory
- Material claims and verification status
- Outstanding dependencies
- Next decision gate
- Human approval status: pending unless explicitly completed

## Optional export layout

```text
decision/
  company-context-summary.md
  context-and-gaps.md
  assumptions-and-unknowns.md
  data-request-register.md
  research-plan.md
  evidence-ledger.md
  market-entry-draft.md
  review-findings.md
  revised-decision-brief.md
  unresolved-items.md
  executive-deck-outline.md
  decision-pack-index.md
```

## Do not

- Do not alter source content during packaging.
- Do not remove limitations, unresolved items, or review findings to make the package look more conclusive.
- Do not mark the decision approved.
