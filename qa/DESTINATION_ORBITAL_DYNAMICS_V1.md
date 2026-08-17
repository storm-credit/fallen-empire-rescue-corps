# Destination Orbital Dynamics QA v1

Status: **ORDER-OF-MAGNITUDE ORBITAL QA — FUTURE PLANET VALUES PROVISIONAL**
Project: 《우주선에는 인간이 한 명뿐이다》
Target: Ross 128 b
Depends on:
- `canon/DESTINATION_CLIMATE_MODEL_V1.md`
- `narrative/FINAL_SETTLEMENT_ARCHITECTURE_V1.md`

---

# 0. Present Astronomy vs Future Fiction

Present robust Ross 128 values from the NASA Exoplanet Archive / Bonfils et al. solution:

- stellar mass: ~0.168 M☉ (one literature solution; archive also lists alternatives)
- planet `M sin i`: ~1.40 M⊕
- semimajor axis: ~0.0496 AU
- period: ~9.8658 d

Future-fiction working planet values:

- true mass: 1.48 M⊕
- radius: 1.16 R⊕
- synchronous rotation: 9.8658 d

Calculations below use those values as a design test.

---

# 1. Hill Sphere

Using:

`R_H ≈ a (Mp / 3M*)^(1/3)`

with:
- `a = 0.0496 AU`
- `Mp = 1.48 M⊕`
- `M* = 0.168 M☉`

working Hill radius:

**~153,000 km from planet center**.

This is small compared with Earth's Hill sphere because Ross 128 b orbits very close to its low-mass star.

---

# 2. Conservative Large-Satellite / Habitat Zone

Long-term prograde satellite stability is normally substantially inside the full Hill radius; compact exoplanet/exomoon literature commonly treats roughly half the Hill radius as an outer stability scale before more detailed eccentricity/inclination effects.

For design, do not place civilization-critical habitats near the theoretical edge.

Use a conservative working operational envelope:

**planet-center radius ~15,000–45,000 km**

for the large primary planet-bound habitats.

This is well inside ~0.4 R_H (~61,000 km).

Exact stable limits must later include:
- actual planet eccentricity
- stellar tides
- habitat mutual perturbations
- inclination
- stationkeeping

---

# 3. Synchronous Orbit Check

If the planet's rotation is synchronous with its ~9.8658-day year, the orbital radius for a satellite with the same ~9.8658-day period is:

**~221,000 km from planet center**.

That is **outside the ~153,000 km Hill radius**.

Therefore:

> Ross 128 b cannot support an ordinary stable planet-synchronous/geostationary orbit.

This is a useful hard worldbuilding consequence.

No city-sized station remains permanently over one surface settlement by passive orbit.

---

# 4. Example Planet-Bound Habitat Orbits

Using future planet mass 1.48 M⊕:

| Radius from center | Approx orbital period | Approx altitude above 1.16 R⊕ surface |
|---:|---:|---:|
| 15,000 km | 4.2 h | ~7,600 km |
| 20,000 km | 6.4 h | ~12,600 km |
| 25,000 km | 9.0 h | ~17,600 km |
| 30,000 km | 11.8 h | ~22,600 km |
| 40,000 km | 18.2 h | ~32,600 km |
| 45,000 km | ~21.7 h | ~37,600 km |

These are not final assignments.

They show that multiple large habitats can occupy **hours-scale planetary orbits** rather than synchronizing with the surface.

---

# 5. Four Large Habitats Around the Planet

Previous ending architecture proposed H1/H2/H4/H5 as planet-associated orbit worlds.

This remains feasible at order-of-magnitude level if they are not simply placed in one crowded equatorial ring.

Preferred geometry family:

## Inner pair
H5 + one service-heavy habitat at ~18,000–24,000 km class.

Advantages:
- shorter surface transit
- fast orbital period
- logistics role

## Outer pair
H1/H2/H4 subset at ~30,000–45,000 km class.

Advantages:
- greater separation
- lower orbital angular speed
- more room for large shield/industrial appendages

Use:
- different orbital planes / nodes
- phase separation
- active collision avoidance / stationkeeping

A 1.5-km-radius habitat is physically tiny relative to tens of thousands of km orbital spacing.

Mutual gravitational interaction among tens-of-billions-tonne habitats remains tiny compared with a ~9×10^24 kg planet, though collision/navigation risk is operationally serious.

---

# 6. Recommended Revision: Only Three Major Habitats Deep in Planet Orbit

Although four is physically possible, three is narratively and operationally cleaner.

Recommended planet-bound large habitats:

### H2 Biosphere Commons
Planetary ecological backup.

### H4 Kinship Belt
Family/care continuity anchor.

