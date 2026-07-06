# shihchengwei-lab

I use coding agents to build small tools for coding agents.

That sounds circular because it is. The useful part is the constraint: agent
output should not be merged because it looks plausible or because CI is green.
It needs a narrow work boundary, a record of what changed, and a handoff a
human can own.

This account is where I test that workflow. Some repos are usable tools, some
are prototypes, and some are notes from poking at agent behavior. The shared
question is simple: can agent-produced work become easier to inspect, resume,
and review?

## Start Here

| Repo | What It Is For |
|---|---|
| [`coding-agent-guardrails`](https://github.com/shihchengwei-lab/coding-agent-guardrails) | Umbrella toolkit for constraining, recording, and handing off agent work. |
| [`slime-coding`](https://github.com/shihchengwei-lab/slime-coding) | Declares a small edit corridor before the agent touches files. |
| [`agentcam`](https://github.com/shihchengwei-lab/agentcam) | Records an agent run: changed files, risk flags, logs, and verification evidence. |
| [`corridor-ci`](https://github.com/shihchengwei-lab/corridor-ci) | Checks that a PR says why it exists, what it touched, what ran, and where review should start. |
| [`kiss-my-diff`](https://github.com/shihchengwei-lab/kiss-my-diff) | A small KISS rule file for pushing agents toward smaller diffs. |

## Working Pattern

1. Draw the corridor before editing.
2. Let the agent work inside it.
3. Record what actually changed.
4. Make the handoff visible.
5. Keep responsibility with the person who chooses to merge.

## Current Focus

`coding-agent-guardrails` is the current front door. It pulls together the
pieces that matter most to me right now: smaller agent edits, observable runs,
compact PR handoffs, and CI checks that ask for evidence instead of trust.

I am less interested in replacing human review than in making agent-produced
work less slippery. A reviewer still has to decide. The tools should make that
decision better grounded.

## Notes

Most projects here are side projects and experiments. Expect rough edges, quick
iteration, and working names. The durable theme is AI-agent workflow design:
boundaries, records, and human-owned handoffs.
