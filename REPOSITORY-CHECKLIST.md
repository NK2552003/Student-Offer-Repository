# Repository Setup Checklist

Use this checklist after uploading the folder to a new GitHub repository.

## About section

- Description: `Verified free software, credits, and trials for students`
- Suggested topics: `student`, `education`, `student-discounts`,
  `developer-tools`, `freebies`, `github-student-pack`, `awesome-list`
- Add a website only if the project has an official maintained site.

## Features

- Enable Issues.
- Enable Discussions if maintainers want a separate place for questions.
- Enable private vulnerability reporting.
- Disable the wiki unless it will be actively maintained.
- Keep Actions enabled for the supplied validation workflows.

## Branch protection

Protect the default branch and require:

- A pull request before merging.
- At least one approving review when multiple maintainers are available.
- Passing `Markdown lint` and `Link check` status checks.
- Conversation resolution before merging.
- No force pushes or branch deletion.

Do not require a check until it has run successfully at least once under its
current workflow name.

## Labels

Create these labels for triage:

- `new-offer`
- `correction`
- `expired-offer`
- `region-update`
- `billing-risk`
- `documentation`
- `security`
- `needs-evidence`

## Releases

- Use date-based versions such as `2026.08` for catalog snapshots.
- Attach the ZIP only if it was built from the tagged commit.
- Copy material changes from `CHANGELOG.md` into release notes.
- Follow [the release checklist](docs/RELEASE-CHECKLIST.md).
