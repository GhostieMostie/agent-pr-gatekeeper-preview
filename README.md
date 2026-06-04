# Agent PR Gatekeeper

A maintainer-side triage system for AI-generated, agent-authored, and low-context pull requests.

Use it when a PR arrives faster than your reviewers can verify it. The goal is not to ban AI-assisted work. The goal is to require enough evidence that maintainers can make a fast, fair decision.

## Buy This If

- Your repo receives vague AI-generated PRs.
- Reviewers are spending time reconstructing context instead of reviewing code.
- Contributors mix CI failures, bounty claims, and implementation claims in one thread.
- You need a lightweight intake gate before deep review.
- You want to welcome useful AI-assisted work without accepting unsupported submissions.

## What It Helps With

- Decide whether a PR is ready for review.
- Ask for evidence without shaming the contributor.
- Separate CI classification from code review.
- Require human validation for AI-assisted work.
- Keep bounty/payment language reputation-safe.

## Free Preview

- [Free AI PR triage checklist](./free-ai-pr-triage-checklist.md)
- [Free agent PR risk scorecard](./free-agent-pr-risk-scorecard.md)
- [Sample PR brief](./sample-pr-brief.json)
- [Request a template or workflow](https://github.com/GhostieMostie/agent-pr-gatekeeper-preview/issues/1)

## Before / After

Weak maintainer response:

> This looks AI-generated. Closing.

Gatekeeper response:

> Thanks for the PR. Before review, please add the linked issue, validation commands, CI classification, and a human-validation note. That will let us review the behavior instead of reconstructing context.

## Paid Kit

The full kit includes a no-dependency report generator, GitHub PR brief fetcher, maintainer comment generator, bounty claim safety gate, agent disclosure policy, CI classification request, review readiness report, dry-run GitHub Action scaffold, and five-minute PR gate workflow.

Launch price target: `$99`.

Checkout coming after Polar product setup.

## Why This Is Different

Most AI code review tools try to judge the patch. Agent PR Gatekeeper judges whether the patch has enough evidence to deserve human review. That makes it useful before maintainers burn attention.

## Responsible Use

Do not use this to accuse contributors of AI misuse. Use it to require evidence, protect review time, and make useful AI-assisted work easier to accept.
