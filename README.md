# ediiiz/skills

A curated [scilla](https://github.com/ediiiz/scilla) Collection of agent skills for Svelte, shadcn-svelte, and Matt Pocock's engineering & productivity workflows.

## Install

Install into the current project:

```sh
bunx scilla-cli add ediiiz/skills
```

Or install globally (for every project):

```sh
bunx scilla-cli add ediiiz/skills -g
```

Non-interactive install (recommended skills):

```sh
bunx scilla-cli add ediiiz/skills -y
```

Keep installed skills up to date:

```sh
bunx scilla-cli update ediiiz-skills
```

## Included Sources

All references float to the latest upstream commits on their default branch:

- **Matt Pocock Skills** ([`mattpocock/skills`](https://github.com/mattpocock/skills))
  - `mattpocock/skills/skills/engineering` — engineering workflows (grilling, specs, tickets, TDD, code review, domain modeling, etc.)
  - `mattpocock/skills/skills/productivity` — productivity & agent workflows (`grill-me`, `handoff`, `writing-for-agents`, etc.)
- **Svelte Official Skills** ([`sveltejs/ai-tools`](https://github.com/sveltejs/ai-tools))
  - `sveltejs/ai-tools/tools/skills` — `svelte-code-writer`, `svelte-core-bestpractices`, `svelte-mcp-feedback`
- **shadcn-svelte Skills** ([`huntabyte/shadcn-svelte`](https://github.com/huntabyte/shadcn-svelte))
  - `huntabyte/shadcn-svelte/skills` — `shadcn-svelte`

## Managing this Collection

```sh
bunx scilla-cli check .
```
