# Codex Skills Hub

<p align="center">
  <img src="assets/hub-icon.svg" alt="Codex Skills Hub icon" width="140" />
</p>

<p align="center">
  A curated landing page for high-value Codex skills focused on agent architecture, team orchestration, and developer workflows.
</p>

## Featured Skills

### 1. Harness Creator

Design safe, layered, production-ready agent harnesses.

- Repository: [harness-creator](https://github.com/Arthurescc/harness-creator)
- Best for: coding agents, CLI runtimes, tool orchestration, MCP-enabled assistants, planning/subagent systems
- Core value: turns fuzzy "build an agent" requests into concrete architecture, implementation order, and safety rules

### 2. Agent Teams Creator

Analyze and design protocol-driven agent team runtimes.

- Repository: [agent-teams-creator](https://github.com/Arthurescc/agent-teams-creator)
- Best for: coordinator/worker runtimes, task-board-driven multi-agent systems, mailbox protocols, verifier flows
- Core value: makes task board, mailbox, coordinator, and isolation boundaries explicit instead of collapsing them into vague swarm language

### 3. Stitch UI Bridge

Bridge frontend design prompts from Codex, Claude Code, or Cursor into Stitch and get raw export code back.

- Repository: [stitch-ui-bridge](https://github.com/Arthurescc/stitch-ui-bridge)
- Best for: UI prototyping, frontend design generation, Stitch browser automation, raw export handoff, privacy-safe local bridge workflows
- Core value: turns a logged-in Stitch browser session into a structured local design backend with stage-aware waiting and optional `Thinking with 3.1 Pro`

## Why This Hub Exists

These skills are not generic prompt snippets. They are reusable, tested skill packages designed to improve how Codex structures analysis and design work.

They were independently designed and developed, then refined through practical testing to improve:

- output quality
- architecture clarity
- implementation readiness
- facts-vs-inference discipline
- safety and verification depth
- frontend design iteration speed

## Quick Install

### Harness Creator

```bash
git clone https://github.com/Arthurescc/harness-creator \
  "${HOME}/.codex/skills/harness-creator"
```

### Agent Teams Creator

```bash
git clone https://github.com/Arthurescc/agent-teams-creator \
  "${HOME}/.codex/skills/agent-teams-creator"
```

### Stitch UI Bridge

```bash
git clone https://github.com/Arthurescc/stitch-ui-bridge \
  "${HOME}/.codex/skills/stitch-ui-bridge"
```

On Windows, replace `${HOME}` with `%USERPROFILE%`.

Restart Codex after installation so the skill list refreshes.

## Landing Page

Open [index.html](index.html) locally, or use the GitHub Pages site for a lightweight skill showcase.

## Chinese Documentation

See [README.zh-CN.md](README.zh-CN.md).

## License

MIT
