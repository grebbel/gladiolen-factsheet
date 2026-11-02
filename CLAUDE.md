# CLAUDE.md

Standing instructions for this project. Read `PRD.md` first for scope, audience and deliverable.

## Project

Evidence-based factsheet on pesticide use in gladiolus cultivation in the Netherlands, and its environmental and health impacts. Audience: policymakers and the general public. Output: static site in `docs/` for GitHub Pages. Focus of sources is from 2010 onwards. 

## Folder layout

- `sources/`: original documents only (PDFs and link files; read-only, never edit)
- `notes/`: `source-overview.md` (the source list), one markdown note per source, plus `synthesis.md`
- `docs/`: the website (`index.html`, `style.css`)
- `PRD.md`: requirements

## Evidence rules (most important)

1. Never state a fact, figure, date, limit or substance name unless it appears in a note in `notes/`.
2. Never fill gaps from memory. If something is missing, write "not found in sources" and add it to the gaps list.
3. Every claim on the page carries a numbered citation that resolves to the reference list.
4. Distinguish hazard from risk, and detection from harm.
5. Label evidence strength: strong, moderate, limited or conflicting.
6. If sources disagree, report both and say so. Do not pick a side silently.
7. Quote sparingly (short phrases only, in quotation marks). Otherwise paraphrase.
8. If a PDF can't be read or a source is unclear, stop and ask. Do not guess.

## Note template (`notes/<author-year-short-title>.md`)

```
---
title: "<Full title>"
authors: "<Authors / organisation>"
year: <YYYY>
type: peer-reviewed | report | regulatory-decision | dataset
source: "<URL, or path to file in sources/>"
relevance: <1-5>
tags:
  - type/<type>
  - substance/<substance-name>
  - topic/<topic>
---

## Key findings
(bullets, each with page/table reference)

## Figures and data
(value, unit, year, location in source)

## Methods and limitations
(short)

## Quality flags
(e.g. small sample, not NL-specific, old data)

## Related notes
(wikilinks to notes on the same substance or topic, and to sources that agree or disagree, e.g. [[smith-2018-bulb-residues]])
```

Template rules (keep notes compatible with Quartz/Obsidian):

- The frontmatter holds the metadata; do not repeat the title as a `#` heading in the body.
- Use `year`, not `date`. Quartz reads `date` as the date of the page itself.
- Tags are lowercase, with hyphens instead of spaces, grouped by prefix (`type/`, `substance/`, `topic/`). Use one spelling per substance across all notes.
- Link between notes with `[[file-name]]` (no `.md`). Use plain Markdown links for `sources/` and external URLs.
- `synthesis.md` links to each note it draws on with `[[...]]`.

## Writing style

- Plain language first; explain technical terms on first use
- Spelling is UK English 
- Neutral, factual tone; no advocacy
- Short sentences, active voice
- Dutch place and organisation names in their original form

## Web page rules

- Plain HTML and CSS; no frameworks, CDNs or trackers
- Semantic headings, alt text, good contrast, responsive layout
- Show "last updated" date
- Check that all reference links resolve before finishing
- the page states it is an independent personal investigation licensed CC BY 4.0.

## Working rules

- Work in small steps and summarise what changed after each one
- Never delete files in `sources/`
- Do not commit or push without being asked
- Ask before making assumptions about scope
