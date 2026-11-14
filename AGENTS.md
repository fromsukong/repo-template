# AGENTS.md — repo-template

**Cursor CLI running Grok 4.7** is a recognized coding agent in this repo (joined 2026-11-14). Owner is Supakone (Prame).

Template for a new `@fromsukong` repo. Placeholders (`{Repo Name}`, `{product-name}`, `{repo-name}`) stay as placeholders in this repository. Fill them only in the new repo created from the template.

A repo created from here keeps:

- `product/spec.md` — the repository specification (this is what `products-dev` sparse-checkouts)
- `AGENTS.md` — replace the template notes with rules for that repo
- `.cursor/rules/cursor-cli.mdc` — the always-on Cursor CLI rule for that repo
- `src/` — application source, not copied into `products-dev`

## Hard rules for this template repo

1. Do not replace the placeholders with a real product.
2. Do not add application source here.
3. Do not commit or push unless asked. When asked, branch and open a PR. No secrets in git.
