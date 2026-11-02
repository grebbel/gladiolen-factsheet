---
title: "CBS data exports collected in phase 1 (files in data/)"
authors: "Centraal Bureau voor de Statistiek (CBS); exported by the project owner"
year: 2025
type: dataset
source: "data/ (files listed below); CBS news item https://www.cbs.nl/en-gb/news/2025/13/area-used-to-grow-flower-bulbs-has-increased-in-10-years-decreased-in-2024"
relevance: 3
tags:
  - type/dataset
  - topic/gladiolus
  - topic/cultivation-area
  - topic/pesticide-use
  - topic/national-statistics
---

Source ID in [[source-overview]]: S15. Documents the files that were already in `data/` before phase 3, as asked in `data/README.md`. The owner's exports were made on 28 October 2026 (dates in two file names); the other files have no date.

Checked on 2 November 2026 against the CBS open data API (see [[cbs-2025-85130NED-gewasbescherming-per-gewas]] and [[cbs-2026-80780ned-areaal-iridaceae]]). Where values match, the API notes are the source to cite; this note adds only what is not in those notes.

## Files and origin

| File | Content | Origin | Check |
| --- | --- | --- | --- |
| `table_aa4fcd25-….csv` | Bulb area per crop, 1,000 ha, 2014–2024 (incl. gladioli) | CBS news item 28 March 2025, chart "Area used to cultivate flower bulbs" | Matches 80780ned (e.g. gladioli 0.70 thousand ha in 2024 = 698 ha) |
| `table_0b753ca5-….csv` | Number of bulb farms per crop, 2014–2024 | Same news item, chart "Farms that cultivate flower bulbs" | Matches 80780ned (gladioli 107 farms in 2024) |
| `table_9d679f07-….csv` | Share of bulb area per crop by agricultural area (%) | Same news item, chart "Area used to grow flower bulbs (% of total for the Netherlands as a whole)" | **Year not stated** in file or on the CBS page |
| `table_c90e8175-….csv` | kg active substance per ha, 15 crops, 2016 and 2020 | CBS publication on pesticide use (exact page not identified); 2020 marked provisional | Matches 85130NED (gladiolen 35.7 and 19.4) |
| `table_17d8e287-….csv` | Total kg active substance, 15 crops, 2016 and 2020 | As above | Matches 85130NED (e.g. lily bulbs 601 thousand kg in 2020 = 600,558 kg) |
| `table_83781b89-….csv` | National use by group (million kg), 2012, 2016, 2020 | As above | Consistent with 85130NED national totals |
| `80780ned_TabelIndeling_20261028205939.csv` | Land use, Nederland and Zuid-Holland, 2000–2026 (main land-use classes, potatoes) | CBS 80780ned export | No Iridaceae rows |
| `85430NED_html_20261028210803.html` | Trade export for code 06031970 (other cut flowers) and 02013000 (beef), monthly 2025 | CBS 85430NED export | No gladiolus codes; superseded by [[cbs-2026-85430NED-handel-gladiolen]] |

## Key findings (not in the API notes)

- **[gladiolus] Regional spread:** CBS states "lilies and gladioli are grown throughout the Netherlands" (news item, 28 March 2025).
- **[gladiolus] Share of the national gladiolus area by agricultural area** (`table_9d679f07-….csv`, column "Gladioli (%)"; year not stated): Zuidelijk Veehouderijgebied 27%, Veenkoloniën en Oldambt 13%, Westelijk Holland 12%, Zuidwestelijk Akkerbouwgebied 12%, Oostelijk Veehouderijgebied 11%, Noordelijk Weidegebied 10%, Centraal Veehouderijgebied 5%, IJsselmeerpolders 4%, Zuidwest-Brabant 4%, Rivierengebied 2%.
- By contrast, tulips are concentrated in the IJsselmeerpolders (49%) and Westelijk Holland (33%), and hyacinths and daffodils mainly in Westelijk Holland (81% and 85%) (same file).

## Figures and data

- See the table above; full values in the files.

## Methods and limitations

- CBS agricultural areas (*landbouwgebieden*) are statistical regions, not provinces.
- The regional chart's reference year is not given; it is probably 2024 (the news item covers 2014–2024), but this is not stated. Treat as "recent year, not specified".

## Quality flags

- Official statistics; values verified against the API where possible.
- Regional shares: year not stated.

## Related notes

- [[cbs-2026-80780ned-areaal-iridaceae]]
- [[cbs-2025-85130NED-gewasbescherming-per-gewas]]
- [[lmb-2009-voortgangsrapportage]]: in 2007 gladiolus was concentrated in Limburg and Noord-Brabant.
