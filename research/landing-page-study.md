# Landing-page study — case databases & learning-oriented sites

Compiled 2026-04-27. For the Ukraine-vs-Russia case database (~40 records, learning audience, mixed novice/journalist/lawyer).

## Five archetypes that exist in the wild

| Archetype | Examples | Best for | Worst for |
|---|---|---|---|
| **A. Search-bar-as-product** | ICIJ Offshore Leaks, Met Collection, Smithsonian, Jus Mundi | Datasets too big to browse (>1k records) | Newcomers without a query |
| **B. Pre-built query gallery** | Climate Case Chart, Lawfare, Long Now Ideas, Pudding | Teaching taxonomy by example | Repeat experts |
| **C. Protagonist gallery** | OCCRP Russian Asset Tracker, Conflict Observatory, Wikipedia portals | Narrative onboarding | System-level overviews |
| **D. Map-or-tool-as-page** | Bellingcat TimeMap, HUDOC, TRIAL UJIM | Spatial/temporal datasets | Narrative onboarding |
| **E. Narrative-led topic page** | Our World in Data, Aeon, JSTOR Daily | Learning audiences | Returning experts |

## Why search-bar-as-product is wrong for us
40 records is too small to need search. Search assumes a question the visitor doesn't yet have. HUDOC is the cautionary tale: beloved by lawyers, hostile to anyone who doesn't already know "respondent State" or "Article 8."

## Why a pure map is wrong for us
The dataset isn't really geographic. It's *forum-and-stakes* shaped (which court? which Ukrainian harm? which legal claim?).

## What works for us — hybrid B + C + (E as second screen)
Hand the visitor a small set of **named lenses** (forum, theme, defendant, outcome, money), each containing a small **protagonist gallery** of 4–6 case cards, with a short **narrative explainer** on second scroll.

## Above-the-fold notes for top references

- **OCCRP Russian Asset Tracker** — Hero = grid of large oligarch portrait cards with valuations. No abstract count. Single ask: "click a face."
- **Climate Case Chart** — Hero = three pre-baked example searches you can click. Scope ("3,000 cases") under title. Single ask: "try one of these."
- **ICIJ Offshore Leaks** — Hero = giant search bar with realistic placeholder. Three numbers communicate scope. Single ask: "type a name."
- **Conflict Observatory** — Hero band, then row of report-family card tiles (Cultural Heritage, Healthcare, Mass Graves, Energy). Atomic unit = report family.
- **Bellingcat TimeMap** — No marketing landing; the tool itself is the page. Intro overlay states scale ("2,500+ verified incidents"). Single ask: "filter, scrub, click."
- **Our World in Data — Poverty** — Title + serif lead paragraph + photo. Then "Five key insights" curriculum block. Dataset hides; narrative greets.
- **Aeon** — Single oversized featured essay tile. Strict singularity. Single ask: "start reading this one piece."
- **Stanford Encyclopedia of Philosophy** — Plain table of contents, A–Z anchor strip, dense alphabetical entries. The contents *are* the product.

## Five concepts for our landing page

### Concept 1 — "Forty cases, five forums" (lens grid)
Hero: 5-tile grid by forum (ICJ · ECtHR · ICC · PCA Arbitrations · National Courts), each tile shows a count and a one-line stake.
Curriculum: "the world has more than one court, and which one matters depends on what you're suing about."
Reference: Climate Case Chart × OCCRP.

### Concept 2 — "There are four 'Hague courts'" (myth-busting)
Hero: illustration of four building silhouettes (ICJ, ICC, PCA, Special Tribunal), each clickable.
Curriculum: forum literacy — almost everyone arrives confused that ICJ ≠ ICC ≠ PCA.
Reference: Our World in Data + Stanford Encyclopedia.

### Concept 3 — "Wall of forty" (protagonist gallery)
Hero: full-width grid of 40 small cards, each with a plain-language nickname ("The Genocide Case", "MH17", "Naftogaz Crimea").
Sortable by date / forum / money / outcome.
Curriculum: "there aren't dozens of separate fights — there are about three big stories told in many courtrooms."
Reference: OCCRP Russian Asset Tracker × Pudding.

### Concept 4 — "The legal docket of a war" (timeline)
Hero: horizontal timeline 2014→2026, 40 dots clustered in three visible bumps (2014, 2017–18, 2022–24).
Below: small map + "Read by chapter" picker (Annexation / Donbas / MH17 / Full-scale invasion / Sanctions).
Curriculum: "these cases have a chronology — the legal response to 2022 is layered on top of 2014."
Reference: Bellingcat TimeMap.

### Concept 5 — "Start with one case" (Aeon-style singular hero)
Hero: one editorial card filling the viewport — strong photograph (ICJ Great Hall), serif headline, 12-min reading-time tag, one button "Begin." Small "or browse all 40 →" link bottom-right.
Curriculum: "international law is narratable; you need a story to start with, the rest are footnotes."
Reference: Aeon × JSTOR Daily.

## Hybrid recommendation
**Concept 1 lens grid + Concept 5 "Start here" callout** as a 6th asymmetric tile. Curious reader gets a runway, journalist gets a list, lawyer gets the index.
