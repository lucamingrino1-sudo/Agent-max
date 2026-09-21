# Reply Scoring & Routing

Every reply gets scored and routed. None sit unrouted — a hot lead is
escalated to a human account manager the same day it comes in, not batched
with the rest of the campaign's results.

## Score tiers

| Tier | Signal | Examples | Routing | SLA |
|---|---|---|---|---|
| 🔥 Hot | Explicit interest, asks for pricing/call, confirms fit | "Can we set up a call this week?", "What does this cost?" | Escalate directly to the account manager assigned to that vertical | Same day |
| 🌤 Warm | Interested but has questions, or good timing objection | "Interesting, tell me more", "Not now, check back in Q2" | Add to nurture sequence; log the objection/timing for follow-up | Within 1 business day |
| ❄️ Cold / Not interested | Explicit no, unsubscribe, wrong contact | "Not interested", "Remove me" | Suppress from future sends on this and related sequences | Immediate suppression |
| 🚫 Out-of-office / Auto-reply | Non-human automated response | OOO, mail delivery notices | No action — do not count against reply rate | N/A |

## Escalation path (Hot leads)

1. Tag the reply Hot and identify the vertical/service it maps to.
2. Notify the account manager owning that vertical the same day, with the
   full thread and prospect context (company, segment, which sequence/variant
   they were on).
3. Log the handoff (date, AM, lead) so it isn't double-touched by outreach.
4. Pause that prospect from any further outreach sends immediately.

## Notes

- A Warm reply's objection/timing gets fed back into cadence and offer
  testing — this is part of "silence is data" (see `identity/SOUL.md`).
- Cold/unsubscribe replies suppress across the whole domain-to-prospect
  relationship, not just the current sequence.
