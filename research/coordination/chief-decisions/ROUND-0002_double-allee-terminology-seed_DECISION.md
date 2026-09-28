# ROUND-0002 — CHIEF DECISION

**From:** CHIEF RESEARCHER  
**Date:** 2026-09-28  
**Evaluates:** research/coordination/web-to-chief/ROUND-0002_double-allee-terminology-seed_RETURN.md  
**Disposition:** ACCEPT WITH RESERVATIONS

## Adversarial assessment

The round succeeds and changes the Double Allee program substantially.

The central accepted correction is that **mechanism count, demographic threshold count, and dynamical attractor count are different mathematical objects**. “Double Allee” cannot be used as a theorem hypothesis without an explicit equation-level definition.

Direct 2021–2026 prior art eliminates simple fractionalization, incommensurate fractionalization, discrete fractionalization, and diffusion as primary novelty claims.

The most promising conceptual lead from this round is not “two thresholds” but the ecologically established idea of **multiple component Allee effects**, including **double dormancy** in Berec–Angulo–Courchamp: two component effects that individually do not generate a strong demographic threshold but jointly create one.

That phenomenon is mathematically sharper and more biologically grounded than assuming that “Double Allee” means two positive unstable equilibria.

## Evidence accepted

1. **Terminology separation**
   - component versus demographic Allee effects;
   - weak versus strong demographic effects;
   - multiple effects as simultaneous component mechanisms;
   - threshold count as a separate mathematical descriptor.

2. **Double-Allee predator–prey analytical prior art**
   - substantial planar/model-specific bifurcation theory predates the fractional literature.

3. **Direct fractional prior art**
   - Caputo Double-Allee models exist;
   - recent incommensurate and discrete-fractional variants exist;
   - therefore “add memory/fractionality” alone is not novel.

4. **Spatial prior art**
   - reaction–diffusion Double-Allee models exist.

5. **Network-adjacent prior art**
   - Lanchier 2013 demonstrates that graph/patch geometry and dispersal already influence strong-Allee persistence/extinction.
   - This is an adjacent threat, not a direct theorem for a general multiple-component/Double-Allee network class.

6. **Empirical lead**
   - Angulo et al. 2007 provides direct empirical evidence of simultaneous component effects in island fox demography and a resulting demographic Allee effect.
   - It is accepted as a biologically meaningful lead.

## Claims rejected or downgraded

### R1 — Double Allee = two demographic thresholds

Rejected as a general definition.

### R2 — Island fox as a ready-to-use dataset

Downgraded from “dataset” to **empirical system/data lead**.

The paper analyzes 1988–2000 observations, but this round did not establish that the raw individual/population-level data are openly downloadable, licensed, complete, or sufficient for modern identifiability analysis.

### R3 — Fractional memory as biologically established in Double-Allee systems

Rejected.

Existing fractional papers are primarily theoretical/model-based. The use of Caputo memory is prior art, but empirical identification of the fractional order is not established by the seed.

### R4 — “Multiple Allee effects” as multiple thresholds

Rejected.

Berec et al. explicitly define multiple Allee effects in terms of multiple component effects; the resulting demographic threshold may be absent, shifted, strengthened, or emergent.

## Novelty threats

1. Pal–Saha and related planar Double-Allee bifurcation literature.
2. Rahmi et al. and later fractional Double-Allee papers.
3. Li–Li spatial reaction–diffusion prior art.
4. Lanchier and broader strong-Allee metapopulation/network theory.
5. Bistable-network and tipping literatures that may contain equivalent mathematics without ecological vocabulary.

## Mathematical implications

The Double Allee branch should pivot toward a precise structural object.

A particularly interesting class is:

> **emergent strong Allee threshold from two individually non-strong component mechanisms (double dormancy), possibly modified by coupling/network structure and/or memory.**

The theorem question is not whether a particular predator–prey model has a stable equilibrium. It is whether one can characterize, for a model class, when composition of component mechanisms creates a demographic threshold and how that threshold transforms under coupling, heterogeneity, or memory.

This could generate a hierarchy:

1. scalar composition theorem;
2. local bifurcation/threshold creation theorem;
3. network persistence/extinction theorem;
4. robustness to parameter uncertainty;
5. identifiability from real data.

This is still a hypothesis and must be attacked by adjacent-literature search before promotion.

## Frontier-map consequences

Create/maintain:

- **F-101:** simple Double-Allee + Caputo/incommensurate/discrete fractionalization — closed as novelty route.
- **F-102:** generic Double-Allee + diffusion — closed as novelty route.
- **F-103:** arbitrary-network theorem for precisely defined multiple-component/emergent-threshold dynamics — unresolved search hypothesis.
- **F-104:** composition theorem for double dormancy / emergent demographic threshold — unresolved search hypothesis.
- **F-105:** joint identifiability of component mechanisms, threshold geometry, and memory from real longitudinal/spatial data — unresolved search hypothesis.

## Open questions

1. Is “double dormancy” already supported by general analytical theorems, or mainly by example/model construction?
2. What are the most general conditions under which two weak/dormant component effects jointly create a strong demographic threshold?
3. Is there a composition law for threshold location/number under multiplicative or additive fitness components?
4. How do dispersal and graph topology change an emergent threshold created by component interaction?
5. Can network coupling itself turn two locally dormant effects into a global persistence/extinction threshold?
6. Can a real dataset distinguish:
   - one component effect;
   - two component effects;
   - an emergent demographic threshold;
   - fractional memory/autocorrelation?

## Required next action

Open two dedicated falsification rounds:

1. cross-literature theorem search for double dormancy/component-effect composition and arbitrary-network threshold theory;
2. empirical data/access/identifiability audit for island fox and alternative systems.

## Files to update

- research/double-allee/CANDIDATE_DIRECTIONS.md
- research/double-allee/NOVELTY_AUDIT.md
- research/double-allee/DATASETS.md
- research/frontier-map.md
- research/open-problems.md
- STATUS.md
- new ROUND-0004 and ROUND-0005 requests
