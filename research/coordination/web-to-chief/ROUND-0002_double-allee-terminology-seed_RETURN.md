# ROUND-0002 — WEB SEARCH RETURN

**From:** WEB SEARCHER  
**To:** CHIEF RESEARCHER  
**Date:** 2026-09-28  
**Answers:** `research/coordination/chief-to-web/ROUND-0002_double-allee-terminology-seed_REQUEST.md`  
**Status:** COMPLETE FOR SEED SCOPE

## Executive finding

“Double/Multiple Allee effect” is **not one standardized mathematical object**.

Foundational ecological usage separates component and demographic Allee effects. “Multiple Allee effects” commonly means multiple component mechanisms acting simultaneously, not two demographic critical densities. Mathematical predator–prey papers use “Double Allee effect” for several specific functional forms, often combining a strong threshold factor with another low-density suppression mechanism.

The novelty search also found direct prior art for:
- Caputo fractional Double-Allee systems (at least since 2021);
- later fractional local/global/Hopf analyses;
- incommensurate fractional Double-Allee dynamics;
- discrete fractional Double-Allee models;
- reaction–diffusion Double-Allee models.

Therefore simple “Double Allee + fractional derivative” or “Double Allee + diffusion” directions are already covered.

## Search coverage

### Sources/databases

Primary ecology/mathematical-biology publisher pages, PubMed, DOI-indexed web search, author manuscripts/arXiv where available, plus citation/author follow-up searches.

### Query families

See `research/web-search/QUERY_REGISTRY.md`.

Families included:
- exact “double Allee effect”;
- “multiple Allee effects”;
- component versus demographic terminology;
- strong versus weak;
- two/multiple thresholds;
- depensation/critical density;
- saddle-node/fold/hysteresis;
- predator–prey bifurcation;
- fractional/Caputo/incommensurate/discrete;
- diffusion/spatial;
- metapopulation/network/dispersal;
- real-data/multiple mechanisms;
- identifiability/inverse-problem phrasing;
- bistability/tipping vocabulary without “Allee”.

### Citation expansion

Performed around foundational terminology sources and the principal mathematical Double-Allee model family. The search also moved outside Double-Allee vocabulary to strong-Allee patch/network theory.

### Recent-literature check

2025–2026 papers were found for incommensurate fractional and discrete fractional Double-Allee models, so the recent frontier materially affects novelty claims.

## Strongest evidence found

### Terminology control

Stephens–Sutherland–Freckleton (1999), DOI 10.2307/3547011, and Courchamp–Clutton-Brock–Grenfell (1999), DOI 10.1016/S0169-5347(99)01683-3, provide foundational Allee terminology.

Berec–Angulo–Courchamp (2007), DOI 10.1016/j.tree.2006.12.002, treats **multiple Allee effects** as multiple component mechanisms and gives empirical examples.

### Analytical Double-Allee prior art

González-Olivares et al. (2011), DOI 10.1016/j.camwa.2011.08.061, studies consequences for limit-cycle multiplicity.

Pal–Saha (2015), DOI 10.1016/j.chaos.2014.12.007, gives substantial qualitative analysis of a predator–prey Double-Allee model, including strong/weak regimes, bistability/separatrices and codimension-one/two bifurcation structure.

### Fractional prior art

Rahmi et al. (2021), DOI 10.3390/fractalfract5030084, directly combines a Double Allee effect with Caputo memory and analytical stability work.

Further sources include:
- DOI 10.1371/journal.pone.0305179 (2025);
- DOI 10.1016/j.cjph.2025.09.020 (2025, including incommensurate orders);
- DOI 10.3390/fractalfract10050304 (2026, discrete fractional).

### Spatial/network-adjacent prior art

Li–Li (2024), DOI 10.3934/math.20241309, provides direct reaction–diffusion Double-Allee prior art.

Lanchier (2013), DOI 10.1239/aap/1386857863, gives analytical interacting-patch/geometry results for strong Allee dynamics. This is important adjacent theory even though it is not labeled “Double Allee”.

## Closest prior art

For a future structural research direction:
- **fractional-memory closest:** Rahmi et al. 2021 and 2025–2026 extensions;
- **bifurcation closest:** Pal–Saha 2015;
- **topology closest:** Lanchier 2013 strong-Allee patch theory;
- **spatial closest:** Li–Li 2024;
- **empirical multiple mechanisms:** Berec et al. 2007 and the primary studies it synthesizes.

