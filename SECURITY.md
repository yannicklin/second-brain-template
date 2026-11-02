# Security and Privacy

## Repository visibility

Keep this repository private unless XXXXX deliberately creates a separate public profile.

## Never store

- passwords or authentication tokens
- private keys
- recovery codes
- confidential customer or employer data
- unredacted private conversations
- identity documents or financial account details

## AI integration permissions

Use least privilege:

- read access to `main`
- write access only when branch and pull-request creation is required
- no permission to bypass branch protection
- no permission to merge to `main`

If a secret is committed, revoke or rotate it immediately. Removing it from the latest file is not sufficient because Git history retains earlier versions.
