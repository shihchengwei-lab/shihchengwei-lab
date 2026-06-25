# shihchengwei-lab

Side projects for making AI coding agents easier to inspect, resume, and control.

These repos come from real Claude Code / AI-agent workflows: session handoff, context loss, second-opinion review, agent run recording, companion transparency, and authority separation.

## Main map

### Agent session control
- `kiss-my-diff` — Keep It Simple, Stupid for coding-agent diffs: smaller patches, fewer touched files.
- `slime-coding` — slime-mould-inspired system simulation for editing only the minimal corridor where the requirement and the repo meet.
- `coding-guidelines` — Andrej Karpathy-inspired empirical-science loop for injecting minimal coding rules every turn.
- `claude-code-session-kit` — hooks for context alerts, session startup, and handoff validation.
- `sporepath` — turns AI chat history into a local memory graph with active focus paths and dormant latent paths.

### Audit and review
- `cold-eyes-reviewer` — diff-centered second-pass review gate for Claude Code.
- `agentcam` — local-first flight recorder for AI coding-agent runs.

### Companion / transparency work
- `cinder-capture` — captures Claude Code Cinder bubble text and reinjects it into context. _(archived)_
- `Buddy_similar` — rebuilds a Buddy-like second-opinion companion with explicit data-flow disclosure.
- `claude-code-buddy-transparency-case` — evidence record of a non-auditable server-side actor in Claude Code's Buddy feature.

### Architecture / research prototypes
- `separation-and-audit-alignment` — theory notes on pipeline-level authority separation.
- `separation-and-audit-claude-code` — Claude Code reference implementation.
- `fourth-path-local-lab` — local prototype and benchmark route-validation lab. _(archived)_

### Adjacent tools
- `workslop-checker` — checks whether AI-written documents are ready to hand off.
- `generate-high-quality-art-image2` — prompt contract for Image 2.0 generation.
