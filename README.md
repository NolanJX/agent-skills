# agent-skills

Skills for the artisanal programmer. AI for speed, craft for control.

Artisanal as in handcrafted, not as in Luddite. The point of this repo is to let AI accelerate everything it can. The non-negotiable: your hands stay on the wheel. To that end, every skill here plays by the same three rules:

- **Readable.** Plain Markdown only.
- **Self-contained.** No hidden dependencies.
- **User-invoked.** `disable-model-invocation: true` — it runs when you ask, never when the model decides.

## Skills

All skills are user-invoked (never invoked by the model), so global installation via the [Skills CLI](https://github.com/vercel-labs/skills) is recommended:

```bash
npx skills add https://github.com/NolanJX/agent-skills --skill <skill-name>
pnpx skills add https://github.com/NolanJX/agent-skills --skill <skill-name>  # if using pnpm
```

> **Self-contained versions.** Some upstream skills are thin wrappers that delegate to other skills — installing one via the Skills CLI means installing its dependencies separately too. When a skill below is described as a *self-contained version*, it inlines the delegated content directly, so it installs standalone with no extra skills required. For example, Matt Pocock's `grill-me` and `grill-with-docs` delegate to `grilling` (and, for `grill-with-docs`, `domain-modeling`); the versions in this repo inline those skills' content.

### conventional-commits-draft

Draft a Conventional Commits message from the staged diff. Adapted from [awesome-copilot's git-commit skill](https://github.com/github/awesome-copilot/blob/main/skills/git-commit/SKILL.md).

```bash
npx skills add https://github.com/NolanJX/agent-skills --skill conventional-commits-draft
pnpx skills add https://github.com/NolanJX/agent-skills --skill conventional-commits-draft  # if using pnpm
```

### grill-me

A self-contained version of [Matt Pocock's `grill-me`](https://github.com/mattpocock/skills).

```bash
npx skills add https://github.com/NolanJX/agent-skills --skill grill-me
pnpx skills add https://github.com/NolanJX/agent-skills --skill grill-me  # if using pnpm
```

### grill-with-docs

A self-contained version of [Matt Pocock's `grill-with-docs`](https://github.com/mattpocock/skills).

```bash
npx skills add https://github.com/NolanJX/agent-skills --skill grill-with-docs
pnpx skills add https://github.com/NolanJX/agent-skills --skill grill-with-docs  # if using pnpm
```
