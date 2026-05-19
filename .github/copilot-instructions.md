# Copilot instructions for learngit (C:\learngit)

Purpose
- Concise, repo-specific guidance for Copilot sessions: where to look for build/test/lint commands, the high-level layout, and any repository-specific conventions.

Build / test / lint
- No build, test, or lint configuration files detected in this repository root (Makefile, CMakeLists.txt, package.json, setup.py, etc. were not found when this file was created).
- When a build system or test harness is added, update this section with:
  - the primary build command (e.g., make, cmake --build, npm run build)
  - how to run a single test (not just the whole suite)
  - lint/static-analysis commands (e.g., clang-tidy, cppcheck, eslint)

High-level architecture
- Repository currently contains no source or orchestration files. Treat as an empty/uninitialized workspace.
- For future structure, prefer documenting here in short form (one line per component) when files are added, for example:
  - src/: application source
  - tests/: unit and integration tests
  - tools/: helper scripts

Key conventions
- None detected. When adding code, add conventions that Copilot should follow (naming, error handling, build flags, thread-safety expectations) to this file so future sessions can apply them automatically.

Other AI assistant / tooling config
- No assistant/config files (CLAUDE.md, AGENTS.md, .cursorrules, .clinerules, CONVENTIONS.md, AIDER_CONVENTIONS.md, etc.) were detected.
- If any of those are added, merge their important guidance into this document.

Notes for Copilot sessions
- Before proposing changes that affect repository-wide behavior (build system, CI, tests), update this file with the new commands and conventions so later suggestions remain consistent.
- Keep suggestions scoped to the minimal set of files needed; prefer small, reversible changes in an otherwise-empty repo.

Summary
- This is a minimal, updatable scaffold for Copilot to use when this repository is populated. Update with concrete build/test/lint commands and architecture notes after adding code.
