# Source-Material Intake

This folder defines how material is supplied to `learn-me` during bootstrap or later learning.

## Minimum structure

```text
intake/
  manifest.yml
  bootstrap-answers.md
  sources/
    linkedin/
    facebook/
    blog/
    discord/
    conversations/
    drafts/
    other/
```

Only `manifest.yml` is required. Source files may also remain outside this repository when privacy, copyright, employer confidentiality, or size makes copying inappropriate. In that case, record an authorised path, link, or description in the manifest.

## Intake principles

- Classify material before learning from it.
- Prefer final, approved, or published work over unreviewed AI drafts.
- Preserve platform and language context.
- Keep original and revised versions together when edits reveal preferences.
- Do not commit confidential employer/customer material, credentials, private keys, or raw sensitive conversations.
- A source may inform a proposal, but only XXXX-approved content merged into `main` becomes authoritative.

## Recommended source bundle

For useful bootstrap results, provide approximately:

- 5 to 10 representative items per important platform or language
- 3 to 5 before/after editing pairs
- 3 to 5 rejected outputs with short rejection reasons
- 2 to 5 examples for each genuine perspective or role

Quality and clear classification matter more than volume.

## Source authority

Use these values:

- `self_written`: written substantially by XXXXX
- `ai_assisted_approved`: AI-assisted and accepted after review
- `ai_draft_edited`: AI draft substantially edited by XXXXX
- `rejected`: not representative; useful only as a negative example
- `reference_only`: factual or topical input, not evidence of XXXXX's voice
- `unknown`: ownership or approval status still needs clarification

## Learning weight

- `high`: strongly representative and recent
- `medium`: useful with context
- `low`: old, experimental, atypical, or weak evidence
- `negative`: teaches what to avoid, not what to imitate
