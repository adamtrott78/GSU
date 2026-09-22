# GSU Governance SVG Production Specification

**Status:** STAGE 2 — SLIDE-BY-SLIDE FORMATTING REVIEW  
**Deck:** GSU Governance Leadership Review  
**Meeting:** September 22, 2026  
**Output:** 1920 × 1080 SVG slides

This document is the implementation authority for slide geometry and rendering. `PRESENTATION_PLAN.md` remains authoritative for content / claims, and `SCRIPT.md` remains authoritative for narration.

---

# Working deck-wide production defaults

These are the current Stage 2 defaults. They remain subject to bounded adjustment during the slide-by-slide formatting pass unless a slide section below explicitly says **FORMATTING LOCKED**.

## Canvas and safe area

- canvas: `1920 × 1080`
- aspect ratio: `16:9`
- background: `#F8FAFC`
- outer safe margins: left/right `96 px`, top/bottom `72 px`
- usable area: `1728 × 936 px`
- baseline rhythm: `12 px`; prefer major spacing in `24 px` increments

## Grid

- 12-column working grid
- gutter: `24 px`
- effective column width: approximately `122 px`

## Typography

Primary safe stack:

`Arial, Helvetica, sans-serif`

Working scale:

- eyebrow / metadata: `18 px`, weight `700`, tracking approximately `1.2 px`
- content-slide title: `44 px`, weight `700`, line-height approximately `52 px`
- supporting line: `24 px`, weight `400`
- section / card header: `22 px`, weight `700`
- body: `22 px`, weight `400`, line-height approximately `30 px`
- annotation / secondary detail: `18 px`, weight `400`
- strong footer / action statement: `20–22 px`, weight `700`

## Palette

- background: `#F8FAFC`
- white: `#FFFFFF`
- primary text: `#0F172A`
- secondary text: `#334155`
- muted text: `#64748B`
- light border: `#CBD5E1`
- divider: `#E2E8F0`
- deep navy: `#0F2747`
- medium blue: `#2B5F9E`
- soft blue: `#EAF2FB`
- slate accent: `#49627A`
- slate tint: `#EEF3F7`
- proposed amber text: `#B45309`
- proposed amber stroke: `#F5B041`
- proposed amber fill: `#FFF4DB`
- warning fill where structurally necessary: `#FEE4E2`

## Shapes and connectors

- ordinary card radius: `16 px`
- major container radius: `20 px`
- ordinary card stroke: `2 px #CBD5E1`
- emphasized container stroke: `2.5–3 px`
- standard connector: `3 px #49627A`
- liaison / secondary relationship: `3 px`, dashed `8 8`
- no decorative stock imagery
- minimal / no shadowing

## Content-slide header pattern

Slides 2–11 use the common header unless a later locked slide section overrides it:

- eyebrow: `GSU GOVERNANCE REVIEW`, x `96`, y approximately `96`
- title begins x `96`, y approximately `128–145`
- thin blue rule below title, spanning working width
- top-right metadata: `UMass Dartmouth • AFT Local 6350 • Sept. 22, 2026`, right aligned

Slide 1 intentionally does not use this chrome.

---

# Slide 1 — A Governance Structure for Graduate Student Employees

## Status

**FORMATTING LOCKED**

## Production job

Create a minimal opener whose reading order is:

1. title;
2. Local 6350 → GSU containment relationship;
3. meeting goal;
4. subtitle / metadata.

The slide should feel institutional and deliberate, not decorative.

## Canvas

- `1920 × 1080`
- background `#F8FAFC`

## Eyebrow

- text: `UMASS DARTMOUTH • AFT LOCAL 6350`
- horizontally centered
- y approximately `112`
- font `18 px`, weight `700`
- tracking approximately `1.2 px`
- color `#49627A`

## Main title

- text: `A Governance Structure for Graduate Student Employees`
- bounding box: x `360`, y `190`, w `1200`
- horizontally centered text
- font `54 px`, weight `700`
- line-height approximately `62 px`
- color `#0F172A`
- maximum 2 lines

## Subtitle

- text: `GSU leadership review • September 22, 2026`
- horizontally centered
- y approximately `350`
- font `26 px`, weight `400`
- color `#475569`

## Structural motif

### Local 6350 box

- x `700`
- y `485`
- w `520`
- h `82`
- radius `18`
- fill `#0F2747`
- no visible heavy shadow
- text: `LOCAL 6350`
- centered
- font `28 px`, weight `700`
- text color `#FFFFFF`

### Connector

- center x `960`
- begins at bottom center of Local box, y `567`
- ends at top center of GSU box, y `625`
- stroke `4 px #49627A`
- simple downward arrowhead
- no connector label

### GSU box

