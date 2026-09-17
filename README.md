# Company Brain to Market Entry

Participant kit for Michał Krzyżanowski's DataCamp webinar, **Write a Market Entry Strategy Report with Perplexity Computer**, September 17, 2026.

**The question:** Is this market attractive *for us*?

Build a company-grounded research workflow, inspect its evidence, and produce a draft recommendation. The company is fictional; external market evidence must be researched and verified. No country is predetermined to win.

[Download the workshop ZIP](https://github.com/michalkrzyzanowski-ai/perplexity-market-entry-kit/archive/refs/tags/v0.1.zip) · [Webinar](https://www.datacamp.com/webinars/write-a-market-entry-strategy-report-with-perplexity-computer) · [Copyable prompts](prompts.md)

## Before you start

- To watch: a browser and the webinar link. No coding or Perplexity subscription needed to watch.
- To execute the prompts: a laptop/desktop browser, a Perplexity account with Computer access, and available credits. Confirm you can start a Computer task before the session. Webinar registration does not include Perplexity credits.
- Basic familiarity with AI chat is helpful. No Git, GitHub account, API keys, or existing company brain required.
- Check [current credit requirements](https://www.perplexity.ai/help-center/en/articles/13838041-how-credits-work-on-perplexity). Usage varies; this kit does not promise a runtime or credit budget.
- Use the supplied fictional case. If adapting it, upload only information you are authorized to share with the tool.

## Five-minute setup

1. Download the ZIP above and extract it. Or open individual files here and use GitHub's download-raw-file control.
2. Open Perplexity Computer and create a dedicated Project/workspace for **Kestrel EU Entry**, if available in your account. Otherwise attach the same files directly to a new Computer task. Interface labels can vary.
3. Upload these **seven files**:
   - `company-brain/overview.md`
   - `company-brain/icp.md`
   - `company-brain/offer-and-positioning.md`
   - `company-brain/capabilities-and-constraints.md`
   - `company-brain/decision-criteria.md`
   - `decision-brief.md`
   - `templates/market-entry-report.md`
4. Copy the **Research instructions** from [prompts.md](prompts.md) into project instructions, or send them as the first task message if that setting is unavailable.
5. Run **Prompt 1: Context-gap check**. Confirm the agent lists all seven files and cites their contents. If it cannot read a file, reattach it before continuing.

## During the webinar

The build-along exercise is the context-gap check. Identify one missing fact that could change the decision. Do not launch the full research run until you have answered the questions and approved its plan.

If you are watching without Computer access, read the [decision brief](decision-brief.md) and [constraints](company-brain/capabilities-and-constraints.md). Share one missing fact or unsafe assumption in the webinar chat.

The presenter may show pre-run research to avoid waiting for a long task. Your output can differ. Compare evidence quality and reasoning, not whether you chose the same country.

## Run the complete workflow afterwards

Follow the numbered [prompts](prompts.md):

1. Check context and gaps. Stop and answer.
2. Propose a bounded plan. Stop and review.
3. Approve the plan and execute research.
4. Review the draft in a separate review-only task.
5. Revise and record what remains unverified.

Use the [quality checklist](quality-checklist.md) before relying on a recommendation. The agent never grants final approval.

## What is in the kit?

| File | Purpose |
|---|---|
| [Company brain](company-brain/overview.md) | Five short fictional company-context files |
| [Decision brief](decision-brief.md) | Poland vs Germany, constraints, and explicit alternatives |
| [Prompts](prompts.md) | Instructions and copyable steps with approval pauses |
| [Quality checklist](quality-checklist.md) | Evidence checks and human approval |
| [Company-context template](templates/company-context.md) | Adapt the method to your company |
| [Decision-brief template](templates/decision-brief.md) | Define a different research decision |
| [Report template](templates/market-entry-report.md) | Executive summary, evidence, fit, and unresolved issues |

## Important boundaries

- All Kestrel numbers, customers, capabilities, and proof points are invented for teaching. Treat them as scenario inputs, never external evidence or real case-study results.
- Internal goals do not prove demand. Existing customer interest does not prove willingness to buy.
- Source links are not verification. Confirm a source supports the exact claim and its scope.
- Regulatory questions are research questions, not legal conclusions. Escalate unresolved applicability questions to qualified review.
- A separate review task can still repeat an error. Humans verify the material claims and own the decision.
- This release contains prompts and templates, not a benchmarked workflow or a completed market-research report. No fabricated sample results are included.

## Troubleshooting

- **No Computer access or credits:** follow the reading/chat exercise; run the tool later if you choose.
- **Agent cannot see files:** attach them directly and ask it to name each file and summarize one relevant constraint.
- **Agent starts research too early:** stop it; resend the current prompt's stop condition.
- **Slow or expensive run:** reduce scope, use the approved plan, and inspect account usage before starting another task.
- **Citation unavailable:** mark it unavailable. Do not invent a quotation or mark it verified.

## Version and presenter

Workshop snapshot: **v0.1**. The ZIP link points to this version so it remains consistent with the session.

Prepared by [Michał Krzyżanowski](https://michalkrzyzanowski.com). This is the presenter's participant kit, not an official Perplexity product or a DataCamp-maintained repository.

You may use and adapt the original prompts, fictional case, templates, and checklist for learning and your own internal work. Please retain attribution when sharing the kit. Third-party sources retain their own terms.
