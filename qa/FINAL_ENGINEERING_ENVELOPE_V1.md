# Final Engineering Envelope v1

Status: **PROVISIONAL FREEZE CANDIDATE — B6 CLOSURE DOCUMENT**
Project: 《우주선에는 인간이 한 명뿐이다》
Parents:
- `SF_NUMERICAL_BUDGET_V1.md`
- `PROPULSION_TRADE_STUDY_V1.md`
- `RADIATION_ARCHITECTURE_V2.md`
- `VOYAGE_ENGINEERING_V3.md`
- `DESTINATION_ORBITAL_DYNAMICS_V1.md`

Purpose:
Choose one coherent order-of-magnitude engineering set so later narrative design cannot casually change ship scale, remaining propellant, heat burden, or arrival timing.

This is not a detailed spacecraft design and does not claim present-day feasibility.

---

# 1. Preferred Mission Numbers

## Destination
Ross 128 system / Ross 128 b.

## Distance
~11 ly class.

## Peak cruise speed
**~0.02c ≈ 6,000 km/s.**

## Voyage duration
**~600 years.**

## Story start
**T-6 years** before final system insertion.

## Story-start target-relative velocity
Preferred working center:

**~650 km/s.**

## Story-start remaining distance
Under a roughly smooth final six-year deceleration:

**~410 AU class.**

Exact trajectory will vary; these are design anchors.

---

# 2. Preferred Mass Timeline

## A. Post-boost interstellar departure mass

**~5.1 × 10^11 kg**

= ~510 million metric tonnes.

This is the mass after the Solar-System external acceleration infrastructure has done most launch work.

It includes:
- civilization/habitats
- shielding/volatiles
- settlement reserve
- interstellar braking propellant
- forward sacrificial material

## B. Main braking-phase onset mass

**~4.85 × 10^11 kg**

Difference from departure is mostly:
- forward-shield erosion/replacement mass
- long-voyage consumable conversion/losses
- discarded/reconfigured cruise structures

Not 500 years of uncontrolled life-support leakage.

## C. EP001 / T-6-year mass

**~4.03 × 10^11 kg**

At this point most of the large fusion braking propellant has already been expended during the previous ~50+ years of approach.

## D. Final insertion mass before large settlement redistribution

**~3.90 × 10^11 kg**

Most of that mass remains in-system as:
- habitats
- atmosphere/water
- industrial structures
- settlement modules
- orbital infrastructure

Arrival is redistribution, not destruction of hundreds of millions of tonnes.

## E. Early post-arrival retained civilization mass

Working:

**~3.7–3.9 × 10^11 kg**

depending on:
- final propulsion hardware disposal/retention
- shield discard
- residual maneuver reserve
- structures deliberately placed on escape/storage trajectories

Do not Freeze tighter than this unless a later plot needs exact mass accounting.

---

# 3. Why the Braking Propellant Math Closes

Preferred fusion effective exhaust velocity:

**~0.07c ≈ 21,000 km/s.**

This is the project's major propulsion extrapolation.

Preferred total velocity reduction split from peak cruise:

- magnetic/plasma drag: ~20–25% class
- controlled direct-fusion propulsion: ~75–80% class

Working fusion-provided total Δv:

**~4,500–4,600 km/s.**

Ideal rocket-equation mass ratio at `ve ≈ 21,000 km/s`:

`exp(4550 / 21000) ≈ 1.24`

This implies roughly:

**~19–20% of braking-onset mass**

is expended as idealized propulsion reaction mass across the controlled braking campaign.

With a braking-onset mass near `4.85×10^11 kg`, that corresponds to order:

**~9×10^10 kg**

of fusion propulsion mass consumed across the long approach.

This is consistent with the difference between braking-onset and late-approach mass after allowing for other reserve changes.

---

# 4. T-6 Remaining Burn

At EP001:

- mass: ~`4.03×10^11 kg`
- relative speed still to remove: ~650 km/s class
- effective exhaust: ~0.07c

Ideal remaining propellant fraction:

`1 - exp(-650 / 21000) ≈ 3%`

Working remaining interstellar/final-insertion propellant:

**~1.2 × 10^10 kg class**

= ~12 million tonnes.

This is deliberately large enough that:
- propulsion reserve is still visible in material politics
- a final burn is physically consequential

but small enough that most braking mass has already been spent before the story.

---

# 5. Story-Start Mass Budget

Target total:

**~4.03 × 10^11 kg**

Accounting bins below assign multifunctional mass once even when it serves several purposes.

