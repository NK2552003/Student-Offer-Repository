# Contributing

Student promotions change quickly. Contributions should make the catalog safer
and more accurate, not merely larger.

By contributing, you agree to follow the [Code of Conduct](CODE_OF_CONDUCT.md)
and license your contribution under the repository's [CC BY 4.0 license](LICENSE.md).

## Ways to contribute

- Propose a new verified student offer.
- Correct price, duration, eligibility, country, verification, or billing data.
- Move an ended promotion to the archive and document its replacement.
- Repair a direct official link.
- Improve regional coverage, wording, accessibility, or maintenance tooling.

Use the supplied issue forms for a proposal or correction. A pull request is
welcome when you can make and verify the change directly.

## Add an offer only when

- The provider has an official offer, pricing, help, terms, education, or
  authoritative partner page.
- The benefit is student- or education-specific, or it is a learner program
  included because it replaced a student license.
- Eligibility, duration, region, verification, and renewal behavior can be
  described honestly.
- The offer was checked on the date included in the contribution.

## Required data

Use the matching table format in the target file. An active listing must convey
these canonical fields:

```md
| Provider | Benefit | Duration | Eligibility | Region | Verification | Card required | Auto-renewal | Official source | Checked YYYY-MM-DD |
```

Use `Unknown — confirm at activation` instead of guessing. See
[docs/OFFER-SCHEMA.md](docs/OFFER-SCHEMA.md) for definitions and
[docs/STYLE-GUIDE.md](docs/STYLE-GUIDE.md) for writing rules.

## Evidence order

1. Provider terms or current official offer page.
2. Provider help center, pricing, or education documentation.
3. An authoritative partner page, such as GitHub Education.
4. A reputable secondary source for discovery or context only—never as the
   sole proof of an active offer.

Do not copy large blocks of provider text. Summarize the relevant facts and
link the source.

## Do not add

- Referral, affiliate, shortened, or user-specific links.
- “Lifetime” accounts sold by third parties.
- VPN or location-bypass instructions.
- Methods to create fake school emails or documents.
- Private student, account, identity, or payment information.
- Expired offers without a clear **Ended** label.
- Ordinary free tiers presented as exclusive student deals.
- Marketing claims that cannot be verified from authoritative sources.

## Local workflow

1. Create a branch from the current default branch.
2. Open the official source and verify the complete offer.
3. Edit the smallest appropriate catalog or documentation file.
4. Add or update the source trail in `SOURCES.md` when useful.
5. Add a short `CHANGELOG.md` entry for a material student-facing change.
6. Check Markdown, relative links, and changed external links.
7. Open a pull request and complete every relevant checklist item.

Example commands when the corresponding tools are installed:

```bash
npx markdownlint-cli2 "**/*.md"
lychee --no-progress "./**/*.md"
```

GitHub Actions also runs these checks after a pull request is opened.

## Updating an existing offer

1. Confirm the activation path still exists.
2. Re-check price, duration, deadline, countries, school level, verification,
   payment method, and renewal terms.
3. Update the checked date only after reviewing those material fields.
4. If new activation ended, move the offer to
   `offers/ENDED-OFFERS.md` instead of silently deleting it.
5. Explain material changes in the pull request and changelog.

## Pull-request review

Maintainers may ask for a stronger source, clearer regional wording, or a
billing warning. A working URL alone is not enough: the page must support the
specific catalog claim.

Pull requests should be focused. Separate unrelated offers or repository-policy
changes when that makes review safer. Maintainers may close promotional,
duplicative, unverifiable, or unsafe submissions.

## Conflicts of interest

If you work for, represent, receive compensation from, or have an affiliate
relationship with a provider, disclose it in the issue or pull request. A
disclosure does not automatically disqualify a contribution, but hidden
promotion may be removed.

## Security and conduct

Use [SECURITY.md](SECURITY.md) for malicious links, leaked secrets, or private
data. Never put sensitive information in a public issue. Community behavior is
governed by [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).
