# Manager Mode — a Claude Code plugin

A skill that makes Claude work the way a busy, non-technical person wants to be
worked for. Instead of burying you in technical detail, Claude hands the real
work to a background worker, checks on it, and reports back in short
manager-style summaries: **what's happening, what's done, and what it needs from
you** — with no jargon. It also explains how things work in plain English as it
goes, and if anything breaks it stops and walks you through a fix.

## What you get

Type `/manager-mode` (or just say things like *"keep it simple, I'm not
technical"*) and Claude switches into this calm, summarize-everything style for
the rest of your task.

## Install

In Claude Code, add this repository as a plugin marketplace, then install the
plugin:

```
/plugin marketplace add Kyarha/claude-manager-mode
/plugin install manager-mode@claude-manager-mode
```

Once installed, it's available across all your projects.

## What's inside

```
claude-manager-mode/
├── .claude-plugin/
│   ├── plugin.json         # plugin manifest
│   └── marketplace.json    # lets Claude Code install it
└── skills/
    └── manager-mode/
        └── SKILL.md         # the skill itself
```

## License

MIT
