<!-- Built with ClaudeTemplate - see ClaudeTemplate.md -->
<!-- WARNING: Do not remove. Enables template features (/brain, /commit, etc.) -->

# Project Context

## Overview

**AutoToon** — A web-based cartoon production pipeline where AI handles asset generation, storyboarding, and process automation, while actual animation happens in open-source 2D animation tools. The goal is NOT per-frame AI image generation, but AI-assisted production workflows wrapping real animation tools (potentially via MCP).

## Phases

- **Phase I** — Research tools and techniques for 2D cartoon creation
- **Phase II (MVP)** — Build a simple AI-assisted cartoon creation process
- **Phase III** — Package as a web app/tool for others to use and potentially purchase

## Project Structure

- **Source code**: `src/` (not yet created)
- **Tests**: none yet
- **Config files**: none yet
- **Generated artifacts**: none yet

## Language & Tooling

- **Language**: Python (backend), web frontend TBD
- **Framework**: TBD (research phase)
- **Build**: none yet
- **Test**: none yet
- **Package manager**: TBD

## Build & Test Entry Points

These are the approved commands. Do not invent alternatives.

- Build: none yet
- Test: none yet
- Lint: none yet

## Intent Management

Intents are stored under `Intents/{FeatureName}/` with numbered intent files.
See `/brain` command for the BRAIN workflow.

## Target Styles

- 2D cartoons (Futurama, Bob's Burgers style)
- B/W noir style
- General 2D animation as used in modern cartoon production

## Key Decisions

- AI generates **assets, storyboards, and automates processes** — not individual frames
- Prefer **open-source** animation tools for easier MCP integration
- Web-based tool for building and organizing assets
- Solo developer

## Constraints

- No budget constraints defined yet (to be addressed during final design)
- Open-source tooling preferred for MCP wrappability
- Tool selection depends on Phase I research findings
