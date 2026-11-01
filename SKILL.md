---
name: project-workflow
description: Read project requirements, maintain a compact work plan and evidence-based decision notes, and prepare bounded handoffs when parallel work is requested. Use for project kickoff or ongoing coordination; preserve existing document owners and required forms.
---

# Project workflow

Help the user keep project direction, work assignments and consequential decisions understandable. Work within the requested phase and the project's existing rules.

## Resolve the project and scope

- Identify the actual working project from the user's request and its README. The checkout containing this skill is a tool source, not automatically the target project. Keep generated project documents in the target project's authorized directory.
- Read applicable instructions, the README, relevant requirements, existing plans/records and the structure of relevant inputs before proposing changes. If a collaboration or submission form exists, read its actual questions and preserve its required headings and format. Do not require such a form or assume a fixed question count.
- Reuse settled user decisions. Separate explicit requirements, stakeholder-confirmed conditions, preferences and provisional assumptions. Ask only questions whose answers change scope, validity, interfaces or the next action. Prepare stakeholder questions for the user to convey; do not send messages on their behalf without authorization.
- Apply the requested scope: setup, planning, implementation support or recording. A setup-only request does not authorize implementation. Respect read-only mode and existing execution permissions. Independent work can continue while a genuinely blocking question remains open.

## Keep three responsibilities distinct

Reuse an existing owner for each responsibility. For a small project without suitable owners, the following are optional defaults, not a required scaffold:

| Responsibility | Optional default | Contents |
|---|---|---|
| Operating guidance | `AGENTS.md` | Short document map, execution/verification conventions, file ownership and when records are updated |
| Current work direction | `WORK_PLAN.md` | Goal, required outputs, constraints/assumptions, actionable work, interfaces, owners and acceptance checks |
| Consequential reasoning | `DECISIONS.md` | Decisions and reasons, material alternatives/changes, verification evidence, contribution boundaries and remaining limits |

- Preserve supplied instructions and required documents. Add only the small amount of operating guidance needed; do not replace an existing AGENTS file or copy the entire plan into it.
- If Issues, an existing plan, ADRs or an adopted record directory already own this information, update or link those owners instead of creating duplicate files. This skill does not migrate records or install another recording workflow.
- Use the project's established or user-requested document language and filenames. Create only documents with actual content; do not create empty architectural, task or diary folders.

## Establish useful work direction

1. Summarize the required behavior, inputs/outputs, actual execution environment and evidence that will establish completion. Identify the smallest working path through all mandatory parts.
2. Resolve high-impact questions and label unanswered assumptions. Distinguish inviolable conditions from preferences that can be traded off. Do not silently convert a suggested target into a mandatory constraint.
3. Use the existing stack and structure where suitable. Infer no mandatory UI, database, container, agent role, optimizer or deployment requirement from an unrelated example.
4. Schedule early integration and verification before optional refinement. Adapt milestones to the actual project and any stated time budget; do not impose a universal duration or claim access to a timer the agent cannot observe.
5. Keep operational task status in its plan/Issue owner. Keep the reasoning for important choices in its decision owner and link between them when useful.

## Prepare parallel work only when requested

- Split genuinely independent work after agreeing on shared input/output contracts. Specify fields, units and failure behavior only to the extent needed to avoid incompatible implementations.
- Give each assignment a goal, source context, mandatory conditions, allowed and excluded files, shared interface, acceptance checks and expected completion report.
- Assign one active writer to each shared file and one coordinator to the common plan/decision notes. Dependency manifests, schemas and shared configuration need an explicit owner. Do not create a complete project copy or a directory per worker merely to represent assignments.
- Produce a short handoff pointing to the current plan and assignment. The user can relay it to another permitted session. Do not assume separate sessions automatically share conversation context or remain synchronized after a plan changes.
- Workers return changed files, actual checks/results, blockers and proposed interface changes. The coordinator verifies and integrates them. A worker report is evidence to inspect, not proof that the whole project is complete.

## Record at consequential moments

Update the existing decision owner after a meaningful choice, discovery, failed approach, changed assumption or important integration result, before unrelated work. Routine commands do not need individual entries.

Keep a brief summary at the top: the few key decisions and reasons, strongest verified results and material remaining limits. Place a Markdown horizontal rule below it, then retain the supporting detail grouped by decision/topic.

For each material entry, preserve only useful facts:

- Decision or change, its context and reason; important alternatives if actually considered.
- Source of the condition: requirement, user/stakeholder confirmation, observation or assumption.
- Actual action and evidence: relevant files, checks, observations and evaluation context.
- Human decisions/reviews versus AI proposals/implementation; do not infer human approval, motives or authorship from the existence of code.
- Status and limits: proposed, implemented, checked or unresolved as the evidence supports. Do not describe an intended test as a passed test.

Do not fabricate a retrospective to fill a form. Use actual work to update required collaboration answers while preserving the original questions. Link existing evidence instead of copying sensitive originals, long logs or transcripts.

## Verify and hand back

Read back changed documents, check relevant references, preserve concurrent edits and report what was actually updated and checked. Ask only about unresolved matters that affect the current output or next action. Keep examples, placeholders and temporary stand-ins distinguishable from working functionality.

Applying this skill does not authorize publication, external data transfer, account/configuration changes, tool installation or bypassing any host/project restriction. It has no background service; future updates occur only while an authorized agent is actively working.
