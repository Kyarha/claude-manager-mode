<div align="center">

# 🧑‍💼 Manager Mode

### A Claude Code plugin for people who want results, not jargon.

*Hand off the work. Get clear updates. Make the calls that matter.*

![Type](https://img.shields.io/badge/type-Claude%20Code%20plugin-5A4FCF)
![Skill](https://img.shields.io/badge/skill-manager--mode-22A06B)
![License](https://img.shields.io/badge/license-MIT-blue)
![Jargon](https://img.shields.io/badge/jargon-0%25-ff5c5c)

</div>

---

## What is this?

**Manager Mode** changes *how Claude talks to you* — not what it can do.

By default, Claude tends to show its work: files, commands, technical detail. If
you're not a developer (or simply don't want the noise), that's a wall of stuff
between you and the answer.

This plugin flips it around. Claude starts treating you like a manager treats a
trusted team: it takes the job, does the heavy lifting quietly in the background,
and reports back in short, plain-English updates —

> **Here's what I'm doing. Here's what's done. Here's the one thing I need from you.**

No file names. No error codes. No command-line anything. Just the signal.

---

## What it does for you

| | |
|---|---|
| 🎯 **Plays back your task** | Repeats what you asked in one plain sentence, so you know it understood. |
| 🤝 **Does the work out of sight** | Hands the real work to a background worker — you're not watching technical output scroll by. |
| 📣 **Reports up, briefly** | Short updates: what's happening, what's done, what (if anything) it needs from you. |
| 🎓 **Teaches you gently** | Explains how the thing works in plain English as it goes — learn while staying hands-off. |
| 🛟 **Guides you through problems** | If something breaks, it stops, explains it in plain terms, and walks you through the fix. |

---

## See the difference

**Without Manager Mode:**
> Running `npm install`… `ERR! ENOENT: missing dependency 'sharp'`. The build
> failed during the asset pipeline step because the native module didn't compile
> against your Node version…

**With Manager Mode:**
> It tried to start, but one of the pieces it relies on isn't installed yet. I can
> install it for you in a moment — just need your go-ahead. 👍

---

## How to use it

Once installed, simply type:

```
/manager-mode
```

…and Claude switches into this calm, summarize-everything style for the rest of
your task. You can also just *say* what you want — phrases like **"keep it
simple,"** **"I'm not technical,"** or **"just tell me what you're doing"** turn
it on automatically.

---

## Install

In Claude Code, run these two lines:

```
/plugin marketplace add Kyarha/claude-manager-mode
/plugin install manager-mode@claude-manager-mode
```

That's it — it's now available across **all** your projects on this machine.

> 💡 **Prefer not to install a plugin?** You can also just drop the
> [`skills/manager-mode/`](skills/manager-mode/) folder into `~/.claude/skills/`
> and it'll work everywhere too. The plugin route is simply the tidy,
> install-once way to do the same thing.

---

## What's inside

```
claude-manager-mode/
├── .claude-plugin/
│   ├── plugin.json          # tells Claude Code what this plugin is
│   └── marketplace.json     # lets Claude Code find and install it
├── skills/
│   └── manager-mode/
│       └── SKILL.md          # the skill itself — the actual instructions
└── README.md                 # you are here
```

The whole thing is just a few small text files. The "brain" of it is
[`SKILL.md`](skills/manager-mode/SKILL.md) — readable in plain English if you're
ever curious what it tells Claude to do.

---

## License

[MIT](LICENSE) — free to use, share, and adapt.

<div align="center">
<sub>Made for people who'd rather manage the work than wade through it.</sub>
</div>
