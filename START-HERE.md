# Start here: market-entry decision sprint

This kit helps you turn a business question into a reviewable, evidence-backed decision package using Perplexity Computer and a company second brain.

## What you will produce

- A validated decision context
- A record of assumptions, unknowns, and data requests
- An approved research plan
- An evidence ledger and market-entry draft
- An AI review of decision-critical claims
- A revised decision brief and an executive-deck outline

## Two ways to run the workflow

- **Copyable prompts:** follow the five steps in [prompts.md](prompts.md). Nothing to install.
- **Perplexity Computer Skills:** install the eight skills below once, then run them in order. Adds a workflow state file, assumption and data-request registers, an executive deck outline and a decision pack.

Use one or the other for a run, not both.

## Set up the skills

1. In Perplexity Computer, open Skills and upload each file in `skills/` as a custom skill (eight uploads). Each file starts with the YAML frontmatter Perplexity requires.
2. Create a Project or task and attach the inputs:
   - `company-brain/` (five files) and `decision-brief.md`, or your own equivalents
   - `templates/market-entry-report.md`
   - `templates/assumptions-and-unknowns-template.md`
   - `templates/data-request-register-template.md`
   - `templates/executive-deck-outline.md`
3. Skills load automatically based on your request. Name the skill you want at each step, for example "Run skill 02: plan research", so the right one loads.

## Choose your starting mode

### A. File-based context
Choose this when you have company context files. Use the files in `company-brain/` plus `decision-brief.md`.

### B. Interview-based context
Choose this when you have no usable company files. Perplexity asks focused questions and creates a minimum context pack.

### C. Hybrid context
Choose this when some files exist but decision-critical details are absent. Perplexity uses readable files first and asks only for missing information.

## Recommended sequence

1. Run `skills/00-choose-context-mode.md`.
2. Run `skills/01-build-or-validate-context.md`.
3. Review and complete `decision/context-and-gaps.md`.
4. Run `skills/02-plan-research.md`; explicitly approve the plan.
5. Run `skills/03-research-market-entry.md`.
6. Run `skills/04-review-evidence.md` in a new, review-only task.
7. Run `skills/05-revise-decision-brief.md`.
8. Run `skills/06-create-executive-deck.md`.
9. Run `skills/07-export-decision-pack.md`.

## Non-negotiable rules

- Supplied company files are company context, not external evidence. Cite them by filename.
- Treat goals as goals, not forecasts or demonstrated facts.
- Do not silently fill evidence gaps with assumptions.
- Keep market attractiveness separate from company fit.
- Include postponement or no-go when it is a realistic option.
- Prefer primary and official sources for external claims.
- Record source URL, title, publisher, publication date, observation period, geography/population, and limitations.
- Do not mark any claim human-verified unless a person has actually checked it.
- A plan is not permission to research. Research is not a human decision.

## Workshop principle

Public research explains the market. Company context explains what matters to the company. Combining both produces more relevant research, clearer assumptions, stronger governance, and a decision package that a human can review.
