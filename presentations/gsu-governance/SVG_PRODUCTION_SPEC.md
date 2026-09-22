# GSU Governance SVG Production Specification

**Status:** STAGE 2 — SLIDE-BY-SLIDE FORMATTING REVIEW  
**Deck:** GSU Governance Leadership Review  
**Meeting:** September 22, 2026  
**Output:** 1920 × 1080 SVG slides

This document is the implementation authority for slide geometry and rendering. `PRESENTATION_PLAN.md` remains authoritative for content / claims, and `SCRIPT.md` remains authoritative for narration.

---

# Deck-wide production defaults

## Canvas / grid
- canvas: `1920 × 1080`, 16:9
- background: `#F8FAFC`
- safe margins: left/right `96 px`, top/bottom `72 px`
- 12-column working grid, `24 px` gutters
- baseline rhythm: `12 px`; prefer `24 px` major spacing increments

## Typography
Safe stack: `Arial, Helvetica, sans-serif`

- eyebrow / metadata: `18 px`, 700
- content-slide title: `44 px`, 700, ~`52 px` line-height; long titles may use `40–42 px`
- section / card header: `22 px`, 700
- body: `22 px`, 400, ~`30 px` line-height
- annotation: `18 px`, 400
- footer / action statement: `20–22 px`, 700

## Palette
- background `#F8FAFC`
- white `#FFFFFF`
- primary text `#0F172A`
- secondary text `#334155`
- muted text `#64748B`
- light border `#CBD5E1`
- divider `#E2E8F0`
- deep navy `#0F2747`
- medium blue `#2B5F9E`
- soft blue `#EAF2FB`
- slate accent `#49627A`
- slate tint `#EEF3F7`
- proposed amber text `#B45309`
- proposed amber stroke `#F5B041`
- proposed amber fill `#FFF4DB`
- warning fill `#FEE4E2`

## Shapes / connectors
- ordinary card radius: `16 px`
- major container radius: `20 px`
- ordinary stroke: `2 px #CBD5E1`
- emphasized stroke: `2.5–3 px`
- standard connector: `3 px #49627A`
- secondary / liaison line: `3 px`, dashed `8 8`
- no stock imagery; minimal / no shadowing

## Content-slide header
Slides 2–11 use:
- eyebrow `GSU GOVERNANCE REVIEW`, x `96`, y ~`96`
- title begins x `96`, y ~`128–145`
- thin blue rule below title across working width
- top-right metadata: `UMass Dartmouth • AFT Local 6350 • Sept. 22, 2026`

Slide 1 intentionally omits this chrome.

---

# Slide 1 — A Governance Structure for Graduate Student Employees

## Status
**FORMATTING LOCKED**

## Geometry / hierarchy
Reading order: title → Local/GSU relationship → meeting goal → subtitle.

### Eyebrow
- centered, y `112`
- `UMASS DARTMOUTH • AFT LOCAL 6350`
- `18 px`, 700, `#49627A`

### Main title
- x `360`, y `190`, w `1200`
- `54 px`, 700, ~`62 px` line-height
- centered, max 2 lines, `#0F172A`

### Subtitle
- centered, y ~`350`
- `GSU leadership review • September 22, 2026`
- `26 px`, `#475569`

### Local 6350 box
- x `700`, y `485`, w `520`, h `82`
- radius `18`, fill `#0F2747`
- centered white `LOCAL 6350`, `28 px`, 700

### Connector
- center x `960`, y `567 → 625`
- `4 px #49627A`, simple downward arrowhead

### GSU box
- x `560`, y `625`, w `800`, h `96`
- radius `18`, fill `#EAF2FB`, stroke `2.5 px #2B5F9E`
- centered `GRADUATE STUDENT EMPLOYEES / GSU`, `30 px`, 700, `#0F2747`

### Goal panel
- x `180`, y `845`, w `1560`, h `120`
- radius `16`, fill `#EAF2FB`, stroke `2 px #2B5F9E`
- label `GOAL TODAY`, `18 px`, 700, `#2B5F9E`
- statement: `Approve the structure in principle or identify the changes needed before Local review.`
- `26 px`, 600, `#0F2747`

## QA
- no content-slide header chrome
- title dominates
- GSU must visually remain beneath / inside Local 6350 rather than appearing separate
- goal panel is strongest secondary element
- no clipping; keep text within safe area

---

# Slide 2 — Local 6350 already has pieces of multi-unit governance—GSU is the missing structure

## Status
**FORMATTING LOCKED**

## Header
Use common chrome. Long title may use `40–42 px`, max 2 lines.

## Main comparison groups
Treat each side as one grouped object.

### Left — MAINTAINER-SPECIFIC
- outer: x `96`, y `270`, w `760`, h `410`
- radius `18`, white fill, `2 px #CBD5E1`
- header strip h `46`, fill `#EEF3F7`
- two stacked article cards with `24 px` gap:
  - `ARTICLE III — MEMBERSHIP`: written for Maintainers; conflicts with adding another organized AFT unit
  - `ARTICLE V — BARGAINING`: Custodial / Grounds / Power Plant / Trades composition

