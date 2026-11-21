# shihchengwei-lab

I make games with coding agents.

I’m a vibe coder. AI does the programming. I set the goals, question its choices, and ask for evidence that the result does what I asked.

In open source, I share findings and questions from AI-assisted pull request reviews.

## Skills

- Proficient in prompt engineering

## Achievements (With AI)

- Helped keep one new message scheduled while old ones were cleared. [Apache Pulsar #27666](https://github.com/apache/pulsar/pull/27666#issuecomment-7028249450)
- Flagged how two events could share a number if the clock went back after a restore. [Apache Flink #30022](https://github.com/apache/flink/pull/30022#issuecomment-7037952294)
- Helped a database return the right rows (5–9) after a column was recreated. [ClickHouse #133120](https://github.com/ClickHouse/ClickHouse/pull/133120#issuecomment-7056154288)

## Start Here

| Repo | What It Is For |
|---|---|
| [Masters’ Nudge](https://github.com/shihchengwei-lab/masters-nudge) | Short structural feedback while a coding agent works, with published comparisons of results and costs. |
| [project-6s](https://github.com/shihchengwei-lab/project-6s) | A Codex skill for cleaning up outdated docs, duplicate artifacts, and stale tests. |

## Current Shape

Games are where this started. The tools grew out of problems I kept running
into while working with coding agents.

Sometimes I end up building a tool for the agent that was supposed to be
building the game.

The thing can exist and still need to be smaller, clearer, and better.

## How I Work

I draw on basic ideas from industrial safety: designing hazards out,
interlocks, and pointing and calling. They shape the questions I ask
when working with coding agents.

The questions I keep coming back to:

1. Do we need this?
2. Can we change the design so this special case is no longer needed?
3. Is this bearing weight, or is it just packaging?
