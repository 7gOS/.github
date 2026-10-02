# 7gOS organization defaults

This repository supplies defaults for **every repository in the `7gOS` organization that
does not define its own**. It is not a product — it is a specification.

| Path | Purpose |
|---|---|
| `profile/README.md` | The organization's public landing page (this repository must be public for it to render) |
| `ISSUE_TEMPLATE/` | 5 active issue forms, one per organization-level Issue Type |
| `ISSUE_TEMPLATE/_deferred/` | 3 deferred forms. GitHub ignores subdirectories, so they are kept but inactive |
| `PULL_REQUEST_TEMPLATE.md` | Default pull request template for every repository in the organization |
| `SECURITY.md` | Organization-wide security disclosure policy |

## Knowledge objects do not get issues

Notes, insights, research and decisions do not appear here. Their value lies in
accumulating and being referenced — they have no terminal state, so turning them into
issues produces a backlog that never reaches "done".

Issues carry only what has a **lifecycle and needs to be driven to closure**:
Idea / Initiative / Article / Task / Bug.

## Before renaming or adding a template

Confirm the corresponding Issue Type already exists. The three under `_deferred/` are
enabled once research moves onto GitHub.

## Do not edit this repository on the web

Its contents are generated from a single local source of truth and pushed from there.
Changes made in the web UI will be overwritten on the next sync.