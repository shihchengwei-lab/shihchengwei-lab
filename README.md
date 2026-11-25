# shihchengwei-lab

I make games with coding agents.

I’m a vibe coder. AI does the programming. I set the goals, question its choices, and ask for evidence that the result does what I asked.

In open source, I share findings and questions from AI-assisted pull request reviews.

## Skills

- Proficient in prompt engineering

## Achievements (With AI)

- Found a case where a database put two rows in the wrong order. [Apache DataFusion #27597](https://github.com/apache/datafusion/pull/27597#issuecomment-7049002958)
- Found a save that went through but was reported as failed after a retry. [Apache Iceberg Go #2679](https://github.com/apache/iceberg-go/pull/2679#issuecomment-7136908103)
- Found a query that ran directly but wouldn’t start from a saved plan. [Apache Flink #30080](https://github.com/apache/flink/pull/30080#issuecomment-7151901415)
- Found an error message that pointed to the wrong line. [Apache Spark #60724](https://github.com/apache/spark/pull/60724#issuecomment-7112147391)
- Spotted how writing `.123000` as `.123` could make a search miss a match. [ClickHouse #133245](https://github.com/ClickHouse/ClickHouse/pull/133245#issuecomment-7063928589)

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
