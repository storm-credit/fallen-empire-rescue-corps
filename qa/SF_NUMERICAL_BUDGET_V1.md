# SF Numerical Budget v1

Status: **ORDER-OF-MAGNITUDE QA — NOT FROZEN CANON**
Project: 《우주선에는 인간이 한 명뿐이다》
Population target: ~300,000
Purpose: determine whether the preferred ship/voyage model survives basic arithmetic.

This file intentionally uses conservative ranges and labels future extrapolations. The goal is not to pretend a 300,000-person interstellar ship is achievable today. The goal is to avoid contradictions that simple arithmetic would expose.

---

# 1. Primary Habitat Geometry

Working model:

- 8 rotating cylindrical habitat worlds
- radius per habitat: **1,500 m**
- axial length per habitat: **1,600 m**
- nominal inhabited gravity at outer surface: ~1 g
- habitats paired in counter-rotation where practical to reduce net angular momentum / attitude-control burden

## 1.1 Rotation rate

For centripetal gravity:

`a = ω²r`

At `r = 1,500 m` and `a = 9.80665 m/s²`:

- angular velocity: ~0.0809 rad/s
- rotation rate: **~0.772 rpm**
- tangential speed at ground: **~121 m/s**

### QA verdict

PASS.

The rotation rate is far below the multi-rpm regimes historically studied as problematic/adaptation-relevant for humans.

The very large radius is expensive structurally but excellent for everyday comfort and minimizes Coriolis weirdness.

---

# 2. Primary Living Area

Inner cylindrical surface per habitat:

`2πrL ≈ 15.08 km²`

Eight habitats:

**~120.64 km² primary inner living surface**

If 300,000 people were evenly distributed:

**~2,487 people/km²**

Actual density varies strongly by habitat.

### Interpretation

This is not spacious countryside for everyone, but it is enough to support:

- dense neighborhoods
- parks / ecological areas
- local water features
- industry/service districts
- visible open landscapes

provided a large fraction of agriculture and industry is stacked or located outside prime residential surface.

### QA verdict

PASS.

The surface is large enough for social/geographic differentiation but still small enough that material accounting matters.

---

# 3. Habitat Volume / Atmosphere

Full geometric cylinder volume across eight habitats:

`8 × πr²L ≈ 90.5 km³`

The full volume need not all have identical pressure or be completely unobstructed, but an open-drum architecture implies a very large atmosphere inventory.

At an average atmospheric density on the order of `0.9–1.1 kg/m³`:

Atmosphere mass order of magnitude:

**~8×10^10 to 1×10^11 kg**

= roughly **80–100 million tonnes**.

### This sounds enormous, but it is useful mass

The atmosphere provides:
- breathing gas reservoir
- thermal inertia
- some radiation column depth on inward-looking trajectories
- ecological buffering

At a 1.5 km radial path and ~1 kg/m³ average density, a ray traveling inward through the habitat atmosphere can encounter order `1,500 kg/m²` of atmospheric column (~150 g/cm²), though exact directional shielding varies greatly.

### QA verdict

PASS WITH MASS CONSEQUENCE.

The open-habitat look is viable only if the ship is accepted as hundreds of millions of tonnes, not a light spacecraft.

---

# 4. Radiation Shielding

Current deep-space shielding literature strongly favors hydrogen-rich materials such as water/polyethylene over simple aluminum for GCR mitigation, while also showing that long-duration shielding mass becomes enormous.

For a generation ship, shielding must be multifunctional:

- water
- ice
- food/process-water stocks
- organic/polymer materials
- soil/substrate
- stored carbonaceous feedstocks
- structural low-Z composites
- dedicated storm shelters

## 4.1 Exposed habitat shell area

Eight cylinder lateral surfaces:

**~120.6 km²**

Eight pairs of circular endcaps:

**~113.1 km²**

Simple total exposed habitat envelope order:

**~233.7 km²**

Real integrated geometry will differ because habitats connect to common structures and some surfaces can share shielding.

## 4.2 Working areal shielding envelope

Do **not** promise Earth-surface radiation levels everywhere.

Working design target for major inhabited directions:

