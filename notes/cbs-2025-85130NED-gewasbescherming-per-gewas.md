---
title: "Gewasbeschermingsmiddelen in de landbouw; werkzame stof, gewas, toepassing (CBS StatLine 85130NED)"
authors: "Centraal Bureau voor de Statistiek (CBS)"
year: 2025
type: dataset
source: "https://www.cbs.nl/nl-nl/cijfers/detail/85130NED (link file: sources/cbs-85130NED-link.md; extracts: data/cbs-85130NED-gladiolen-2012-2024.csv, data/cbs-85130NED-vergelijking-gewassen-2012-2024.csv)"
relevance: 5
tags:
  - type/dataset
  - topic/gladiolus
  - topic/pesticide-use
  - topic/national-statistics
  - substance/mancozeb
  - substance/fluazinam
  - substance/folpet
  - substance/pendimethalin
  - substance/metamitron
  - substance/glyphosate
  - substance/captan
  - substance/thiophanate-methyl
---

Source ID in [[source-overview]]: S12. Official statistics. Table last modified by CBS on 13 November 2025; downloaded through the CBS open data API on 2 November 2026. Years: 2012, 2016, 2020 (final) and 2024 (provisional). Next update expected December 2027, covering 2026.

"Location in source" below refers to the extract files in `data/` (columns *jaar*, *werkzame_stof_of_groep*, and the measure columns), which are unchanged CBS values.

**This is the main source on pesticide use on gladiolus.** Gladiolus ("Gladiolen") is one of 45 crops in the table. Iris, crocus and freesia are **not** listed separately.

## Key findings

- **[gladiolus] Pesticide use per hectare on gladiolus fell by about 80% between 2012 and 2024**: 41.9 kg active substance per ha (2012), 35.7 (2016), 19.4 (2020), 8.2 (2024, provisional) (`cbs-85130NED-gladiolen-2012-2024.csv`, rows "Totaal van alle werkzame stoffen").
- Over the same period the gladiolus area with pesticide use fell from 1,113 to 695 ha, and total use from 46,675 to 5,756 kg. Pesticides were used on 99.6–100% of the gladiolus area in all four years (same rows).
- **Fungicides** dominated in 2012 (30.4 kg/ha of 41.9) and fell most, to 3.6 kg/ha in 2024. Herbicides fell from 8.8 to 3.9 kg/ha, and insecticides from 2.6 to 0.4 kg/ha (rows "F", "H", "I").
- The largest substance by weight on gladiolus in 2012 was mancozeb (14,858 kg; used on 67.8% of the area). Mancozeb was banned in 2021 ([[pan-nl-2025-analyse-cbs-cijfers]]) and does not appear in 2024.
- In 2024 the largest substances by weight were folpet (fungicide, 1,017 kg), pendimethalin (herbicide, 882 kg), metamitron (herbicide, 652 kg), glyphosate (herbicide, 615 kg) and captan (fungicide, 368 kg).
- The number of different active substances recorded on gladiolus rose from 23 (2012) to 34 (2024), while total kilograms fell.
- **Comparison with other crops** (`cbs-85130NED-vergelijking-gewassen-2012-2024.csv`): in 2016 gladiolus (35.7 kg/ha) used more per hectare than tulips (27.2) and less than lily bulbs (124.5). In 2020 gladiolus (19.4) was below tulips (25.8) and above hyacinths (17.0). All values are well above the all-crop average (7.9 in 2016; 7.0 in 2020).

## Figures and data

**Gladiolus, all active substances** (`cbs-85130NED-gladiolen-2012-2024.csv`):

| Year | Status | Firms | Area with use (ha) | % of area | Total (kg) | kg/ha |
| --- | --- | --- | --- | --- | --- | --- |
| 2012 | final | 172 | 1,113 | 100.0 | 46,675 | 41.9 |
| 2016 | final | 149 | 929 | 100.0 | 33,151 | 35.7 |
| 2020 | final | 107 | 812 | 99.9 | 15,722 | 19.4 |
| 2024 | provisional | 105 | 695 | 99.6 | 5,756 | 8.2 |

**Gladiolus, by group, kg/ha** (same file):

| Group | 2012 | 2024 |
| --- | --- | --- |
| Fungicides and bactericides (F) | 30.4 | 3.6 |
| Herbicides and haulm killing (H) | 8.8 | 3.9 |
| Insecticides and acaricides (I) | 2.6 | 0.4 |
| Plant growth regulators (PGR) | 0.2 | 0.0 |

**Gladiolus, largest substances by weight** (same file; % = share of gladiolus area treated; dose = kg per treated ha per year):

| 2012 | kg | % area | dose | 2024 | kg | % area | dose |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Mancozeb (F) | 14,858 | 67.8 | 19.7 | Folpet (F) | 1,017 | 73.3 | 2.0 |
| Fluazinam (F) | 4,813 | 78.7 | 5.5 | Pendimethalin (H) | 882 | 90.3 | 1.4 |
| Glyphosate (H) | 2,763 | 83.0 | 3.0 | Metamitron (H) | 652 | 79.3 | 1.2 |
| Captan (F) | 2,238 | 71.9 | 2.8 | Glyphosate (H) | 615 | 71.0 | 1.2 |
| Metamitron (H) | 1,891 | 76.8 | 2.2 | Captan (F) | 368 | 47.5 | 1.1 |
| Pendimethalin (H) | 1,640 | 92.1 | 1.6 | Dimethenamid-P (H) | 186 | 68.1 | 0.4 |
| Thiophanate-methyl (F) | 1,422 | 17.4 | 7.3 | Prothioconazole (F) | 176 | 82.8 | 0.3 |
| Chloridazon (H) | 1,291 | 70.8 | 1.6 | MCPA (H) | 130 | 49.6 | 0.4 |
| Prochloraz (F) | 888 | 26.5 | 3.0 | Fluopyram (F) | 120 | 65.1 | 0.3 |
| Tebuconazole (F) | 842 | 76.4 | 1.0 | Azoxystrobin (F) | 110 | 25.1 | 0.6 |