- x `560`
- y `625`
- w `800`
- h `96`
- radius `18`
- fill `#EAF2FB`
- stroke `2.5 px #2B5F9E`
- text: `GRADUATE STUDENT EMPLOYEES / GSU`
- centered
- font `30 px`, weight `700`
- text color `#0F2747`

The wider lower box must visually communicate that GSU sits inside / beneath the broader Local umbrella rather than appearing as a separate peer organization.

## Goal panel

- x `180`
- y `845`
- w `1560`
- h `120`
- radius `16`
- fill `#EAF2FB`
- stroke `2 px #2B5F9E`

Inside panel:

### Label

- text: `GOAL TODAY`
- centered or left-aligned within the central text group, whichever reads cleaner in the final SVG
- font `18 px`, weight `700`
- color `#2B5F9E`

### Goal statement

- text: `Approve the structure in principle or identify the changes needed before Local review.`
- centered
- font `26 px`, weight `600`
- color `#0F2747`
- keep to one line if metrics permit; otherwise allow two balanced lines

## Slide 1 QA constraints

- no common content-slide header chrome
- title must dominate the page
- diagram must not be mistaken for a hierarchy in which GSU leaves Local 6350
- connector must be visually simple
- goal panel must be the strongest secondary element after the title / diagram
- no clipping at 1920 × 1080 render
- all text must remain comfortably inside the 96 px horizontal safe area

---

# Slide 2 — Local 6350 already has pieces of multi-unit governance—GSU is the missing structure

## Status

**FORMATTING LOCKED**

## Production job

Make the existing constitutional mismatch legible as a two-sided comparison that converges on one result: Draft 1 formally defines the GSU chapter.

## Header

Use common content-slide chrome.

Because the title is long, allow a two-line title at `40–42 px` if required to preserve clean wrapping. Do not reduce below `40 px` unless rendering proves necessary.

## Main comparison region

Treat each side as one grouped visual object rather than four disconnected article cards.

### Left group — MAINTAINER-SPECIFIC

- outer container: x `96`, y `270`, w `760`, h `410`
- radius `18`
- fill `#FFFFFF`
- stroke `2 px #CBD5E1`
- section-header bar: h `46`, fill `#EEF3F7`
- section-header text: `MAINTAINER-SPECIFIC`, `20–22 px`, weight `700`, color `#0F2747`

Internal article cards:

1. `ARTICLE III — MEMBERSHIP`
   - x approximately `120`, y approximately `340`, w approximately `712`, h `130–145`
   - white or very light neutral fill
   - explain: written for Maintainers; conflicts with adding another organized AFT unit
2. `ARTICLE V — BARGAINING`
   - same width / height
   - y approximately `505`
   - explain: committee composition is Custodial / Grounds / Power Plant / Trades

Use `24 px` vertical gap between cards.

### Right group — MULTI-UNIT PIECES ALREADY EXIST

- outer container: x `1064`, y `270`, w `760`, h `410`
- radius `18`
- fill `#FFFFFF`
- stroke `2 px #AFC0D3`
- section-header bar: h `46`, fill `#EAF2FB`
- section-header text: `MULTI-UNIT PIECES ALREADY EXIST`, `20–22 px`, weight `700`, color `#0F2747`

Internal article cards:

1. `ARTICLE IX — ELECTIONS`
   - x approximately `1088`, y approximately `340`, w approximately `712`, h `130–145`
   - explain: chapter-specific voting already exists, but chapters are not defined
2. `ARTICLE XV — CONTRACTS`
   - same width / height
   - y approximately `505`
   - explain: only members of the affected bargaining unit vote on that agreement

## Convergence

Two restrained diagonal connectors leave the lower inner edges of the grouped containers and converge on the central result box.

- stroke `3 px #49627A`
- no oversized arrowheads
- connectors must terminate cleanly at the result box and never run through text

## Result box

- x `660`
- y `735`
- w `600`
- h `120`
- radius `18`
- fill `#0F2747`
- text centered
- first line: `DRAFT 1`, approximately `22 px`, weight `700`, white
- second line: `FORMAL GSU CHAPTER`, approximately `28 px`, weight `700`, white

This is the strongest object below the title and should visually read as the synthesis / destination of both sides.

## Bottom conclusion

- centered around y `925`
- text: `THE PIECES ALREADY EXIST. DRAFT 1 DEFINES HOW GSU FITS.`
- font `22 px`, weight `700`
- color `#0F2747`

## Slide 2 QA constraints

- both grouped columns must feel balanced in weight and height
- left group should read as Maintainer-specific machinery; right group as existing multi-unit concepts
- article cards must remain subordinate to their group header and the central result
- result box must be visually stronger than any article card
- connectors may not cross labels or body text
- bottom conclusion must remain readable without competing with the result box
- all text must fit within 1920 × 1080 without reducing body text below the deck default unnecessarily

---

# Slide 3 — Formatting review pending
