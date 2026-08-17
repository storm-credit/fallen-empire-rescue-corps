# Propulsion Trade Study v1

Status: **ADVERSARIAL NUMERICAL QA — NOT FROZEN**
Project: 《우주선에는 인간이 한 명뿐이다》

Purpose: identify exactly how speculative the generation ship propulsion must be and prevent vague “fusion engine” handwaving.

---

# 1. Non-Negotiable Problem

A civilization-scale ship traveling near `0.02c` carries an enormous kinetic energy and momentum budget.

No city-grid reactor can brake it.

The propulsion system is therefore one of the launch civilization's largest engineering achievements.

This is the project's **single largest physical extrapolation**.

---

# 2. Current Technology Anchors — What They Do and Do Not Prove

## Magnetic sail

NASA-hosted advanced-concept work has analyzed magnetic sails as field-effect devices interacting with solar wind / interstellar medium and specifically notes potential use as a brake for interstellar spacecraft.

This establishes the **physical family**, not performance for a generation ship.

## Direct fusion products

NASA/NIAC has studied aneutronic fusion spacecraft architectures where charged fusion products are conditioned/nozzled directly into propulsive exhaust.

This establishes the **architectural family**, not a demonstrated reactor or generation-ship exhaust performance.

## Current practical fusion-drive concepts

More conservative direct-fusion-drive studies generally discuss exhaust velocities / specific impulses suitable for fast Solar-System missions, orders of magnitude below what this project needs for a low-propellant 0.02c ship.

Therefore:

> The project's high-effective-exhaust fusion drive is explicitly centuries-ahead speculative technology.

---

# 3. Rocket-Equation Burden

For a pure rocket maneuver, ideal mass ratio:

`MR = exp(Δv / ve)`

where `ve` is effective exhaust velocity.

For braking an entire `0.02c` without external assistance:

| Effective exhaust | Mass ratio | Propellant fraction |
|---|---:|---:|
| 0.05c | ~1.49 | ~33% |
| 0.07c | ~1.33 | ~25% |
| 0.08c | ~1.28 | ~22% |
| 0.10c | ~1.22 | ~18% |

These are ideal values before reserves, inefficiency, vector changes, and final insertion.

### Interpretation

A 0.05–0.08c effective exhaust is enough to keep fuel mass large but not absurdly dominant.

The difficulty is building such an engine at adequate thrust/power, not the ideal rocket equation alone.

---

# 4. Hybrid Magnetic-Braking Cases

Let magnetic/plasma sail drag remove part of the cruise velocity without onboard reaction mass.

Illustrative ideal cases:

## If drag removes 10% of total Δv
Fusion must provide ~0.018c.

- ve 0.05c → propellant ~30%
- ve 0.07c → ~23%
- ve 0.08c → ~20%
- ve 0.10c → ~16%

## If drag removes 20%
Fusion provides ~0.016c.

- ve 0.05c → ~27%
- ve 0.07c → ~20%
- ve 0.08c → ~18%
- ve 0.10c → ~15%

## If drag removes 40%
Fusion provides ~0.012c.

- ve 0.05c → ~21%
- ve 0.07c → ~16%
- ve 0.08c → ~14%

### Important

The magnetic-sail percentages above are **scenario variables**, not proven achievable performance.

The effective interaction area required for a ship this massive could be extraordinary.

Do not canonize 40% merely because it helps the spreadsheet.

---

# 5. Preferred Working Trade

For further design, use a deliberately conservative middle ground:

### Peak cruise
~0.02c.

### Magnetic/plasma braking contribution
Working range:
**~10–30% of interstellar Δv**.

### Fusion controlled braking contribution
Working range:
**~70–90%**.

### Effective fusion exhaust velocity
Working fiction range:
**~0.06–0.08c**.

### Ideal total braking-propellant fraction
Roughly:
**~20–30% class**

before contingency / maneuver reserves.

This is large, visible mission mass—not a tiny fuel tank.

---

# 6. Why the Exhaust Velocity Is a Major Extrapolation

Current fusion-propulsion literature supports the idea that fusion can provide much higher exhaust velocity than chemical/fission-thermal systems and that charged products can, in principle, be directed for thrust.

It does **not** demonstrate:
- `0.06–0.08c` useful bulk effective exhaust
- adequate engine lifetime
- adequate magnetic-nozzle efficiency
- generation-ship thrust
- multi-petawatt continuous jet power

This project deliberately places its biggest technology miracle here.

Hard rule:
Never explain it with vague words like `quantum drive` or `reactionless engine`.

---

# 7. Power Burden

For a rocket jet:

`jet power ≈ 0.5 × thrust × exhaust velocity`

