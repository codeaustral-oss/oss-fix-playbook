# OSS Fix Playbook

CodeAustral OSS uses this playbook for small, reviewable open-source fixes.

The goal is simple: help maintainers close scoped issues without creating review noise.

## Quality Bar

- The issue is understood before code changes start.
- Existing pull requests are checked to avoid duplicate work.
- The patch is scoped to the maintainer's request.
- Behavior changes include tests where practical.
- Verification notes are included in the pull request.
- Review feedback is handled quickly and plainly.

## Standard Flow

1. Read the issue, contribution guide, and recent related pull requests.
2. Reproduce the bug or confirm the missing behavior.
3. Make the smallest complete change.
4. Run the narrowest meaningful test suite.
5. Open a pull request with problem, solution, and verification notes.
6. Keep payment and admin details out of public threads.

## Decision Rules

Use the scoring sheet in [examples/scorecard.md](examples/scorecard.md) before starting paid work. A task should score at least 75/100 before implementation.

## Maintainer-Friendly Notes

- Small patches beat broad rewrites.
- A clear failing case is better than a long explanation.
- If acceptance criteria are unclear, ask one specific question before coding.
- If several contributors already have active pull requests, do not add another duplicate.

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
