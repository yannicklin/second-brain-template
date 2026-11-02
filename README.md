# XXXX Second Brain

A small, portable, version-controlled profile that AI tools can read and use.

## Authority model

- `main` contains the approved representation of XXXXXX.
- `learn/*` branches contain proposed learning only.
- Pull requests are hypotheses until manual reviews and merges them.
- AI tools must never merge their own proposals.

## Repository structure

```text
profile/
  identity.md
  rules.md
  style.md
  examples.md
intake/
  README.md
  manifest.yml
  bootstrap-answers.md
  sources/
skills/
  learn-me/SKILL.md
  use-me/SKILL.md
  review-me/SKILL.md
.github/
  CODEOWNERS
  pull_request_template.md
  workflows/validate-profile.yml
AGENTS.md
CONTRIBUTING.md
SECURITY.md
```

## How an AI tool should use this repository

1. Read `AGENTS.md`.
2. For normal work, follow `skills/use-me/SKILL.md`.
3. To bootstrap or propose durable learning, follow `skills/learn-me/SKILL.md` and use the source format under `intake/`.
4. To inspect, correct, forget, or restore profile content, follow `skills/review-me/SKILL.md`.
5. Treat only merged content on `main` as authoritative.

## Initial setup on GitHub

1. Create a private repository.
2. Upload this repository content.
3. Replace `YOUR_GITHUB_USERNAME` in `.github/CODEOWNERS`.
4. Protect the `main` branch:
   - Require a pull request before merging.
   - Require one approval.
   - Dismiss stale approvals when new commits are pushed.
   - Require the `Validate profile files` status check.
   - Block force pushes and branch deletion.
5. Give AI integrations no permission to merge to `main`.

## Example prompts

### Use my profile

> Read AGENTS.md and use the use-me skill. Analyse this architecture and recommend the smallest reliable option.

### Learn from a conversation

> Use the learn-me skill to review this conversation. Create only a proposed diff on a learn/* branch. Do not merge it.

### Review or reset

> Use the review-me skill to show what the repository currently says about my communication style. Propose corrections, but do not change main.
