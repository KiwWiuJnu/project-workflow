# Project Workflow

A small, dependency-free skill for keeping project direction and decision notes useful while working with a coding agent.

## Scope

- Read the project's README and requirements before organizing work.
- Reuse existing rules, plans and record owners; preserve required collaboration forms when present.
- Separate operating guidance, the current work plan and evidence-based decision notes.
- Keep a short decision summary above a horizontal rule, with supporting detail below.
- Prepare bounded parallel assignments when requested, with explicit interfaces and file ownership.
- Distinguish human decisions/reviews from AI suggestions and implementation.

The package contains only this README and [SKILL.md](SKILL.md). It supplies instructions, not an MCP server, executable daemon or application implementation. It assumes no domain, framework, deployment method, time limit or fixed questionnaire.

## Use

After cloning this repository into `project-workflow/`, ask your coding agent:

> Read `project-workflow/SKILL.md` and apply it to the current project. Start with its README and requirements, reuse existing documents, and prepare the work plan, decision record and necessary questions before implementation.

Keep generated documents in the actual project's directory, not in the cloned skill package. For an existing project, specify the narrower action you need, such as updating the current plan or recording a decision.

The agent can read the file directly. Automatic skill discovery is optional and follows the supported installation process of the agent you use; this repository does not change agent configuration or install itself.

## Documents

When there are no suitable existing owners, small projects can use:

| File | Responsibility |
|---|---|
| `AGENTS.md` | Short operating guidance and document map |
| `WORK_PLAN.md` | Requirements, interfaces, assignments, acceptance checks and current status |
| `DECISIONS.md` | Summary, reasons, actual verification, contribution boundaries and limits |

These names are defaults. Existing plans, Issues, ADRs, record indexes and user-selected names take precedence. A supplied collaboration form retains its actual questions and format.

## Permissions and boundaries

Use the package only within the rules of the host environment and project. Reading it does not authorize sending data, publishing a repository, changing access controls or installing tools. Parallel work is optional and requires the applicable authorization and supported tools.

There are no dependencies, runtime services, bundled project data or external network calls in this package.
