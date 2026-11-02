---
title: "Goederen; grensoverschrijding, GN (8 digits, afdeling I-IV), (niet-)EU (CBS StatLine 85430NED): gladiolus corms and cut gladioli"
authors: "Centraal Bureau voor de Statistiek (CBS)"
year: 2026
type: dataset
source: "https://www.cbs.nl/nl-nl/cijfers/detail/85430NED (link file: sources/cbs-85430NED-link.md; extract: data/cbs-85430NED-gladiolen-handel-2015-2026.csv)"
relevance: 4
tags:
  - type/dataset
  - topic/gladiolus
  - topic/imports
  - topic/trade-data
  - topic/national-statistics
---

Source ID in [[source-overview]]: S14. Official trade statistics (cross-border goods flows, *grensoverschrijding*), by 8-digit customs code (GN, the Dutch name for the EU Combined Nomenclature). Table last modified by CBS on 2 October 2026; downloaded through the CBS open data API on 2 November 2026.

Codes extracted:
- **06011040** gladiolus corms, dormant ("Gladiolebollen, in rusttoestand")
- **06031910** cut gladioli ("Gladiolen, afgesneden bloemen en bloemknoppen")

No separate codes for iris, crocus or freesia were found in the table (search on the code titles).

Status: 2015–2023 final; 2024 revised provisional; 2025 provisional; **2026 covers January–May only** (the annual value equals the sum of the five months). **2021 has no values** in the table.

Values are rounded by CBS to whole millions (euros or pieces), so small flows show as 0.

## Key findings

- **[gladiolus] The Netherlands imports few gladiolus corms and exports many.** Imports were 2–33 million corms per year (2015–2025); exports were 464–755 million per year.
- Corm exports fell from 755 million (2015) to 464 million (2024), then 512 million (2025). Export value was €26–38 million per year.
- Corm imports came mainly from outside the EU: for example 30 of 33 million in 2023 and 13 of 13 million in 2024.
- **[gladiolus] Cut gladioli:** imports were 0–15 million stems per year, almost all from other EU countries; exports were 23–105 million stems per year.
- Countries of origin within "EU" and "non-EU" are not given in this table.

## Figures and data

Totals, all countries (`cbs-85430NED-gladiolen-handel-2015-2026.csv`, rows "Totaal landen"):

| Year | Corms: import (mln pieces) | Corms: export (mln pieces) | Corms: export (mln €) | Cut: import (mln stems) | Cut: export (mln stems) | Cut: export (mln €) |
| --- | --- | --- | --- | --- | --- | --- |
| 2015 | 7 | 755 | 38 | 8 | 70 | 21 |
| 2016 | 3 | 710 | 38 | 15 | 102 | 32 |
| 2017 | 2 | 705 | 34 | 9 | 49 | 17 |
| 2018 | 4 | 677 | 32 | 3 | 52 | 17 |
| 2019 | 3 | 679 | 31 | 3 | 55 | 18 |
| 2020 | 2 | 600 | 26 | 14 | 48 | 16 |
| 2021 | no data | no data | no data | no data | no data | no data |
| 2022 | 22 | 584 | 32 | 0 | 68 | 18 |
| 2023 | 33 | 524 | 32 | 1 | 23 | 10 |
| 2024 | 13 | 464 | 29 | 0 | 45 | 27 |
| 2025 | 4 | 512 | 33 | 1 | 105 | 73 |
| 2026 (Jan–May) | 3 | 316 | 24 | 0 | 23 | 29 |

Import value of corms was €0–1 million per year; of cut gladioli €0–3 million (same file).

## Methods and limitations

- Cross-border trade includes goods passing through the Netherlands (transit). [[benninga-2008-productie-handelsdata]] notes that customs-based figures include transit and exclude estimates for small firms.
- Rounding to whole millions hides small flows.
- 2021 missing; 2024–2026 provisional.

## Quality flags

- Official statistics; gladiolus-specific: strong for the order of magnitude.
- **Implausible values to check:** cut-gladioli export value in 2025 (€73 million for 105 million stems) and January–May 2026 (€29 million for 23 million stems) imply a much higher value per stem than in earlier years (about €0.3). This may reflect provisional data or a classification change; not explained in the source.
- Trade in corms does not show where they are grown on; pesticide residues on traded corms or flowers are not covered.

## Related notes

- [[cbs-2026-80780ned-areaal-iridaceae]]: Dutch gladiolus area.
- [[benninga-2008-productie-handelsdata]]: where trade data can be found.
- [[mantingh-2026-pesticiden-in-boeketten]]: residues on imported cut flowers (no gladioli sampled).
