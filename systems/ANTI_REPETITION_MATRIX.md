# Anti-Repetition Matrix

Status: ACTIVE QA FRAMEWORK — EPISODE ROWS NOT YET POPULATED
Project: 《우주선에는 인간이 한 명뿐이다》

## 1. Purpose

Long-form failure rarely comes from literally repeating the same plot. It comes from repeating the same **story experience** under different names.

Every Arc must eventually receive a signature so neighboring arcs can be compared.

---

## 2. Arc Signature Fields

| Field | Allowed families / examples |
|---|---|
| Primary Engine | E1 Transition / E2 Claim / E3 Culture / E4 Relationship / E5 System / E6 History / E7 Faction / E8 Arrival / E9 Information |
| Secondary Engines | 0–2 engine IDs |
| Dominant Habitat | H1–H8 / Axis / Forward / Aft / multi-habitat |
| Conflict Family | person-person / family / institution / society / technology / environment / self / value-value |
| Tension Type | physical / social / emotional / moral / mystery / political / temporal |
| Social Scale | individual / household / neighborhood / institution / habitat / shipwide |
| Emotional Temperature | warm / comic / uneasy / grief / anger / awe / dread / hopeful / conflicted |
| Payoff Type | competence / emotional / factual / social / political / exploratory / repair/rescue / choice consequence |
| Mystery Intensity | 0 background / 1 hint / 2 secondary / 3 primary |
| Physical Risk | 0 none / 1 inconvenience / 2 meaningful / 3 life-threatening / 4 mass-risk |
| Publicity | private / local / professional / habitat-public / shipwide-public |
| Primary Relationship | R1–R7 / none |
| Theme | 1–2 theme IDs only |
| Ending Mode | closure / reversal / decision / revelation / consequence / promise / emotional callback |

---

## 3. Similarity Warning Rules

Trigger **YELLOW** if two consecutive Arcs share:

- same primary engine
- same dominant habitat
- same tension type
- same payoff type

Trigger **RED** if they additionally share either:

- same primary relationship
- same social scale
- same core dilemma

A RED pair must be redesigned unless repetition is explicitly being used for contrast and the changed meaning is documented.

---

## 4. Repetition That Is Allowed

Repetition can be powerful when meaning changes.

Examples:

- Same relocation procedure before and after ontology reveal
- Same family ritual first as comfort, later as political statement
- Same medical test first treated as routine, later understood historically
- Same habitat revisited after a policy change
- Same person making the opposite choice after character growth

Mark these as `DELIBERATE_CALLBACK`, not accidental repetition.

---

## 5. Mystery Monotony Checks

Within any rolling 10-episode window, flag if:

- more than 60% of episode endings are pure question/revelation hooks
- more than 3 episodes in a row end with inaccessible information rather than action/consequence
- protagonist spends more than 2 consecutive episodes primarily gathering information without making a consequential choice
- no factual question receives an answer
- no relationship state changes
- no non-mystery reward occurs

Thresholds are provisional and will be tuned after pilot blueprints.

---

## 6. Conflict Monotony Checks

Within any 3 consecutive Arcs, require meaningful variation in at least three of:

- conflict family
- social scale
- physical-risk level
- dominant relationship
- public/private scope
- habitat
- payoff type

---

## 7. Philosophy Monotony Checks

Do not allow multiple adjacent Arcs to ask the same abstract question with cosmetic changes.

Examples of distinct questions:

- Is restoration the same person?
- Does a parent own a child’s developmental data?
- Can biological vulnerability justify extra resources?
- Can a community refuse identity recording?
- Does a launch-era charter bind artificial descendants?

All relate to personhood but produce different action structures.

---

## 8. Physical-Crisis Monotony Checks

E5 System Constraint must rotate the **meaning** of failure.

Bad escalation:

`small oxygen leak → larger oxygen leak → giant oxygen leak`

Better:

- heat system forces resource priority
- transit failure isolates caregivers
- agriculture contamination tests local autonomy
- network outage changes identity verification
- structural repair requires destroying heritage space
- exterior maintenance forces unequal risk allocation

---

## 9. Relationship Monotony Checks

No relationship should repeat one emotional beat endlessly.

Examples of forbidden loops:

- parent repeatedly says “come home”
- lover repeatedly asks “do you trust me?”
- mentor repeatedly hides information
- rival repeatedly blocks plan

Each return must change one of:

- power balance
- knowledge
- obligation
- intimacy
- trust
- material dependency
- public alignment

---

## 10. Future Table Template

| Arc ID | Primary | Secondary | Habitat | Conflict | Tension | Scale | Payoff | Mystery | Risk | Relationship | Theme | Similarity Flag |
|---|---|---|---|---|---|---|---|---:|---:|---|---|---|
| ARC-001 | TBD | TBD | TBD | TBD | TBD | TBD | TBD | TBD | TBD | TBD | TBD | — |

This file becomes operational once macro/episode blueprints exist.
