# Free AI PR Triage Checklist

Use this before deep review.

## 1. Is The Work Identifiable?

- [ ] Linked issue, bug, bounty, or goal.
- [ ] PR summary describes behavior, not just files changed.
- [ ] Scope is narrow enough to review.

## 2. Is There Evidence?

- [ ] Reproduction or before/after notes.
- [ ] Validation commands.
- [ ] Relevant logs or screenshots.
- [ ] CI status is included.

## 3. Is CI Classified?

- [ ] Passing
- [ ] Code-actionable
- [ ] Flaky
- [ ] Auth-only
- [ ] Infra-owned
- [ ] Unknown

Unknown red CI means ask for classification before deep review.

## 4. Is AI Use Reviewable?

- [ ] AI assistance disclosed if applicable.
- [ ] Human validation stated.
- [ ] Contributor can explain the final diff.
- [ ] No fabricated APIs, benchmarks, issue links, or maintainer claims.

## 5. Is Paid-Work Language Safe?

- [ ] Assignment or claim status is public.
- [ ] No implication of acceptance before review.
- [ ] No duplicate or overlapping claim.
- [ ] Payment route is separate from implementation evidence.

## Decision

- Ready for review.
- Needs evidence.
- Needs CI classification.
- Needs scope split.
- Park until facts are added.
- Reject with concise explanation.
