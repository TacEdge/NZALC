# 07 — Decisions Required Before Redesign

*Status register, updated 1 Oct 2026 for the two-day delivery constraint (DC-1). The record of design positions and their reasons is in [`08-decision-log.md`](08-decision-log.md), which takes precedence over docs 01–06 where they conflict. Docs 01–06 are the historical audit record. **Phase 2 has not begun.***

## Status key

| Status | Meaning |
|---|---|
| **SETTLED** | Design position locked (see 08) |
| **PROVISIONAL** | Working position. Phase 2 may proceed on it, but it may change |
| **OWNER INPUT REQUIRED** | Needs the named owner. Phase 2 proceeds on the stated assumption |
| **BLOCKING PHASE 2** | Phase 2 cannot start without it |

The register also shows whether each item must be resolved **before the final architecture is locked**. Under DC-1 that is a separate gate from starting Phase 2.

## Summary register

| Decision | Subject | Status | Owner | Blocks Phase 2 start? | Needed before architecture lock? |
|---|---|---|---|---|---|
| **DC-1** | **Two days of NZALC delivery; development must continue without further NZALC instruction** (new) | **SETTLED** | — | — | — |
| **D3** | Development structures and learner framing | **SETTLED** | — | — | — |
| **D5-a** | CM / PUP design approach | **SETTLED** | — | — | — |
| **D14** | Resilience definition | **SETTLED** | — | — | — |
| **D18** | Ownership model and two-part workbook (new) | PROVISIONAL | Project lead; TAD to confirm staff role | No | Yes (TAD staff role) |
| **D2/4** | TAD timetable, position of the two days, re-sequencing freedom | OWNER INPUT REQUIRED (**no longer blocking Phase 2 start**) | TAD | **No** | **Yes** |
| **D6** | Pressure tools introduced early (now within the two days) | PROVISIONAL | Project lead | No | No |
| **D17** | Development loop frequency | PROVISIONAL (principle DR-1 SETTLED) | Design team, using TAD input | No | **Yes** |
| **D9/15** | TAD staff involvement after the two days; post-exercise facilitation; onward handover | OWNER INPUT REQUIRED (**priority raised**) | TAD; NZALC; IET schools | No | **Yes** |
| **D1/16** | Assessment regime and doctrine currency | OWNER INPUT REQUIRED | Training design / COG 1 owner; doctrine owner | No | **Yes** (assessment); Phase 4 (doctrine) |
| **D7** | Which reflection tools are LDS-standard | OWNER INPUT REQUIRED | ELDA / Tony | No | **Yes** |
| **D8** | Purpose of twin Lesson Reflection pages | PROVISIONAL (subordinate to DT-1) | ELDA / Tony; project lead | No | No |
| **D11** | Content scope adjustments | PROVISIONAL (**now subordinate to DT-1**) | Project lead | No | No |
| **D5-b** | CM terminology, pilot status, WIN, PUP Workbook | OWNER INPUT REQUIRED | CM Framework programme; NZALC | No | No (Phase 4) |
| **D10/13** | Specialist sign-off: mental health and cultural content | OWNER INPUT REQUIRED | APS; cultural adviser | No | No (Phase 4) |
| **D12** | Format, ownership and privacy | PROVISIONAL | Project lead | No | No (Phase 4) |

**Requirements and tests** (detail in 08 §1.8):

| ID | Requirement / test |
|---|---|
| DC-1 | Two-day delivery |
| DR-1 | Reapply before review |
| DR-2 | Early Identity vs Reputation evidence (intent: Day 1) |
| DR-3 | Ex One / Ex Two remain the major evidence points |
| DR-4 | No new administrative burden |
| **DR-5** | Self-sustaining after NZALC (new) |
| **DT-1** | Topic test (new) |
| **ST-3** | Experience test (new) |

---

## Settled

### DC-1. Two-day delivery constraint — **SETTLED** (new)

> NZALC has **two days** of direct Lead Self delivery at TAD. The design must establish a development process capable of continuing beyond those two days **without relying on further NZALC instruction**.

- The design problem is **not** "fit the workbook into two days". It is "what must a recruit learn, experience, practise and leave with after two days so that they can continue developing themselves through the remainder of TAD?"
- The Phase 1 content findings (docs 01–02) stand. The sequencing assumptions in docs 03, 04 §5 and 06 §4.2, which assumed lessons spread across the course, are superseded.

### D3. Development structures and learner framing — **SETTLED** (unchanged)

