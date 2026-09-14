# Offer Schema

Every active-offer row should let a student answer: “What do I get, can I get
it, how long does it last, and could it charge me later?”

## Canonical fields

| Field | Required | Rule |
| --- | ---: | --- |
| Provider | Yes | Use the provider's public product or organization name |
| Benefit | Yes | State the concrete plan, credit, product, or allowance |
| Duration | Yes | Use a fixed period, `while eligible`, or an honest unknown |
| Eligibility | Yes | State school level, age, enrollment, or other known criteria |
| Region | Yes | Name countries, worldwide availability, or `check region` |
| Verification | Yes | School email, document review, SheerID, GitHub, institution, or unknown |
| Card required | Yes | `Yes`, `No`, or `Unknown — confirm at activation` |
| Auto-renewal | Yes | State what happens after the free benefit |
| Official source | Yes | Link to the provider or authoritative program page |
| Checked | Yes | Use an ISO date: `YYYY-MM-DD` |

Some topic-specific tables use shorter headers. They must still include the
same facts in the row or nearby notes.

## Status vocabulary

- **Free while eligible** — no fixed end date is published; re-verification
  may be required.
- **Free period** — premium access ends after a stated duration.
- **Credit** — a balance or usage allowance with its own expiry and overage
  rules.
- **Institution-gated** — a school must purchase, sponsor, or join the program.
- **Discount after trial** — a free period becomes a lower student price.
- **Check region** — country, institution, or rollout restrictions apply.
- **Ended** — students should not expect new activations.

## Writing rules

- Describe benefits precisely; avoid “huge,” “best,” or “unlimited” unless the
  official source uses and defines the term.
- Distinguish individual access from institution-provided access.
- State a redemption deadline separately from benefit duration.
- If a payment method is required, state whether the offer renews and at what
  kind of price when known.
- Use `Unknown — confirm at activation` instead of inferring a billing term.
- Link directly to official sources, not tracking or affiliate redirects.
- Do not copy long passages from provider pages.

## Example

```md
| Example Provider | Pro plan | 12 months | Enrolled university students | Selected countries | School email or documents | Yes | Converts to paid plan unless cancelled | [Official terms](https://example.com/student) | 2026-08-21 |
```

The example is structural only and is not a real offer.
