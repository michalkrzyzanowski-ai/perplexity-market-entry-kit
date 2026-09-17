# Copyable workshop prompts

Use one step at a time. Replace bracketed fields before sending. Do not paste all prompts together.

## Research instructions

Put these in dedicated project instructions, or send them as the first message with the seven files listed in the README.

```text
You support the decision in decision-brief.md using the five attached Kestrel company-brain files and market-entry-report.md.
All Kestrel facts and figures are fictional scenario inputs. Do not search for the company or present its figures as external evidence.
Cite the filename for company information. Treat goals as goals, not demonstrated facts. Name unreadable or missing files rather than assuming their contents.
Work in stages: context and gaps; proposed plan; explicit human approval; research and draft. Stop at each requested gate. A request for a plan does not authorize execution.
Prefer primary/official sources for external claims. Record exact URLs, title, publisher, publication date, observation period, geography, and relevant limitations. If unavailable, mark the field unknown.
Separate company facts, external evidence, assumptions, AI interpretation, recommendations, and open questions. Search for counter-evidence.
Assess market attractiveness separately from company fit. Consider a Poland pilot, a Germany pilot, and postponement. Do not preselect a winner.
Do not invent market size, demand, willingness to pay, legal applicability, cost, or payback. Explain what inputs are missing.
Follow market-entry-report.md. A human approves the final decision. Never label your own findings human-verified.
```

## 1. Context-gap check: live build-along

```text
Before researching, list the seven attached files and confirm which you can read. Stop if required files are missing.
Restate the decision and cite the company facts and constraints you will use.
List missing information and assumptions you would otherwise make. Ask at most five questions that could change the recommendation.
Do not search the web or draft the report yet. Wait for my answers.
```

Read the questions. Answer from the supplied scenario or say "unknown". If you introduce an invented answer for practice, label it as a new fictional assumption.

## 2. Research plan: wait for approval

```text
My answers to the context questions:
[Paste numbered answers. Explicitly mark unknowns and any new fictional assumptions.]

Propose a bounded plan for the decision brief using three workstreams: demand and target-customer evidence; route to market and company fit; readiness barriers and unresolved dependencies.
For each, state the questions, preferred sources, and what would count as insufficient evidence.
Keep the output to an executive summary with 3–5 material claims and supporting tables. Use the supplied report template.
Do not run the research yet. Wait for my explicit plan approval.
```

## 3. Execute the approved plan

Only send this after reading the plan. Narrow it first if it is too broad.

```text
I approve the plan, subject to these changes:
[Write changes or "No changes".]

Execute that plan. Compare a Poland pilot, a Germany pilot, and postponement.
Use the company files for scenario context and researched sources for external evidence. Look for evidence against the preferred option.
Create a draft following market-entry-report.md. Include exact source URLs, limitations, a separate attractiveness/fit comparison, assumptions, and next validation actions.
Keep the executive summary to one page. Mark all human-verification fields "not yet checked" unless I have explicitly supplied a human check.
If key evidence is missing, give a conditional recommendation or insufficient-evidence finding. Do not force a country selection.
```

## 4. Separate reviewer task

Download/save the draft. Start a fresh review-only task with the draft, five company files, and decision brief attached. Do not apply the research-authoring instructions to this task. A new task is an additional check, not guaranteed independence from the original model or its memory.

```text
This task is review only. Do not run the authoring workflow or improve the prose.
Read the attached draft, decision brief, and company context. Name any missing inputs.
Identify the 3–5 claims that materially drive the recommendation. Open their cited sources and determine whether each supports the exact claim, units, population, geography, and period. Quote only a short relevant passage and give its location.
Mark each claim: supported, partly supported, unsupported, or source unavailable. If a source cannot be accessed, do not invent a passage.
Distinguish old publication dates from old observation periods; flag stale evidence without automatically rejecting an older applicable source.
Find contradictions, hidden assumptions, and company goals presented as facts. Check that attractiveness and fit are separate and postponement is considered.
Output: claim | source URL | supporting passage/location | verdict | limitation | effect on recommendation.
Then list the top issues a human must resolve. Do not issue an approved verdict or label any AI check human-verified.
```

## 5. Revise and hand off for human review

Return to the authoring task with the reviewer output. Do not paste confidential source material into a different service.

```text
Review findings:
[Paste the reviewer table and issues.]

Revise the draft. For each material issue, show the correction or explain why it remains unresolved. Remove unsupported claims or label them explicitly as assumptions.
Update the recommendation only where evidence justifies it. Include what evidence would change it.
Keep an unresolved-items table with next action and proposed owner. Leave final human approval pending. Do not change human-verification status unless I provide the actual check.
```

Finish with the [human checklist](quality-checklist.md). Save the draft and reviewer table separately so corrections remain visible.
