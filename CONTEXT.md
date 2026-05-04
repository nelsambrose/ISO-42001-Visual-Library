# Project Context

This file provides context for AI assistants and contributors 
working with this repository.

---

## What this project is

This is a visual learning library for ISO/IEC 42001:2023, 
the international standard for AI Management Systems (AIMS). 
It contains infographic cards created to help people learn, 
understand and retain the standard.

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

Two visual layers per topic:

**Reference cards:** Dense, comprehensive, accurate. 
For looking things up, audit preparation, briefing colleagues. 
Created using ChatGPT image generation.

**Memory cards:** Minimal, visual, memorable. 
For learning the standard for the first time or retaining 
key concepts. Created using Gemini image generation.

**Deep dive cards:** Go beyond the overview into specific 
aspects: individual clauses, controls, principles, 
certification, failure modes, framework connections.

The two-layer approach is deliberate. How you learn something 
and how you look it up later are different problems that need 
different solutions.

---

## Folder structure

```
ISO-42001-Visual-Library/
│
├── README.md          (public-facing introduction)
├── CHANGELOG.md       (history of all additions)
├── CONTEXT.md         (this file)
│
├── reference/         (detailed reference cards)
├── memory/            (memorable visual cards)
└── deep_dives/        (specific topic deep dives)
```

---

## File naming conventions

Reference cards: `clause_04_context.png`, `clause_05_leadership.png`
Memory cards: `clause_04.png`, `01_pdca_plan.png`
Deep dives: `annex_a_controls_part1.png`, `getting_certified.png`
Overviews: `00_overview.png`

Always use lowercase, hyphens or underscores, no spaces.
Always use two-digit numbering for ordered files (01, 02 etc).

---

## Image standards

All images are PNG format, portrait orientation unless 
otherwise specified. Landscape images are used only for 
GitHub banner or header purposes.

Reference cards: professional style, dark navy or white 
background, clean typography, no cartoon elements.

Memory cards: visual, engaging, may include cartoon characters 
or humorous elements. Content must remain accurate regardless 
of tone.

---

## Content accuracy

All cards have been verified for accuracy against 
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

The repo is actively maintained and growing. 
See CHANGELOG.md for current contents and planned additions.

---

## Working with this repo

If you are an AI assistant helping with this project:

- Do not modify image files
- Do not rename existing files without instruction
- When adding new entries to CHANGELOG.md, follow the 
  existing format exactly
- When updating README.md content tables, keep the 
  formatting consistent
- Always confirm before making any structural changes 
  to the folder layout
- The content is ISO 42001 specific: do not introduce 
  content from other frameworks without instruction
