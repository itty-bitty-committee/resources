# Project CLAUDE.md - Resources

## Project Overview

Shared assets, branding, and reusable GitHub Actions workflows for Mikey Pro and related projects. Contains logos, color palettes, icons, social images, code of conduct templates, and CI workflow files (bump-n-pub, dispatch-ncu).

## Tech Stack

- **Type:** Asset/config repository (no runtime code)
- **Module type:** ESM (`"type": "module"`)
- **Linting:** mikey-pro (ESLint/Prettier/Stylelint)

## Commands

No build or test scripts. This is an assets-only repository.

## Conventions

- ESM module type for JS config files
- Project assets organized by project name in `assets/` (mikey-pro, gitlang, cloudy-nights, etc.)
- Reusable GitHub Actions workflows in `workflows/` (bump-n-pub, dispatch-ncu)
- `CODE_OF_CONDUCT/` is a git submodule
- No test suite — assets verified visually, workflows tested by consuming repos
- Conventional commits: `feat:`, `fix:`, `chore:`, etc.