### Right — MULTI-UNIT PIECES ALREADY EXIST
- outer: x `1064`, y `270`, w `760`, h `410`
- radius `18`, white fill, `2 px #AFC0D3`
- header strip h `46`, fill `#EAF2FB`
- two stacked article cards with `24 px` gap:
  - `ARTICLE IX — ELECTIONS`: chapter-specific voting exists, chapters undefined
  - `ARTICLE XV — CONTRACTS`: affected bargaining unit votes on its agreement

## Convergence / result
- two restrained `3 px #49627A` diagonal connectors from lower inner group edges
- result box: x `660`, y `735`, w `600`, h `120`
- radius `18`, fill `#0F2747`
- centered white text: `DRAFT 1` above `FORMAL GSU CHAPTER`
- second line ~`28 px`, 700

## Bottom conclusion
- centered y ~`925`
- `THE PIECES ALREADY EXIST. DRAFT 1 DEFINES HOW GSU FITS.`
- `22 px`, 700, `#0F2747`

## QA
- both sides balanced
- result box stronger than article cards
- connectors never cross text
- bottom conclusion remains secondary to synthesis box

---

# Slide 3 — The building blocks already exist in other AFT locals—we can adapt them to GSU

## Status
**FORMATTING LOCKED**

## Header
Use common chrome. Because the title is long, use `40–42 px`, max 2 lines.

## Comparator panels
Two equal source panels, intentionally shorter than the original draft to preserve breathing room for the synthesis.

### Chelsea Local 1340
- x `120`, y `265`, w `720`, h `270`
- radius `18`, white fill, `2 px #CBD5E1`
- header strip fill `#EEF3F7`
- header: `CHELSEA LOCAL 1340 — UNIT-SPECIFIC LEADERSHIP`
- body: 3 concise lines / bullets from the locked plan

### Chelmsford Local 3569
- x `1080`, y `265`, w `720`, h `270`
- radius `18`, white fill, `2 px #AFC0D3`
- header strip fill `#EAF2FB`
- header: `CHELMSFORD LOCAL 3569 — SEPARATE REPRESENTATIVE GOVERNANCE`
- body: 4 concise lines / bullets from the locked plan

## Convergence
- one restrained connector from each comparator panel into the synthesis panel
- `3 px #49627A`
- connectors converge cleanly at the upper edge of the synthesis box
- no line may pass through text

## GSU synthesis panel
- x `500`, y `610`, w `920`, h `220`
- radius `20`
- white body fill
- `3 px #2B5F9E` stroke
- shallow header strip fill `#EAF2FB`
- header: `GSU DRAFT 1 — ADAPTED FOR GRADUATE WORKERS`, `22–24 px`, 700

Inside, use a clean two-column arrangement rather than one long list:

Left column:
- `4 elected officers`
- `Representative Council`
- `annual terms + open eligibility`

Right column:
- `college / school representation`
- `GSU-selected bargaining team`

Body text `20–22 px`; spacing must keep the synthesis legible at a glance.

## Boundary strip
- x `300`, y `885`, w `1320`, h `64`
- radius `14`
- fill `#EEF3F7`
- no heavy border
- centered `LOCAL 6350 EXECUTIVE BOARD: UNCHANGED`
- `22 px`, 700, `#0F2747`

This boundary statement is strong but visually secondary to the GSU synthesis panel.

## QA
- comparator panels have equal visual weight
- synthesis panel is the dominant object below the title
- arrows communicate selected ideas feeding Draft 1, not organizational hierarchy
- boundary strip cannot compete with the synthesis box
- no text below `20 px`

---

# Slide 4 — One Local, two bargaining units: preserve Local leadership and add GSU self-governance

## Status
**FORMATTING LOCKED**

## Header
Use common chrome. Long title may use `40–42 px`, max 2 lines.

## Production job
Make the architecture unmistakable: Local 6350 is the enclosing organization; Local-wide governance remains unchanged; Maintainers and GSU are distinct bargaining-unit chapters; the GSU President has a liaison relationship upward, not a Local office or Executive Board seat.

## Outer Local container
- x `120`, y `255`, w `1680`, h `620`
- radius `22`
- fill `#FFFFFF`
- stroke `2.5 px #AFC0D3`

Attach `AFT LOCAL 6350` visually to the outer container itself rather than floating it as an independent peer object.

### Local label
- centered on / just inside the upper border
- compact navy label / pill
- approximately `24 px`, weight `700`
- fill `#0F2747`, white text

## Local-wide governance band
- x `160`, y `295`, w `1600`, h `145`
- radius `16`
- fill `#EEF3F7`
- no heavy internal border