### H5 Exchange Ring
Surface-orbit logistics interface.

### H1 Civic Core — revise to star-planet co-orbital / transfer network

Why move H1 out of deep planet orbit:
- prevents the old civic center from physically dominating the surface
- reduces large-habitat crowding
- reinforces final political decentralization
- lets H1 sit as a network node among planetary and star-centric worlds

H1 can operate from a controlled star-centric co-orbital orbit while maintaining distributed offices on surface/H5/H2.

This is a **narrative improvement produced by orbital QA**, not merely physics.

---

# 7. Star-Centric Habitat Families

The remaining large habitats need not fit inside the planet's Hill sphere.

Preferred solution:

**artificially maintained star-centric or co-orbital settlement groups near Ross 128 b's orbital radius.**

Possible families:

### Trojan-like leading/trailing regions
Near the planet's L4/L5 geometry (~60° ahead/behind), subject to detailed future astrodynamic design.

Advantages:
- huge physical separation from planet orbit congestion
- same broad stellar-energy environment
- long-term recognizable “world clusters”

### Nearby non-identical star-centric orbits
Slightly different semimajor axes / resonant configurations with continuous low-level stationkeeping.

Advantages:
- easier to assign distinct industrial/privacy/archive worlds
- avoids pretending passive L4/L5 solves every multi-body issue

Preferred canon wording until further QA:

> `planet-associated orbit` versus `Ross 128 co-orbital / star-centric settlement orbit`

Do **not** freeze exact Lagrange-point addresses yet.

---

# 8. Transport Consequence

Planet-bound habitats at tens of thousands of km:
- surface transfer can occur in hours
- frequent cargo/passenger service plausible with advanced high-thrust in-system vehicles

Star-centric/co-orbital habitats:
- can lie hundreds of thousands to millions of km away depending configuration
- travel becomes a scheduled inter-world trip rather than an elevator ride

This is desirable.

The ending's “more than one world” should be felt in travel time and logistics.

---

# 9. Communications Consequence

Even millions of km create only seconds-to-tens-of-seconds light time.

Therefore:
- governance/data can remain tightly connected technologically
- physical travel and material shipment remain nontrivial

This creates a civilization that is politically plural without relying on communications isolation.

---

# 10. Surface Relay Architecture

Because no stable geostationary orbit exists:

Use a constellation of:
- low/medium planetary-orbit communication satellites
- navigation beacons
- relay stations attached to moving large habitats

Surface settlements see different orbital habitats pass through the sky.

This becomes a strong visual/cultural motif:

> the old ship worlds move overhead rather than owning a fixed longitude.

---

# 11. Planetary Tidal / Orbital Maintenance

Large habitats require active maintenance because:
- stellar perturbations matter
- the Hill sphere is compact
- a synchronous planet has strong star-defined geometry
- industrial modules detach/reattach

Do not frame stationkeeping as zero-cost.

But required delta-v is tiny compared with interstellar braking; this is normal civilization infrastructure.

---

# 12. Surface Launch / Descent

At ~1.10 g and near-Earth-size radius, planetary escape velocity remains Earth-class or somewhat higher.

Therefore surface logistics are **not free**.

This supports H5 orbital exchange as a real economic function.

Do not use routine personal commuting from surface to orbit as if taking a train.

Cargo/passenger transport remains scheduled and energy-intensive.

---

# 13. Preferred Habitat Fate Revision

## Planet-bound large habitats
- H2 Biosphere Commons
- H4 Kinship Belt
- H5 Exchange Ring

## Ross 128 co-orbital / star-centric large habitats
- H1 Civic Core
- H3 Fabrication Concord
- H6 Memory Commons
- H7 Low-Link Communities
- H8 Legacy Habitat

This 3/5 split is now preferred over the previous 4/4 split.

Why:
- safer orbital packing
- stronger political decentralization
- more distinct world geography
- H1 stops physically mapping to “planet capital”

---

# 14. Final Physical Metaphor

The old ship does not become:

`planet + satellites around a capital`.

It becomes:

`three close planetary-orbit worlds + surface settlements + five wider star-centric/co-orbital worlds + distributed industry`.

The civilization's geography itself rejects one privileged center.

---

# 15. Current QA Verdict

## Hill-sphere logic
**PASS.**

## No geostationary orbit
**STRONG PHYSICAL CONSEQUENCE / PASS.**

## Three large planet-bound habitats
**PREFERRED.**

## Five star-centric/co-orbital habitats
**PASS AT ARCHITECTURE LEVEL; exact resonances/L4-L5 need later simulation.**

## Full final insertion map
Still OPEN.

Recommendation:
Update final settlement architecture from 4/4 to **3 planet-bound / 5 star-centric** before Freeze.
