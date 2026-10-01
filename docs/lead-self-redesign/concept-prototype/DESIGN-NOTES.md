# Concept Demonstrator — Design Notes

*Maps each prototype moment to the Phase 2 architecture, the source material, the Learning Outcomes and Value Adds where supported, its status, and the assumptions it rests on. Reference codes: Phase 1 docs `../0N-*.md`; Phase 2 docs `../phase-2/0N-*.md`; decision log `../08-decision-log.md`; workbook page numbers are printed page numbers.*

## Global design decisions (all provisional unless stated)

| Decision | Status | Basis |
|---|---|---|
| One coherent story with pre-filled example entries, editable, carried across screens | Prototype choice | Demonstrates the evidence thread (Phase 2 03 §6) better than blank forms would |
| Five questions shown as the journey strip, not as chapters | **Settled** (08 §1.4) | |
| Day 1 / Day 2 / Part 2 labels; "Orientate" not used | Settled (08 L5) | |
| Doctrinal text quoted verbatim with citation; recruit-facing text is new | **Settled** constraint | Phase 2 brief, fixed constraint 3 |
| Section Commander view as a toggle, not a separate product | Prototype choice | T3 package is out of scope (stop condition) |
| Reviewer view with status chips | Prototype choice | Brief §8 |
| Palette and type from the NZ Army tokens in the PUP repository (swamp, kawakawa, waiouru, moawhango, NZDF red); condensed display face | Prototype choice | Brief §6. Not a brand decision; NZDF brand rules apply at Phase 4 |
| Part 2 screens show function only; a reviewer-mode banner says so | **Settled** that format is unresolved (08 L26) | |
| Mechanism labels under pressure are neutral working labels | Settled (08 §1.7) | No CM terminology, no WIN |

## Moment-by-moment map

Status key: **S** settled · **P** provisional · **TT** timetable dependent · **V** depends on validation · **U** unresolved (format / assessment).

### 1. Cover — Your Lead Self Journey
- **Architecture:** 08 §1.4 learner framing; Part 1 / Part 2 (08 §1.6).
- **Source:** New. Te reo "Taki Tūwā" from workbook p.3/p.4.
- **LO / VA:** —
- **Status:** S (frame); P (Part naming).
- **Assumptions:** none.

### 2. Why this matters
- **Architecture:** Phase 2 02 block 1A; principle P1 (experience before explanation).
- **Source:** Leadership definition verbatim, NZDDP 0.06 para 1.11 via workbook p.1. Rest is new recruit-facing gloss.
- **LO / VA:** LO 1.2 (orientation to Lead Self).
- **Status:** P (wording).
- **Assumptions:** Section Commander can deliver this framing in their own words (T3 requirement T1, T3).

### 3. Lead Self expectations
- **Architecture:** Phase 2 02 block 1A; 06 §1.3 (Value Adds: explicit instruction candidate).
- **Source:** Value Add sentences and full text verbatim from workbook p.4 / pp.71–74. Behaviour Statements verbatim from pp.5–6.
- **LO / VA:** LO 1.2; all four Value Adds.
- **Status:** S (doctrine verbatim); P (explicit instruction); **P (mapping)**: grouping Behaviour Statements under each Value Add follows the audit's indicative mapping (Phase 1 01 §4), not a doctrinal one.
- **Assumptions:** ELDA confirms the indicative mapping, or supplies the authoritative one. Full Framework table remains reference (06).

### 4. Who am I?
- **Architecture:** Phase 2 02 block 1B; 01 V1, M3; DR-2.
- **Source:** Identity/reputation definitions verbatim, workbook p.7. Values commitment from p.17.
- **LO / VA:** LO 1.1; underpins Support Others ("regularly reflecting on their behaviour…").
- **Status:** S (early identity statement); P (prompt wording).
- **Assumptions:** privacy rule for this entry (D12, 09 B3).

### 5. Experience — observed section task
- **Architecture:** Phase 2 02 block 1D; principle P4 (the section is the unit).
- **Source:** Task adapted from workbook pp.47–49 (specified/implied tasks; first-parade and RRR routine synchronisation).
- **LO / VA:** LO 1.2; Follow Leader's Intent; Support Others (team contribution).
- **Status:** **P (task choice)**, S (an observed real task on Day 1). TT for interaction with other week-1 serials.
- **Assumptions:** section size allows one buddy per recruit and one Section Commander observation each (09 O5); the task is real enough to generate behaviour worth observing.

