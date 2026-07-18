# RunsOnItsOwn.ai — Approved Shared Context

## Purpose

This directory is the canonical Markdown record of approved, non-sensitive RunsOnItsOwn.ai shared business context.

## Operating model

- Canonical Markdown is the source of truth.
- The private GitHub repository provides backup, history, rollback, and transferability.
- The existing local Gbrain installation is a retrieval index of approved repository state; it is not the normal shared-context authoring surface.
- Canonical updates require TJ's explicit approval.
- The normal update sequence is:

```text
owner approval → canonical Markdown edit → Git diff review →
commit/push → embeddings-disabled Gbrain sync → retrieval verification
```

## Exclusions

Do not store credentials, tokens, passwords, private keys, connection details, customer records, raw conversations, raw source uploads, session logs, workbench mechanics, temporary troubleshooting, or unapproved drafts here.

Raw source material and the private weekly-review queue remain outside this directory and outside Gbrain until explicitly approved for canonicalization.
