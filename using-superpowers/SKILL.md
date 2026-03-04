---
name: using-superpowers
description: Guidance on when and how to use installed skills. Use skills when they are clearly relevant to the current task.
---

# Using Skills

## When to Use Skills

**Invoke a skill when it is clearly relevant to the task at hand.** Use your judgment — don't load skills for simple questions or unrelated tasks.

**Good reasons to invoke a skill:**
- The task directly matches a skill's domain (e.g., debugging → `systematic-debugging`)
- The user explicitly asks to use a skill
- You're about to do specialized work where a skill provides concrete patterns or tooling

**Skip skill invocation for:**
- Simple factual questions
- Quick file edits unrelated to any skill domain
- Tasks where your built-in knowledge is sufficient

## How to Access Skills

Read the skill's `SKILL.md` file to load its instructions, then follow them.

## Skill Priority

When multiple skills could apply, use this order:

1. **Process skills first** (debugging, planning) — these determine HOW to approach the task
2. **Implementation skills second** (frontend-design, ui-styling) — these guide execution

## Skill Types

**Rigid** (TDD, debugging): Follow exactly. Don't adapt away discipline.

**Flexible** (patterns): Adapt principles to context.

The skill itself tells you which.

## User Instructions

Instructions say WHAT, not HOW. "Add X" or "Fix Y" doesn't mean skip skill workflows when a relevant skill exists.
