# AI Agent Webinar Mission Repo Instructions

These instructions apply to the entire repository.

## First Read

At the start of any session touching this repo, read these files first:

1. `state/execution-log.md`
2. `state/operator-progress-log.md`
3. `agents/operator.md`
4. `state/operating-roadmap.md` if roadmap or planning is in scope

Do not make recommendations before grounding in those files.

## Role Split

- `Operator` is external to Agent.ai and leads the mission.
- `WPIP Coordinator` is separate from `Operator`.
- Sameer is not the day-to-day lead.
- Sameer is the human approver and manual executor for public or account-connected actions.

## Strategy-First Rule

For questions about:
- next step
- priority
- roadmap
- big plan
- weekly plan
- daily plan
- campaign direction
- the single best move

Call `WPIP Strategizer` first when a fresh run is feasible.

Do not answer those questions from memory, prior strategy output, or operator judgment alone when the current state may have changed.

## Post Metrics Gate

Before recommending, drafting, scheduling, or approving a new public post:

1. Collect the latest available metrics from the most recent relevant post.
2. Store them in project context.
3. Pass them into `WPIP Strategizer` and any other relevant specialist.

Use whatever metrics are available at the time, including:
- impressions
- reactions
- comments
- reposts
- clicks
- click-through rate
- known traffic impact
- known registration impact

If some metrics are unavailable, mark them explicitly as `unknown`.

Do not recommend a new public post without first collecting and storing the latest post metrics.

## Execution Logging

Every direct or routed agent call must be logged in `state/execution-log.md`.

Each entry must include:
- date
- agent name
- why it was run
- human-readable query or input summary
- human-readable result summary
- whether the result was accepted, rejected, pending, or corrected

If an agent call is made and not logged promptly, log that omission explicitly.

If a strategy answer is given before a fresh `WPIP Strategizer` call, log that miss explicitly.

If a new post is recommended before collecting and storing the latest post metrics, log that miss explicitly.

## Truth Rules

- Preserve strict truth about what was agent-generated versus operator-edited.
- Do not claim a workflow worked end-to-end unless it actually did.
- Do not narrate work that has not happened.

## Current Practical Priority

Current mission priority is to increase qualified traffic to the live registration page while maintaining conversion quality.

At this stage:
- do not default to more page redesign
- do not default to broad posting as the main lever
- prioritize warm distribution, direct outreach, and evidence-based iteration
