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

# Slide 2 — Formatting review pending