| Structure | Sequence |
|---|---|
| NZALC development method | LEARN → PRACTICE → PRESSURE → APPLY → REINFORCE |
| Recruit self-development loop | EXPERIENCE → FEEDBACK → REFLECT → ADAPT → REAPPLY ↺ |
| Pressure thread (not a loop) | PREPARE → PERFORM → RECOVER |

- Learner framing is **"Your Lead Self Journey"**, supported by: *Who am I? How do I affect others? How do I perform? What does the evidence tell me? What will I change?* These are not necessarily chapters.
- DC-1 does not add a model. It concentrates the NZALC method in the two days and makes the recruit loop the engine thereafter.

### D5-a. CM / PUP design approach — **SETTLED** (unchanged)

- Terminology on hold.
- Source-supported integration points only: recognise interference; maintain situational awareness; regulate response; refocus attention; act; review performance.
- No WIN without a source.
- Terminology swappable.

### D14. Resilience definition — **SETTLED** (unchanged)

Retain the workbook definition until CM terminology is approved.

---

## Unresolved

### D18. Ownership model and two-part workbook — PROVISIONAL (new)

| | |
|---|---|
| **Decision required** | Confirm the ownership model and the emerging two-part workbook architecture |
| **Why it matters** | It defines what each party is responsible for, and therefore what the workbook must do on its own after the two days |
| **Design assumption meanwhile** | **NZALC:** two days establishing understanding, self-awareness, behavioural language, practical tools, feedback and reflection capability, and initial development priorities. **TAD:** the environment in which recruits experience, practise, perform under pressure, work with others, receive consequences and feedback, and reapply. **Workbook:** continuity, becoming less a classroom workbook and more a simple personal development tool. **Part 1 — My Lead Self Foundation** supports the two days. **Part 2 — My Lead Self Development** supports the rest of TAD, driven by the recruit loop. TAD instructors are **not** assumed available for extra Lead Self delivery or administration (DR-5) |
| **Emerging two-day intent** | Day 1 *Understand Me and My Impact*; Day 2 *Perform, Learn and Develop*; plus the end-state statement (08 §1.5). **Design intent only. Not a timetable, and content sequencing is not resolved** |
| **Owner** | Project lead. TAD to confirm staff role (Q13) |
| **Blocks Phase 2 start** | No |
| **Needed before lock** | Yes (TAD staff role) |

### D2/4. TAD timetable, position of the two days, re-sequencing freedom — OWNER INPUT REQUIRED

| | |
|---|---|
| **Decision required** | Supply the TAD programme: when the two NZALC days fall, Ex One, Ex Two, field and other pressured activity, existing debriefs/AARs, march-out. Confirm whether the two days' position is fixed |
| **Why it matters** | Phase 2 can design the two days and the Part 2 loop conceptually without it. It **cannot** lock post-NZALC touchpoints, feedback and reapplication opportunities, placement against Ex One / Ex Two, or the end-to-end journey without it |
| **Design assumption meanwhile** | The two days occur early in TAD, before Ex One, and are contiguous. Ex One and Ex Two occur later, with time between them to reapply |
| **Owner** | TAD |
| **Blocks Phase 2 start** | **No** (revised; previously BLOCKING) |
| **Needed before lock** | **Yes** |

### D6. Pressure tools introduced early — PROVISIONAL

| | |
|---|---|
| **Decision required** | Confirm that the comfort-zone check, P = P – I, a small set of mental skills and the SSR are established during the two days |
| **Why it matters** | Under DC-1, anything not established during the two days must be learned from the workbook alone. Recruits face pressure from week one |
| **Design assumption meanwhile** | Within the two days, consistent with the Day 2 emphasis. Less timetable-dependent than before |
| **Owner** | Project lead |
| **Blocks Phase 2 start** | No |

### D17. Development loop frequency — PROVISIONAL (principle DR-1 SETTLED)

| | |
|---|---|
| **Decision required** | The mechanism and frequency by which the recruit loop turns after the two days and between the major evidence points |
| **Why it matters** | This is now the core of Part 2. Without it, the loop turns only at Ex One and Ex Two. With TAD staff assumed unavailable, any mechanism must be recruit-run and peer-supported |
| **Locked principle (DR-1)** | A recruit must have an opportunity to deliberately reapply an identified behaviour and receive some external evidence before the next major LDP review |
| **Design assumption meanwhile** | Ex One and Ex Two remain the major evidence points (DR-3). A lightweight check-in between them is recruit- and peer-run (e.g. a short buddy conversation) and attached to existing TAD activity (DR-4, DR-5). The existing *Rest, Revise, Reflect* evening routine (workbook p.49) is a **candidate** attachment point, to be confirmed with TAD. **Frequency not prescribed** |
| **Owner** | Design team, using TAD input (Q1, Q3) |
| **Blocks Phase 2 start** | No |
| **Needed before lock** | **Yes** |

