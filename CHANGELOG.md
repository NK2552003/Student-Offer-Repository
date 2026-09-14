# Changelog

Material catalog and repository changes are recorded here. Offer providers may
change terms between repository releases.

## 2026-09-11

Six-agent verification pass across the catalog (AI/research, entertainment/
trials, design/CAD, dev/cloud, productivity/data, and new-offer discovery),
followed by one consolidated edit pass.

### Renamed, rebranded, or moved

- Adobe Creative Cloud All Apps → **Creative Cloud Pro (20+ apps)**; student
  price is now US$19.99/mo in year one, rising to US$39.99/mo in year two.
- Notion "Plus" education plan → **Education Plan**; a separate free tier for
  student organizations (unlimited members) now exists; K–12 is explicitly
  excluded from the Education Plan.
- Coda → rebranded to **Superhuman Docs**; `coda.io/for/education` now
  redirects and current education terms are unconfirmed — flagged for
  re-verification.
- Altium Designer Pro → now branded plain **Altium Designer**.
- Cisco Packet Tracer's course host rebranded from Skills for All to
  **NetAcad**; URL updated.
- SAS academic page now lists **Viya for Learners** and **Viya Workbench for
  Learners**; OnDemand for Academics is no longer shown there.
- JMP Student Edition description softened from "full statistical software"
  to JMP's own framing, an "easy-to-use version."
- GitHub Student Developer Pack: GitHub's docs no longer list GitHub Pro as a
  Pack-exclusive benefit (many former Pro features are now free for
  everyone); the Pack's headline benefit is reframed around **Copilot
  Student**.

### URL fixes (redirects/migrations)

- Claude for Education → `claude.com/solutions/education`.
- Adobe Substance 3D → `substance3d.adobe.com/education/`.
- Ansys Student → `ansys.synopsys.com/academic/students` (Synopsys–Ansys
  acquisition).
- SketchUp download → `sketchup.trimble.com/download`.
- Cisco Packet Tracer → `netacad.com/courses/packet-tracer`.
- Databricks student resources → `databricks.com/university`.
- Lucid educational account → `lucid.co/solutions/education` (old help-article
  URL now 403s).

### Added

- Claude for Teachers (K–12) and Claude for Scientists (academic/nonprofit
  researchers).
- A "Newly verified free plans" section: **Affinity** (by Canva, permanently
  free unified design app) and **GitHub Copilot (Student)** as student-
  targeted offers; plus 16 confirmed open free tiers useful to students
  (Obsidian, Zotero, Overleaf, Supabase, Vercel Hobby, Warp, Postman, AWS
  Free Tier, Spline, Rive, DaVinci Resolve, Otter.ai, Grammarly, Todoist,
  Prezi, and Mistral "Vibe").
- A "Needs manual verification" section covering claims that could not be
  confirmed on an official page: OpenAI ChatGPT Plus for students (reported
  4 free months, US), Bentley Education, Esri ArcGIS for students, Gamma,
  Quizlet, and xAI Grok.
- DigitalOcean's $200 Student Pack credit to `ENDED-OFFERS.md` (ended around
  August 2026; the redemption page now 404s).
- Enrichment details: Framer (~1,000 AI credits/month, re-verify roughly
  every 11 months), Linear (100% student discount vs. 75% for staff;
  excludes high-school/for-profit/online-only institutions), Red Hat
  (no-cost subscription covers up to 16 systems, individuals only),
  Databricks (Free Edition is perpetually free).
- A security note (`SECURITY.md`) documenting a prompt-injection attempt
  found embedded in the Firecrawl student-offer page during re-verification.
  It was not acted on and no repository content was changed because of it.

### Corrected or downgraded

- The Microsoft 365 "12 months Premium on us" banner was not present on the
  education page during the 2026-09-11 recheck; the claim is downgraded to
  region/session-dependent across `FREE-STUDENT-OFFERS.md`,
  `TRIALS-CREDITS.md`, `ENDED-OFFERS.md`, and `INDIA.md`. Treat it as
  inactive unless you see a zero-price checkout yourself.

### Flagged for manual recheck (link live, terms unverified by automation)

Figma, Autodesk, Unreal Engine, Twinmotion, Canva Education, PTC Creo,
JetBrains, Google Cloud Skills, GitLab for Education, Oracle Academy Cloud,
Replit for Education, Tableau, Microsoft college-student pricing, YouTube
Premium Student (JS-only page), and Amazon Prime US/UK (503 bot-block).
These are marked **(unverified 2026-09-11)** or **(verify in-browser)** in
the relevant tables rather than removed, since the links themselves are
still live.

## 2026-08-21

### Catalog

- Created the structured student-offer repository.
- Added direct free plans, credits, trials, GitHub Student Developer Pack
  benefits, an India-focused guide, verification guidance, and billing-safety
  notes.
- Replaced the older “Google Gemini student year ended” understanding with
  Google's new offer announced on 2026-08-19:
  - Google AI Pro free for one year for eligible U.S. college students.
  - Google AI Plus free for one year for eligible students in 140+ markets
    outside the U.S., subject to listed country exclusions.
  - Redemption deadline: 2026-12-31.
  - Payment method and auto-renewal warning documented.
- Marked the Handshake Google AI Plus promotion as a separate U.S./Canada
  route, not the worldwide route students should use.
- Marked Cursor, Windsurf, the previous Gemini offer, and DigitalOcean's
  earlier GitHub Pack redemption window as ended rather than active.
- Expanded the active catalog with verified education programs from Adobe
  Substance 3D, Onshape, Ansys, Siemens, PTC, Altium, GitLab, SAP, Databricks,
  Oracle, Lucid, Coda, Craft, Airtable, Whimsical, Axure, JMP, EViews, Cisco,
  Red Hat, Google Workspace, Replit, and Microsoft developer tooling.
- Added general professional trials that are useful to students but are not
  student-exclusive, with payment and auto-renewal warnings.
- Added the inventory-limited GitHub Foundations Certification voucher.
- Clarified that Microsoft's current “12 months on us” education banner can
  route to a paid 50%-off plan, so the final checkout must show a zero price.
- Expanded the India guide with globally published programs that Indian
  students can test through official verification flows.

### Repository

- Added a CC BY 4.0 license, disclaimer, citation metadata, governance,
  contributor guidance, support policy, security policy, and code of conduct.
- Added offer-schema, style, maintenance, release, and GitHub setup guides.
- Added structured issue forms and a pull-request checklist.
- Added Markdown linting, weekly link checking, and Dependabot configuration
  for GitHub Actions.
