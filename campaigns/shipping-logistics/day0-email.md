# Day 0 Email — Shipping & Logistics

Two variants testing different angles on the same CTA (free rate audit).
Per the testing plan, track opens/replies per domain and per segment before
promoting a winner.

---

## Variant A — Cost angle

**Subject lines (A/B within the variant):**
- A1: Quick question about {{Company}}'s shipping rates
- A2: Are you overpaying on shipping right now?

**Body:**

```
Hi {{FirstName}},

Quick one — when's the last time someone actually checked whether
{{Company}} is getting a good deal on shipping?

We run a free rate audit for e-commerce brands: send over your last
2-3 months of carrier invoices, and we'll tell you straight —

- If there's money to save, we'll show you exactly where.
- If your rates are already solid, we'll tell you that too.

No pitch, no obligation either way. It's a 10-minute look at invoices
you already have.

Worth sending over?

{{SenderName}}
All In 1 Commerce
```

---

## Variant B — Reliability / process angle

**Subject lines (A/B within the variant):**
- B1: Is your shipping process actually working for {{Company}}?
- B2: Rates aside — is your fulfillment keeping up?

**Body:**

```
Hi {{FirstName}},

Most brands we talk to aren't just worried about shipping cost — it's
reliability, and whether the process scales as order volume grows.

We offer a free audit: send your last 2-3 months of carrier invoices
and we'll tell you honestly where things stand — savings opportunities,
and whether the setup itself needs streamlining, not just cheaper rates.

If everything's already dialed in, we'll say so. No obligation.

Mind sending over your recent invoices?

{{SenderName}}
All In 1 Commerce
```

---

## Notes

- Keep both variants to a single clear CTA: send recent carrier invoices.
  Don't mention the broader 7-solution subscription in this touch — that's
  the follow-up conversation once a prospect engages (see `brief.md`).
- `{{Company}}`, `{{FirstName}}`, `{{SenderName}}` are merge fields —
  fill in from whatever personalization data the sending platform supports.
- Plain-text, short, no heavy formatting or links in Day 0 — cold sends
  with links/HTML from unwarmed domains hurt deliverability.
