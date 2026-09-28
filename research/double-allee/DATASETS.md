# Double Allee — Dataset Inventory

**Status:** preliminary empirical leads only. No dataset has yet passed access + identifiability audit.

## D-001 — Island fox demographic system

**Primary study:** Angulo, Roemer, Berec, Gascoigne, Courchamp (2007), *Double Allee Effects and Extinction in the Island Fox*, DOI 10.1111/j.1523-1739.2007.00721.x.

**Species/system:** island fox populations on the California Channel Islands.

**Study period reported:** 1988–2000.

**Observed/analyzed quantities reported in the paper:**
- fox density;
- adult and pup survival;
- proportion of breeding adult females;
- Golden Eagle presence/predation context;
- per-capita population trends.

**Ecological relevance:**
- simultaneous component Allee effects were reported for survival and breeding;
- adult-survival effect was associated with eagle predation;
- component effects generated a demographic Allee effect;
- the paper reports suboptimal growth below roughly 7 foxes/km^2.

**What is NOT yet verified:**
- open raw-data repository;
- license/access conditions;
- exact per-island sample sizes and missingness in reusable machine-readable form;
- measurement-error model;
- whether enough time points/replicates remain after stratification;
- whether the observations can distinguish one mechanism from two;
- whether any fractional-memory parameter is identifiable.

**Current classification:** strongest empirical **system lead**, not yet an approved dataset.

**Next action:** ROUND-0005 must trace supplementary material, repositories, author/institution archives, and any later reuse of the underlying data.

---

## D-002 — Other candidate systems from multiple-Allee literature

### Plant systems: pollination + inbreeding

**Potential value:** two biologically distinct component mechanisms; possible repeated reproductive/demographic measurements.

**Unknowns:** raw longitudinal data, threshold observability, spatial replication.

### Crested Ibis reintroduction

**Potential value:** conservation recovery with multiple demographic components.

**Unknowns:** open repeated-measure data and sufficient low-density regime coverage.

### Gray wolves

**Potential value:** mate limitation/social/cooperative mechanisms and long-term monitoring.

**Unknowns:** whether mechanisms are separable from harvest/environmental forcing and whether low-density transitions are sampled.

### Gypsy moth / spongy moth

**Potential value:** mate-finding Allee effects, spatial spread and patch thresholds; rich invasion literature may offer data.

**Unknowns:** whether a genuinely multiple-component mechanism is documented in the same observational system.

## Dataset acceptance gate

A dataset can be promoted only if ROUND-0005 establishes:

1. legal/open or realistically obtainable access;
2. repeated observations spanning the low-density regime;
3. at least one measured demographic component beyond aggregate abundance;
4. enough replication or time depth for model discrimination;
5. a plausible observation-error model;
6. a defensible route to one-vs-two component comparison;
7. no obvious structural non-identifiability that makes the intended theorem/application meaningless.

Fractional-order estimation is optional. It must not be forced if the data do not support it.
