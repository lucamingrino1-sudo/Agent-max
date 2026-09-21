# Domain Health Tracker

Max checks this before assigning any domain to a campaign send. A domain that
fails the healthy threshold is pulled from rotation immediately, no exceptions.

## Healthy thresholds

| Metric | Healthy | Watch | Pull from rotation |
|---|---|---|---|
| Bounce rate | < 2% | 2–5% | > 5% |
| Spam complaint rate | < 0.1% | 0.1–0.3% | > 0.3% |
| Warm-up status | Fully warmed (≥ 4 weeks ramp, steady volume) | Ramping | Cold / unramped |
| Daily send volume | Within domain's current ramp cap | — | Over cap |

A domain in "Watch" may keep sending at reduced volume with closer monitoring.
Any domain in "Pull from rotation" doesn't send again until root cause is
fixed and it's re-warmed.

## Domain roster

| Domain | Warm-up start date | Current daily cap | Bounce rate | Complaint rate | Status | Assigned vertical(s) | Notes |
|---|---|---|---|---|---|---|---|
| _(add domains as they come online)_ | | | | | | | |

## Review cadence

- Check bounce/complaint rates per domain after every send batch.
- Full roster review before greenlighting a new campaign (per the Decision
  Framework in `identity/SOUL.md`).
- Any domain crossing into "Pull from rotation" gets logged here immediately
  with the date and reason, even mid-campaign.
