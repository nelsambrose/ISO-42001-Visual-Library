# Project Context

This file provides context for AI assistants and contributors 
working with this repository.

---

## What this project is

This is a visual learning library for ISO/IEC 42001:2023, 
the international standard for AI Management Systems (AIMS). 
It contains reference material and infographic cards created
to help people learn, understand and retain the standard.

It is not a code project. It is an image library with 
supporting documentation.

---

## Who built it and why

Built by Nelson Ambrose, Head of Software Development and 
AI Governance Lead at Pepper Ireland. Nelson is building 
deep expertise in AI governance frameworks as part of a 
career trajectory toward Chief AI Officer roles.

The library was built because high quality visual resources 
for ISO 42001 do not exist publicly. Most available materials 
are either too dense, too shallow, or designed for people 
who already know the standard.

---

## Design philosophy

Multiple card layers per topic:

**Reference catalogue:** Neutral source facts, key messages,
definitions and reusable base material. This is the canonical
content source for each topic.

**Funny infographic cards:** Humorous visual versions based on
the matching reference topic. They should be memorable and
engaging without distorting the facts.

**Professional infographic cards:** Polished, business-ready
visual versions based on the matching reference topic. They
should be suitable for briefings, audit preparation and
professional sharing.

**Funny simple memory cards:** Minimal cards that use one strong
visual hook to help people remember the clause number and core
keyword. They are intentionally simpler than the full infographics
and are not intended to explain every sub-clause. Stored in
`cards/funny/simple/`.

The multi-layer approach is deliberate. How you learn something,
how you recall it quickly, and how you look it up later are
different problems that need different solutions.

---

## Folder structure

```
ISO-42001-Visual-Library/
│
├── README.md
├── CHANGELOG.md
├── CONTEXT.md
│
└── cards/
├── annex-a/
│   ├── overview/
│   ├── domain/ (professional/ + funny/)
│   └── control/ (professional/ + funny/)
├── audit/ (reference/ + professional/ + funny/)
├── about/
├── reference/
├── professional/
│   ├── *.png (main infographic cards)
│   └── simple/ (clause-04-....png etc.)
├── funny/
│   ├── *.png (main infographic cards)
│   ├── simple/ (clause-04-....png etc.)
│   ├── expanded/
│   └── archive/
└── archive/ (top-level)
```

---

## File naming conventions

Use topic slugs as filenames. Slugs must be lowercase kebab-case,
with no spaces, and should be descriptive enough to stand alone.

Use the same basename for the same topic across folders where
applicable:

```text
cards/reference/ai-risk.md
cards/funny/ai-risk.png
cards/professional/ai-risk.png
```

For clause-based topics, use two-digit clause numbers:

```text
cards/reference/clause-04-context-of-the-organisation.md
cards/funny/clause-04-context-of-the-organisation.png
cards/professional/clause-04-context-of-the-organisation.png
```

For Annex A domain cards, use the same basename across the
professional and funny folders:

```text
cards/annex-a/domain/professional/governance.png
cards/annex-a/domain/funny/governance.png
```

---

## Image standards

All images are PNG format, portrait orientation unless 
otherwise specified. Landscape images are used only for 
GitHub banner or header purposes.

Reference catalogue entries: neutral, factual and reusable.
They should contain source facts, definitions, key messages and
any notes needed to generate matching visual versions.

Funny infographic cards: visual, engaging and humorous. They may
include cartoon characters or playful framing. Content must remain
accurate regardless of tone.

Professional infographic cards: polished, restrained and suitable
for sharing with colleagues, auditors and senior stakeholders.

---

## Content accuracy

Published cards must be verified for accuracy against
ISO/IEC 42001:2023. If adding new cards, accuracy 
must be verified before committing.

Key accuracy principles:
- Sub-clause numbers must be correct
- Bullet point content must reflect the actual standard
- No invented requirements or controls
- Humorous framing is acceptable, inaccurate content is not

---

## Current status

The library is private while being built out. 
It will be made public once ISO 42001 coverage is 
considered substantially complete.

The repo currently contains project documentation, reference catalogue
entries, funny and professional infographic cards for the overview and
Clauses 4 to 10, Annex A overview and domain image sets, an Audit
Readiness mini-deck (audit-01 to audit-05, professional and funny), an
author overview card, and archive variants for additional card versions.

The repo is actively maintained and growing. 
See CHANGELOG.md for current contents and planned additions.

---

## Working with this repo

If you are an AI assistant helping with this project:

- Do not modify image files
- Do not rename existing files without instruction
- When adding new entries to CHANGELOG.md, follow the 
  existing format exactly
- When updating README.md card tables, keep the formatting
  consistent and embed image cards directly when available
- Keep the documented `cards/annex-a/`, `cards/audit/`, `cards/about/`,
  `cards/archive/`, `cards/reference/`, `cards/funny/`, and
  `cards/professional/` structure unless instructed otherwise
- The content is ISO 42001 specific: do not introduce 
  content from other frameworks without instruction