### D9/15. TAD staff involvement, post-exercise facilitation, onward handover — OWNER INPUT REQUIRED (priority raised)

*Consolidates D9 and D15, extended for DC-1.*

| | |
|---|---|
| **Decision required** | (1) Who currently facilitates the post-Ex One and Ex Two feedback rounds and the LDPs (workbook Ch 13) if NZALC is present for only two days? (2) Are TAD staff available for any Lead Self touchpoint after the two days? (3) Can the final LDP be handed to the next phase or unit? |
| **Why it matters** | DR-3 makes the exercise feedback rounds the major evidence points. They are the strongest existing chain in the workbook. If no one facilitates them, the chain depends entirely on recruits running a structured hot-seat process themselves (risk R1) |
| **Design assumption meanwhile** | NZALC instructors observe and facilitate only within the two days. After that, the exercise feedback rounds must be designed to be **recruit-run with minimal instruction**. TAD staff involvement is optional upside. The final LDP includes a recruit-owned commitment for the next unit; no formal handover is assumed |
| **Owner** | TAD and NZALC (1, 2); IET schools (3) |
| **Blocks Phase 2 start** | No |
| **Needed before lock** | **Yes** |

### D1/16. Assessment regime and doctrine currency — OWNER INPUT REQUIRED

| | |
|---|---|
| **Decision required** | Confirm LOs and aim are fixed. State how LO 1.1–1.3 are assessed at PL 1. **Under DC-1: is assessment completed within the two days, or does it rely on artefacts produced later (e.g. the pre-march-out LDP), and who assesses them?** Confirm doctrinal text is current |
| **Why it matters** | If LO 1.3 is evidenced by an LDP produced after NZALC has left, someone else must assess it, or the assessed artefact must be the one produced within the two days |
| **Design assumption meanwhile** | LOs fixed and verbatim. An initial LDP produced within the two days is assessable evidence for LO 1.3. Later LDPs are developmental. Doctrinal text as printed is current |
| **Owner** | Training design / COG 1 owner; doctrine owner |
| **Blocks Phase 2 start** | No |
| **Needed before lock** | **Yes** (assessment); Phase 4 (doctrine) |

### D7. LDS-standard reflection tools — OWNER INPUT REQUIRED

| | |
|---|---|
| **Decision required** | Are DEB/DESC, Keep/Stop/Start, Strength/Development Area rating, SSR and the hot-seat round LDS-standard? |
| **Why it matters** | Under DC-1, these tools must be learned in two days and then used without an instructor. Their number and complexity now matter more |
| **Design assumption meanwhile** | Treat as standard. Keep formats. Vary frequency and linkage. Prefer the smallest set a recruit can run alone |
| **Owner** | ELDA / Tony |
| **Blocks Phase 2 start** | No |
| **Needed before lock** | **Yes** |

### D8. Twin Lesson Reflection pages — PROVISIONAL (subordinate to DT-1)

Assumption: collapse the twins. Under DC-1 and DT-1, the lesson-by-lesson reflection pattern is itself under test. Owner: ELDA / Tony to confirm original intent.

### D11. Content scope adjustments — PROVISIONAL (now subordinate to DT-1)

- The specific scope assumptions recorded on 30 Sep (Instruction Styles; Five-Step and OODA; Functional Leadership; frame of reference; framework table to appendix) are retained as **inputs**.
- Every existing subject is now subject to the **DT-1 topic test**: is it a concept, tool, lens, activity, prompt or supporting reference within the journey, rather than automatically a standalone lesson?
- **Nothing is removed or merged yet.** The doc 02 classifications are inputs to DT-1, not final.

### D5-b. CM terminology, pilot status, WIN, PUP Workbook — OWNER INPUT REQUIRED

Unchanged. Assumption: neutral, swappable labels on the source-supported integration points; no WIN; Red Head–Blue Head and Prepare–Perform–Recover named but not elaborated. Owner: CM Framework programme; NZALC (PUP Workbook). Needed before Phase 4 content.

### D10/13. Specialist sign-off — OWNER INPUT REQUIRED

Unchanged. APS (mental-health continuum and the self-location prompt); cultural adviser (Tōtara and te reo). Needed before Phase 4.

