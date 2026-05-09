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
visual versions based on the matching reference topic.
They should be suitable for briefings, audit preparation and
professional sharing.

**Simple memory cards (Professional + Funny):** Minimal cards 
that use one strong visual hook to help people remember the 
clause number and core keyword. Stored in `cards/professional/simple/` 
and `cards/funny/simple/`.

The multi-layer approach is deliberate. How you learn something,
how you recall it quickly, and how you look it up later are
different problems that need different solutions.

---

## Folder structure
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

---

## File naming conventions

Use lowercase kebab-case slugs. Use the same basename across layers:

```text
cards/reference/clause-04-context-of-the-organisation.md
cards/professional/clause-04-context-of-the-organisation.png
cards/professional/simple/clause-04-context-of-the-organisation.png
cards/funny/clause-04-context-of-the-organisation
