# CAS Major Flowsheets — Proof of Concept

A semester-by-semester course-sequencing "flowsheet" for a pilot set of
University at Buffalo College of Arts and Sciences majors, modeled on
the School of Engineering & Applied Sciences' own advisement flowsheets
(`engineering.buffalo.edu/.../flowsheets.html`), which CAS currently has
no equivalent of.

**Live site**: published via GitHub Pages from this repo.

## What this is — and isn't

This is an independently produced proof of concept, **not** a University
at Buffalo publication and **not** endorsed by UB, the College of Arts
and Sciences, or the UB Curriculum Office.

Each program's sequencing is parsed directly from the Undergraduate
Catalog's own "Curricular Plan" section for that major
(`catalogs.buffalo.edu`, 2026-2027 catalog year) — a roadmap the catalog
itself describes as non-binding ("Your actual plan may vary..."), not an
authoritative requirements list. Always confirm actual requirements with
an academic advisor and the official Undergraduate Catalog.

## Pilot programs

- Biochemistry BS
- Computational Physics BS
- Linguistics BA
- Linguistics BA — Chinese Language and Linguistics Concentration
- Linguistics BA — Japanese Language and Linguistics Concentration
- Fine Arts BFA — Painting Concentration
- Dance BFA

Chosen to sample across degree types and credit loads: two high-credit
BS degrees, a base BA plus two of its language concentrations, and two
different BFA (studio-art and performance) tracks.

## Files

- `index.html` — the site itself, self-contained (no external
  dependencies).
- `flowsheets_pilot.json` — the structured data behind it (year →
  semester → course/requirement slots, with "OR" alternatives grouped).

## Provenance

Built from a private repository maintained for UB academic-affairs work.
This repo publishes only the derived, already-public catalog-sequencing
data for this pilot set of programs — not the source repository itself.
