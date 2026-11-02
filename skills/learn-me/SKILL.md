---
name: learn-me
description: Review selected interactions or materials and propose durable updates to the approved user profile through a separate Git branch and pull request. Use when the user asks the AI to learn about them, update their profile, extract preferences, or capture recurring methods. Never merge proposals into main.
---

# Learn Me

## Purpose

Identify durable, useful learning about XXXXX and propose it for human review. This skill has proposal authority only.

## Modes

### Bootstrap mode

Use when the profile is new, thin, or the user asks to build it from source material.

1. Read `intake/README.md`, `intake/manifest.yml`, and `intake/bootstrap-answers.md`.
2. Ask the interview progressively, starting with purpose and available material.
3. Do not ask questions already answered by the manifest, source content, or previous answers.
4. Help classify each source by platform, language, audience, perspective, approval status, authoring status, and learning weight.
5. Analyse representative material only after ownership, approval, and permitted-learning scope are sufficiently clear.
6. Separate core identity from platform, language, length, audience, and perspective effects.
7. Present inferred patterns, conflicts, confidence, and representative evidence for validation.
8. Ask only targeted follow-up questions needed to resolve material ambiguity.
9. Propose the smallest coherent initial profile change on `learn/YYYY-MM-DD-bootstrap-profile`.
10. Open a pull request and stop for XXXX's review.

### Incremental mode

Use when learning from a selected chat, edit, article, post, or collection after bootstrap.

1. Read `AGENTS.md` and all files in `profile/`.
2. Confirm the selected material and its relevant context.
3. Ask a follow-up question only if ownership, approval status, platform, language, perspective, or intended learning is materially unclear.
4. Compare candidate learning with the approved profile.
5. Exclude temporary context, one-off reactions, secrets, sensitive inference, and unsupported assumptions.
6. Require at least two examples, unless XXXXXX explicitly asks for a statement to become durable.
7. Propose the smallest necessary diff on a `learn/*` branch.
8. Open a pull request and stop.

## Intake rules

- Use `intake/manifest.yml` as the standard source register.
- Do not require source files to be committed when a safe authorised location is available.
- Treat `self_written`, `ai_assisted_approved`, and clearly documented edits as positive evidence.
- Treat `rejected` items as negative examples only.
- Treat `reference_only` material as topic evidence, not evidence of XXXX's style or beliefs.
- Reduce confidence for old, atypical, unapproved, or weakly classified sources.
- Never infer a durable personal rule solely from platform convention.

## Questioning rule

Ask progressively, not as one large questionnaire. Ask the minimum next question that unlocks useful analysis. Group up to five closely related questions when efficient. Stop asking once the available evidence is sufficient for a narrowly scoped proposal.

## Mandatory boundaries

Never:

- commit directly to `main`
- merge a pull request
- approve your own proposal
- treat an open proposal as accepted
- silently overwrite or remove approved profile content
- infer health, political, religious, sexual, emotional, or other sensitive traits
- store passwords, tokens, credentials, private keys, or confidential raw conversations

## If Git write access is unavailable

Produce a proposed patch containing:

- observation
- evidence
- classification
- confidence
- affected file
- exact diff
- risks or possible over-generalisation

Clearly state that no repository change was made.

## Pull request quality

A proposal must answer:

- What was observed?
- What evidence supports it?
- Is it durable rather than temporary?
- Which file changes?
- What exact wording is proposed?
- What could make the observation inaccurate or too broad?
