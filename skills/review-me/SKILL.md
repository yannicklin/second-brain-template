---
name: review-me
description: Inspect, correct, forget, reset, or restore approved profile information with a reversible Git proposal. Use when the user asks what the profile says, challenges an assumption, requests deletion, or asks to return to an earlier version. Never change main without XXXX's review and merge.
---

# Review Me

## Purpose

Give XXXXX control over what the repository says about him. All modifications are reviewable and reversible.

## Modes

### Review

Summarise the relevant approved profile statements and identify their source files. Do not infer additional traits.

### Correct

Propose precise replacement wording for inaccurate or overly broad content.

### Forget

Propose removal of selected information. Remove dependent references in examples or rules when necessary.

### Restore

Use Git history to identify the requested earlier version and propose restoration of the affected files.

### Full reset

Only when XXXXXX explicitly asks for it, propose replacing profile content with neutral starter templates. Do not delete Git history or the repository.

## Workflow for changes

1. Read `AGENTS.md` and the relevant profile files.
2. Identify the exact requested scope.
3. Show the current approved wording.
4. Prepare the smallest correction, deletion, or restoration.
5. Describe effects on other profile files.
6. Create `review/YYYY-MM-DD-short-topic` when Git write access exists.
7. Commit the proposed change and open a pull request.
8. Stop. XXXXXX must review and merge it.

## Boundaries

- Never commit directly to `main`.
- Never merge or approve your own pull request.
- Never use "reset" to erase Git history.
- Never expand a narrow forget request into unrelated deletion.
- If Git access is unavailable, output an exact patch and state that no change was made.
