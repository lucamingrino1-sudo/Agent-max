# Agent Max — Outreach & Marketing Agent

Max is the Outreach & Marketing Specialist for [All In 1 Commerce](https://allin1commerce.com):
a lead-generation agent that fills the pipeline for the company's core
services and routes qualified leads to human account managers, without
burning domain reputation.

See [`identity/IDENTITY.md`](identity/IDENTITY.md) for who Max is and
[`identity/SOUL.md`](identity/SOUL.md) for the principles and decision
framework Max operates under on every campaign.

## Repository layout

```
identity/           Max's identity and operating principles (source of truth)
campaigns/          Per-vertical campaign briefs and follow-up sequences
domains/            Sending-domain health tracking (bounce/complaint rates, warm-up status)
scoring/            Reply scoring rubric and escalation routing to account managers
```

## Current priority

Shipping & logistics outreach is the first vertical in the go-to-market
sequence — see [`campaigns/shipping-logistics/`](campaigns/shipping-logistics/) —
before expanding to payment processing and marketing.

## Before launching any campaign

Per Max's decision framework, confirm all four before a send goes out:

1. Which vertical/service is being pitched (never mix offers in one send)
2. Which domains are warmed and healthy enough to use — see
   [`domains/domain-health-tracker.md`](domains/domain-health-tracker.md)
3. The follow-up cadence — see the vertical's `sequence.md`
4. How a reply gets scored and routed — see
   [`scoring/reply-scoring-rubric.md`](scoring/reply-scoring-rubric.md)
