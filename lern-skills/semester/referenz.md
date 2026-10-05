# Reference – Mobile UX Prototyping (companion to the study partner, v1.2, 2026-10-03)

*Everything here also stands in the course script; the script remains the binding source. This file exists so the assistant works with the module's definitions instead of its own.*

## The semester's topics and learning objectives

| # | Topic | Core conflict (one sentence) | LO |
|---|---|---|---|
| 1 | Claims and their sources | The most-cited statistic of the field is seven years old – and nobody notices, because it sounds plausible. | 5 |
| 2 | Patterns as a language | Patterns are congealed experience – and precisely therefore potentially outdated the moment you need them. | 3 |
| 3 | Severity: formula and rubric | The redesign wanted to do everything right and cost 1.7 stars: the most severe flaw bothers nobody in the review. | 3 |
| 4 | The fidelity decision | High fidelity has become free – and therefore worthless as a signal of maturity. | 1 |
| 5 | Building with the machine | The tool builds faster than you can think – so which of you is designing? | 2, 4 |
| 6 | Anchor I: The audit lab | The generated UI passes every first glance and fails the concrete context. | 4, 3 |
| 7 | Friction by design | The same company that defends friction as protection ran an install flow that 65 % of users abandoned, until one simplification cut the drop-offs by 60 %. | 3, 9 |
| 8 | Notifications: designing against the filter | Your notification competes against an AI filter that summarizes, throttles, or silences it. | 7 |
| 9 | Offline states and sync conflicts *(no in-class session this term – self-study from the script)* | The sync engine is production-ready in 2026 – the UX of the conflict case is unresearched. | 8 |
| 10 | Dark patterns: naming and judging | Between persuading and manipulating runs a line that carries €120-million fines – and that nobody can draw sharply. | 9 |
| 11 | Anchor II: The Brussels hearing | Infinite scroll and autoplay are either good engagement design or a legal violation – being fought over right now. | 9, 7, 5 |
| 12 | Defending your design *(no in-class session this term – self-study from the script)* | In the final presentation I examine the trace that building left in your thinking: your decisions, your discards, and what they cost. | 6, 2 |
| 13 | Apps and the agent thesis | The claim that AI agents will replace apps is unsupported – and could still be true. | 5, 4 |

Learning objectives (short form): LO1 fidelity decision · LO2 iterative building with AI as a tool · LO3 pattern analysis and severity ranking · LO4 auditing AI-generated UIs/analyses · LO5 sourcing market claims · LO6 presenting and moderating · LO7 notification strategy · LO8 offline/conflict UX · LO9 dark patterns and regulation. All nine are graded. LO8 (offline) is checked in every concept (self-assessment S9); LO7 and LO9 count in the presentation and the seminar paper wherever the student's project takes them up. Everyone trains all three in the regular exercises U4 and U5. Every topic's closing section names the graded objectives.

Session structure: **one 90-minute lecture per topic**, plus exercise double sessions, each covering two topics: U1 = Topics 1+2 · U2 = Topics 3+4 · U3 = Topics 5+6 · U4 = Topics 7+8 · U5 = Topics 9+10 are the regular, required exercises (no upload of their own, no bonus points; they build the material for Parts A, B, C and the seminar paper). Topics 11 to 13 have no exercise sheet. Topic 13 ends with an ungraded final task (the dated prediction). Every lecture ends with a **bridge task: voluntary, posted on the topic's Padlet** – no submission, no deadline, no penalty. Exercise teams have **three people, four only if the numbers do not divide**.

Semester plan: 14 weeks are planned, and two topics are droppable. This term both drop: **Topics 9 and 12 have no in-class session**; their material is fully covered in the script, and the topic skill for Topic 9 and the skill `defense-rehearsal` support the self-study. The offline part of Exercise U5 is prepared from the script.

## Assessment structure

No written exam. The assessment is a **seminar paper plus a presentation**, the presentation staged in three graded parts:

- **Part A** and **Part B:** 15 minutes each, in your team with the lecturer, not in front of the class – 20 points each. **Part A** runs within Exercise U2 (26 October / 2 November): design question, fidelity decision (rung) with its reasons, and the self-named blind spot. **Part B** runs within Exercise U4 (23 / 30 November): the state of the prototype, including the mandatory section *Discarded alternatives*.
- **Part C**, the final presentation: 15 to 20 minutes per team in front of the whole exercise group, plus a discussion the team moderates – about 30 minutes per team, 30 points. Week 14 (13 January) is only the make-up date for Part C in case of illness.
- The **seminar paper**: about 5,000 words that record your decisions – 30 points, due Friday, 15 January 2027.
- **Uploads**, the only four of the module: Friday, 23 October (A) · Friday, 20 November (B) · Friday, 18 December (C) – both exercise groups, regardless of their own presentation date – and Friday, 15 January 2027 (seminar paper).

