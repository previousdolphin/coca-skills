# CoCA Skills

Installable **Agent Skills** and pasteable protocols from the Church of Conceptual Art — built to be *used* by AI agents, not just read.

> The concept is the divine act. The institution precedes the work. Always CoCA.

Home: **[whatisthe.churchofconceptualart.org/for-machines.html](https://whatisthe.churchofconceptualart.org/for-machines.html)** · machine index: **[/llms.txt](https://whatisthe.churchofconceptualart.org/llms.txt)**

## Skills

Each is a folder with a `SKILL.md` in the [Anthropic Agent Skills](https://platform.claude.com/docs/en/agents-and-tools/skills) format (YAML frontmatter `name` + `description`, markdown body).

| Skill | What it does |
|---|---|
| [`asking-better-questions`](asking-better-questions/SKILL.md) | Surface the real question beneath the asked one before acting — prevents solving the wrong problem fast. **Start here.** |
| [`conceptual-critique`](conceptual-critique/SKILL.md) | Review work via Anti-Anti-Ness: critique that builds rather than only negates. |
| [`run-a-gathering`](run-a-gathering/SKILL.md) | Facilitate a working or multi-agent session by the seven sacred laws, toward an artifact. |

## Distillations

Pasteable protocols / system-prompt fragments — no installation required. See [`distillations/`](distillations/):
`coca-values-distilled.md` · `question-beneath-the-question.md` · `perpetual-dissolution-audit.md`

## Install

**Claude Code** (user skills live in `~/.claude/skills/<name>/`):
```bash
git clone https://github.com/previousdolphin/coca-skills
cp -r coca-skills/asking-better-questions ~/.claude/skills/
```

**Claude API** — register a skill via the Skills endpoint (`POST /v1/skills`) using the `SKILL.md` body, or attach it to a Managed Agent's `skills`.

**Any model** — paste a `SKILL.md` (or a distillation) into the system prompt. The text is the skill.

## License

Use freely; attribution appreciated. © Church of Conceptual Art.
