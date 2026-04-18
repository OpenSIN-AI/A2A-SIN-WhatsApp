# Contributing to A2A-SIN-WhatsApp

## Scope first

Before changing code or docs, verify the change genuinely belongs to the **WhatsApp** surface.

Put the change here when it affects:
- WhatsApp messaging, routing, or automation workflows
- WhatsApp evidence, recovery, auth, or session handling
- WhatsApp contracts tied to delivery and automation flows

Do **not** put the change here when it belongs to:
- generic messaging ownership outside WhatsApp
- unrelated social, community, or product platform behavior
- organization SSOT docs or architecture ownership

## Workflow

1. Branch from the latest `main`.
2. Make the smallest repo-scoped change possible.
3. Run validation command(s) relevant to the touched surface.
4. Include exact validation commands and evidence in the PR.

## Boundary checklist

- Does this change stay within WhatsApp ownership?
- Does another repo already own the adjacent platform behavior?
- Does this PR avoid redefining shared docs, runtime, or platform canon?

## Boundary Rules

Before adding a feature or top-level claim, answer:

1. Is this specifically WhatsApp integration work?
2. Does another OpenSIN repo already own the canonical source of truth?

### Put it in `A2A-SIN-WhatsApp` if:
- it improves WhatsApp integration
- it improves this repo's A2A agent behavior

### Do NOT put it in `A2A-SIN-WhatsApp` if:
- it claims broader product, ops, or docs ownership

## License

By contributing, you agree that your contributions will be licensed under the Apache License 2.0.