| Family | Working mass |
|---|---:|
| Habitat atmosphere | ~8.5×10^10 kg |
| Water / soil / organic feedstock / passive shielding inventory | ~1.05×10^11 kg |
| Rotating habitat + pressure-shell + axial structural mass | ~8.5×10^10 kg |
| Civil industry / fabrication / transport / civil radiators / power plant | ~4.0×10^10 kg |
| Active radiation-shield coil/support infrastructure | ~2.0×10^10 kg |
| Interstellar propulsion plant dry hardware / magnetic nozzle / high-temp thermal structures | ~2.5×10^10 kg |
| Remaining propulsion/final-insertion reaction mass | ~1.2×10^10 kg |
| biology / food reserves not counted above / medical / computing / small craft / miscellaneous certified reserves | ~3.1×10^10 kg |

Total:

**~4.03×10^11 kg.**

These are not procurement spreadsheets. They are scale constraints.

---

# 6. Civil Power

Preferred normal electrical civilization:

**~40 GW** center.

Working normal range:

**30–50 GW.**

High industrial/settlement-conversion periods:

**~60–100 GW electrical**.

Primary civil power:
advanced fusion-class reactors.

Emergency / black-start:
- fission
- isotope
- distributed stored energy

Civil power is not propulsion power.

---

# 7. Propulsion Thrust and Power at EP001

To remove ~650 km/s over six years on a ~4×10^11 kg vehicle requires order:

### Mean linear deceleration
**~0.0034 m/s²**

≈ `3.5×10^-4 g`.

Habitat residents barely feel this compared with ~1g rotation.

### Mean thrust
**~1.3–1.4×10^9 N**.

### Ideal directed-jet kinetic power
For `ve ≈ 0.07c`:

**~1.4×10^16 W**

= **~14 petawatts**.

This is why propulsion is a dedicated mission machine rather than part of the city grid.

---

# 8. Propulsion Waste Heat Constraint

The engine cannot convert a normal reactor's power into electricity and then dump most of it as heat.

Preferred architecture:

> charged fusion products are magnetically directed into exhaust with only a tiny fraction thermalizing into the ship.

Even then:

### If 0.1% of ~14 PW thermalizes
~14 TW waste heat.

### If 0.3%
~42 TW.

Therefore the propulsion plant needs:
- very high direct-exhaust fraction
- reactor/nozzle structures physically distant from habitats
- dedicated high-temperature heat rejection
- replaceable high-flux structures

Working propulsion-radiator family:

**tens to low hundreds of km² effective high-temperature radiator surface**,

operating much hotter than civil habitat radiators.

This is separate from the ~80–150 km² civil radiator system.

### Freeze discipline

Do not put an exact `99.9xxx%` efficiency into reader prose.

Author-facing rule:

**If later engineering requires >~0.3% of propulsion power to become ordinary ship heat for long periods, the thermal architecture must be redesigned.**

---

# 9. Civil Heat Rejection

For normal 30–50 GW civilization:

Preferred distributed civil radiator surface:

**~80–150 km² physical/effective class**

depending on temperature loops.

Separate loops:
- habitat/environment
- industrial
- reactor/power

Radiators remain strategic visible infrastructure and a legitimate story constraint.

---

# 10. Radiation Architecture Mass/Technology Boundary

Preferred protection stack:

1. low-Z passive mass
2. atmosphere geometry
3. water/feedstock placement
4. superconducting active magnetic shielding
5. local deep safe zones

Working active shield infrastructure mass:

**~2×10^10 kg class**

including:
- coils
- support
- cryogenic systems
- power conditioning
- structural separation

This is a worldbuilding mass allowance, not a field-strength proof.

The technology remains a major extrapolation but does not replace passive shielding.

---

# 11. Active Shield vs Propulsion/Magnetic Braking

Do not imply the same coil simply does everything.

They are different systems with different geometry.

### Radiation shield
localized around habitat groups, optimized to deflect charged cosmic-ray trajectories while keeping inhabited regions low-field.

### Magnetic/plasma brake
large mission-scale interaction structure oriented along the velocity / plasma environment.

### Propulsion magnetic nozzle
high-field engine structure aligned with fusion exhaust.

Operational coordination is required so fields do not interfere beyond certified limits.

During high-propulsion phases:
- some shield configurations may be adjusted
- passive/dose-management layers carry more burden in affected sectors

No household experiences random magnetic chaos as normal operation.

---

# 12. Forward Shield at EP001

The enormous cruise-era forward sacrificial system has already lost/reconfigured substantial mass.

At T-6:
- relative speed is hundreds, not thousands, of km/s
- dust hazard remains severe
- forward protection is still maintained

Some forward shield inventory becomes **future settlement/industrial feedstock** only after speed and geometry make that safe.

This provides another real source of arrival material without a miracle spare warehouse.

---

# 13. Atmosphere / Life-Support Mass Closure

Atmosphere order:

**~8×10^10–1×10^11 kg**

is retained.

The ship does not lose 2% water each processing pass into space.

