# cs-genesis

A Claude Code plugin marketplace with two plugins for starting a project properly.

| Plugin | What it does |
| --- | --- |
| `genesis-the-protocol` | Interviews you about a project idea, then produces a system design, tech stack, low-level design and architecture files. |
| `genesis-the-architect` | Installs branching, folder-structure and coding standards into a repo and registers them in `CLAUDE.md`. |

## Install

Add the marketplace once, then install what you need:

```
/plugin marketplace add ChetanS07/cs-genesis
/plugin install genesis-the-protocol@cs-genesis
/plugin install genesis-the-architect@cs-genesis
```

## Use

```
/genesis-the-protocol:genesis-the-protocol
/genesis-the-architect:genesis-the-architect
```

Each plugin lives in its own repository and is versioned separately. This repository only holds the catalog.
