# policy-bot-sandbox

Throwaway repo to spike [Palantir policy-bot](https://github.com/palantir/policy-bot) as a merge gate.

Success test:
1. A docs-only PR should go green with no human review.
2. A `.tf` PR should stay pending until `cyridae` (stand-in for Platform Team) reviews.
