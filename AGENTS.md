# AGENTS.md

## Project scope

This repository contains the AI Employees Platform monorepo.

## Repository structure

- `apps/`: deployable applications.
- `packages/`: reusable platform packages.
- `reference-projects/`: external projects used for research and comparison.
- `docs/`: research, architecture, licensing, and architectural decisions.

## Development guidelines

- Keep shared logic inside `packages/`.
- Document architecture changes in `docs/decisions/`.
- Record third-party license information in `docs/licenses/`.
- Never commit credentials, API keys, generated build output, or local environment files.
- Add tests and documentation alongside new functionality.
