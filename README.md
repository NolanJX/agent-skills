# agent-skills

## Skills

### conventional-commits-draft

Draft a Conventional Commits message from the staged diff. Adapted from [awesome-copilot's git-commit skill](https://github.com/github/awesome-copilot/blob/main/skills/git-commit/SKILL.md).

Install with the [Skills CLI](https://github.com/vercel-labs/skills):

> User-invoked (never invoked by the model), so global installation is recommended.

```bash
npx skills add https://github.com/NolanJX/agent-skills --skill conventional-commits-draft
pnpx skills add https://github.com/NolanJX/agent-skills --skill conventional-commits-draft  # if using pnpm
```

> **Self-contained versions.** Matt Pocock's `grill-me` and `grill-with-docs` are thin wrappers that delegate to the `grilling` (and, for `grill-with-docs`, `domain-modeling`) skills — installing either via the Skills CLI means installing those dependencies separately too. The versions below inline that content directly, so each installs standalone with no extra skills required.

### grill-me

A self-contained version of [Matt Pocock's `grill-me`](https://github.com/mattpocock/skills).

Install with the [Skills CLI](https://github.com/vercel-labs/skills):

> User-invoked (never invoked by the model), so global installation is recommended.

```bash
npx skills add https://github.com/NolanJX/agent-skills --skill grill-me
pnpx skills add https://github.com/NolanJX/agent-skills --skill grill-me  # if using pnpm
```

### grill-with-docs

A self-contained version of [Matt Pocock's `grill-with-docs`](https://github.com/mattpocock/skills).

Install with the [Skills CLI](https://github.com/vercel-labs/skills):

> User-invoked (never invoked by the model), so global installation is recommended.

```bash
npx skills add https://github.com/NolanJX/agent-skills --skill grill-with-docs
pnpx skills add https://github.com/NolanJX/agent-skills --skill grill-with-docs  # if using pnpm
```
