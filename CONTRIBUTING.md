# Contributing to embedded-systems

This skill was forked from [`Jeffallan/claude-skills`](https://github.com/Jeffallan/claude-skills) (path: `skills/embedded-systems`).

## Contribution guidelines

- See the [org-wide contributing guide](https://github.com/mm-skills/.github/blob/main/CONTRIBUTING.md) for general guidelines.
- If your fix applies to the **original upstream repo**, please consider contributing there too.
- Use `sync.sh` to check for and merge upstream changes into this fork.

## Upstream sync

```bash
# Check for upstream changes
.agents/skills/skill-manager/scripts/sync.sh '{"name": "embedded-systems", "action": "check"}'

# Merge upstream changes
.agents/skills/skill-manager/scripts/sync.sh '{"name": "embedded-systems", "action": "merge"}'
```