**Comparison of crops, all substances, kg/ha** (`cbs-85130NED-vergelijking-gewassen-2012-2024.csv`, 2016 and 2020 rows):

| Crop | 2016 | 2020 |
| --- | --- | --- |
| Lily bulbs | 124.5 | 113.7 |
| Tulips (open field) | 27.2 | 25.8 |
| Gladiolus | 35.7 | 19.4 |
| Hyacinths | 19.1 | 17.0 |
| Narcissus | 14.0 | 17.0 |
| Floriculture crops, total | 9.9 | 4.1 |
| All crops | 7.9 | 7.0 |

Values for 2012 and 2024 for these crops are in the same file.

**[gladiolus] Pyrethroid and neonicotinoid insecticides** (added 11 November 2026; `data/cbs-85130NED-gladiolen-2012-2024.csv`). These are used in small amounts by weight but on a large share of the area:

| Year | Substance (group) | % of farms | Area with use (ha) | % of area | Total (kg) | Dose (kg/ha treated) |
| --- | --- | --- | --- | --- | --- | --- |
| 2012 | Esfenvalerate (pyrethroid) | 43.4 | 635 | 57.1 | 76 | 0.1 |
| 2012 | Deltamethrin (pyrethroid) | 51.4 | 657 | 59.0 | 17 | 0.0 |
| 2012 | Thiacloprid (neonicotinoid) | 47.7 | 339 | 30.5 | 201 | 0.6 |
| 2016 | Esfenvalerate | 70.8 | 691 | 74.4 | 56 | 0.1 |
| 2016 | Deltamethrin | 33.8 | 338 | 36.4 | 4 | 0.0 |
| 2016 | Thiacloprid | 33.3 | 230 | 24.8 | 34 | 0.1 |
| 2016 | Imidacloprid (neonicotinoid) | 15.5 | 143 | 15.4 | 22 | 0.2 |
| 2020 | Esfenvalerate | 54.6 | 506 | 62.3 | 26 | 0.1 |
| 2020 | Deltamethrin | 8.8 | 60 | 7.3 | 0 | 0.0 |
| 2020 | Thiacloprid | 20.1 | 208 | 25.6 | 37 | 0.2 |
| 2024 (provisional) | Esfenvalerate | 46.7 | 383 | 54.8 | 24 | 0.1 |
| 2024 (provisional) | Deltamethrin | 11.5 | 69 | 9.9 | 1 | 0.0 |

- Thiacloprid and imidacloprid do not appear for gladiolus in 2024; imidacloprid appears only in 2016. Other pyrethroids (cypermethrin, lambda-cyhalothrin) and abamectin do not appear for gladiolus in any year.
- Values of 0.0 and 0 are rounded in the CBS table.
- Relevance: these substances weigh little, so they hardly affect total kg/ha, but they were used on a large share of the gladiolus area. Pyrethroids are the largest contributors to toxic pressure in Dutch surface water nationally ([[visser-2025-toxische-druk-bestrijdingsmiddelen]]); thiacloprid caused declines in water insects in an experiment ([[barmentlo-2021-neonicotinoid-aquatic-insects]]). Neither source is about gladiolus fields.

## Methods and limitations

- CBS survey of professional arable and horticultural farms; includes work by contractors (table description).
- kg/ha "gebruik per jaar per hectare" is per hectare of the crop; "dosering" is per treated hectare (table definitions).
- 2024 figures are provisional.
- **Soil disinfection appears not to be covered.** The substance list includes metam-sodium and dazomet, but CBS records no metam-sodium use on any crop and dazomet only once (2012, forestry and hedging plants). The table description does not mention soil disinfection. So the gladiolus totals probably exclude soil disinfection, which [[lmb-2009-voortgangsrapportage]] describes as common before gladiolus planting. Not confirmed in sources.
  - **Update 11 November 2026:** [[cbs-2023-vergelijking-afzet-gebruik]] states that metam-sodium has been in the CBS questionnaire since 2020, that its use "was in 2020 niet meer" very high, and that in 2012 it was still "substantieel". It also says products used before and after the growing season are not always included. So: soil disinfection was not asked about in 2012 and 2016; from 2020 it was asked about, but this table records no metam-sodium use on any crop. Whether that means near-zero use or under-reporting is not found in sources.
- Bulb and corm disinfection (dipping before planting) is not separately identified in the extract.
- Iris, crocus and freesia: not found in this table.

## Quality flags

- Official statistics, recent, gladiolus-specific: strong.
- Four survey years only.
- Not directly comparable with older bulb-sector figures that include soil disinfection (S7: 102 kg/ha for all bulbs in 2007).
- Fewer substances by weight does not mean lower hazard; the table does not measure toxicity.

## Related notes

- [[cbs-2026-80780ned-areaal-iridaceae]]: area of gladiolus and related crops.
- [[molema-nd-gewasafhankelijk-toedienen-gladiolen]]: gladiolus use in 1995 (about 27 kg/ha, mostly fungicides).
- [[lmb-2009-voortgangsrapportage]]: soil disinfection before gladiolus planting.
- [[pan-nl-2025-analyse-cbs-cijfers]]: NGO reanalysis of the national totals from the same table.
