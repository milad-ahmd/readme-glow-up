<div align="center">

# ✨ readme-glow-up

**An Agent Skill that turns a boring README into one people want to star, using only facts from your repo.**

[![License: MIT](https://img.shields.io/github/license/milad-ahmd/readme-glow-up)](LICENSE)
[![Stars](https://img.shields.io/github/stars/milad-ahmd/readme-glow-up?style=social)](https://github.com/milad-ahmd/readme-glow-up)
![Works with](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Cline%20%7C%20Cursor%20%7C%20Codex-8A2BE2)

[Install](#-install) · [What it does](#-what-it-does) · [Example](#-example) · [Other skills](#-more-skills)

</div>

## 😩 The problem

Most repos lose visitors in the first 10 seconds: no tagline, no quickstart, no demo, no badges. Great code goes unnoticed.

## 🎯 What it does

- 🔍 **Reads your repo first**: it detects the stack, real install/test commands, license and git remote.
- 🚫 **Never invents facts**: unknowns become `<!-- TODO -->` comments instead of made-up claims.
- 🏷️ **Adds only real badges**: license, release, CI, npm/PyPI, built from your actual remote.
- 🚀 **Copy-paste quickstart** that runs in under 60 seconds.
- 🧭 **A proven structure**: hero, why, quickstart, features, usage, config, contributing, license.
- ♻️ **Keeps what matters**: sponsors, citations and acknowledgements stay in.

## 📦 Install

**Claude Code** (personal skills):

```bash
git clone https://github.com/milad-ahmd/readme-glow-up /tmp/readme-glow-up
mkdir -p ~/.claude/skills && cp -r /tmp/readme-glow-up/skills/readme-glow-up ~/.claude/skills/
```

**Per project** (Claude Code / Cline / any tool that reads `SKILL.md`): copy `skills/readme-glow-up` into your project's `.claude/skills/` folder.

**Any other agent**: paste the contents of [`SKILL.md`](skills/readme-glow-up/SKILL.md) into your rules or system prompt.

## 💬 Example

Open your agent in any repo and say:

```text
Glow up the README of this repo
```

You get a rewritten `README.md` plus a list of TODOs (for example "record a demo GIF to docs/demo.gif").

## 🧩 More skills

🧰 **[See all 17 skills and the one-line installer → milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills)**

- 🔎 [pr-reviewer-pro](https://github.com/milad-ahmd/pr-reviewer-pro): senior-engineer-level PR reviews
- 📚 [awesome-agent-skills](https://github.com/milad-ahmd/awesome-agent-skills): a curated list of Agent Skills

## 🤝 Contributing

Issues and PRs are welcome, especially before/after examples from your own repos.

## 📄 License

[MIT](LICENSE) © Milad Ahmadi

<div align="center">

**If this made your README shine, a ⭐ helps others find it.**

</div>