### D12. Format, ownership and privacy — PROVISIONAL

Unchanged. Assumptions: format-neutral; peer sheets separate from the bound workbook; privacy rule *mine / shared with my section / seen by instructors*. Under DC-1, Part 2 must be physically portable and quick to use in barracks and in the field. Needed before Phase 4.

---

## Assumptions and risks created by DC-1

### Assumptions (to confirm)

| # | Assumption | Confirm with |
|---|---|---|
| A1 | The two NZALC days are **contiguous** | TAD |
| A2 | The two days fall **early in TAD, before Ex One** | TAD |
| A3 | TAD instructors are **not** available for additional Lead Self delivery or administration | TAD |
| A4 | Recruits keep the workbook with them through TAD and have some routine personal time in which to use it | TAD |
| A5 | An initial LDP produced within the two days can serve as LO 1.3 evidence | COG 1 owner |

### Risks

| # | Risk | Effect | Mitigation for Phase 2 to explore |
|---|---|---|---|
| **R1** | **No facilitator for the Ex One / Ex Two feedback rounds** after NZALC leaves | The strongest existing evidence chain (DR-3) degrades or does not happen | Resolve Q12 urgently. Design the rounds to be recruit-run from a one-page script rehearsed during the two days |
| R2 | **Decay.** A self-run process competes with a heavy TAD schedule and fades without an external prompt | Part 2 goes unused after week one | Attach to existing TAD events (DR-4); keep each use to minutes; buddy pairing creates mutual prompting |
| R3 | **Peer feedback quality** without instructor coaching | Vague or unsafe feedback; low trust in the process | Practise feedback during the two days (DR-2); DEB/DESC as the single format |
| R4 | **Cramming.** Two days invite compressing 91 pages of content | Recreates the content problem in less time; Day 2's emphasis list is already long | DT-1 and ST-3 applied rigorously |
| R5 | **Timing unknown.** If the two days fall after Ex One, or are split, the early feedback point and the exercise review structure change | Rework of the Part 2 design | Design Part 2 around *events*, not dates; confirm A1/A2 early |
| R6 | **Assessment gap.** If LO 1.3 relies on the pre-march-out LDP, no NZALC assessor is present | LO cannot be assessed as designed | Resolve Q4; A5 as fallback |
| R7 | **TAD staff unaware of the shared language** (Above the Line, comfort zone, DEB/DESC) | Recruits use a language their instructors don't reinforce; CN expects units to "reinforce common language" | Raise with TAD as an option, e.g. a one-page staff brief. **Not assumed** |
| R8 | **Audit classifications assumed lesson-based delivery** | Doc 02's KEEP/MODIFY verdicts may not hold under DC-1 | Treat as inputs to DT-1 (D11) |

---

## Source material required

| Needed | For | Decision | Needed before |
|---|---|---|---|
| TAD training programme / timetable, incl. the two NZALC days | Post-NZALC touchpoints; final journey | D2/4, D17 | Architecture lock |
| Who facilitates post-exercise feedback and LDPs now | DR-3 viability | D9/15 | Architecture lock (**priority**) |
| COG 1 assessment specification | LO 1.3 evidence | D1/16 | Architecture lock |
| Evidence of which reflection tools are LDS-standard | Tool set | D7 | Architecture lock |
| NZALC PUP Workbook | Red Head–Blue Head, Prepare–Perform–Recover, mental-skills practice | D5-b, D6 | Phase 4 |
| WIN source (only if wanted) | "Refocus attention" | D5-b | Phase 4 |
| Current two-day NZALC lesson plans (if any) | Avoid discarding what works in delivery | D18 | Phase 2 (useful) |
| CM Framework decision (COMDT ACS) | Terminology | D5-b, D14 | Phase 4 |

---

# DESIGN BRIEF FOR PHASE 2

*Phase 2 has not begun. It may begin at the conceptual level without the TAD timetable. The timetable is overlaid before the architecture is locked. This brief reflects the design position in 08 as of 1 Oct 2026.*

## The design problem

> **What must a recruit learn, experience, practise and leave with after two days with NZALC so that they can continue developing themselves through the remainder of TAD, without further NZALC instruction?**

The problem is not to fit the existing workbook into two days.

## Purpose

Design the **developmental architecture** of:

- **(a)** the two-day NZALC intervention at the conceptual level, and
- **(b)** the workbook as a two-part tool: Part 1 *My Lead Self Foundation* and Part 2 *My Lead Self Development*.

