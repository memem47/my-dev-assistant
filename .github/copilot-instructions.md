# GitHub Copilot Instructions

## Project Overview

This repository is for My Dev Assistant.

My Dev Assistant is a small development support tool for practical software development workflows.

The tool generates development artifacts from a short task description.

Generated artifacts include:

- Issue title
- Issue description
- Branch name
- Conventional Commit message
- Pull Request title
- Pull Request description

## Important Documents

Before implementing or modifying code, refer to the following documents:

- `docs/project_charter.md`
- `docs/roadmap.md`
- `docs/v0.1_requirements.md`
- `docs/v0.1_design.md`

## Current Target

The current target is v0.1.

v0.1 is a minimum CLI prototype.

Do not implement features outside the v0.1 scope unless explicitly requested.

## v0.1 Scope

Implement:

- CLI input
- Rule-based artifact generation
- Console output
- Basic error handling
- Unit-testable generation logic

Do not implement:

- GUI
- GitHub API integration
- OpenAI API integration
- Database
- History saving
- Clipboard integration

## Coding Policy

Use Python.

Keep the implementation simple and readable.

Separate responsibilities:

- `cli.py` handles command-line input and output
- `generator.py` handles generation rules
- `models.py` defines data structures
- `__main__.py` starts the CLI

Avoid unnecessary external dependencies.

Prefer standard library features for v0.1.

## Testing Policy

Generation logic should be easy to unit test.

Tests should focus on:

- task type detection
- branch name generation
- commit message generation
- empty input handling
- complete artifact generation

## Output Policy

Console output should be human-readable and copy-friendly.

Follow the output format defined in `docs/v0.1_requirements.md` and `docs/v0.1_design.md`.

## Development Policy

Use small commits.

Use Conventional Commits.

Examples:

- `docs: add copilot instructions`
- `feat: add minimum CLI prototype`
- `test: add generator tests`