**~100–200 g/cm² multifunctional equivalent**

= `1,000–2,000 kg/m²`

If naively applied across the full 233.7 km² envelope, that alone implies:

- 1,000 kg/m² → ~2.34×10^11 kg
- 1,500 kg/m² → ~3.51×10^11 kg
- 2,000 kg/m² → ~4.67×10^11 kg

This demonstrates why shielding dominates ship mass.

## 4.3 Architectural correction

Do not literally wrap every geometric surface with the same independent slab.

Reduce mass by:

- shared shield geometry between paired/clustered habitats
- storing water/food/feedstock where it provides shielding
- using atmospheric column depth as part of inward-direction protection
- placing high-occupancy sleeping/medical/childcare zones under greater mass
- dedicated solar-particle-event shelters with much heavier local protection
- keeping low-occupancy industrial/service regions at different dose standards

### QA verdict

PASS ONLY IF SHIP MASS IS HUGE.

A lightweight generation ship is rejected.

---

# 5. Working Total Ship Mass

Do not freeze a single number yet.

Current credible storytelling envelope:

**~5×10^11 to 1×10^12 kg**

= **500 million to 1 billion metric tonnes**.

Illustrative mass families:

- radiation / volatile / ecological shielding inventory: 2–4×10^11 kg
- atmosphere: ~0.8–1.0×10^11 kg
- habitat structure / pressure / rotating systems: ~0.8–1.5×10^11 kg
- axial spine / industrial / radiators / transit / reserve structures: ~0.5–1.0×10^11 kg
- water / agriculture / process / biochemical inventory not already counted as shielding: tens of billions kg
- propulsion / fuel / forward-impact protection / spares: potentially 1–2×10^11 kg

These categories overlap because material should do multiple jobs.

### Mandatory design principle

**Single-purpose dead mass is minimized.**

Water can be:
- life-support inventory
- radiation shield
- thermal buffer
- reaction/process feedstock

Structural/feedstock mass can later become settlement material.

### QA verdict

PASS as civilization-scale infrastructure.

This mass makes the propulsion problem the hardest engineering extrapolation in the setting.

---

# 6. Food / Crop Area

NASA bioregenerative-life-support studies provide a useful current anchor:

- ~20–25 m² crop area/person can supply approximately one person's oxygen demand under intensive controlled conditions
- ~40–50 m² crop area/person can provide approximately dietary calories, depending on crop/light assumptions

For 300,000 people:

- oxygen-equivalent crop canopy: **~6–7.5 km²**
- full-calorie crop canopy at 50 m²/person: **~15 km²**

This is crop **growing area/canopy**, not necessarily ground footprint.

## Working future ship food architecture

Do not rely on picturesque fields alone.

Use:
- 10–15 km² equivalent high-intensity crop canopy
- vertical/multilevel crop racks
- H2 cultural/open-field food landscapes
- microbial/fungal protein
- fermentation
- cultured animal products
- algae where useful
- seed/genetic libraries
- stored reserve foods for system failures

A three-to-five-layer controlled agriculture stack could compress much of the high-intensity crop footprint to a few km² of floor area while preserving separate visible ecological/cultural landscapes.

### QA verdict

PASS.

Agriculture fits comfortably within a 120 km² civilization if it is technologically intensive and partly stacked.

---

# 7. Food Energy / Lighting Power

Human dietary chemical energy at ~2,500 kcal/day/person:

300,000 people consume approximately:

**~36 MW average metabolic food energy**.

Producing that chemically useful energy through artificial lighting requires far more electrical input due to:
- LED losses
- photosynthetic efficiency
- non-edible biomass
- processing
- pumping
- environmental control
- cooling

NASA crop-light regimes imply hundreds of watts/m² class electrical/optical intensity for intensive controlled agriculture.

Working agriculture electrical budget:

**~3–6 GW**

including lighting and associated control/cooling, with future efficiency gains and microbial food production.

### QA verdict

PASS if civilization-scale electrical generation is tens of GW.

---

# 8. Civilization Electrical Power

Working cruise/late-voyage habitat power envelope:

**Normal: ~30–50 GW electrical**

