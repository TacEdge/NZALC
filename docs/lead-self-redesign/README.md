# Lead Self Workbook Redesign — Phase 1: Development Architecture Audit

**Status:** Phase 1 complete. Decisions reviewed 30 Sep 2026 and updated 1 Oct 2026 for the **two-day NZALC delivery constraint (DC-1)**. Phase 2 has **not** begun. It can begin at the conceptual level without the TAD timetable, which is needed before the architecture is locked (see `07`). The current design position is in `08-decision-log.md`. Docs 01–06 are preserved as the historical audit record; where they conflict with 08, 08 wins.

**Scope:** Reverse-engineer and audit the *Lead Self Leadership Development Workbook, NZ Army Recruit Training (TAD), Version April 2026* (91 PDF pages, 84 numbered pages) against its stated aim and Learning Outcomes. Test it against a proposed developmental spine and identify where Combat Mindset / Performance Under Pressure material could integrate.

## Documents

| # | Document | Answers |
|---|---|---|
| 01 | [Current-state map](01-current-state-map.md) | What is in the workbook, page by page, and what each part is for |
| 02 | [Content audit](02-content-audit.md) | KEEP / MODIFY / MERGE / MOVE / REMOVE for every component, with reasons |
| 03 | [Development journey](03-development-journey.md) | What a recruit experiences now, and where the knowledge → behaviour-change chain breaks |
| 04 | [Proposed architecture](04-proposed-architecture.md) | How the existing content sits against the proposed spine (conceptual only) |
| 05 | [CMC integration map](05-cmc-integration-map.md) | Where Combat Mindset / PUP concepts intersect existing content, strictly from supplied sources |
| 06 | [Reflection and evidence system](06-reflection-and-evidence-system.md) | Whether the reflection tools form one system, and a proposed evidence trail |
| 07 | [Decisions required](07-decisions-required.md) | Status register (SETTLED / PROVISIONAL / OWNER INPUT / BLOCKING), assumptions, owners, plus the **Phase 2 design brief** |
| 08 | [Decision log](08-decision-log.md) | Current design position, log of decisions, owner questions, minimum information for Phase 2 |

## Sources used

| Code | Source | Location | Status |
|---|---|---|---|
| **WB** | Lead Self Workbook (TAD) 2026, Version April 2026 | `reference/Lead Self Workbook (TAD) 2026.pdf` | Current, in use |
| **CN** | *Performance Under Pressure and Combat Mindset in the New Zealand Army*, Draft Capability Note | `tacedge/pup` → `capability-note.md` | **Draft** |
| **FP** | *Combat Mindset Framework Proposal* (responds to COMDT ACS direction, 16 Jul 2026), and its one-page summary | `tacedge/pup` → `way-forward.md`, `output/combat-mindset-onepager-portrait.pdf` | **Draft; decisions sought, not yet approved** |

Material that CN and FP cite but that was **not** supplied: *PUP Workbook*, *Lead Teams Workbook*, *LDS Lead Leaders Workbook*, *ELDA Lead Leaders Workbook (LPR)*, *LSYS (Officers) Workbook May 26*, NZDDP 0.06. Nothing here relies on those documents beyond what CN and FP quote from them.

The "LEARN → PRACTICE → PRESSURE → APPLY → REINFORCE" methodology and the nine-step spine came from the tasking brief. Neither appears in any supplied source document.

## Page-reference convention

`p.N` is the **printed page number** in the workbook footer. The PDF page is `p.N + 7` (e.g. p.14 = PDF page 21). Front matter uses the printed roman numerals (p.ii to p.v).

## Reading order for the review session

1. `03` — the journey and its gaps (15 min). This is the core diagnosis.
2. `06` — the reflection system (10 min). This is where most of the redesign value is.
3. `05` — CMC (10 min). Read the "status of sources" warning first.
4. `07` — make the calls.
5. `01`, `02`, `04` as reference while deciding.