### 6. Feedback — what I intended vs what they saw
- **Architecture:** Phase 2 02 block 1E; brief §C steps 3–5; 01 C2–C4, V2, V3; 06 §2.3 (DEB/DESC kept).
- **Source:** Feedback purposes and DEB/DESC, workbook pp.10–11; "feedback… the primary tool for aligning identity and reputation" (p.10).
- **LO / VA:** LO 1.1; Support Others; Pursue Excellence ("provide honest feedback…").
- **Status:** S (DEB/DESC; intention-vs-impact explicit); **V** (AS-4 peer feedback usefulness; AS-5 Section Commander feedback safety); **U** (assessment relationship, 04 §5.1).
- **Assumptions:** recruits will give specific, honest observations in week 1 with a Section Commander present. If validation finds self-censoring, the buddy carries more of this moment and the Section Commander's observation moves to the exercises.

### 7. One priority
- **Architecture:** Phase 2 01 C8, M1; 03 rule L1; 09 A4.
- **Source:** Replaces the chapter Keep/Stop/Start (Phase 1 02 reflection group). Behaviour Statement example "Get others' input into decisions." verbatim, p.5.
- **LO / VA:** LO 1.3 (the seed of the LDP); tagged to one Value Add.
- **Status:** S (one active priority); **P ("When / I will" format)**; D7 dependency (if Keep/Stop/Start is an LDS-standard tool required at this point).
- **Assumptions:** Section Commander checks each priority is observable (T3 skill T5); a section priority list held by the Section Commander is acceptable (09 B3).

### 8. Pressure — how do I perform?
- **Architecture:** Phase 2 02 blocks 2A–2B; 07 mechanisms M1–M4; D6 (pressure tools early).
- **Source:** Comfort Zone and stretch-zone test, workbook p.8 (quoted in substance); Performance = Potential − Interference, p.58; tools from p.59 (tactical breathing, grounding, instructional self-talk), p.34 (SA levels), p.54 (circle of concern). Draft Capability Note §2–3 for the interference framing.
- **LO / VA:** LO 1.1; Pursue Excellence ("Practice resilience skills to stay calm"); Apply Good Judgement ("remaining calm and increasing their situational awareness").
- **Status:** S (source-supported mechanisms only); **P (neutral labels; subset of tools; placement on Day 2)**.
- **Assumptions:** Red Head–Blue Head is not shown because no supplied source defines it (07 §1); PUP Workbook needed (D5-b). Mental-health continuum not shown here; pathway appears at moment 11.

