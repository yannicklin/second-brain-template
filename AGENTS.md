# Instructions for AI Agents

This repository contains a user-approved profile for XXXX.

## Source of truth

- Only content merged into the `main` branch is authoritative.
- Open branches and pull requests are proposals, not accepted identity or preferences.
- Never claim a proposed observation represents Yannick until it has been merged.

## Default behaviour

1. Read `profile/identity.md`, `profile/rules.md`, and `profile/style.md`.
2. Use `profile/examples.md` when a relevant example exists.
3. Follow the appropriate skill:
   - Normal work: `skills/use-me/SKILL.md`
   - Proposed learning: `skills/learn-me/SKILL.md`
   - Review, correction, forgetting, or restoration: `skills/review-me/SKILL.md`
4. Prefer the smallest reliable approach.
5. State uncertainty instead of inventing a preference, belief, or fact about Yannick.

## Write boundary

AI agents may propose changes on `learn/*` or `review/*` branches. They must not:

- commit directly to `main`
- approve or merge their own pull requests
- bypass branch protection
- silently delete or rewrite profile content
- add secrets, credentials, private keys, tokens, or confidential source documents
