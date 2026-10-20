# Consumer Review Analysis Skill

This repository contains the reusable Codex skill for the consumer-review collection lab. The collector and analyzer implementation lives in the companion repository: [222438/consumer-review-collector](https://github.com/222438/consumer-review-collector).

## Contents

- `SKILL.md`: when and how Codex should collect and analyze consumer reviews
- `agents/openai.yaml`: UI display name and invocation prompt
- `references/schema.md`: canonical CSV fields and metric definitions
- `references/github-sources.md`: inspected public GitHub references and pinned commits
- `references/companion-tool.md`: setup and relationship to the separate CLI repository

## Install locally

Copy this repository's contents into `$CODEX_HOME/skills/consumer-review-collector` (or `~/.codex/skills/consumer-review-collector`) and clone the companion tool repository for collection commands. The installed skill itself contains guidance; the companion repository contains the executable Python scripts.

Validate this skill with the Codex skill creator validator:

```powershell
python C:\Users\<user>\.codex\skills\.system\skill-creator\scripts\quick_validate.py .
```
