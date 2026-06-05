# Agent PR Gatekeeper

A maintainer-side intake system for low-context pull requests that arrive before the evidence is ready.

Use it when a PR arrives faster than your reviewers can verify it. The goal is not to accuse contributors or guess how the work was written. The goal is to require enough context, validation, and CI classification that maintainers can make a fast, fair decision.

## Buy This If

- Your repo receives vague PRs with weak summaries or missing validation.
- Reviewers are spending time reconstructing context instead of reviewing code.
- Contributors mix CI failures, bounty claims, and implementation claims in one thread.
- You need a lightweight intake gate before deep review.
- You want to welcome useful contributions without accepting unsupported submissions.

## What It Helps With

- Decide whether a PR is ready for review.
- Ask for evidence without shaming the contributor.
- Separate CI classification from code review.
- Require a clear human verification note when work was generated, assisted, or hard to audit.
- Keep bounty/payment language reputation-safe.

## Free Preview

- [Free AI PR triage checklist](./free-ai-pr-triage-checklist.md)
- [Free agent PR risk scorecard](./free-agent-pr-risk-scorecard.md)
- [Sample PR brief](./sample-pr-brief.json)
- [Request a template or workflow](https://github.com/GhostieMostie/agent-pr-gatekeeper-preview/issues/1)

## Before / After

Weak maintainer response:

> This does not look ready. Closing.

Gatekeeper response:

> Thanks for the PR. Before review, please add the linked issue, validation commands, CI classification, and any verification note that helps us trust the behavior. That lets us review the change instead of reconstructing context.

## Paid Kit

The full kit includes a no-dependency report generator, GitHub PR brief fetcher, maintainer comment generator, bounty claim safety gate, agent disclosure policy, CI classification request, review readiness report, dry-run GitHub Action scaffold, and five-minute PR gate workflow.

Launch price: `$99`.

Full kit checkout: https://buy.polar.sh/polar_cl_tXz7ggyNV5Xfbj9yOBQfgm5S01ytadHbt6HUP213LgG

Use the full kit if you want a repeatable intake layer instead of one-off comment wording. The paid download turns a PR URL or brief into a review-readiness report, evidence-gap list, maintainer-safe comment, and dry-run GitHub Actions artifact that your repo can adopt without letting automation comment publicly by default.

## Why This Is Different

Most review tools start after the reviewer is already engaged. Agent PR Gatekeeper starts one step earlier: does this PR have enough evidence to deserve human review right now?

## Responsible Use

Do not use this to accuse contributors. Use it to require evidence, protect review time, and make useful work easier to accept.
