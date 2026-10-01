# Phase 2 — Lead Self Experience Architecture

**Status:** Reviewed 1 Oct 2026. Core architecture **provisionally accepted, pending lightweight user validation** (`10`). Concept demonstrator (`../concept-prototype/`) reviewed by CI NZALC: product direction **provisionally accepted, pending the same validation** (09 §0). **HOLD before Phase 3.** Not a workbook design, not visual design, not a timetable.

**Central question.** What must happen during the two Section Commander-delivered Lead Self days in Week 1 to start a development process that recruits can continue through TAD, supported by their Section Commander? And how does that process stay alive after Day 2 without becoming extra administration?

**Governing record.** `../08-decision-log.md` (start at §1.0). Phase 1 documents in `../` are unchanged.

## Documents

| # | Document | Answers |
|---|---|---|
| 01 | [Recruit end state](01-recruit-end-state.md) | What the recruit leaves Day 2 knowing, able to do, holding as evidence, and committed to |
| 02 | [Two-day experience architecture](02-two-day-experience-architecture.md) | What Day 1 and Day 2 must do, as experience blocks rather than chapters |
| 03 | [Development loop design](03-development-loop-design.md) | EXPERIENCE → FEEDBACK → REFLECT → ADAPT → REAPPLY for a recruit, a peer, the Section Commander and the workbook |
| 04 | [Section Commander role](04-section-commander-role.md) | The minimum useful Section Commander behaviours, and what Train the Trainer must give them |
| 05 | [Workbook role and architecture](05-workbook-role-and-architecture.md) | Why the workbook goes unused, and what Part 1 and Part 2 should be |
| 06 | [Content placement test](06-content-placement-test.md) | DT-1 and ST-3 applied to every existing topic and activity |
| 07 | [Pressure integration](07-pressure-integration.md) | The six source-supported mechanisms, placed across the system |
| 08 | [Architecture test](08-phase2-architecture-test.md) | ST-1 to ST-5, with verdicts and conditions |
| 09 | [Phase 3 decisions required](09-phase3-decisions-required.md) | What must be decided before detailed design (Phase 2 decision register) |
| 10 | [Validation plan](10-validation-plan.md) | Lightweight conversations with recruits and Section Commanders to test ST-4 and ST-5 |

`TIMETABLE DEPENDENT` marks every placement that cannot be fixed without the TAD programme.

---

## The proposed system on one page

### Who does what

| Role | Party |
|---|---|
| **Owner of development** | **Recruit** |
| Coach, observer, feedback source | **Section Commander** (Cpl), as part of normal section leadership |
| Observer and feedback partner | **Buddy** (one paired recruit) |
| Development tool and evidence thread | **Workbook**: Part 1 Foundation and Part 2 Development |
| Environment where behaviour is practised, pressured and reapplied | **TAD training** |
| System designer; develops Section Commanders | **NZALC**, through Train the Trainer (T3) |

### The system end to end

