# Project Validation: My Dev Assistant

## 1. Background

In both personal and professional software development, developers repeatedly create:

- Issues
- Branch names
- Commit messages
- Pull Request descriptions
- Design notes

However, creating these manually every time is time-consuming and often inconsistent.

In addition, the project aims to practice a modern AI-assisted development workflow using ChatGPT and GitHub Copilot.

---

## 2. Problems to Solve

Current development workflows have several inefficiencies:

- Writing Issue descriptions takes time
- Branch naming conventions are inconsistent
- Commit messages are not standardized
- Pull Request descriptions are often incomplete
- Development documents are scattered
- There is no small project dedicated to leaning practical development workflows

The project aims to solve these problems while serving as a hands-on learning environment.

---

## 3. Project Goal

The goal is to create a small development support tool that generates development artifacts from a short task description.

The tool will generate:

- Issue title
- Issue description
- Branch name
- Conventional Commit message
- Pull Request title
- Pull Request description

Example input:

```txt
Add error handling for invalid RAW image size
```

Example output:

```txt
Issue title:
Invalid RAW image size error

Branch:
fix/invalid-raw-image-size

Commit:
fix: handle invalid RAW image size

PR title:
Fix invalid RAW image size handling
```

---

## 4. Initial Scope (v0.1)

The first version will intentionally remain small.

v0.1 will:

- Accept a short task description
- Generate Issue / Branch / Commit / PR text
- Use simple template-based generation
- Run locally without external AI APIs

v0.1 will NOT include:

- Cloud synchronization
- AI API integration
- Database management
- Complex GUI features

The purpose of v0.1 is to establish the basic workflow and repository structure.

---

## 5. Expected Development Workflow

The project itself will be developed using practical software engineering workflows.

The intended workflow is:

1. Create GitHub Issue
2. Create feature branch
3. Implement small feature
4. Commit with Conventional Commit format
5. Create Pull Request
6. Review and improve documentation
7. Merge and continue iteratively

The project is intended to simulate real-world development on a small scale.

---

## 6. Learning Objectives

This project is designed to practice and improve:

### Software Development Skills

- Python development
- GUI or CLI tool development
- File and data management
- Git operations
- Repository organization

### Development Process Skills

- GitHub workflow
- Issue-driven development
- Branch management
- Conventional Commits
- Pull Request creation
- Documentation writing
- Incremental releases
- Refactoring

### AI-Assisted Development Skills

- Using ChatGPT for design discussions
- Using GitHub Copilot for implementation assistance
- Combining AI tools with human-driven design decisions

---

## 7. Proposed Technologies

The following technologies are planned for the initial version:

Category|Technology
-|-
Language|Python
UI|CLI or PySide6
Repository|GitHub
AI Support|ChatGPT/GitHub Copilot
Data Storage|JSON or SQLite
Documentation|Markdown

## 8. Success Criteria

v0.1 will be considered successful if:

- A task description can be entered
- Issue / Branch / Commit / PR text can be generated
- The generated text can be copied easily
- The repository contains proper Issues, branches, commits, and Pull Requests
- The project demonstrates a repeatable development workflow

## 9. Long-Term Vision

The long-term goal is not simply to create a utility tool.

The broader objective is to build a personal development environment that supports:

- Project organization
- AI-assisted development
- Documentation management
- Development workflow standardization
- Knowledge accumulation

The tool may gradually evolve into a personal "development operating system" for future projects.
