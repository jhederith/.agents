# Agent Skills

A curated, interoperable collection of reusable **agent skills** for modern AI coding assistants and generative AI platforms.

This repository provides a shared home for skills designed to extend, guide, and standardize agent behavior across:

- Google Gemini
- Cursor
- Antigravity
- Claude
- ChatGPT
- Qwen
- GitHub Copilot
- DeepSeek

## Purpose

The goal is to make high-quality agent capabilities portable, discoverable, and easy to maintain. Each skill captures a focused workflow, behavioral contract, or domain-specific operating procedure that an AI agent can apply consistently.

Skills are intentionally modular: they can be added, reviewed, versioned, and reused independently without coupling them to a single vendor, model, or development environment.

## Repository Structure

```text
skills/
└── <skill-name>/
    └── SKILL.md
```

Every skill should include a `SKILL.md` file containing:

- A concise name and activation description
- The intended use cases and scope
- Clear behavioral rules and constraints
- Practical guidance for consistent execution

## Design Principles

- **Portable:** Prefer platform-agnostic instructions whenever possible.
- **Composable:** Keep each skill focused on one capability or workflow.
- **Explicit:** Describe activation criteria, expected behavior, and boundaries clearly.
- **Maintainable:** Use readable Markdown and evolve skills through small, reviewable changes.
- **Agent-friendly:** Structure content so both humans and AI systems can discover and apply it reliably.

## Contributing

Add new capabilities under `skills/<skill-name>/SKILL.md`. Keep the skill self-contained, technically precise, and broadly reusable across supported agents.