```
 BEFORE COURSE        WEEK 1: TWO LEAD SELF DAYS (Section Commander-delivered)          REST OF TAD (recruit-owned, Section Commander-supported)
┌─────────────┐   ┌───────────────────────────────────────────────────────────┐   ┌──────────────────────────────────────────────────────────────────────┐
│ NZALC T3    │   │ DAY 1  Understand me and my impact                         │   │                                                                      │
│ → Section   │   │  Who am I? ── identity statement ("how I want my section    │   │   EVERYDAY TAD TRAINING                                              │
│   Commanders│   │               to experience me")                           │   │   recruit holds priority · buddy notices · Section Commander  │
│   experience│   │  How do I affect others? ── section task ──▶ buddy +        │   │   asks one question at natural moments ("How did your priority go    │
│   the loop, │   │     Section Commander observe ──▶ first feedback ──▶        │   │   today?") · pressure debrief after hard days (optional, 2 min)      │
│   learn to  │   │     intention vs impact ──▶ first insight                  │   │                       │                                              │
│   deliver,  │   │                                                            │   │                       ▼                                              │
│   coach,    │   │ DAY 2  Perform, learn and develop                          │   │   CHECKPOINT(S) before Ex One · TIMETABLE DEPENDENT                  │
│   observe,  │   │  How do I perform? ── interference, zone check, regulate,  │   │   buddy: "did you do it, what did I see?" · 1 line in Part 2         │
│   facilitate│   │     refocus, SA ──▶ PREPARE ─ pressure task ─ RECOVER      │   │                       ▼                                              │
│   feedback  │   │  ★ First REAPPLY of Day 1 insight, observed by buddy        │   │ ═ EX ONE ═ PREPARE → PERFORM → RECOVER                               │
│   rounds    │   │  What does the evidence tell me? ── evidence from both days │   │   Section Commander-facilitated feedback round (self + peers +       │
│             │   │  What will I change? ── first priority                      │   │   Section Commander) ──▶ review priority ──▶ LDP-1 (recruit-owned)   │
│             │   │     "When ___, I will ___"                                 │   │                       ▼                                              │
│             │   │  Hand-over: the loop named (already done once) · buddy      │   │   REAPPLY in training · checkpoint(s) · TIMETABLE DEPENDENT          │
│             │   │     pairs · Part 2 · how the Section Commander will check in│   │                       ▼                                              │
│             │   │  Leaves with: priority · evidence · Part 2 (format TBD) ·   │
│             │   │     buddy                                                  │   │ ═ EX TWO ═ same round ──▶ "did LDP-1 work?" ──▶ LDP-2                │
└─────────────┘   └───────────────────────────────────────────────────────────┘   │                       ▼                                              │
                                                                                  │ MARCH-OUT: identity statement revisited ("what evidence shows I've   │
                                                                                  │ changed?") · section commitment revisited · next-unit priority       │
                                                                                  └──────────────────────────────────────────────────────────────────────┘
```

### Three structures, connected, not combined (08 §1.3)

| Structure | Where it runs |
|---|---|
| **NZALC method:** LEARN → PRACTICE → PRESSURE → APPLY → REINFORCE | The shape of the two days (and of T3) |
| **Recruit loop:** EXPERIENCE → FEEDBACK → REFLECT → ADAPT → REAPPLY ↺ | Turns once inside the two days (Day 1 → Day 2), then through the rest of TAD. Ex One and Ex Two are the major turns |
| **Pressure thread:** PREPARE → PERFORM → RECOVER | The frame around the Day 2 pressure task, Ex One and Ex Two, and any hard day |

## Five headline design moves

1. **The loop is done before it is explained.** Recruits complete one full turn inside the two days: Day 1 feedback leads to a Day 2 reapply, with evidence. Day 2 then *names* what they have just done. They leave having practised the method, not just heard about it.
2. **Identity vs Reputation is the first experience, not the first diagram.** A real section task on Day 1, observed by a buddy and the Section Commander, gives every recruit evidence of the gap between what they intended and how others saw it, inside their first week.
3. **The Section Commander's core contribution is one question at natural moments:** *"You said your priority was X. How did you go today?"* Plus facilitating the two exercise feedback rounds. No extra lessons and no workbook checking.
4. **Part 2 is defined by function, not format.** It must let the recruit quickly see their priority, capture evidence when needed, reflect briefly, update the priority, and build the LDP (FR-1 to FR-8). It is optimised for use, not completion. **Its physical form is unresolved** until we know what recruits actually carry and use. Most of the developmental effect after Day 2 comes from conversations.
5. **No topic earns a standalone lesson by default.** A topic gets deliberate instruction only where recruits need knowledge, a model or a tool before they can practise the behaviour (06 §1.1). Six topics are the strongest current candidates. Trust, Conflict, Judgement and Above/Below the Line remain open.

## Biggest risks to this architecture

- **Section Commander buy-in and consistency.** The system relies on them more than any other element. The T3 package becomes a primary product.
- **The unconfirmed reason recruits don't reopen the workbook.** The hypotheses in 05 are being tested through the validation plan (`10`) before any format is chosen.
- **Feedback from a Section Commander may feel like assessment.** The distinction between developmental feedback and formal assessment is kept explicit and unresolved (04 §5.1, 09 B6).
