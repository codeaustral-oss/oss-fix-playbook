# Example: Issue To Fix

## Issue

A CLI command accepts comma-separated values but fails when a value includes whitespace.

## Reproduction

```bash
tool parse "alpha, beta,gamma"
```

Expected normalized values:

```text
alpha
beta
gamma
```

## Patch Shape

- Add a parser test for whitespace around comma-separated values.
- Trim values after splitting.
- Keep empty-value behavior unchanged.

## Verification

```bash
npm test -- parser
```