**Peak / major industrial-transition periods: ~60–100 GW**

Illustrative demand families:

- agriculture / food: 3–6 GW
- habitat lighting / climate / pumping: several GW
- industrial recycling / fabrication: 5–15 GW variable
- computing / communications / medical systems: several GW
- transit / axial logistics: variable
- life support / water / atmosphere: several GW
- reserve margin / maintenance / storage losses

Propulsion power is **not** treated as normal city-grid load. The interstellar braking/propulsion system is a separate multi-order-of-magnitude system operating in long-duration campaigns.

### Power source

Advanced fusion-class generation remains a major future technology assumption.

Fission/isotope black-start / local emergency sources provide restart resilience.

### QA verdict

PASS AS SPECULATIVE FUTURE TECHNOLOGY.

Do not write “unlimited fusion power.” Heat rejection and maintenance remain limiting.

---

# 9. Waste Heat / Radiators

In deep space, almost every watt eventually becomes waste heat.

Radiator requirement can be order-estimated from blackbody emission.

For emissivity ~0.9 and 40 GW rejected:

- 320 K radiator equivalent: ~75 km² one-sided ideal emitting area
- 350 K: ~52 km²
- 400 K: ~31 km²
- 450 K: ~19 km²
- 500 K: ~13 km²

Real systems need:
- margins
- nonideal orientation
- pump/loop redundancy
- micrometeoroid protection
- multiple temperature loops

## Working architecture

Use large deployable radiator farms totaling order:

**~80–150 km² effective physical radiator surface**, distributed among temperature loops.

High-temperature industrial loops reduce required area.
Habitat comfort loops run cooler and require larger panels.

### Story consequence

Radiators are genuinely strategic infrastructure.

Damage, shadowing, coolant shortages, conversion, and maintenance windows can create E5 system pressure without inventing explosions.

### QA verdict

PASS.

The radiator scale is enormous but visually and narratively useful.

---

# 10. Water / Closed-Mass Logic

NASA has demonstrated ~98% overall water recovery on the ISS using brine-processing additions, which is impressive for exploration missions but **not sufficient as a literal net-loss rate for six centuries**.

Example:

If only 5 kg/person/day moved through a personal water loop:

300,000 × 5 kg/day = 1.5 million kg/day.

At a literal 2% permanent loss:

~30,000 kg/day would disappear from use.

Over 600 years:

~6.6 million tonnes would be lost.

Broader agricultural/industrial water flows make literal 2% vent loss even less acceptable.

## Generation-ship correction

Distinguish:

### First-pass/process recovery
May be ~98–99+% in a subsystem.

### Civilization-scale mass recovery
Must be **effectively near-closed**, plausibly >99.99% for water inventory over long averaging periods.

Crucially:

“not recovered on this pass” does **not** mean “ejected into space.”

It can remain in:
- brine
- wet waste
- biomass
- sludge
- industrial chemistry
- construction material
- storage

and be reprocessed later.

External venting is an emergency/failure state, not routine waste disposal.

### QA verdict

PASS AFTER CORRECTION.

The ship is a closed material economy, not a scaled-up ISS logistics model.

---

# 11. Air / Oxygen / Carbon

For 300,000 people, oxygen/carbon flows are hundreds of tonnes/day class.

No single ISS-like oxygen generator is credible at this scale.

Use hybrid loops:

- crop photosynthesis
- algae/microbial systems where useful
- CO2 capture
- electrolysis
- chemical reduction loops
- large atmosphere buffer
- industrial oxygen reserves

The huge habitat atmosphere makes short-term fluctuations easier to buffer, but long-term elemental balance remains tightly managed.

### Key principle

The ship tracks **atoms**, not trash bags.

Carbon, nitrogen, phosphorus, sulfur, potassium, trace metals, and water are all strategic inventories.

### QA verdict

PASS conceptually; detailed elemental budgets can stay below reader-facing level.

---

# 12. Forward Interstellar-Dust Hazard

At `0.02c ≈ 6,000 km/s`, even tiny particles are dangerous.

Classical kinetic-energy examples:

