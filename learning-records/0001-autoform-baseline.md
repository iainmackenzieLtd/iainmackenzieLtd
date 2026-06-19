# Baseline: prior AutoForm project establishes real starting competence

The user disclosed a substantial prior project (AutoForm — a Playwright-driven, governance-conscious
form-filling agent built with Claude Code over several sessions, ~1700 lines across `app.py` and
`agents/*.py`). The project's own `notes/autoform_learning_log.md` already self-assessed a clean split:
understood (how an AI agent loop works, why code-level safety beats prompt-only safety, git hygiene for
secrets, Docker's purpose, local vs server environments) vs. still dependent on Claude for (reading code
to know what to change, diagnosing terminal errors independently, structuring new features from scratch,
spotting non-obvious costs/risks before deploy).

This sets the floor higher than a typical first session: conceptual architecture (instruction vs code,
governance-by-structure) is already internalised. The actual gap is hands-on code literacy and independent
diagnosis — not concepts. User chose "reading code & diffs" as the first concrete skill to close.

**Implications:** future lessons can skip re-explaining *why* code-level enforcement matters (already
understood, see `notes/architecture.md` in the AutoForm project) and go straight to *how* to read it.