Inside:
- heading `LOCAL-WIDE GOVERNANCE — UNCHANGED`, `22 px`, 700, `#0F2747`
- primary line `President • Vice-President • Treasurer • Secretary`, `24 px`, 700
- secondary line `Existing Executive Board structure preserved`, `20–22 px`, `#334155`

## Divider / lower section label
- divider around y `465`, `2 px #E2E8F0`
- centered lower label around y `490`: `BARGAINING-UNIT CHAPTERS`, `22 px`, 700, `#0F2747`

## Maintainers chapter box
- x `200`, y `545`, w `620`, h `245`
- radius `18`
- fill `#FFFFFF`
- stroke `2 px #CBD5E1`
- title `MAINTAINERS`, `24 px`, 700
- supporting line `Existing unit governance preserved`, `22 px`, `#334155`
- do not diagram Maintainers internal governance further

## GSU chapter box
- x `1100`, y `545`, w `620`, h `245`
- radius `18`
- fill `#EAF2FB`
- stroke `2.5 px #2B5F9E`

Inside:
- title `GRADUATE STUDENT EMPLOYEES / GSU`, `24 px`, 700, `#0F2747`
- officer rows rather than a tall four-item list:
  - `President • Vice President`
  - `Treasurer • Secretary`
- centered downward arrow
- `Representative Council`, `22–24 px`, 700

## Liaison relationship
Draw the liaison specifically from the `President` position inside the GSU box upward to the existing Local-wide governance band.

- stroke `3 px #49627A`
- dashed `8 8`
- small muted `liaison` annotation only if necessary
- must not originate from the whole GSU box
- must not terminate on the Executive Board text in a way that implies membership
- visual weight must remain secondary to the chapter / Local containment structure

## Bottom statement
- centered around y `935`
- `ONE LOCAL • DISTINCT BARGAINING UNITS • DEMOCRATIC UNIT SELF-GOVERNANCE`
- `22 px`, 700, `#0F2747`

## QA
- outer container must immediately communicate that both units remain inside Local 6350
- Local-wide governance must read as structurally above both bargaining-unit chapters without implying day-to-day control of each chapter
- Maintainers and GSU boxes are peers inside the bargaining-unit section
- liaison line reads as communication / coordination only
- no visual cue may imply a GSU Local-wide officer or automatic Executive Board seat
- GSU internal contents remain readable without crowding

---

# Slide 5 — Draft 1 adds GSU governance while preserving Local 6350 leadership

## Status
**FORMATTING LOCKED**

## Header
Use common content-slide chrome. Standard `44 px` title if it fits cleanly; reduce to `42 px` only if necessary.

## Production job
Make the package scope instantly legible: left = broader Local structures preserved; right = GSU-specific governance added or clarified. The rows are parallel for scanning only and must not imply one-for-one replacement.

## Left panel — PRESERVED
- x `96`, y `270`, w `840`, h `550`
- radius `18`
- fill `#FFFFFF`
- stroke `2 px #CBD5E1`
- header bar h `56`, fill `#EEF3F7`
- header `PRESERVED`, `22–24 px`, 700, `#0F2747`

Five horizontal rows separated by `2 px #E2E8F0` rules:
1. `LOCAL LEADERSHIP` — `Pres • VP • Treas • Sec`
2. `EXECUTIVE BOARD` — `existing composition`
3. `MAINTAINERS GOVERNANCE` — `existing structure`
4. `LOCAL FINANCES` — `treasury controls`
5. `LOCAL CONSTITUTION` — `name + amendment process`

Row heading: `20–22 px`, 700. Supporting line: `20 px`, 400, `#334155`.

## Right panel — ADDED / CLARIFIED
- x `984`, y `270`, w `840`, h `550`
- radius `18`
- fill `#FFFFFF`
- stroke `2 px #AFC0D3`
- header bar h `56`, fill `#EAF2FB`
- header `ADDED / CLARIFIED`, `22–24 px`, 700, `#0F2747`

Five horizontal rows separated by `2 px #E2E8F0` rules:
1. `GSU CHAPTER` — `formally defined`
2. `GSU LEADERSHIP` — `Pres • VP • Treas • Sec`
3. `REPRESENTATION` — `Representative Council`
4. `GSU BARGAINING` — `GSU-selected team`
5. `GRAD-WORKER RULES` — `terms • dues • continuity`

Use the same row geometry and typography as the left panel.

## Bottom conclusion strip
- x `270`, y `875`, w `1380`, h `72`
- radius `14`
- fill `#0F2747`
- centered white text: `ADD A GSU GOVERNANCE LAYER — DO NOT REBUILD THE LOCAL`
- `22 px`, 700

## QA
- panels must have equal visual weight
- rows align for scanning but have no arrows or connector semantics between left/right
- bottom conclusion is the strongest object after the title
- no row heading or supporting line should wrap unnecessarily
- keep all body text at or above `20 px`

---

# Slide 6 — Formatting review pending
