# 🧠 Second Brain — Claude Code + Obsidian

A "second brain" vault template where **you capture and decide**, and **Claude organizes, connects and challenges**.
Notes are plain Markdown: you read and edit them in [Obsidian], and [Claude Code] reads and writes them from the terminal, guided by a `CLAUDE.md` file and four custom slash commands.

> 🇧🇷 **Resumo:** template de "segundo cérebro" para Obsidian + Claude Code. Você captura e decide; o Claude organiza, conecta e questiona. Quatro comandos (`/hoje`, `/despejo`, `/decidir`, `/semana`) cuidam da nota do dia, da organização do Inbox, das decisões guiadas e da revisão semanal. O conteúdo do vault (comandos, templates e regras) está em português.

## How it works

| Command | When | What it does |
| --- | --- | --- |
| `/hoje` (*today*) | Every morning | Creates the daily note with priorities, yesterday's open tasks and pending decisions |
| `/despejo <text>` (*brain dump*) | Whenever something is on your mind | Splits loose text into tasks, ideas, people and decisions, and files each one in the right place |
| `/decidir <decision>` (*decide*) | Before a decision that matters | Interviews you, searches the vault for related history, argues against your preferred option and records the decision |
| `/semana` (*week*) | Friday or Sunday | Weekly review: patterns, what got stuck, decisions due for review and next week's focus |

The core of the system is `/decidir`: it never decides for you, but it makes you look at every option, at what happened in similar past decisions, and at the strongest case against the option you're leaning toward. Each decision gets a review date, so you can later check whether what you expected actually happened.

## Structure

```
├── CLAUDE.md             # Claude's instructions: who you are, rules, where things go
├── 00-Comece-aqui.md     # Quick start guide and routine
├── .claude/commands/     # /hoje, /despejo, /decidir, /semana
├── .obsidian/            # Vault settings + "neural network" graph theme
├── 00-Inbox/             # Raw input
├── 01-Diario/            # One note per day
├── 02-Areas/             # Ongoing areas of life and work
├── 03-Projetos/          # Things with a goal and an end
├── 04-Decisoes/          # One note per decision
├── 05-Pessoas/           # One note per person
├── 06-Conhecimento/      # Learnings and references
├── 07-Revisoes/          # Weekly and monthly reviews
├── 99-Templates/         # Note templates
└── 99-Arquivo/           # Nothing is deleted: it's archived here
```

## Getting started

1. Clone or download this repository and open the folder as a vault in Obsidian.
2. Fill in the **Quem sou** (*who I am*) section of `CLAUDE.md`, or ask Claude: *"interview me to complete the Quem sou section of CLAUDE.md"*.
3. Open a terminal in the folder and run `claude`.
4. Start with just `/hoje` and `/despejo` in the first week.

**Requirements:** [Obsidian] and [Claude Code].

## Privacy

This repository contains only the **system** (structure, rules, commands and templates). If you use it as a base, don't commit your own notes: keep your personal vault out of Git or in a private repository.

[Obsidian]: https://obsidian.md
[Claude Code]: https://claude.com/claude-code
