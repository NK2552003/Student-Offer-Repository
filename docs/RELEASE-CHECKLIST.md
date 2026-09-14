# Release Checklist

## Content

- [ ] Review every offer with a near-term deadline.
- [ ] Confirm active and ended offers are in the correct files.
- [ ] Check new or changed billing and auto-renewal warnings.
- [ ] Confirm region and school-level language is supported by sources.
- [ ] Update the repository's `Last web review` date.
- [ ] Add material changes to `CHANGELOG.md`.

## Quality

- [ ] Run Markdown lint.
- [ ] Run the automated link check and manually review bot-blocked pages.
- [ ] Check internal relative links.
- [ ] Confirm issue forms and workflow YAML parse correctly.
- [ ] Remove private data, referral parameters, and temporary files.
- [ ] Confirm `CITATION.cff` and license metadata match the release.

## Version and archive

- [ ] Choose a date-based version such as `2026.08`.
- [ ] Update the version and release date in `CITATION.cff`.
- [ ] Tag the reviewed commit.
- [ ] Build the ZIP from that exact tag or commit.
- [ ] Test the ZIP before attaching it to a release.
- [ ] Include the catalog review date and important deadlines in release notes.

## After publishing

- [ ] Verify the release and ZIP are downloadable.
- [ ] Open the README and a sample of catalog links from the published repo.
- [ ] Triage new corrections and link failures.
