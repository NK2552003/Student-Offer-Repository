# Maintenance Guide

## Review cadence

Review high-impact or deadline-driven offers monthly. Review the broader
catalog at least once per quarter when maintainer capacity permits.

Prioritize:

1. Offers with an upcoming redemption deadline.
2. Offers requiring a payment method or automatic renewal.
3. High-traffic AI, cloud, developer, design, and productivity programs.
4. Entries previously reported as unavailable.
5. Rows with the oldest checked dates.

## Verification procedure

1. Open the exact official source linked in the row.
2. Confirm that a student can still reach an application or activation path.
3. Re-check benefit, duration, eligibility, region, verification, card, and
   renewal terms.
4. Follow links to current terms when the landing page is ambiguous.
5. Update the row's checked date only after reviewing the material fields.
6. Record a material change in `CHANGELOG.md`.
7. Run Markdown and link checks before merging.

A successful HTTP response alone does not prove that an offer is active.

## Status changes

- If terms changed, update the active row and changelog.
- If activation is temporarily unclear, add a caution and open an issue.
- If new activation ended, move the entry to `offers/ENDED-OFFERS.md`.
- If a program was replaced, link the replacement and keep a short historical
  explanation.
- If a page is malicious or compromised, follow `SECURITY.md` and remove the
  link promptly.

## Link-check triage

- `404` or `410`: search the provider's official site for a moved page.
- `403` or bot challenge: verify manually in a normal browser before changing
  the catalog.
- Redirect: replace with the final canonical official URL when stable.
- Timeout: retry later and verify through provider navigation.
- Domain change: confirm ownership and program continuity before updating.

## Release rhythm

Use date-based releases such as `2026.08`. A release is a reviewed snapshot,
not a guarantee that every external offer remains unchanged afterward.

See [RELEASE-CHECKLIST.md](RELEASE-CHECKLIST.md) for the publication procedure.
