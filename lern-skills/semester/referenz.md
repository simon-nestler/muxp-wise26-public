# Reference – Mobile UX Prototyping (companion to the study partner, v1.1, 2026-09-18)

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
| 9 | Offline states and sync conflicts | The sync engine is production-ready in 2026 – the UX of the conflict case is unresearched. | 8 |
| 10 | Dark patterns: naming and judging | Between persuading and manipulating runs a line that carries €120-million fines – and that nobody can draw sharply. | 9 |
| 11 | Anchor II: The Brussels hearing | Infinite scroll and autoplay are either good engagement design or a legal violation – being fought over right now. | 9, 7, 5 |
| 12 | Defending your design | In the colloquium I examine the trace that building left in your thinking: your decisions, your discards, and what they cost. | 6, 2 |
| 13 | Apps and the agent thesis | The claim that AI agents will replace apps is unsupported – and could still be true. | 5, 4 |

Learning objectives (short form): LO1 fidelity decision · LO2 iterative building with declared AI · LO3 pattern analysis and severity ranking · LO4 auditing AI-generated UIs/analyses · LO5 sourcing market claims · LO6 presenting and moderating · LO7 notification strategy (Column 2) · LO8 offline/conflict UX (Column 2) · LO9 dark patterns and regulation (Column 2). Column 2 = taught seriously, supported by the bonus track, not directly examined.

Session structure (as of 17./18.09.2026): **one 90-minute lecture per topic**, plus six exercise double sessions U1–U6, each covering two topics (U1 = T01+T02 · U2 = T03+T04 · U3 = T05+T06 · U4 = T07+T08 · U5 = T09+T10 · U6 = T11+T12). Every lecture ends with a **bridge task of twenty minutes at most: voluntary, posted on the topic's Padlet** – no submission, no deadline, no penalty; each session and each sheet names the material it works with when the Padlet stays empty. Exercise teams are **three to four people**. In the T12 panels and in sheet U6, one run is **5 minutes defense + 5 minutes questions and anchor feedback + 2 minutes role change**.

Semester plan (as of 15.09.2026): 14 weeks, week 14 holds the defense slots. Topics 9 and 12 are droppable. If holidays cost one week, Topic 9 becomes self-study from the script; if they cost two, Topic 12 does too. An extra week becomes an open Q&A session.

## Definitions as used in this module

- **Pattern:** a named, recurring solution to a recurring design problem, proven by use. Distinct from *component* (one platform's implementation) and *guideline* (one platform's rules). Four families this semester: navigation, forms, feedback, search.
- **Severity** = task criticality × frequency × inescapability. Footnote: for those affected, frequency and inescapability are measured *within the affected group*. Non-factors: ugliness, loudness of complaint.
- **Fidelity decision rule:** first the question, then the cheapest rung that answers it. Every rung lies about something; the chosen rung's blind spot is named, not hidden.
- **Declaration four-liner:** tool · prompt · post-editing · time – under every submission with AI involvement.
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

Exam: seminar paper (3,000–6,000 words) + 30-min colloquium; the question pool is open in the learning platform. Bonus: exercise sheets U1–U5, upload within 48 h (U6 is a backup date and counts only if it replaces a cancelled regular exercise). Mandatory SA elements: exposé (question, rung, justification, blind spot) · discarded-alternatives chapter · peer audit with written responses · declaration lines throughout.
