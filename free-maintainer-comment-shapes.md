# Free Maintainer Comment Shapes

Use these when a PR needs evidence, not heat.

## Missing Evidence

```md
Thanks for the PR. Before review, please add the linked issue or goal, reproduction or before/after notes, validation commands, CI status/classification, and a human-validation note if AI assistance was used. That will make the change easier to review fairly.
```

## Red CI

```md
Before review, please classify the failing CI as code-actionable, flaky, auth-only, infra-owned, or unknown. Include the failing check link, one relevant log excerpt, local validation if available, and the smallest next action needed from maintainers.
```

## Broad Scope

```md
Thanks for the work here. This appears broad enough that review would be safer after a split or short design note. Please narrow the PR to one behavior change, link the issue it resolves, and list the validation command that proves that specific change.
```

## Bounty Safety

```md
Implementation review and reward status should stay separate. Please clarify the public claim/payment route before using bounty or payment language in the PR thread.
```
