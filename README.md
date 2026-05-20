# OSS Fix Playbook

How CodeAustral OSS approaches small open-source fixes.

## Quality Bar

- Understand the issue before coding.
- Check existing pull requests to avoid duplicate work.
- Keep the patch scoped to the maintainer's request.
- Add or update tests when the change affects behavior.
- Include verification notes in the pull request.
- Respond to review quickly and plainly.

## Standard Flow

1. Read the issue, contribution guide, and recent related PRs.
2. Reproduce the bug or confirm the missing behavior.
3. Make the smallest complete change.
4. Run the narrowest meaningful test suite.
5. Open a PR with problem, solution, and verification.
6. Keep payment/admin details out of public threads.

## Work We Prefer

- Bug fixes with clear reproduction steps.
- Tests for known regressions.
- Documentation that unblocks users.
- UI polish with concrete acceptance criteria.
- Build, CI, and integration fixes.

## Work We Avoid By Default

- Speculative security reports.
- Crypto, wallet, smart-contract, or payment-protocol code.
- Duplicate bounty PRs where several contributors are already active.
- Issues without maintainer activity or acceptance criteria.