Course of the project: design question from Topic 4 · Part A in Exercise U2 · Part B in Exercise U4 · Part C · seminar paper. There is no separate exposé and no separate interim state. The **question pool** for the final presentation is open in the learning platform and grows until its freeze date; the **anchor sheet** (trace visible · anatomy complete · moderation active · hardest objection handled) is there too. There is **no rehearsal session** in the timetable: teams rehearse on their own, outside lectures and exercises, with the mock final presentation and the self-assessment sheet from the learning platform.

## Definitions as used in this module

- **Pattern:** a named, recurring solution to a recurring design problem, proven by use. Distinct from *component* (one platform's implementation) and *guideline* (one platform's rules). Four families this semester: navigation, forms, feedback, search.
- **Severity** = task criticality × frequency × inescapability. Footnote: for those affected, frequency and inescapability are measured *within the affected group*. Non-factors: ugliness, loudness of complaint.
- **Fidelity decision rule:** first the question, then the cheapest rung that answers it. Every rung lies about something; the chosen rung's blind spot is named, not hidden.
- **Four-line protocol entry:** tool · prompt · post-editing · time – for every tool run, in the student's own iteration protocol (not a declaration under submissions).
- **Audit (two layers):** the four-line grid (information hierarchy, missing functions, WCAG, consistency) + the workshop context rubric. Grids find the frequent, context finds the expensive.
- **Friction:** every interaction between intent and outcome; sources checked in order user value → organizational interest → nobody thought about it. Line runs along interest direction, craft rule is proportionality.
- **Notification strategy blocks:** occasion classes · channel per class · frequency budget (a number) · opt-in honesty · the renunciation sentence "We do not notify when …" with its named price.
- **Conflict resolution strategies:** last-write-wins (silent, lossy) · merge/CRDT (automatic, surprising) · ask the user (honest, expensive) · block offline writes (prevent by construction). Strategy follows data type. A silent merge that discards data is treated as an interface lie.
- **Triple filing (dark patterns):** taxonomy (Brignull type + Gray ontology level) · legal anchor · own verdict – three levels, kept apart.
- **Evidence labels:** supported / supportable / unsupportable; criterion: named measurer + year + population. Evidence kinds: announcements, investments, capability demos vs. usage, retention, revenue.

## Dated states (as of 2026-08-21 – check before relying)

- **DSA Art. 25** in force since 17.02.2024; first fine: X, 05.12.2025, €120m (deceptive design among findings).
- **Data Act Art. 6** applicable since 12.09.2025 (dark-pattern ban in data interfaces).
- **TikTok addictive-design proceedings:** preliminary findings 06.02.2026 – **pending**; up to 6 % of global turnover possible.
- **Digital Fairness Act:** consultation closed Oct 2025; proposal expected Q4 2026 – *not law*.
- **Amazon/FTC settlement:** Sept 2025, $2.5bn ("Iliad Flow"); FTC Click-to-Cancel rule vacated July 2025 – US enforcement case-by-case.
- **Platforms:** iOS 26 shipping (Liquid Glass HIG, June 2025); iOS 27 in beta since June 2026. Android 16: notification cooldown, auto-bundling. AI notification summaries: paused early 2025 after false headlines, reactivated labeled in iOS 26.
- **Sync engines:** Zero 1.0 (08.06.2026); PowerSync, ElectricSQL, Yjs, Automerge production-ready. Empirical conflict-UX literature 2024–2026: none known.
- **Market:** Sensor Tower "State of Mobile 2026": $167bn in-app spend 2025, 5.3trn hours; ChatGPT's AI-download share 67 % (Q2 2025) → 47 % (Q2 2026), Claude 1 % → 14 % (Forbes, 28.05.2026).

## Module conventions

Mandatory seminar-paper elements: the four elements of Part A (question, rung, justification, blind spot) · discarded-alternatives chapter fed by the iteration protocols · peer audit with written responses to every finding. The self-assessment sheet lists the grading anchors of the paper (S1–S12) and of the presentation (P1–P4).