Civilization-scale elemental recovery is effectively near-closed over long averaging periods.

Waste is usually:
- chemically transformed
- stored
- reprocessed

not discarded.

This is mandatory for six centuries.

---

# 14. Agriculture / Food Closure

High-intensity crop canopy equivalent:

**~10–15 km² class**

plus:
- stacked growing systems
- H2 ecological production
- microbial/fungal protein
- fermentation
- cultured animal products

Agricultural electric demand:

**several GW class**, included inside civil 30–50 GW.

No need to devote the full 120 km² living surface to visible farmland.

---

# 15. Arrival Mass Conversion

The old ship is not thrown away.

At arrival, approximately hundreds of billions of kg of useful civilization remain.

Mass changes category:

- habitat → retained world
- pressure shell → surface/orbital settlement
- shielding water → life support / settlement shielding
- industrial line → orbital/surface factory
- propellant tanks → storage/structure where certified
- axial modules → transfer infrastructure

The story's material theme therefore has physical support:

> continuity often means reuse under changed function, not preservation of form.

---

# 16. Surface Settlement Scale Closure

At series end only:

**~20,000–30,000 people**

need live sustainably on the planet surface.

This is much easier than moving all 300,000 immediately.

The majority remain in habitat worlds while:
- atmosphere processing
- water extraction
- agriculture
- local construction
- higher-g adaptation

mature.

This keeps H2/H4/H5 and wider habitats necessary after arrival.

---

# 17. Engineering Miracle Hierarchy

To preserve SF discipline, technologies are ranked.

## Tier 1 — Core major miracles

### M1. Synthetic developmental cognition
Designed scaffold can causally bootstrap human-level artificial-origin conscious development in organic neural tissue.

### M2. Civilization-scale ultra-high-performance direct fusion propulsion
Effective exhaust ~0.06–0.08c with petawatt-class directed power and extreme direct-exhaust/thermal management.

These are the two largest assumptions.

---

## Tier 2 — Strong extrapolations from recognizable research families

### T2-A. Adult neural state capture / restoration
Highly limited, expensive, imperfect, consent-bound.

### T2-B. Large superconducting active radiation shielding
Works with passive mass rather than replacing it.

### T2-C. Long-life industrial self-renewal / closed material economy
No single ecosystem miracle; civilization continually rebuilds its infrastructure.

### T2-D. Advanced fusion civil power
Tens-of-GW-class reliable long-duration reactors.

---

## Forbidden miracle stacking

Do not add without redesign:
- FTL
- reactionless drive
- gravity control / antigravity
- arbitrary matter replicators
- instant teleportation
- perfect mind reading
- universal nanotech magic
- perfect resurrection
- hidden simulation as physics escape hatch

The existing miracle budget is already full.

---

# 18. Failure / Story Constraint Rules

These numbers must constrain narrative.

### If a habitat wants more shielding
That mass comes from somewhere.

### If a settlement module leaves the ship
Its previous shielding/structural/service function must be replaced or accepted as lost.

### If propulsion thermal margin narrows
Civil society may need operating restrictions even though city electrical supply is fine.

### If a large habitat changes orbit
Transit, shield geometry, and propellant budgets matter.

### If H8 wants full preservation
The certified settlement shell material still has an opportunity cost.

No future scene may solve these with `the ship AI found spare capacity` unless that capacity was previously budgeted.

---

# 19. What Remains Intentionally Approximate

Not needed before manuscript Blueprint:
- exact coil Tesla-meter value
- exact fusion reaction / reactor geometry
- exact radiator emissivity/material
- exact atmospheric composition of every habitat
- exact propellant isotope chemistry
- detailed 8-body insertion simulation

These can be fixed only if an episode turns on them.

The current envelope is strong enough to keep those future choices bounded.

---

# 20. B6 Verdict

## Story-start mass
**CLOSED AT ORDER-OF-MAGNITUDE / WORKING POINT: 4.03×10^11 kg.**

## Remaining propellant
**CLOSED AT WORKING POINT: ~1.2×10^10 kg.**

## Arrival mass
**CLOSED AT WORKING POINT: ~3.9×10^11 kg.**

## Civil power / heat
**PASS.**

## Radiation architecture
**PASS AS MAJOR BUT BOUNDED EXTRAPOLATION.**

## Interstellar propulsion
**PASS FOR SCIENCE FICTION ONLY AS THE PROJECT'S LARGEST EXPLICIT ENGINEERING MIRACLE.**

## Arrival/settlement consistency
**PASS.**

### B6 STATUS

**PROVISIONAL PASS / NO LONGER A MACRO FREEZE BLOCKER.**

The project may now proceed to integrated Canon / Character / Relationship / SF / Webnovel QA before any Macro Freeze or Episode Blueprint.
