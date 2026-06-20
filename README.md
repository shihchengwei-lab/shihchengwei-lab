# shihchengwei-lab

Side projects for making AI coding agents easier to inspect, resume, and control.

These repos come from real Claude Code / AI-agent workflows: session handoff, context loss, second-opinion review, agent run recording, companion transparency, and authority separation.

## Main map

### Agent session control
- `claude-code-session-kit` — hooks for context alerts, session startup, and handoff validation.
- `coding-guidelines` — UserPromptSubmit hook that injects minimal coding rules every turn.
- `slime-coding` — slime-mould discipline that edits only the minimal corridor where the requirement and the repo meet, enforced via Claude Code hooks.

### Audit and review
- `cold-eyes-reviewer` — diff-centered second-pass review gate for Claude Code.
- `agentcam` — local-first flight recorder for AI coding-agent runs.

### Companion / transparency work
- `cinder-capture` — captures Claude Code Cinder bubble text and reinjects it into context.
- `Buddy_similar` — rebuilds a Buddy-like second-opinion companion with explicit data-flow disclosure.
- `HITCON_2026_talk_raw` — raw materials for the Buddy / Cinder transparency forensics talk.

### Architecture / research prototypes
- `separation-and-audit-alignment` — theory notes on pipeline-level authority separation.
- `separation-and-audit-claude-code` — Claude Code reference implementation.
- `fourth-path-local-lab` — local prototype and benchmark route-validation lab.

### Adjacent tools
- `workslop-checker` — checks whether AI-written documents are ready to hand off.
- `generate-high-quality-art-image2` — prompt contract for Image 2.0 generation.
