# VEYRA — Project Instructions for Claude Code

This file is loaded automatically at the start of every Claude Code session in
this repository. It is the persistent source of truth for VEYRA's business
rules, architecture decisions and constraints. Keep it current: when a rule is
agreed, record it here in the same change.

## Rules for Claude (always apply)

1. **Never invent business rules.** Only the rules written in this file (or
   stated explicitly by the project owner in the current session) are real.
   If a rule is missing or ambiguous, ask — do not guess and do not fill gaps
   with "typical" behavior.
2. **Never change business rules or business logic without explicit owner
   approval.** This covers editing the rules below and changing code that
   implements them. Refactors must preserve behavior exactly.
3. **Respect every "Do not change" item** in the section below. If a task
   seems to require touching one, stop and ask first.
4. When the owner states a new rule or decision in a session, propose adding
   it to this file (verbatim, with the date) so it survives the session.
5. If code and this file disagree, do not silently "fix" either one — report
   the conflict to the owner.

## Current repository state (verified 2026-09-30)

- The repository contains no application code yet. The only tracked file
  besides this one is `text.txt`.
- There is no build system, package manifest, test suite, or linter
  configured, so there are no build/test commands to run.
- Update this section when real code, commands or structure are added.

## Business rules

<!-- Owner: add each rule as a numbered item. State it exactly; Claude will
     treat the wording as authoritative. Example format:
     BR-1 (YYYY-MM-DD): <rule> -->

_None recorded yet._ Claude must not assume any business rule exists until it
is written here.

## Architecture decisions

<!-- Format: AD-1 (YYYY-MM-DD): <decision> — <reason> -->

_None recorded yet._

## Implementation constraints

<!-- Tech stack, versions, conventions, security/compliance requirements, etc.
     Format: IC-1: <constraint> -->

_None recorded yet._

## Do not change

<!-- Files, modules, APIs, data formats or behaviors that must not be altered
     without explicit owner approval. Format: DNC-1: <item> — <reason> -->

_None recorded yet._
