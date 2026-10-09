# Changelog

All notable additions to the ISO 42001 Visual Library 
are documented here.

The format follows [Keep a Changelog](https://keepachangelog.com).

---

## [Unreleased]

Cards in development:
- Additional reference topics: certification, people impact, ISO 42001 vs ISO 27001, EU AI Act alignment, common failure modes, and AI policy templates

### Removed

- `CLAUDE.md` (internal AI-assistant workflow instructions, not intended as public project documentation). Project context for contributors and assistants remains in `CONTEXT.md`.

---

## [0.3.0] - 2026-09-08

### Changed

- **Licence changed from CC BY 4.0 to MIT.** All cards are now free to use for any purpose, personal or commercial, with attribution appreciated but no longer required. `LICENSE.md` replaced with the standard MIT text; licence references updated across `README.md`, `index.html` (badge, footer, FAQ answer, and `ImageGallery` JSON-LD), all 80 `sitemap.xml` image entries, `llms.txt`, and `CONTEXT.md`. This resolves a contradiction where the README claimed MIT while the badge, licence section, and `LICENSE.md` all stated CC BY 4.0.
- `README.md` per-card descriptions added to all 31 card topics — Clauses 4–10, the four Annex A domains, controls A.2–A.10, the five audit readiness cards, and the six AI principles — adding roughly 1,065 words of descriptive text to what were previously bare image tables.

### Added

- `README.md` "Recommended learning path" — a 19-step ordered route through the library, grouped from foundations through the mandatory clauses, Annex A, audit readiness, and the underlying AI principles.
- `README.md` "Browse by category" — a table of all eight card groups with verified card counts.

### Fixed

- `README.md` table of contents pointed at a non-existent `#how-to-use-it` anchor and omitted half the gallery sections. Rebuilt against the actual headings.

---

## [0.2.1] - 2026-05-25

### Added

- `404.html` — custom GitHub Pages error page matching site colour scheme, with a CTA back to the gallery and `noindex` tag to keep it out of search results.
- `og:locale` meta tag (`en_GB`) added to `index.html` for explicit language/region signalling to social media scrapers.
- `BreadcrumbList` Schema.org JSON-LD block added to `index.html` alongside the existing `ImageGallery` block, enabling breadcrumb display in Google search results.

---

## [0.2.0] - 2026-05-25

### Added

- GitHub Pages site (`index.html` at repo root) — full card gallery with semantic `<figure>`/`<figcaption>` markup, sticky navigation, responsive layout, Open Graph tags, Twitter Card tags, and Schema.org `ImageGallery` structured data.
- Image sitemap (`sitemap.xml`) listing all 80 current cards with titles, captions, and CC BY 4.0 licence URLs (since updated to MIT in 0.3.0; the library is now MIT-licensed), served from the GitHub Pages domain for proper search engine attribution.
- `robots.txt` — allows all crawlers and explicitly declares the sitemap URL.
- SVG favicon (`favicon.svg`) — dark navy rounded square with white "ISO" text, consistent with the site colour scheme.
- `.nojekyll` — disables Jekyll processing so the static HTML is served as-is.
- AI Principles cards (professional and humorous) for Principle-01 through Principle-06: Fairness, Transparency, Accountability, Human Oversight, Privacy, and Safety and Reliability.
- Reference entries for all six AI Principles cards.

### Changed

- All 80+ image filenames renamed following SEO best practices — keyword-rich, hyphenated, prefixed with `iso-42001-`, and suffixed with content type (e.g. `-professional-infographic.png`, `-humorous-simple-memory-card.png`, `-archive-variant.png`). Renamed across 21 batches covering professional, funny, simple, Annex A, audit, AI principles, and archive cards.
- `README.md` alt tags standardised across all sections to descriptive `ISO 42001 [Topic] - [Style] [Type]` format.
- `README.md` section headings prefixed with "ISO 42001" throughout.
- `README.md` captions added below each image group for context and SEO signal.
- `README.md` prominent gallery link added pointing to the GitHub Pages site.
- GitHub Pages source migrated from `/docs` folder to repo root so `cards/` is served directly from the `nelsambrose.github.io` domain, enabling proper same-domain image sitemap attribution.
- `CONTEXT.md` image path references updated to match renamed files.

---

## [0.1.5] - 2026-05-08

### Added

- Audit Readiness mini-deck: professional and funny infographic cards for audit-01 through audit-05 in `cards/audit/professional/` and `cards/audit/funny/`.
- Reference content for all five audit cards in `cards/audit/reference/`.
- `cards/about/` folder with author overview card moved from `cards/funny/`.
- `cards/archive/` folder consolidating all prior `other/` folders from `cards/funny/other/` and `cards/professional/other/`, plus three additional variant cards from `cards/other/`.

### Changed

- Renamed three archive variant cards to follow kebab-case naming conventions based on card content (`audit-01-what-an-auditor-actually-looks-for-2.png`, `audit-01-what-an-auditor-actually-looks-for-3.png`, `audit-02-evidence-vs-good-intentions-2.png`).
- Updated all image alt text in `README.md` to use the `ISO/IEC 42001` format for improved SEO and discoverability, covering overview, clause, Annex A domain, Annex A control, audit, and archive image tables.
- Updated Audit Readiness coverage table link text from `Reference` to `View Reference`.
- Added `## About the Author` section to `README.md`.
- Updated `CONTEXT.md` folder structure and current status to reflect new `cards/audit/`, `cards/about/`, and `cards/archive/` folders.

---

## [0.1.4] - 2026-05-04

### Added

- Simple funny memory cards for Clauses 4 to 10.
- `cards/funny/simple/` folder for clause number and keyword recall.

### Changed

- Updated README to explain the simple memory card layer and show the new memory card gallery.
- Updated project context to document the simple memory card purpose.

---

## [0.1.2] - 2026-05-04

### Added

- Reference catalogue entry for Clause 5: Leadership.
- Reference catalogue entry for Clause 6: Planning.
- Reference catalogue entry for Clause 7: Support.
- Reference catalogue entry for Clause 8: Operation.
- Reference catalogue entry for Clause 9: Performance Evaluation.
- Reference catalogue entry for Clause 10: Improvement.

### Changed

- Updated README current contents table so Clauses 5 to 10 link to their reference catalogue entries.
- Removed completed Clause 5 to 10 reference work from planned coverage.

---

## [0.1.1] - 2026-05-04

### Added

- Funny infographic cards for the overview and Clauses 4 to 10.
- Professional infographic cards for the overview and Clauses 4 to 10.
- Additional funny Clause 8 Operation variant using the Mission Control framing.
- README gallery that displays the card images directly on the GitHub repository page.

### Changed

- Replaced the old `reference/`, `memory/`, and `deep_dives/` convention with `cards/reference/`, `cards/funny/`, and `cards/professional/`.
- Moved existing reference material into `cards/reference/`.
- Standardised topic filenames so matching reference, funny, and professional versions can share the same basename across folders.

---

## [0.1.0] - 2026-05-04

### Added

**Project documentation**
- README with current contents and planned coverage
- CONTEXT guidance for contributors and AI assistants
- CHANGELOG tracking current and planned additions

**Reference catalogue entries**
- Overview: Full ISO 42001 overview with PDCA structure, 
  clause summary, AI principles and certification path
- Clause 4: Context of the Organisation

---

*This library is actively maintained and growing.*
