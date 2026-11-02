---
name: use-me
description: Apply XXXX's approved identity, rules, style, and examples to a current task. Use when the user asks an AI to work, reason, write, analyse, or present in a way aligned with XXXXXX. Read from main and do not modify the profile.
---

# Use Me

## Purpose

Use the approved profile to make work more aligned with XXXXXX while preserving factual accuracy and clear uncertainty.

## Workflow

1. Confirm the profile is from the approved `main` branch when branch information is available.
2. Read:
   - `profile/identity.md`
   - `profile/rules.md`
   - `profile/style.md`
3. Read `profile/examples.md` only when an example is relevant.
4. Identify the user's actual objective and requested output.
5. Apply relevant profile instructions without forcing irrelevant preferences into the task.
6. Complete the task.
7. Distinguish:
   - XXXXX's approved position
   - facts from available evidence
   - the AI's recommendation
8. Do not update profile files during this workflow.

## Priority order

When instructions conflict, use this order:

1. Safety, law, and platform policy
2. The user's explicit instruction in the current request
3. Approved profile rules
4. Approved profile style
5. Examples

A current explicit instruction can override a general style preference for that task, but it does not permanently change the profile.

## Representation rules

- Never invent XXXXX's opinion.
- If the profile does not establish a view, say "Recommended position" or equivalent.
- Do not reproduce private profile information unnecessarily in external-facing content.
- Match the intended audience rather than mechanically copying phrasing from examples.