## Evidence against novelty

1. **Double Allee + Caputo** — DIRECT PRIOR RESULT FOUND.
2. **Double Allee + incommensurate fractional orders** — DIRECT PRIOR RESULT FOUND.
3. **Double Allee + discrete fractional dynamics** — DIRECT PRIOR RESULT FOUND.
4. **Double Allee + spatial diffusion** — DIRECT PRIOR RESULT FOUND.
5. **“Double Allee = two demographic thresholds”** — unsupported as a universal definition; terminology collision.
6. **Topology-dependent Allee thresholds are wholly new** — false at least for adjacent strong-Allee patch/network theory.

## Negative searches and limitations

No general arbitrary-graph theorem for a **precisely defined genuinely multi-threshold Double-Allee local mechanism** was identified in the seed corpus.

No real-data study was identified in the seed that jointly:
- demonstrates a genuinely multi-threshold demographic mechanism;
- estimates/identifies a fractional order;
- establishes identifiability of both from observations.

These are scoped negative findings only. They require dedicated follow-up before any novelty claim.

The seed does not exhaust:
- stochastic metapopulation theory;
- bistable network systems outside ecological vocabulary;
- resilience/tipping literature;
- depensation/fisheries literature;
- inverse problems and structural identifiability;
- real longitudinal/spatial datasets.

## Dataset findings

A major direct empirical source was identified: **Angulo et al. (2007), DOI 10.1111/j.1523-1739.2007.00721.x**. The paper analyzed island-fox demographic data from **1988–2000**, found simultaneous component Allee effects in survival and breeding-female proportion, linked adult survival to Golden Eagle predation, and reported a resulting demographic Allee effect with suboptimal growth below roughly **7 foxes/km²**.

This makes the island fox the strongest concrete dataset lead from the seed round. It still does **not** establish two positive demographic thresholds or fractional-memory identifiability.

Other promising dataset leads for a future dedicated audit include:
- plant systems combining pollination and inbreeding;
- reintroduced Crested Ibis with simultaneous component demographic effects;
- gray wolves;
- gypsy moth mate-finding/critical-patch systems.

No dataset is promoted here as proving a Double Allee effect.

## Source registry

See:
- `research/web-search/SOURCE_REGISTRY.md`
- `research/web-search/2026-09-28_double-allee-terminology-seed.md`

## Files updated

- `research/double-allee/TERMINOLOGY.md`
- `research/double-allee/STATE_OF_ART.md`
- `research/web-search/SEARCH_LOG.md`
- `research/web-search/QUERY_REGISTRY.md`
- `research/web-search/SOURCE_REGISTRY.md`
- `research/web-search/NOVELTY_CHECKS.md`
- `research/web-search/2026-09-28_double-allee-terminology-seed.md`
- `corpus/papers.csv`
- `corpus/theorems.csv`
- `bibliography/references.bib`
- this RETURN

## Recommended next search

Split the next evidence work into two rounds:

1. **Network/multithreshold falsification:** graph Laplacians, stochastic patch models, bistable networks, monotone systems, rescue thresholds, pinning/coupling, and arbitrary topology—without requiring the words “Double Allee”.
2. **Dataset/identifiability audit:** find raw repeated-measure/spatial population datasets and test whether one-versus-multiple thresholds and memory order are structurally/practically distinguishable.

## RETURN TO CHIEF

**What the evidence supports:** “Double/Multiple Allee” must be decomposed into mechanism count and threshold/equilibrium geometry; several naive fractional/spatial combinations are already published; and the island fox provides direct empirical evidence of simultaneous component + demographic Allee effects.

**What the evidence does not support:** It does not support simple fractionalization, incommensurate fractionalization, discrete fractionalization, or adding diffusion as a new research program.

**Main novelty threat:** Existing 2021–2026 fractional Double-Allee literature plus older analytical bifurcation and patch-topology theory.

**Most important unresolved question:** Whether a general theorem for genuinely multi-threshold local dynamics on arbitrary networks—or a data-identifiability theorem coupling thresholds and memory—survives a deeper cross-literature search.