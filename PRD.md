# PRD: Factsheet on Gladiolus and Pesticide Use in the Netherlands

## 1. Purpose

Produce an evidence-based factsheet on pesticide use in gladiolus (*Gladiolus*) cultivation in the Netherlands, and on its environmental and human-health impacts. The factsheet is published as a static GitHub Pages website.

## 2. Audience

- **Primary: policymakers.** Need key findings, the regulatory context, and a clear view of where the evidence is strong, weak or missing.
- **Primary: the general public.** Need plain-language explanations without jargon.

Design consequence: a **plain-language summary at the top**, with progressively more detailed sections below it. Technical terms are explained on first use.

## 3. Scope

**In scope**
- Gladiolus cultivation in the Netherlands (cut flowers and bulb/corm production)
- Pesticide use: which active substances are used or authorised, for which pests and diseases, how and how much (where data exist)
- Environmental impacts: surface water, soil, non-target organisms (e.g. pollinators, aquatic life)
- Human-health impacts: occupational exposure, residents/bystanders, and consumers where relevant
- Dutch and EU regulatory context (authorisation, use restrictions, monitoring)

**Out of scope**
- Other flower or bulb crops, except where needed as context or comparison
- Countries other than the Netherlands, except EU rules that apply here
- Policy recommendations that the sources do not support. The factsheet informs, it does not advocate.

## 4. Research questions

1. What pesticides are used on gladiolus in the Netherlands, and how much?
2. What do monitoring data and studies show about environmental effects (water, soil, non-target species)?
3. What is known about health effects and exposure for workers, residents and consumers?
4. What regulations apply, and how are they enforced?
5. Where is the evidence thin, conflicting or absent?

## 5. Source requirements

- Peer-reviewed papers and authoritative grey literature (e.g. WUR, RIVM, Ctgb, NVWA, CBS, EFSA, European Commission)
- Dutch and English sources accepted
- Each source is saved in `sources/` (PDF or link file) with a matching note in `notes/` (see `CLAUDE.md` for the template)
- Paywalled papers are supplied by the project owner. They are never reconstructed from memory.

## 6. Evidence rules

- Every factual claim on the page traces to a specific source and, where possible, a page or table
- Figures (quantities, concentrations, dates, limits) appear only if present in a note in `notes/`
- Distinguish **hazard** (what a substance can do) from **risk** (likelihood given actual exposure)
- Distinguish **detection** of a substance from **harm**
- State the strength of evidence (e.g. strong, moderate, limited, conflicting)
- Gaps and uncertainties get their own section and are not hidden

## 7. Deliverable

A static website in `docs/`, served by GitHub Pages.

**Page structure**
1. Title and one-paragraph plain-language summary
2. Key findings (5 to 8 short points)
3. Gladiolus cultivation in the Netherlands (context)
4. Pesticide use
5. Environmental impacts
6. Health impacts
7. Regulation and oversight
8. Evidence gaps and uncertainties
9. References (numbered, linked)
10. About this factsheet (date, method, limitations)

**Technical requirements**
- Plain HTML and CSS, no frameworks, no external dependencies or trackers
- Responsive, accessible (semantic HTML, sufficient contrast, alt text), print-friendly
- Last-updated date shown on the page
- Charts, if any, are inline SVG with a text alternative

## 8. Workflow and acceptance criteria

| Phase | Output | Done when |
|---|---|---|
| 1. Source collection | Files in `sources/` | Owner confirms the shortlist is adequate |
| 2. Extraction | One note per source in `notes/` | Each note follows the template and quotes only short passages |
| 3. Synthesis | `notes/synthesis.md` | Each finding links to notes, with evidence strength |
| 4. Draft text | Factsheet content in markdown | Owner has reviewed it against the sources |
| 5. Build | Website in `docs/` | Passes checks in section 7 |
| 6. Publish | GitHub Pages live | URL works, references resolve |

## 9. Open questions

- Language: English only, or also Dutch?
- Which year range should the data cover?
- Should the factsheet carry an institutional affiliation or disclaimer?
- Licence for the page content (e.g. CC BY 4.0)?