- 1 picogram (`10^-12 kg`) → ~18 J
- 1 microgram (`10^-9 kg`) → ~18 kJ
- 1 milligram (`10^-6 kg`) → ~18 MJ
- 1 gram (`10^-3 kg`) → ~18 GJ

Therefore “just use a thick hull” is rejected.

## Mandatory forward protection stack

- very large sacrificial leading mass/shield
- many separated bumper/plasma layers
- replaceable sacrificial tiles/ice/feedstock
- forward dust/radar/optical sensing for larger grains
- active ablation/ionization/deflection attempts for detected objects
- trajectory planning to avoid dense clouds
- habitats far behind the leading shield

Exact active-dust-deflection capability is speculative.

### QA verdict

PASS only as an extreme, continuously maintained subsystem.

Forward shield erosion must exist in maintenance/resource politics.

---

# 13. Interstellar Kinetic Energy

At `0.02c`, nonrelativistic approximation is adequate for order-of-magnitude energy because speed is only ~2% c.

For ship mass:

### 5×10^11 kg
Kinetic energy at 0.02c:
**~9×10^24 J**

### 8×10^11 kg
**~1.44×10^25 J**

### 1×10^12 kg
**~1.80×10^25 J**

This is enormous.

If `8×10^11 kg` were accelerated to that speed over 80 years, the **average useful kinetic-power transfer alone** would be order **5–6 petawatts**, before inefficiencies.

### Consequence

An onboard city-scale 40 GW reactor cannot casually accelerate the ship.

This is why launch acceleration uses civilization-scale external Solar-System infrastructure and why propulsion is treated as a separate mission architecture.

### QA verdict

This is the **largest extrapolation in the project**.

It is acceptable only if explicitly framed as one of the greatest infrastructure projects of the launch civilization.

---

# 14. Propulsion / Braking Budget

## Rejected

- constant 1 g interstellar thrust
- city power reactors casually doing interstellar acceleration
- chemical/nuclear-thermal rockets
- “fusion engine” with no propellant/energy consequences
- magsail alone magically stopping a billion-ton ship at the last minute

## Preferred hybrid

### Launch
Solar-System external momentum/energy infrastructure performs much of initial acceleration over decades.

Family of concepts:
- beamed particle/pellet propulsion
- laser/particle beam momentum transfer
- distributed boost infrastructure

Current NIAC concepts are probe/ton-scale, so generation-ship application is a vast extrapolation.

### Cruise
Mostly coast.

### Early/long braking
Very large magnetic/plasma sail systems gradually shed part of velocity against interstellar medium / target stellar environment.

### Final braking
Advanced onboard fusion direct-exhaust propulsion handles the remaining major delta-v and target-system maneuvering.

Propellant/fusion system may consume a substantial fraction of launch mass.

### Working propulsion mass fraction

Leave exact value OPEN, but reserve roughly:

**~15–25% of initial ship mass**

for propulsion propellant, braking systems, forward shield consumption, and related mission reserves.

This must later be reconciled with exhaust velocity and full delta-v.

### QA verdict

PROVISIONAL PASS, NOT HARD-SF PROOF.

---

# 15. Coherent Voyage Timeline Example

Use as QA reference, not canon yet.

Target distance: **~11 ly**
Peak cruise: **~0.02c**

One possible broad profile:

- ~50 years external-assisted acceleration / departure phase
- ~450–480 years high-speed coast
- ~90–110 years prolonged braking / approach

Total:

**~600–640 years**

This is compatible with the existing story target.

## Story start

If story begins ~15 years before system arrival and braking is already far advanced:

- the ship need not still be moving at 0.02c
- target-system observations are excellent
- arrival engineering decisions are immediate
- characters can plausibly expect to witness settlement

The irreversible settlement-conversion threshold can be only **2–4 years away**, even if physical arrival is farther off.

### QA verdict

PASS.

This timeline is much more coherent than implying the ship remains at full cruise until a last-minute brake.

---

# 16. Data / AI Compute Burden

A major advantage of the current ontology design:

The 300,000 citizens' mature minds are **not running on central computers**.

Their cognition runs in biological brains.

