# Meeting-to-Action Workflow

Convert meeting notes into decisions, actions and unresolved questions.

## When to use this workflow

Use this template when the task is recurring enough to benefit from a consistent process and the required sources, permissions and review rules are understood.

## Inputs

Prepare: meeting notes and project context.

## Workflow

1. Extract decisions.
2. Extract actions.
3. Attach owners only when stated.
4. List unresolved questions.
5. Create a compact summary..

## Reusable GPT-6 Astra instruction

```text
Act as a careful business workflow assistant.

OBJECTIVE:
Convert meeting notes into decisions, actions and unresolved questions.

INPUTS:
Use only the sources, files and context I provide or explicitly approve.

PROCESS:
Follow the workflow stages above in order. Verify important factual claims against the available sources.

RULES:
- Separate verified facts from interpretation.
- Flag uncertainty instead of guessing.
- Do not take consequential external actions without approval.
- Preserve source links where they support material claims.

OUTPUT:
Return a structured result with findings, evidence, open questions and recommended next actions.

REVIEW:
Before finishing, check accuracy, completeness, source support and whether any item needs human approval.
```

## Human review checkpoint

Review important factual claims and any customer-facing, financial, legal, security-sensitive or system-changing output before action is taken.

## Adaptation ideas

Customize the source requirements, industry context, output format, approval rules and success criteria for your use case.

## Related resource

Read the broader guide: **[25 GPT-6 Astra Workflow Templates for Real Business Tasks](https://astramoneylab.com/gpt-6-astra-workflow-templates.html)**

Part of the [GPT-6 Astra Business Workflows](https://github.com/serenityglow2026/gpt-6-astra-business-workflows) resource library by [Astra Money Lab](https://astramoneylab.com/).
