# coder-skills

A collection of agent skills compliant with the [agentskills.io](https://agentskills.io) open spec.

## Skills

| Skill | Description |
|-------|-------------|
| [code-review](code-review/) | Thorough, structured code review with severity-tiered findings |
| [systematic-debugging](systematic-debugging/) | Hypothesis-driven bug diagnosis and resolution |

## Usage

Copy or symlink a skill directory into one of the standard discovery paths:

```
# Project-level (any agent)
<project>/.agents/skills/

# Project-level (client-specific)
<project>/.<client-name>/skills/

# User-level (any agent)
~/.agents/skills/

# User-level (client-specific)
~/.<client-name>/skills/
```

Any agent that supports the agentskills.io spec will discover and load skills from these locations.

## Skill structure

Each skill is a directory containing a `SKILL.md` file with YAML frontmatter and markdown instructions:

```
skill-name/
├── SKILL.md        # Required: metadata + instructions
├── scripts/        # Optional: executable scripts
├── references/     # Optional: additional documentation
├── assets/         # Optional: templates, schemas, data files
└── evals/          # Optional: test cases
```

## License

MIT
