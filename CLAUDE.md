# CLAUDE.md

Standing instructions for this project. Read `PRD.md` first for scope, audience and deliverable.

## Project

Evidence-based factsheet on pesticide use in gladiolus cultivation in the Netherlands, and its environmental and health impacts. Audience: policymakers and the general public. Output: static site in `docs/` for GitHub Pages.

## Folder layout

- `sources/`: original PDFs and link files (read-only; never edit)
- `notes/`: one markdown note per source, plus `synthesis.md`
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
# <Full title>
- Authors / organisation:
- Year:
- Type: peer-reviewed / report / regulatory decision / dataset
- Link or file: 
- Relevance to research questions (1-5):

## Key findings
(bullets, each with page/table reference)

## Figures and data
(value, unit, year, location in source)

## Methods and limitations
(short)

## Quality flags
(e.g. small sample, not NL-specific, old data)
```

## Writing style

- Plain language first; explain technical terms on first use
- Neutral, factual tone; no advocacy
- Short sentences, active voice
- Dutch place and organisation names in their original form

## Web page rules

- Plain HTML and CSS; no frameworks, CDNs or trackers
- Semantic headings, alt text, good contrast, responsive layout
- Show "last updated" date
- Check that all reference links resolve before finishing

## Working rules

- Work in small steps and summarise what changed after each one
- Never delete files in `sources/`
- Do not commit or push without being asked
- Ask before making assumptions about scope