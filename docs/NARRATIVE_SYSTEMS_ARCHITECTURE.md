# Narrative Systems Architecture

Status: ACTIVE DESIGN FRAMEWORK
Project: 《우주선에는 인간이 한 명뿐이다》

## 1. Principle

The series hierarchy is:

`Series → Act → Sub-Act → Arc → Episode`

This hierarchy is only the **vertical story skeleton**. Long-form quality depends on cross-cutting narrative systems that move through many Acts and episodes. These systems must not all be buried inside Act documents.

## 2. Three Management Tiers

### TIER A — Independent Ledgers
Use a dedicated system document because the information crosses many Acts, must remain globally consistent, or can create continuity failures if duplicated locally.

Mandatory independent ledgers:

1. Canon / rule dependencies
2. Mystery question ladder
3. Reveal / clue / red-herring / recontextualization / payoff ledger
4. Character-state ledger
5. Relationship-state ledger
6. Faction dynamics ledger
7. Information economy / who-knows-what ledger
8. Theme / dilemma / choice ledger
9. Consequence ledger
10. Major callback / motif ledger
11. Ending obligation / unresolved-thread ledger
12. Serialization anti-repetition matrix

These ledgers are authoritative for their domain. Act and Episode files reference ledger IDs instead of duplicating truth.

---

### TIER B — Act / Sub-Act Architecture
Use Act/Sub-Act documents when the concern is primarily about **movement across a bounded story phase** rather than global truth.

Manage here:

1. external conflict
2. dominant narrative engine
3. social state change
4. protagonist belief change
5. relationship phase change
6. faction alignment change
7. escalation type
8. primary theme variation
9. wonder/exploration function
10. pacing pattern
11. local MacGuffin, when used
12. local red herring, when used
13. Sub-Act promise and payoff
14. cost of resolution
15. aftermath carried into next Sub-Act
16. entry state / exit state

Rule: a Sub-Act must be a satisfying medium-length story, not merely a container for clues.

---

### TIER C — Episode Blueprint Fields
Use Episode Blueprints for execution-level decisions that do not need an independent global ledger unless they reference a tracked item.

Manage here:

1. immediate episode goal
2. primary engine
3. secondary engine(s)
4. scene pressure
5. episode change
6. immediate reward
7. hook type
8. tension type
9. POV information boundary
10. local choice
11. local cost
12. action/reaction rhythm
13. exposition budget
14. emotional beat
15. read-aloud risks
16. callbacks used
17. ledger IDs touched
18. future consequences created

Rule: every episode should normally contain at least three of the following four qualities:

- Immediate Goal
- Change
- Reward
- Forward Pull

## 3. System Classification

### 3.1 Canon Systems — TIER A
- Physical/ship rules
- AI ontology
- Human ontology
- Birth/reproduction
- Death/backup/restoration
- History
- Institutions
- Destination

Reason: global consistency and hard dependency.

### 3.2 Mystery Systems — TIER A + TIER B
Independent ledger:
- central mystery
- identity mystery
- historical mystery
- institutional mystery
- destination mystery
- personal secrets
- question ladder

Act/Sub-Act:
- which question dominates now
- what answer is earned now
- what new question replaces it

### 3.3 Reveal Systems — TIER A + TIER C
Independent ledger:
- clues
- foreshadowing
- red herrings
- partial reveals
- false resolutions
- confirmations
- recontextualizations
- informational payoffs
- emotional payoffs

Episode:
- exact presentation/use of a tracked reveal item

### 3.4 Character Systems — TIER A + TIER B + TIER C
Independent:
- desire / need / fear / false belief
- long-term arc state
- secrets
- competence boundaries

Act/Sub-Act:
- phase-specific belief pressure and transformation

Episode:
- concrete decision/action demonstrating the current state

### 3.5 Relationship Systems — TIER A + TIER B
Independent:
- trust
- intimacy
- dependency
- resentment
- secrets
- power balance
- rupture/reconciliation state

Act/Sub-Act:
- relationship phase transition

### 3.6 Social Systems — TIER A + TIER B
Independent when rules are systemic:
- law
- economy
- labor
- education
- medicine
- family system
- religion
- media
- class

Act/Sub-Act when depicting change:
- policy crisis
- public reaction
- institutional conflict
- social transformation

### 3.7 Conflict Systems — TIER B + TIER C
Act/Sub-Act:
- dominant conflict family
- escalation pattern

Episode:
- immediate conflict and pressure

Conflict families:
- person vs person
- person vs family
- person vs institution
- person vs society
- person vs technology
- person vs environment
- person vs self
- value vs value

### 3.8 Event Engines — TIER B + TIER C
Track usage globally through anti-repetition matrix, but design events locally.

Candidate engine families:
- district/zone exploration
- personal/family case
- civic/legal/social case
- infrastructure/system failure
- historical excavation
- relationship crisis
- faction maneuver
- destination/voyage development

These are not yet final; the four-direction design phase may replace or add engines.

### 3.9 Escalation — TIER A summary + TIER B execution
Track globally to prevent fake escalation.

Escalation dimensions:
- scale
- meaning
- intimacy
- irreversibility
- social reach
- moral cost
- knowledge risk

### 3.10 Consequence — TIER A + TIER C
Every resolved event may leave:
- personal consequence
- relationship consequence
- social consequence
- political consequence
- resource consequence
- mystery consequence

Major consequences are ledgered; local consequences stay in episode blueprints.

### 3.11 Choice / Cost — TIER A thematic ledger + TIER B/C execution
Major dilemmas must present competing values, not obvious good/evil options.

Pattern:

`Choice → Gain → Cost → Aftermath → New Pressure`

### 3.12 Motif / Symbol — TIER A
Only recurring motifs with cumulative meaning belong in the ledger. Decorative imagery does not.

