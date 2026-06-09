# Kepler Bug Report Guidelines

Hey there! This repository is used for tracking bugs and feature requests in Kepler. Follow these guidelines to submit clear, actionable requests.

## Before Submitting

- **Search existing issues to avoid duplicates**. If your issue already exists, please add a comment or reaction instead of opening a new one.
- **Reproduce bugs on the latest version**. They may already be fixed.
- **Isolate the problem as much as possible**. A minimal reproduction is far more useful than a complex one.

## How to Submit a Bug Report

In order to submit a bug report or feature request, just open a new issue in this repository and select the corresponding template.

### Do

- **Be specific.** "Clicking Save on the settings page throws a 500 error" is useful. "X doesn't work" is not.
- **Include exact steps to reproduce.** A numbered list of actions that reliably triggers the issue helps maintainers verify and fix it faster.
- **Paste error messages verbatim.** Do not paraphrase — the exact wording matters.
- **Attach logs and screenshots** where relevant. Use code blocks for log output.
- **State your environment** — OS, browser or client version, and app version.
- **Describe expected vs. actual behavior.** Explain what you expected to happen and what happened instead.

### Don't

- **Don't open a duplicate.** Search first — if the issue exists, comment on it instead.
- **Don't bundle multiple bugs into one report.** Each issue should describe exactly one problem. However, multiple occurences of the same issue (e.g. "Inconsistent corner radius across components") should be consolidated into a single issue.
- **Don't report security vulnerabilities publicly.** See [Out of Scope](#out-of-scope) below.
- **Don't leave out steps.** "It just crashes" without context is very hard to act on.
- **Don't use vague severity language** like "urgent" or "critical" without explaining the actual impact.

## What Happens Next

1. A maintainer will triage and label the issue as soon as possible.
2. You may be asked for additional information — please respond promptly or the issue may be closed.
3. Once confirmed, the issue will be prioritized and assigned to a milestone.
4. You will be notified when a fix is released.

---

## Out of Scope

This tracker is for verified bugs only. For the following, use the appropriate channel instead:

- **Usage questions** — check the documentation or ask in the community forum.
- **Security vulnerabilities** — do **not** open a public issue; please send any security concerns via email to contact@trykepler.app.
