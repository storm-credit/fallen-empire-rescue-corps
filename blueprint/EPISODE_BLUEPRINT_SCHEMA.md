# Episode Blueprint Schema

Status: **FROZEN BLUEPRINT FORMAT**
Project: 《우주선에는 인간이 한 명뿐이다》
Manuscript: LOCKED

Purpose:
Define the minimum design record required for every episode before manuscript drafting.

No episode prose belongs in this directory.

---

# 1. Required Episode Record

Every episode record must contain:

## Identity
- `Episode`
- `Act`
- `Sub-Act`
- `Arc`
- `Working Function Title` — design label only, not final published title

## Reader Contract
- `Immediate Goal`
- `Primary Engine`
- `Secondary Engine(s)` — max 2
- `Dominant Experience` — competence / mystery / relationship / wonder / social / crisis / aftermath / choice

## External Story
- `External Event`
- `Decision / Action`
- `Result`
- `Cost`

## Character / Relationship
- `Character State IDs`
- `Relationship State IDs`
- `Character Movement`
- `Relationship Movement`

A reveal alone does not count as character movement.

## Information / Mystery
- `Mystery IDs`
- `Information IDs`
- `Clue / Reveal / Payoff IDs`
- `Reader Knows`
- `Haren Knows`
- `Other Relevant Knower(s)`
- `Fair Alternative Interpretation`

If no mystery beat is needed, mark `NONE`; do not invent one.

## Theme / Choice
- `Theme ID(s)` — 1 primary, max 1 secondary
- `Concrete Dilemma`
- `Choice`
- `Who Pays`

## Continuity
- `Consequence IDs`
- `Callback / Motif IDs`
- `Canon Dependencies`
- `Future Payoff / Dependency`

## Serialization
- `Immediate Reward`
- `Forward Pull`
- `Hook Type`
- `Pacing Shape`
- `Aftermath Need`

---

# 2. Four-Point Episode Test

Every episode must provide at least 3 of these 4:

1. **Goal** — a clear present-tense objective
2. **Change** — world/relationship/information state changes
3. **Reward** — reader receives competence, fact, emotion, wonder, consequence, or choice payoff
4. **Forward Pull** — next episode pressure emerges naturally

Any episode scoring fewer than 3/4 is rejected or merged.

---

# 3. Reward Tags

Use one or more:

- `RWD-COMP` competence
- `RWD-FACT` factual answer
- `RWD-EMO` emotional movement
- `RWD-WONDER` world/SF experience
- `RWD-CONSEQ` visible consequence
- `RWD-SOCIAL` social/political result
- `RWD-CHOICE` meaningful decision payoff

Early-series rule:
No three consecutive episodes may lack `RWD-COMP`, `RWD-FACT`, or `RWD-EMO`.

---

# 4. Hook Tags

Rotate among:

- `HK-DECISION`
- `HK-CONSEQUENCE`
- `HK-REVEAL`
- `HK-EMOTIONAL`
- `HK-THREAT`
- `HK-PROMISE`
- `HK-REVERSAL`
- `HK-QUESTION`
- `HK-CLOSURE+NEXT`

Within any rolling ten episodes:
- pure `HK-REVEAL/HK-QUESTION` endings <= 60%
- no three inaccessible-information hooks consecutively
- at least two decision/consequence hooks

---

# 5. Pacing Shape Tags

Examples:
- `FIELD→DISCOVERY→DECISION`
- `TENSION→COMPETENCE→COST`
- `RELATIONSHIP→WORK→REVEAL`
- `WONDER→PROBLEM→CHOICE`
- `AFTERMATH→NEW PRESSURE`
- `PUBLIC CASCADE→LOCAL CONSEQUENCE`

No episode should be only `EXPOSITION→EXPOSITION`.

---

# 6. Mystery Fairness Rule

For every clue:

- it must serve a legitimate scene purpose besides clue delivery,
- Haren's access must follow profession/law/relationship,
- denied access must follow real rules,
- narrator may not conceal Haren's conscious knowledge,
- false interpretation must remain plausible until contradicted.

Major reveal requires at least three independent clue families at series/Arc level.

---

# 7. Relationship Rule

When a relationship is active, record whether one of these changes:

- trust
- power
- knowledge
- obligation
- distance

Repeated conversation with none changing is not relationship movement.

---

# 8. Consequence Rule

A resolved episode problem cannot reset automatically.

If the episode changes:
- resource inventory,
- legal precedent,
- authority,
- public knowledge,
- trust,
- access,
- geography,
then the resulting state becomes input to later blueprints.

---

# 9. SF Explanation Rule

Technical explanation enters only through:

`problem → failed assumption → necessary concept → decision/result`.

If a fact does not change current action, postpone or delete it.

---

# 10. Episode Density Rule

Do not force every ledger into every episode.

Preferred episode layering:

- 1 primary engine
- 0–2 secondary engines
- 1 primary theme or none
- 1–3 active character/relationship movements maximum
- mystery intensity appropriate to Arc

The blueprint is a control system, not a checklist stuffed into prose.

---

# 11. Arc Rollup Requirement

After each Arc, create an Arc QA block checking:

- Arc promise paid?
- at least one meaningful consequence?
- relationship/character state changed?
- no contradiction with Canon?
- primary engine distinct from neighboring Arc?
- mystery answer/new question balance?
- material/social world changed?
- next Arc caused rather than merely adjacent?

---

# 12. Act Rollup Requirement

After each Act:

- permanent world change
- permanent protagonist belief/authority change
- relationship-state changes
- faction-state changes
- factual answers delivered
- new actionable questions
- ending obligations seeded/paid
- anti-repetition audit
- reward-density audit
- SF continuity audit

---

# 13. Blueprint Freeze Rule

An episode blueprint becomes `BLUEPRINT-FROZEN` only after:

- 4-point test PASS
- Canon dependency PASS
- ledger references valid
- no reward desert introduced
- no adjacent signature collision
- future dependencies assigned

Blueprint freeze still does not equal manuscript permission until the full series Gate passes.
