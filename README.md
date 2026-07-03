# shihchengwei-lab

Small tools for making AI coding agents easier to constrain, inspect, and review.

I focus on one problem: AI agents can produce useful code, but their work is often hard to bound, audit, or hand off. These projects turn that friction into small gates, recorders, and review aids.

## Start here

| Repo | What it is for |
|---|---|
| [`slime-coding`](https://github.com/shihchengwei-lab/slime-coding) | Keep an agent inside the smallest necessary edit corridor. |
| [`kiss-my-diff`](https://github.com/shihchengwei-lab/kiss-my-diff) | Give coding agents a tiny KISS rule file for smaller, simpler diffs. |
| [`agentcam`](https://github.com/shihchengwei-lab/agentcam) | Record AI coding runs: changed files, risk flags, and rollback notes. |
| [`cold-eyes-reviewer`](https://github.com/shihchengwei-lab/cold-eyes-reviewer) | Run a second-pass review gate for Claude Code diffs. |
| [`corridor-ci`](https://github.com/shihchengwei-lab/corridor-ci) | Make PRs say why they exist, where they meant to stop, and where review should start. |

## The pattern

Constrain before editing.  
Record what changed.  
Review against evidence.  
Keep the human in control.

## Notes

Some repositories are tools. Some are prototypes or research notes. The main thread is AI-agent workflow design: small boundaries, visible handoff, and less cleanup work for humans.
