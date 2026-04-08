# AGENTS.md

This repo contains agent skills that follow the [agentskills.io](https://agentskills.io) open spec.

## Structure

Each skill is a top-level directory named after the skill, containing a `SKILL.md` file. The directory name must match the `name` field in the SKILL.md frontmatter.

## Conventions

- Skills must be compliant with the agentskills.io spec
- SKILL.md frontmatter requires: `name`, `description`
- SKILL.md body should stay under 500 lines / 5,000 tokens
- Move detailed reference material to `references/` subdirectory
- Scripts go in `scripts/` and should be self-contained, non-interactive, and produce structured output (JSON/CSV to stdout, diagnostics to stderr)
- Description field should use imperative phrasing ("Use when...") and list trigger contexts explicitly

## Adding a new skill

1. Create a directory: `skill-name/`
2. Add `SKILL.md` with YAML frontmatter (`name`, `description`) and markdown instructions
3. Update the skills table in `README.md`