Therefore the ship does not need computational hardware equivalent to simulating 300,000 conscious brains in real time.

Ship compute supports:
- automation
- engineering
- navigation
- archives
- medical models
- civic systems
- robotics
- continuity capture/restoration infrastructure

This is still a major computing civilization, but not a hidden Matrix datacenter.

### QA verdict

STRONG PASS.

---

# 17. Maintenance Across 600 Years

No component is assumed to last the whole voyage unchanged.

The ship survives because it carries:

- machine tools
- material recycling
- foundry/fabrication capability
- electronics manufacturing
- chemical processing
- seed/genetic libraries
- replacement production lines
- metrology/calibration standards
- multiple technical generations

Most of the ship has been replaced, repaired, rebuilt, or re-certified many times.

This directly supports:
- archaeological infrastructure layers
- local technical cultures
- obsolete interfaces
- protagonist transition work

### QA verdict

PASS only if the ship is understood as a self-renewing industrial civilization, not a 600-year-old untouched vehicle.

---

# 18. Major Numerical Findings

## Strong findings

- 1.5 km radius → ~0.77 rpm at 1 g: comfortable design regime
- ~120 km² primary habitat surface fits 300k at city-scale density
- ~15 km² high-intensity crop canopy is a useful current-tech anchor for full dietary calories
- city electrical budget of tens of GW is consistent with intensive agriculture/industry if advanced fusion exists
- radiator farms of tens to >100 km² are physically the correct order for tens of GW waste heat
- organic local cognition eliminates impossible central-AI compute burden

## Expensive but useful findings

- atmosphere itself is tens of millions of tonnes
- radiation shielding plausibly dominates mass
- total ship likely hundreds of millions to ~1 billion tonnes
- forward dust shielding must be massive and sacrificial

## Weakest finding

**Interstellar propulsion/braking is by far the biggest speculative leap.**

The project should be explicit about this rather than burying it in technobabble.

---

# 19. Canon Recommendations from This QA

Promote provisionally:

1. 8 habitats around `r ≈ 1.5 km` class
2. habitat rotation `~0.77 rpm` class
3. primary inner area `~120 km²` class
4. total ship mass `5×10^11–1×10^12 kg` class
5. normal electrical civilization `30–50 GW` class
6. large multi-temperature radiator farms `~80–150 km²` class
7. bioregenerative + physico-chemical hybrid life support
8. essentially closed material economy; first-pass recovery ≠ net mass loss
9. external-assisted launch + long hybrid braking
10. voyage order `~600 years`, story during late braking/approach

Keep OPEN:

- exact target system
- exact shielding thickness / dose standard
- exact total mass
- exact fusion exhaust velocity / propellant fraction
- exact external launch architecture
- exact braking split among sail/fusion/other systems
- exact power grid
- exact atmospheric pressure/composition

---

# 20. Source Anchors

Primary/official sources used for current-technology anchors:

- NASA NTRS — Galactic and Solar Cosmic Ray Shielding in Deep Space
- NASA NTRS — Radiation Engineering Analysis of Shielding Materials
- NASA NTRS — Effects of Simulated Artificial Gravity on Human Performance
- NASA NTRS — Overview of Artificial Gravity
- NASA — ISS 98% Water Recovery Milestone
- NASA NTRS — Bioregenerative Life Support for Humans in Space
- NASA NTRS — Plants for Human Life Support and Space Exploration
- NASA — NIAC pellet-beam / self-guided beamed propulsion studies
- NASA NTRS — Use of Magnetic Sails for Advanced Exploration Missions

These establish physical families and current benchmarks only. None demonstrates feasibility of this generation ship.

---

# 21. Numerical QA Verdict

**WORLD/SHIP HABITABILITY: PASS AT ORDER-OF-MAGNITUDE LEVEL**

**PROPULSION: PROVISIONAL PASS AS EXPLICIT MAJOR FUTURE EXTRAPOLATION**

No current numerical result forces abandonment of the 300,000-person / 600-year / rotating-habitat premise.

But the design must retain the ship's enormous mass and infrastructure costs; shrinking them for convenience would break the credibility gained here.