Even with a few-hundred-million-ton story-era ship, removing hundreds to thousands of km/s over decades implies **petawatt-class to tens-of-petawatts-class jet power**.

That is enormously above the civil 30–50 GW grid.

Therefore:

- propulsion plant is physically separate
- fusion-product energy should go mostly into exhaust rather than thermalizing inside the ship
- propulsion waste heat must use dedicated high-temperature systems
- propulsion maintenance is specialized civilization-scale labor

Do not route propulsion power through ordinary habitat electrical infrastructure.

---

# 8. Thermal Consequence

If even 1% of a 10 PW propulsion power stream became shipboard waste heat:

**100 TW** must be rejected.

That would dwarf the civil thermal system.

Therefore the propulsion architecture requires:

- very high direct-exhaust efficiency
- magnetic structures physically far from inhabited habitats
- dedicated high-temperature heat rejection
- pulse / staged operating architecture where useful
- extensive sacrificial/replaceable components

Exact efficiency is an engineering Freeze blocker.

---

# 9. Mass Definition Correction

The previous broad `5×10^11–1×10^12 kg` figure should not automatically mean story-start mass.

Separate:

### Departure / early-voyage mass
Includes:
- large braking propellant reserve
- forward sacrificial shielding reserve
- settlement consumables

### Late-braking / story-start mass
A substantial fraction of propulsion reserve and forward shielding has already been consumed during centuries of flight / decades of braking.

### Arrival retained mass
Lower again after:
- final propellant burn
- shield disposal/repurposing
- settlement module separation

This materially helps the final transition and should be reflected in v2 numerical mass accounting.

---

# 10. Preferred Future Mass Budget Direction

Do not Freeze exact values yet.

Recommended next numerical target:

### Habitable/industrial dry civilization
**~3–5×10^11 kg class**

### Major departure braking/mission propellant and consumables
additional **~1–2×10^11 kg class**

### Full departure mass
working order:
**~5–7×10^11 kg**

This is somewhat lower than the original upper 10^12 kg case but still civilization-scale.

Reason for reduction:
- better shared shielding geometry
- atmosphere used as part of shielding architecture
- no need to apply 100–200 g/cm² identical slabs to every exposed surface
- low-Z shielding has nontrivial GCR secondary-particle behavior; “more slab always better” is not physically simple

This requires a dedicated radiation architecture revision.

---

# 11. Radiation-Shielding Correction Triggered by This Trade

NASA thick-GCR modeling has found that dose-equivalent behavior can have non-monotonic behavior with shielding thickness/material because of secondary particles; some aluminum cases show a minimum near ~20–30 g/cm² rather than indefinite improvement.

Therefore the previous simple assumption:

> “100–200 g/cm² everywhere is safer”

is too crude.

The generation ship should use:
- hydrogen-rich / low-Z materials
- geometry
- atmosphere
- water/feedstock
- local deep shelters
- active dose management

rather than one universal thickness number.

**Required follow-up:** `RADIATION_ARCHITECTURE_V2.md`.

---

# 12. What Not To Solve With Destination Infrastructure

A tempting fix is to send self-replicating precursor machines that build a petawatt braking array around Ross 128.

Reject as default.

Why:
- if machines can industrialize the target for centuries, why is settlement material scarce?
- they could build much of the colony before humans arrive
- creates a second autonomous-AI infrastructure story
- weakens ship cannibalization

Forward probes may survey and deploy navigation/communications infrastructure, but they do not build a destination civilization capable of braking the entire ship.

---

# 13. Canon Recommendation

Preferred high-level answer:

> Solar-System infrastructure gives the ship its interstellar launch velocity. During approach, enormous magnetic/plasma braking structures shed a meaningful minority of momentum. A centuries-ahead direct-fusion propulsion plant supplies the majority of controlled braking and final insertion. The cost is a very large propellant reserve, a dedicated propulsion thermal system, and decades of continuous braking.

This is scientifically cleaner than:
- reactionless drives
- last-minute braking
- hidden destination megastructure

while still acknowledging the large extrapolation.

---

# 14. Pass / Fail

## Rocket-equation mass fraction
**PASS** within ~20–30% braking-propellant class if fictional exhaust ~0.06–0.08c exists.

## Energy / power
**EXTREME BUT EXPLICIT**.

## Waste heat
**MAJOR ENGINEERING BLOCKER** until efficiency/radiator architecture fixed.

## Magnetic drag
**PHYSICAL FAMILY VALID / SCALE HIGHLY SPECULATIVE**.

## Overall

**PROVISIONAL PASS FOR SCIENCE-FICTION SETTING**

with one explicit technology miracle:

> ultra-high-performance direct fusion propulsion at civilization scale.

The story should never pretend this is near-current engineering.
