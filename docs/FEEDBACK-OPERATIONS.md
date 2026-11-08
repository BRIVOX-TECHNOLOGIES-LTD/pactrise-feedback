# Feedback operations

This document describes how the Pactrise team intends to handle public feedback. It is a process guide, not a service-level guarantee.

## Intake and response

1. **Triage:** Check scope, completeness, privacy, duplicates, and reproducibility.
2. **Understand:** Clarify user impact and the desired outcome.
3. **Prioritize:** Consider customer value, frequency, strategic fit, reliability, risk, and engineering effort.
4. **Plan:** Approved work may be tracked privately in the engineering repository.
5. **Communicate:** Update the public issue when meaningful progress or a decision can be shared safely.

We do not publish internal estimates, credentials, production architecture, security details, private customer cases, or confidential release plans.

## Status labels

| Label | Meaning |
| --- | --- |
| `status: triage` | Awaiting initial review |
| `status: needs-info` | More context is needed |
| `status: under-review` | Being assessed |
| `status: planned` | Accepted for future consideration or planning; no date committed |
| `status: in-progress` | Work has begun |
| `status: released` | Available in the product |
| `status: not-planned` | Not currently planned |
| `status: duplicate` | Already represented by another issue |

## Type labels

`type: feature`, `type: bug`, `type: improvement`.

## Area labels

`area: companies`, `area: sales-partners`, `area: campaigns`, `area: meetings`, `area: payments`, `area: platform`.

## Triage guidelines

- Keep one status label and one type label per issue where possible.
- Ask for missing reproduction steps before labeling a bug confirmed.
- Redirect account-specific support and security disclosures away from public issues.
- Close duplicates with a link to the canonical issue.
- Do not equate reaction counts with priority or promise delivery dates.
- Never publish links to private engineering issues if their titles or metadata expose confidential details.

## Suggested public response

> Thanks for taking the time to share this. We've added it to our review queue. We'll update this thread if we need more context or have a meaningful product decision to share.

## Release communication

When a change is shipped, update the original issue with a short user-facing description, any important limitations, and a link to public documentation when available. Close the issue only when the reported outcome is addressed.
