# 25-hvac-design-ashrae — Codex Agent

A specialist subagent from the **57 Agents for US Engineers** bundle (HL).

## What this agent does

See `25-hvac-design-ashrae.md` for the full description, frameworks, reference tables, and operating flow.

## Installation

### Prerequisites

- [Codex](https://docs.Codex.com/Codex-code) installed and logged in
- A terminal with `unzip`

### Install in 30 seconds

**1. Unzip this archive:**

```bash
unzip 25-hvac-design-ashrae.zip
```

**2. Copy the agent into your Codex project:**

```bash
mkdir -p .codex/agents
cp 25-hvac-design-ashrae.md .codex/agents/

# OR install globally for all projects:
mkdir -p .codex/agents/
cp 25-hvac-design-ashrae.md .codex/agents/
```

**3. Restart Codex** (or run `/agents` to refresh).

**4. Invoke the agent.** Just describe your task — Codex will pick this subagent automatically when relevant, or call it explicitly:

```
Use the hvac-design-ashrae subagent to ...
```

## Verifying installation

```bash
ls .codex/agents/   # should list 25-hvac-design-ashrae.md
# OR
ls .codex/agents/ # for global install
```

In Codex, run `/agents` to see the agent listed.

## Updating

When a new version is released, re-run the unzip + copy steps above. The new file overwrites the old one.

## Uninstall

```bash
rm .codex/agents/25-hvac-design-ashrae.md
# OR
rm .codex/agents/25-hvac-design-ashrae.md
```

## Support

- Documentation: [Codex docs — Subagents](https://docs.Codex.com/Codex-code)
- Issues / questions: open an issue at the repo where you bought this bundle.

---

© HL — 57 Agents for US Engineers
