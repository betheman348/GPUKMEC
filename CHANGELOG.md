# Changelog

## v2.0 — 22 May 2026

**Major restructure following regulatory review.**

Repositioned the tool from a clinical decision-support calculator to an educational reference. Following queries raised about the boundary between clinical reference tools and Software as a Medical Device (SaMD) under MHRA classification, the tool has been restructured to:

- Surface excerpts of CoSRH UKMEC 2025 published criteria rather than calculate eligibility.
- Display all relevant published rows in tabular form for each scenario; no single "verdict" category is rendered.
- Remove all synthesised clinical conclusions (no "no restriction", "contraindicated", or method-level recommendation).
- Remove the cumulative risk warning previously generated from user input.
- Remove the mood/anxiety dynamic annotation previously triggered by user input.
- Reword all interface language from "patient assessment" and "calculator" to "scenario filters" and "reference".
- Emphasise the educational reference framing throughout, including in the disclaimer, footer, and meta descriptions.

The user reads all rows of the relevant UKMEC sections and applies clinical judgement. No row is selected, highlighted, or recommended by the tool.

Awaiting written confirmation from MHRA Software Group and the developer's medical defence organisation regarding regulatory positioning.

## v1.0 — 17 May 2026

Initial public release. Implemented UKMEC 2025 categorisation across six contraceptive methods with a calculator-style interface. Withdrawn for restructure on 22 May 2026.