### 9. Reapply under pressure
- **Architecture:** Phase 2 02 block 2C (the loop's first full turn); 07 §3 (Prepare → Perform → Recover as frame); 01 E4–E5, V4, V5, C7.
- **Source:** SSR questions simplified from workbook p.63; Prepare–Perform–Recover named in the Capability Note (detail not supplied).
- **LO / VA:** LO 1.1, 1.2; Apply Good Judgement ("Make decisions in the required time").
- **Status:** S (reapply with evidence inside the two days); **P (pressure task design, 09 O9)**; P (four-question debrief).
- **Assumptions:** a pressure task can be run safely by a Section Commander in week 1 (T3 T6); buddy can observe one behaviour under task load.

### 10. The loop, revealed
- **Architecture:** 08 §1.3 recruit loop; Phase 2 02 block 2G principle "experienced before named"; 01 §1 (loop maps to Behaviour Statements).
- **Source:** Loop wording is the settled design position, not doctrine. Each step's doctrinal anchor is listed in Phase 2 01 §1.
- **LO / VA:** LO 1.3 (method for continuing development); Pursue Excellence ("Acknowledge that personal and professional development is essential and you must own this").
- **Status:** **S**.
- **Assumptions:** none beyond the architecture.

### 11. Handover
- **Architecture:** 08 §1.0 ownership model; Phase 2 04 §2 five behaviours; 02 block 2G; DR-5 (revised).
- **Source:** New. Support pathway references workbook p.60 (content not reproduced).
- **LO / VA:** LO 1.3.
- **Status:** S (ownership; five behaviours as working minimum); **V (ST-4)**.
- **Assumptions:** Section Commanders accept the coaching role and the "doesn't check your book" framing; APS sign-off on how the support pathway is worded (D10/13).

### 12. Everyday
- **Architecture:** Phase 2 03 §3–4.1 (everyday intensity, no record); 05 FR-1, FR-2; 04 §2.1 support-vs-administer.
- **Source:** New.
- **LO / VA:** LO 1.3 in practice; Pursue Excellence.
- **Status:** S (no written entry); **V (AS-6, AS-8: do these moments exist)**; **U (format)**.
- **Assumptions:** Section Commanders have natural moments to ask one question (validation SC-5, SC-6, SC-9).

### 13. Checkpoint
- **Architecture:** Phase 2 03 §4.2; D17; DR-1; 05 FR-3, FR-4, FR-6.
- **Source:** New. Candidate attachment points include the RRR routine (workbook p.49).
- **LO / VA:** LO 1.3.
- **Status:** **TT (placement)**; **P (frequency)**; S (DR-1 principle); **U (format)**.
- **Assumptions:** recruits have a reachable place to write four lines, and a buddy moment to do it (validation R-4, R-5, AS-2, AS-3).

### 14. Exercise One review and LDP
- **Architecture:** Phase 2 03 §4.3 (major intensity); DR-3; Phase 1 06 §4.3 (LDP fields added); 05 FR-5, FR-7, FR-8.
- **Source:** Existing mechanism retained from workbook pp.68–77 (self-assessment, peer feedback, summary, LDP with Keep/Stop/Start and situations). Added fields: evidence citation; identity vs reputation now; "what will others see"; "how will I know"; strength handled as "keep and use deliberately where".
- **LO / VA:** **LO 1.3** (LDP), LO 1.1 (identity vs reputation comparison); all Value Adds via tagging.
- **Status:** S (Ex One/Two as major evidence points); **V (AS-7: who facilitates this round now)**; **U (assessment: is this LDP or the Day 2 priority the LO 1.3 artefact, D1/16)**; **U (format)**; D7 dependency on Keep/Stop/Start.
- **Assumptions:** the round replaces existing post-exercise activity rather than adding to it (validation SC-4). Peer counts ("3 of 7") assume a section of about seven; section size unconfirmed.

### 15. Development over time, and march-out
- **Architecture:** Phase 2 03 §6 evidence thread; brief §N timeline; 01 M3–M4 (values and section commitments revisited, not shown on screen).
- **Source:** Final LDP from workbook p.84, extended with "what evidence shows I've changed?".
- **LO / VA:** LO 1.1, 1.3.
- **Status:** **TT (every placement after Day 2)**; P (march-out content); D9/15 (onward handover not assumed).
- **Assumptions:** the recruit still has the evidence thread at march-out (format-dependent).

## Provisional design assumptions introduced by the prototype itself

These are choices made to build a coherent demonstrator. None is an architecture decision.

| # | Assumption | Where | Why it matters |
|---|---|---|---|
| A | A **single fictional example** (a recruit who takes over under pressure) runs through all screens | 3–15 | Makes the thread legible; a real recruit's thread will be messier and less complete |
| B | The Day 1 task is the **routine-planning** task | 5 | Leading candidate only (09 O9) |
| C | The Day 2 pressure task is described generically ("a clock on it and a plan that changes partway") | 9 | Task design is Phase 3; safety and feasibility unconfirmed |
| D | **Buddy** feedback is split into "got in the way" and "helped" with a Section Commander line alongside | 6 | Mirrors DEB/DESC; the exact sheet is Phase 3 |
| E | The Section Commander gives **one** observation per recruit on Day 1 | 5–6 | Feasibility depends on section size and time (09 O5) |
| F | Behaviour Statements are grouped under Value Adds using the audit's **indicative** mapping | 3 | Needs ELDA confirmation |
| G | Five mental skills are shown as the Day 2 subset | 8 | Selection is provisional; PUP Workbook not supplied |
| H | Checkpoint shown as **four lines**; evidence thread shown as a list of quotes | 13, 15 | Function only; format unresolved |
| I | Peer feedback at Ex One summarised as **counts** ("3 of 7") | 14 | A proposed way to make reputation visible; section size assumed |
| J | The LDP shows **Keep/Stop/Start** for the development area and "keep and use deliberately where" for the strength | 14 | Subject to D7 |
| K | Values commitment and section commitment are **not** shown being revisited at march-out | 15 | Omitted to keep the screen small; both remain in the architecture |
| L | The **support pathway** is referenced in one sentence, not reproduced | 11 | APS content ownership (D10/13) |
| M | The recruit is addressed as "you"; the Section Commander is named by role | all | Avoids inventing persons |
| N | **Visual language** draws on the PUP repository tokens and a condensed display face | all | Not a brand decision |

## What would change this prototype

Per `../phase-2/10-validation-plan.md` §6: adjustments are expected after validation; redesign only on material contradiction. The screens most exposed are 6 (if feedback with a Section Commander present is not safe), 12–13 (if no natural moments or carried item exist), and 14 (if no facilitated post-exercise round exists).
