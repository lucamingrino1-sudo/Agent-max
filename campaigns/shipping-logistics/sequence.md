# Follow-up Sequence — Shipping & Logistics

## Cadence

| Step | Day | Message | Goal |
|---|---|---|---|
| 1 | Day 0 | Initial outreach (Variant A / B) | Surface the pain point, offer the free rate audit, ask for last few months of carrier invoices |
| 2 | Day 3 | Follow-up — different angle, not just a bump | Re-emphasize no-cost/no-obligation framing (we'll tell you if your rates are already good) to re-engage non-repliers |
| 3 | Day 7 | Short breakup-style nudge | Prompt a quick yes/no on sending invoices |
| 4 | Day 14 | Final value-add touch (e.g. a relevant resource/insight) | Last touch before moving to long-term nurture |

The ask never changes across steps — only the angle. Every step is still
pointing at the same low-friction CTA: send recent carrier invoices for a
free audit.

A reply at any step ends the automated sequence for that prospect and routes
per [`scoring/reply-scoring-rubric.md`](../../scoring/reply-scoring-rubric.md).

## Variant testing

Each step ships with at least two subject line variants (A/B) tracked
per domain and per segment. Log results below before promoting a winner
to the default. Full copy in [`day0-email.md`](day0-email.md).

| Step | Variant | Subject line | Sent | Opens | Replies | Notes |
|---|---|---|---|---|---|---|
| 1 | A1 | Quick question about {{Company}}'s shipping rates | | | | Cost angle |
| 1 | A2 | Are you overpaying on shipping right now? | | | | Cost angle |
| 1 | B1 | Is your shipping process actually working for {{Company}}? | | | | Reliability/process angle |
| 1 | B2 | Rates aside — is your fulfillment keeping up? | | | | Reliability/process angle |

## Suppression

Any prospect marked Cold/unsubscribed in the reply-scoring rubric is removed
from every remaining step immediately, not just the one they replied to.