It covers how the three structures (D3) connect, how the recruit loop is handed over and keeps turning, the evidence trail, and the role of every existing subject and activity. **Phase 2 does not design pages and does not produce a detailed two-day timetable.**

## Fixed constraints

1. **DC-1:** two days of NZALC delivery. After that, the process works without NZALC instruction (DR-5). TAD staff are not assumed available.
2. Course aim and LO 1.1–1.3: verbatim.
3. Leadership Framework, Value Adds, Key Elements, Essential Tasks, Behaviour Statements, Mission/Vision/Ethos/Values and te reo: verbatim. Only placement and presentation can change.
4. The three structures in D3 are **connected, not combined**. No new developmental model.
5. Ex One and Ex Two remain the major evidence points (DR-3).
6. DEB/DESC and SSR formats are kept.
7. DR-1, DR-2 and DR-4 are met.
8. No invented doctrine, including CM/PUP. Gaps are flagged, not filled. Terminology is swappable (D5-a).

## What Phase 2 must produce

| # | Output | Description | Timetable needed? |
|---|---|---|---|
| 1 | **Two-day end-state specification** | The desired end state (08 §1.5) broken into the capabilities NZALC must establish, each with how it would be evidenced by the end of Day 2 | No |
| 2 | **Two-day conceptual design** | What must happen on Day 1 and Day 2 to produce the end state, including the early feedback experience (DR-2) and the handover of the recruit loop. Not a timetable | No |
| 3 | **DT-1 topic test results** | Each existing subject classified as concept / tool / lens / activity / prompt / supporting reference, with its role in Part 1, Part 2 or both | No |
| 4 | **ST-3 experience test results** | Each existing activity tested against prepare / perform / extract, with justification for any that fail but remain | No |
| 5 | **Part 2 loop design** | The recruit-run EXPERIENCE → FEEDBACK → REFLECT → ADAPT → REAPPLY tool: what it asks, what it produces, and how a recruit and buddy run it without an instructor | No |
| 6 | **Evidence trail and Identity vs Reputation thread** | From the Day 1 baseline to march-out | Partly |
| 7 | **Pressure / performance integration points** | Where the six source-supported points sit across the two days and Part 2 | No |
| 8 | **Touchpoint map** | Post-NZALC feedback and reapplication points placed on the TAD programme (D17) | **Yes** (provisional until timetable) |
| 9 | **Traceability matrix** | LO → Value Add → component → evidence produced | Partly (D1/16) |
| 10 | **Interactive "Architecture Lab"** (optional) | An HTML tool for placing content blocks and seeing coverage update | No |

## Design principles

- **Two days to start a process, not to cover content.**
- **The workbook becomes a personal tool.** It progressively becomes less of a classroom workbook and more of a simple personal development tool.
- **Self-sustaining.** Everything after the two days can be run by a recruit and a buddy (DR-5).
- **Soldier-centred and plain-language.** Written for an 18-year-old recruit.
- **Behaviour-focused.** Reflections ask about observable actions and words.
- **Evidence over opinion.**
- **Every plan is reapplied and reviewed** (DR-1).
- **Identity vs Reputation is experienced, not just taught** (DR-2).
- **No new administrative burden** (DR-4).
- **Pressure is the environment, not a chapter.**
- **Value Adds are visible throughout.**
- **Doctrinal accuracy over design novelty.**

## Success tests for Phase 2

**Primary tests**

1. Does the recruit reapply their priority with outside evidence before the next major review? (DR-1)
2. Does Identity vs Reputation evidence arrive well before Exercise One? (DR-2)
3. **Does every workbook activity either prepare the recruit for an experience, help the recruit perform through an experience, or help the recruit extract development from an experience?** If not, it needs a clear justification for remaining (ST-3).

**Supporting tests**

4. At the end of Day 2, could a recruit honestly make the end-state statement (08 §1.5)?
5. Can Part 2 be run by a recruit and a buddy without an instructor present?
6. Can we trace any line in a recruit's final LDP back to a specific event and specific feedback?
7. Does every LO have evidence produced at least twice?
8. Does every existing doctrinal element have a home (as content, reference or prompt)?
9. Would a TAD section commander recognise the programme in it, without finding a new form or process to administer?
10. Can the PUP/CM terminology be changed without restructuring?

## Out of scope for Phase 2

Page layouts, visual design, HTML prototypes of learner pages (Phase 4–5), a detailed two-day timetable or lesson plans, rewriting doctrinal text, and resolving Combat Mindset terminology.
