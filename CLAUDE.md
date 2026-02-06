# CLAUDE.md — Portfolio Repository

## Project Overview

This is a **Portfolio** project owned by **Dylan-StudioChimera**. The repository is currently in its initial state with no source code yet committed. This document serves as the foundational guide for AI assistants working on this codebase.

## Current State

- **Status:** New / empty repository — no framework, source code, or configuration files have been added yet.
- **Remote:** `Dylan-StudioChimera/Portfolio` on GitHub
- **Primary branch:** Not yet established (no commits exist)

## Repository Structure

```
Portfolio/
├── CLAUDE.md          # This file — AI assistant guide
└── (empty)            # Project files to be added
```

As the project grows, update this section to reflect the actual directory layout.

## Development Workflow

### Branching

- Feature branches should follow the pattern: `claude/<description>-<session-id>`
- Always push with: `git push -u origin <branch-name>`
- Never force-push to main/master without explicit permission

### Commits

- Write clear, descriptive commit messages
- Use imperative mood in the subject line (e.g., "Add hero section", not "Added hero section")
- Keep the subject line under 72 characters
- Reference issue numbers when applicable

### Code Quality

When a framework and tooling are chosen, document the following here:
- Linting command: _(to be determined)_
- Formatting command: _(to be determined)_
- Type checking command: _(to be determined)_
- Test command: _(to be determined)_
- Build command: _(to be determined)_

**Always run lint and build checks before committing.**

## Conventions for AI Assistants

### General Rules

1. **Read before writing.** Never modify a file you haven't read first.
2. **Minimal changes.** Only make changes directly requested or clearly necessary. Don't refactor surrounding code, add unrequested features, or over-engineer.
3. **No guessing.** If information is missing, check the codebase or ask — don't assume.
4. **Security first.** Never introduce command injection, XSS, SQL injection, or other OWASP Top 10 vulnerabilities. Never commit secrets or credentials.
5. **Keep it simple.** Prefer straightforward solutions. Three similar lines are better than a premature abstraction.

### File Operations

- Prefer editing existing files over creating new ones
- Do not create documentation files unless explicitly asked
- Do not add comments, docstrings, or type annotations to code you didn't change
- Clean up unused code completely — no `_unused` variables or `// removed` comments

### When Adding Dependencies

- Justify why the dependency is needed
- Prefer well-maintained, widely-used packages
- Check for existing functionality in the project before adding new packages
- Pin versions appropriately

## Tech Stack

_(To be filled in once the framework and tooling are selected.)_

| Layer         | Technology |
|---------------|------------|
| Framework     | TBD        |
| Language      | TBD        |
| Styling       | TBD        |
| Testing       | TBD        |
| Build Tool    | TBD        |
| Deployment    | TBD        |

## Key Files Reference

_(To be updated as the project takes shape.)_

| File / Directory | Purpose |
|------------------|---------|
| `CLAUDE.md`      | AI assistant guide (this file) |

## Updating This File

This CLAUDE.md should be kept up to date as the project evolves:
- When a framework is chosen, fill in the Tech Stack table and add build/lint/test commands
- When the directory structure solidifies, update the Repository Structure section
- When conventions emerge from the codebase, document them here
- When CI/CD is configured, add a section on the pipeline
