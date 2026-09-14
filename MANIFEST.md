# Repository Manifest

This file explains what is included in the distribution and which files should
be customized after publishing to GitHub.

## Student-facing content

| Path | Purpose |
| --- | --- |
| `README.md` | Main catalog index, status legend, and project overview |
| `offers/FREE-STUDENT-OFFERS.md` | Free plans available while eligible |
| `offers/TRIALS-CREDITS.md` | Limited periods, credits, and usage allowances |
| `offers/GITHUB-STUDENT-PACK.md` | Organized GitHub Student Developer Pack benefits |
| `offers/INDIA.md` | India-relevant availability and local cautions |
| `offers/ENDED-OFFERS.md` | Ended or replaced promotions kept for clarity |
| `guides/CLAIM-GUIDE.md` | Safe student-verification and claim steps |
| `guides/BILLING-SAFETY.md` | Payment, renewal, and cancellation guidance |
| `SOURCES.md` | Official and authoritative research trail |

## Contribution and community files

| Path | Purpose |
| --- | --- |
| `CONTRIBUTING.md` | Evidence, privacy, writing, and pull-request rules |
| `CODE_OF_CONDUCT.md` | Community behavior and enforcement policy |
| `SECURITY.md` | Private reporting for harmful links, secrets, or data leaks |
| `SUPPORT.md` | Repository support boundaries and provider escalation |
| `GOVERNANCE.md` | Maintainer responsibilities and decision process |
| `CONTRIBUTORS.md` | Optional public contributor acknowledgements |
| `.github/PULL_REQUEST_TEMPLATE.md` | Review checklist for proposed changes |
| `.github/ISSUE_TEMPLATE/offer.yml` | Structured new-offer proposal form |
| `.github/ISSUE_TEMPLATE/correction.yml` | Structured correction and expiry form |
| `.github/ISSUE_TEMPLATE/config.yml` | Issue-template behavior |

## Maintenance and publishing files

| Path | Purpose |
| --- | --- |
| `docs/OFFER-SCHEMA.md` | Canonical catalog fields and status vocabulary |
| `docs/STYLE-GUIDE.md` | Markdown, language, links, privacy, and accessibility |
| `docs/MAINTENANCE.md` | Review cadence and status-change procedure |
| `docs/RELEASE-CHECKLIST.md` | Content, quality, version, and archive checks |
| `REPOSITORY-CHECKLIST.md` | GitHub settings, labels, protection, and release setup |
| `ROADMAP.md` | Current and future maintenance priorities |
| `CHANGELOG.md` | Material catalog and repository changes |
| `.github/workflows/markdownlint.yml` | Markdown validation on changes |
| `.github/workflows/link-check.yml` | Link validation on changes and weekly schedule |
| `.github/dependabot.yml` | Monthly GitHub Actions update proposals |
| `.markdownlint.json` | Markdown lint policy |
| `.editorconfig` | Cross-editor text formatting defaults |
| `.gitignore` | Local editor, cache, build, and environment exclusions |

## Legal and metadata files

| Path | Purpose |
| --- | --- |
| `LICENSE.md` | CC BY 4.0 grant and exclusions |
| `DISCLAIMER.md` | Accuracy, billing, independence, and trademark notice |
| `CITATION.cff` | Citation metadata for GitHub and research tools |
| `MANIFEST.md` | Distribution inventory and customization notes |

## Customize after publishing

- Add the final repository URL to `CITATION.cff` as `repository-code`.
- Add known maintainers to GitHub's access controls; create `CODEOWNERS` only
  after the correct handles are confirmed.
- Enable private vulnerability reporting and branch protection.
- Create the labels listed in `REPOSITORY-CHECKLIST.md`.
- Run the supplied workflows once before making them required checks.
