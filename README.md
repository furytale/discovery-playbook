# Discovery Playbook

**What to find out, what to rely on, and when to act.**

Development is already scheduled, but the team still does not know whether an integration supports the operation it needs. Or the reverse: research continues even though there are enough answers for the next decision.

This playbook proposes working through such situations around a specific decision, rather than a mandatory set of meetings and documents.

> **Discovery helps establish a sufficient basis for the next consequential action—or a reasoned decision not to take it.**

The outcome may be a first use case, a boundary for reuse, a pilot decision, clarified scope, or a decision to stop pursuing a direction. Documents support that choice but do not replace it. A check that confirms the original plan is also a useful result.

The playbook is for CTOs, solution architects, business analysts, product leaders, and technical founders. It helps connect material unknowns to the next decision before they turn into code, an estimate, or a commitment.

**Version 0.1.** This is an evolving practitioner playbook assembled from retrospectives and external ideas about problem-solving and organizing work. Its effectiveness as a complete method has not been formally measured. It is not a scientifically proven universal method.

## Start with the Core

| Element | Main question |
|---|---|
| [Decision](core.md#decision) | What do we want to decide, and who has the authority to decide it? |
| [Uncertainty](core.md#uncertainty) | What could change that decision? |
| [Evidence](core.md#evidence) | What information actually answers our question? |
| [Sufficient depth](core.md#sufficient-depth) | What basis is enough for the next step, and where does the check stop? |
| [Decision / stop](core.md#decision-stop) | What do we do now, on what basis, and within what boundaries? |

**The Core is a reasoning discipline, not five mandatory stages.** Set cost and effort limits before material checks. New information may change the original question. A small, reversible change may need only 20 minutes; a specific unknown in a new direction may call for a separate investigation.

Each Core element explains its purpose, the failure it prevents, a minimum rule, and when it is enough. You can start with the [next-action map](core.md#core-decision-map); there is [one example through the Core](core.md#example) at the end.

## Three application contexts

The Core is shared across all three contexts. The application patterns explain differences in budget, authority, access to people, and commitments:

- [Startup](patterns/startup.md): test a new idea with a bounded bet, or embed discovery in ongoing delivery when an architect or CTO joins.
- [Product company](patterns/product-company.md): test a new direction, market, integration, AI capability, or platform capability while accounting for the existing product and commitments.
- [Outsourcing / presales](patterns/outsourcing-presales.md): connect request qualification, context handoff, effort limits, review of findings, and the transition to an estimate and statement of work (SOW).

These are ways to apply the same Core. You can read the Core and go straight to your context.

## How to use it

Start with the next material decision. Identify the unknown that prevents you from justifying it. Choose an appropriate check, define a sufficient result, and set a cost and effort limit. After the check, confirm or change the next step. Running out of budget is a reason to decide whether to continue, narrow, or stop the work; it is not evidence of readiness.

Record the decision where the team already looks for its tasks and commitments. A new document, separate board, or dedicated tool is not required. If the necessary information already exists, is current, and applies to the situation, there is no need to repeat the research.

Not every task needs a large discovery phase. Minimal discovery does not mean skipping mandatory conditions for safe action. An unverified condition limits dependent work but does not necessarily stop everything else.

English is the canonical language of this playbook, future contributions, and the related article.

## What to add when needed

The playbook does not prescribe a universal set of meetings, documents, job titles, or a fixed research duration. It also does not replace development, quality checks, or management decisions. A coordinator, a reviewer with the relevant expertise, and escalation rules are needed to the extent that findings, authority, or commitments would otherwise be lost; separate staff roles are not required.

**DBR** is described in the section on [managing a discovery queue](patterns/outsourcing-presales.md#flow-control). It is an optional way to align work release with available constrained capacity, not a research method or a sixth Core element. It fits situations where several initiatives compete for one specialist, access to an environment, or another shared limited capability.

DBR is not required for a single bounded question without a flow problem. In a startup or product company, it makes sense when the same competition for shared capacity exists.

## Foundations and development

Practical experience explains the choice of problems, but does not by itself establish the effectiveness of the rules. The playbook's examples are hypothetical. Participants' recollections do not establish other people's motives or prove universal causes of success or failure.

After applying the playbook, review which assumption changed, where a decision was lost, and what helped people make it. Add a rule when a specific problem recurs and the cost of a safeguard is understood. A small question does not require a separate retrospective meeting.

---

Author: Anton Kazka.