### 3.13 MacGuffin — TIER B by default
MacGuffins are optional, not mandatory. A MacGuffin is tracked independently only when it crosses multiple Sub-Acts or carries major reveal obligations.

### 3.14 Faction Dynamics — TIER A
Each major faction requires:
- goal
- philosophy
- resource
- fear
- ally
- enemy
- secret
- current move
- red line
- internal fracture

Factions must move even when the protagonist is absent.

### 3.15 Information Economy — TIER A
For every high-risk fact, track:
- objective truth
- protagonist knowledge
- reader knowledge
- faction knowledge
- false beliefs
- evidence access
- disclosure trigger

### 3.16 POV — TIER A rules + TIER C enforcement
Global POV rules live in the Writing Bible. Each episode enforces what the active POV may know, infer, hide, or misinterpret.

### 3.17 Tension — TIER C, globally balanced
Types:
- physical
- social
- emotional
- moral
- mystery
- political
- temporal

Anti-repetition QA checks consecutive episodes/arcs for tension sameness.

### 3.18 Hook — TIER C
Rotate:
- revelation
- decision
- emotional
- threat
- question
- reversal
- promise

No cliffhanger monoculture.

### 3.19 Reward — TIER B + TIER C
Reward cadence:
- small: 1–3 episodes
- arc: 5–15 episodes
- Sub-Act: medium arc span
- Act: major state change
- series: final long-term obligations

Mystery cannot substitute indefinitely for reward.

### 3.20 Pacing — TIER B + TIER C
Rhythm vocabulary:
- discovery
- tension
- release
- emotion
- wonder
- conflict
- payoff
- aftermath

Aftermath is mandatory after major irreversible events.

### 3.21 Wonder — TIER B + TIER C
Every major ship region should generate positive or unsettling SF wonder through lived culture, not exposition tours.

### 3.22 Humor / Breathing — TIER B + TIER C
Use to prevent tonal exhaustion. Must arise from character/culture rather than genre-breaking gag logic.

### 3.23 Theme — TIER A + TIER B
Master thematic family:
- identity
- memory
- body
- death
- love
- family
- ownership
- copy/original
- continuity
- dignity
- choice
- social recognition

Each Sub-Act should focus on only 1–2 principal thematic questions.

### 3.24 Transformation — TIER B
Every Act must permanently transform at least one:
- character
- relationship
- world state
- social order
- knowledge state
- goal

### 3.25 Callback — TIER A for major callbacks, TIER C for execution
Separate from foreshadowing. A callback may pay emotion, relationship, symbolism, or character growth without solving a mystery.

### 3.26 Anti-Repetition — TIER A
Track Arc signatures including:
- primary engine
- secondary engine
- conflict family
- tension type
- payoff type
- location type
- social scale
- emotional temperature

Consecutive near-duplicate signatures trigger redesign.

### 3.27 Serialization Engine — TIER C + TIER A QA
Episode-level execution; series-level audit.

### 3.28 Style — Independent Bible
Style is not an Act property.

Must later define:
- POV
- sentence rhythm
- description density
- internal monologue
- dialogue ratio
- exposition rules
- terminology limits
- scene transitions
- suspense disclosure rules
- chapter ending discipline

### 3.29 Read-Aloud / Narration — Independent Bible + Episode QA
Must later define:
- pronunciation safety
- name differentiation
- sentence breath length
- speaker clarity
- numeric/symbol speech handling
- repeated endings
- TTS-hostile notation

## 4. Mandatory Independent Files

The following file families should exist before Full Episode Blueprint work is considered complete:

- `systems/MYSTERY_LEDGER.md`
- `systems/REVEAL_PAYOFF_LEDGER.md`
- `systems/CHARACTER_STATE_LEDGER.md`
- `systems/RELATIONSHIP_LEDGER.md`
- `systems/FACTION_DYNAMICS.md`
- `systems/INFORMATION_ECONOMY.md`
- `systems/THEME_DILEMMA_LEDGER.md`
- `systems/CONSEQUENCE_LEDGER.md`
- `systems/CALLBACK_MOTIF_LEDGER.md`
- `systems/ENDING_OBLIGATIONS.md`
- `systems/ANTI_REPETITION_MATRIX.md`

Additional independent bibles:

- `writing/STYLE_BIBLE.md`
- `writing/READ_ALOUD_BIBLE.md`
- `writing/SERIALIZATION_BIBLE.md`

## 5. Reference-ID Rule

Tracked items should use stable IDs so episode plans do not duplicate or silently mutate them.

Examples:

- `M-001` mystery question
- `CL-001A` clue
- `RV-001` reveal
- `PF-001` payoff
- `CH-PRO-01` character-state milestone
- `RL-PRO-FAM-01` relationship milestone
- `FX-003` faction move
- `INF-014` information fact
- `TH-006` thematic dilemma
- `CS-011` consequence
- `CB-008` callback

## 6. Episode Blueprint Contract

Each episode blueprint must eventually include:

- Episode ID
- Sub-Act / Arc
- Primary Engine
- Secondary Engine(s)
- Immediate Goal
- External Event
- Character Change
- Relationship Change
- Social/Faction Movement
- New Information
- Hidden Information
- Ledger IDs Used
- Choice
- Cost
- Immediate Reward
- Consequence Created
- Theme
- Tension Type
- Hook Type
- Pacing Function
- Canon Dependencies
- Future Payoff Target
- Read-Aloud Risk Notes

The blueprint is a contract for later drafting, not prose.

## 7. Current Decision

The project will **not** begin Act design by simply distributing twists across 250 episodes. First it will complete market/comparable research, four genuinely different direction designs, recommend/select a core direction, then build the world and system canon deeply enough that the macro narrative can be derived from stable rules.
