# CLAUDE.md — AI Assistant Guide for SKF_ENG

## Project Overview

SKF_ENG is a newly initialized repository. This document serves as the foundational guide for AI assistants working in this codebase and should be updated as the project evolves.

## Repository Structure

```
SKF_ENG/
├── CLAUDE.md          # This file — AI assistant guide
└── (project files)    # To be added
```

> **Note:** This project is in its initial setup phase. Update this section as directories and files are added.

## Development Workflow

### Branch Conventions

- **Main branch:** `main` (or as configured)
- **Feature branches:** Use descriptive names prefixed with the type of work (e.g., `feature/`, `fix/`, `claude/`)
- Always create pull requests for code review before merging to the main branch

### Commit Messages

- Use clear, descriptive commit messages
- Follow conventional commit format when possible: `type: description`
  - Types: `feat`, `fix`, `docs`, `refactor`, `test`, `chore`, `build`, `ci`
- Keep the subject line under 72 characters

### Code Quality

- Write tests for new functionality
- Ensure all tests pass before committing
- Follow the project's linting and formatting rules (configure as tooling is added)
- Review code for security vulnerabilities (OWASP Top 10)

## Key Conventions for AI Assistants

1. **Read before modifying** — Always read existing files before suggesting changes
2. **Minimal changes** — Only make changes that are directly requested or clearly necessary
3. **No over-engineering** — Keep solutions simple and focused on the current task
4. **Preserve existing patterns** — Follow the conventions already established in the codebase
5. **Security first** — Never introduce command injection, XSS, SQL injection, or other vulnerabilities
6. **No secrets in code** — Never commit `.env` files, credentials, or API keys
7. **Test your changes** — Run the project's test suite after making modifications

## Build & Run

> To be documented as the project's build system is established.

## Testing

> To be documented as the project's test framework is configured.

## Dependencies

> To be documented as dependencies are added to the project.

## Architecture

> To be documented as the project architecture takes shape.

## Useful Commands

> To be documented as the project's tooling is set up.
