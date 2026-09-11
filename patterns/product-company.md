# Product company: a new direction without putting the existing product on hold

[Back to the Playbook](../README.md) · [Core](../core.md)

This pattern applies Core to a company that already has users, a working product, and commitments. Data and experience provide a starting point. At the same time, architecture, operations, customer agreements, and compliance requirements constrain the available options. A new direction has to be tested alongside ongoing work.

Unlike [a new idea in a startup](startup.md), here you can start with observed product use. But the success of an existing solution does not establish demand in a new region, the suitability of another provider, or the value of a new capability.

## Start with the next decision

“Launch a new direction” is too broad for a single check. Choose an action that will lead to material costs or commitments: inviting a group of users to a pilot, choosing a provider, starting a migration, or allocating a team. Name the decision owner, the deadline, and the first scenario.

Depending on the direction, the question might be:

- **New product line:** should we test a specific scenario with the current segment or first look for a different audience?
- **New market, region, or channel:** does the existing scenario fit the local process, buyer, and sales approach?
- **New integration or provider:** are the required operations supported under the available conditions, and is the cost of switching justified?
- **AI capability:** is the result useful on real tasks, and are the errors and the cost of human review acceptable?
- **Platform capability:** which product will use it first, and does that product's result justify developing, deploying, and maintaining the shared mechanism?
- **Material change across several products:** can the first transition preserve the necessary compatibility and current commitments?

These are examples of decisions, not a mandatory research list. For a clear, reversible change, a short review of existing data may be enough.

## Use existing data within its limits

Start with telemetry for the relevant scenario: who uses it, where they stop, and what errors occur. Compare it with support requests, reasons for rejection, customer conversations, and examples of manual work. Check that the data is current, events are complete, and the segment's composition is understood: an aggregate metric may hide different processes.

This information helps select a question. It does not automatically explain the reasons for behavior or establish that users will accept a proposed change. A request from one large customer does not establish demand across the market either.

Available analysts and process owners help make sense of the current product and how the company works. But experience with product telemetry does not automatically mean an ability to research a new market. For a new direction, check that the necessary skills are available and involve the specialist in the relevant check, taking their current commitments into account.

Fresh evidence is needed when the audience, process, or cost of an error changes. For a new region, examine a specific case with a local user and the people involved in the process. For a new workflow step, show it to the people who will have to use it. For AI, test representative tasks and material errors; a good demo using selected examples does not replace that check.

If the question concerns a technical capability, use applicable documentation, code, and a check of behavior in a suitable environment. A user interview does not establish that an API works, and a successful request does not establish product value. Keep the limits of the finding with the result, following the [Evidence](../core.md#evidence) rule.

## Make constraints part of the decision

Trace one end-to-end scenario through the affected systems and teams. Find out what data and permissions are needed, where existing contracts remain in place, who handles failures, and who will maintain the result. Include deployment, migration, and ongoing ownership in the platform or integration estimate.

Separately, compare the new step with current commitments: service availability, promised capabilities and deadlines, support workload, conditions for handling data, and required approvals. If commitments need to change, the initiative owner agrees on those changes with the owners of the affected products. A pilot plan does not authorize silently postponing their delivery or degrading service.

Distinguish an unknown fact from a decision that has not been made. Migration feasibility requires a technical check; postponing a commitment requires a decision by the authorized owner. A discovered contradiction must change the dependent plan before it reaches implementation. Safe, independent work can continue while the contradiction is being resolved.

## Bound the pilot and set a review point in advance

Choose a boundary that lets you test the next question: one scenario, segment, partner, or product. Before starting, agree on acceptable costs and timing, an observable result, conditions for stopping, and the people responsible for operations. Specify how to disable or restore the solution; if the action is irreversible, account for that when choosing the scale and depth of the check.

For example, an AI assistant could prepare drafts for a limited group of operators. Check its usefulness in their work, the types of errors, and the time needed to correct them. The decision to expand the pilot depends on these results and the conditions for handling data. Using a model does not by itself justify automatically taking actions on an operator's behalf.

A small scale does not remove mandatory security and compliance requirements. Pilot success applies to the tested conditions; a broader launch may require additional evidence.

At the review point, the decision owner chooses whether to expand, narrow, repeat a specific check, wait for a dependency, or stop the initiative. Confirming the original plan is also valid. Carry the completed analysis, conditions, and open questions into the work plan; an exhausted budget and participants' silence do not authorize a launch.

## When initiatives compete for the same specialists

Several initiatives may need the same domain expert, architect, data specialist, or compliance specialist at the same time. Make this shared demand visible before promising dates. Those responsible for priorities must choose the order with current commitments in mind; the expert is not obliged to compensate for the conflict by constantly switching tasks.

If a persistent queue develops, you can use [the conditional DBR adaptation for flow control](outsourcing-presales.md#flow-control): keep a small queue of questions with the necessary inputs and release work as the shared specialist becomes available. A single initiative without this competition does not need a separate mechanism.

After the decision, it is useful to compare expected and actual costs, new information, and effects on the current product. A recurring error provides grounds to refine a playbook rule; a one-off difficulty does not require a new mandatory stage.

---

[Back to the Playbook](../README.md) · [Core](../core.md)
