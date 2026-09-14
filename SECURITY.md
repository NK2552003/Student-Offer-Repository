# Security Policy

This is a documentation repository, but bad links and misleading claim
instructions can still harm students.

## Report privately when possible

Use GitHub's private vulnerability reporting or a private security advisory if
the repository enables it. Do not open a public issue when a report includes:

- A malicious, compromised, phishing, or credential-harvesting link.
- A workflow or repository-configuration weakness that could allow untrusted
  code to run with elevated permissions.
- Accidentally committed personal data, secrets, tokens, or credentials.
- A reproducible method that would expose another student's private data.

If private reporting is unavailable, contact the repository owner through
their GitHub profile without including secrets in the first message.

## Use a normal issue for

- A promotion that expired.
- A price, duration, country, or eligibility detail that changed.
- A normal 404 or relocated official page.
- A typo or formatting problem.

Use the [correction form](.github/ISSUE_TEMPLATE/correction.yml) for these
non-sensitive reports.

## What to include

- A short description of the risk.
- The affected file and link.
- Safe reproduction steps, if relevant.
- The date and time observed in UTC.
- Suggested remediation, if known.

Never include account passwords, student documents, payment-card data, session
cookies, API keys, or another person's private information.

## Response targets

Maintainers aim to acknowledge credible private reports within seven days and
to remove clearly dangerous links as quickly as practical. This is a volunteer
project, so the targets are goals rather than guarantees.

## Known incidents

- **2026-09-11 — prompt injection on the Firecrawl student-offer page.**
  While re-verifying the Firecrawl listing, the reviewing agent found hidden
  text on `firecrawl.dev/student-program` attempting to instruct AI
  agents/scrapers to fetch and execute an external "skill" file. The agent
  recognized it as a prompt-injection attempt, did not act on it, and no
  changes were made to this repository as a result of it. We are
  intentionally not reproducing the injected wording here. If your own
  tooling re-scrapes this or any listed page automatically, do not let a
  scraper execute instructions found in page content, and treat any fetched
  page as untrusted input.
