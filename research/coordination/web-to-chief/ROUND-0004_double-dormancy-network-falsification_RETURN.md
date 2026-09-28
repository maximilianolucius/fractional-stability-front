# ROUND-0004 — WEB SEARCH RETURN

**From:** WEB SEARCHER  
**To:** CHIEF RESEARCHER  
**Date:** 2026-09-28  
**Answers:** `research/coordination/chief-to-web/ROUND-0004_double-dormancy-network-falsification_REQUEST.md`  
**Status:** COMPLETE FOR REQUESTED FALSIFICATION SCOPE

## Executive finding

Both candidates survive only after substantial narrowing.

- **C-DA-1:** survives as a potential **general exact composition theorem** for explicitly separable component fitness functions. It is not enough to show emergent Allee behavior: direct two-component threshold papers and general emergent-Allee theorems already exist.
- **C-DA-2:** is much more threatened. Arbitrary-network persistence/extinction theorems already exist for heterogeneous mixtures of logistic and bistable/Allee-like local dynamics. A network paper is distinct only if the separate component mechanisms remain mathematically visible in the theorem.

## C-DA-1 evidence classification

**PARTIAL / CLOSE PRIOR ART — SURVIVES ONLY IN SHARP FUNCTION-CLASS FORM.**

### Strongest direct threat

Guijie Lan (2025), DOI 10.1016/j.chaos.2025.116952, rigorously analyzes a stochastic single-species model with **two component Allee effects**, including deterministic equilibrium existence/stability and a sharp stochastic extinction/permanence threshold.

This directly blocks a claim that rigorous threshold dynamics for two component effects is missing.

### Other close prior art

- Berec et al. 2007 already formulate double dormancy, derive part of the equilibrium logic of a concrete two-component model, and explicitly note a parameter-region separation that required numerical methods.
- de Roos–Persson–Thieme 2003 proves conditions for an emergent Allee effect in a structured predator/prey setting.
- van Kooten–de Roos–Persson 2005 gives parameter conditions for emergent Allee effect/bistability from stage-specific predation.
- Jorge–Martinez-Garcia 2024 gives a bottom-up framework translating a component Allee effect plus endogenous spatial aggregation into demographic effects.

### What was not found

No source was identified that provides the exact proposed general theorem over a separable function class:
- both components individually non-strong;
- necessary-and-sufficient joint threshold creation;
- uniqueness/multiplicity of positive thresholds;
- comparative statics of threshold location;
- fold/nondegeneracy characterization.

That residual claim is mathematically meaningful but must be specified by hypotheses, not by the phrase “double dormancy.”

## C-DA-2 evidence classification

**CLOSE PRIOR ART — SURVIVES ONLY IF COMPONENT DECOMPOSITION CHANGES THE NETWORK THEOREM.**

### Strongest theorem against C-DA-2

Stehlík, Švígler & Volek (2023), DOI 10.1016/j.jmaa.2023.127581, Theorem 1.1.

Their reaction–diffusion-on-graphs framework:
- uses connected arbitrary undirected graphs;
- permits heterogeneous local per-capita growth functions;
- explicitly mixes logistic and bistable local dynamics;
- includes diffusion/migration survival;
- gives conditions separating uniform persistence from local extinction;
- makes the threshold depend on migration, graph structure, and the aggregate/distribution of growth rates.

A theorem saying only “topology/dispersal transforms an Allee/bistable persistence threshold” would therefore be redundant.

### Additional threats

- Nagatani–Ichinose 2019: topology-sensitive Allee equilibria on small, star and complete graphs.
- Zhou–Wang 2004: local Allee effects generate a metapopulation-level occupancy threshold depending on migration/survival.
- Lanchier 2013: stochastic interacting-patch persistence/extinction under strong Allee effects.

## Non-Allee vocabulary search

Searches included:
- bistable networks;
- source–sink dynamics;
- coupled saddle-node/bistable nodes;
- persistence/extinction on graphs;
- graph reaction–diffusion;
- metapopulation rescue;
- stage-structured emergent bistability;
- component-to-demographic scaling.

The strongest non-Allee result was Stehlík et al. 2023.

## Minimal assumptions for a useful surviving C-DA-1 theorem

The function class should impose:
1. separate interpretable component terms;
2. monotonicity/curvature/shape constraints;
3. high-density negative feedback;
4. explicit component-deletion counterfactuals defining dormancy;
5. root transversality at the emergent threshold;
6. finite-zero control.

Without such restrictions, arbitrary smooth compositions can have arbitrary root multiplicity, so uniqueness/general characterization is impossible.

## Strongest prior theorem against each candidate

**C-DA-1:** Lan (2025), DOI 10.1016/j.chaos.2025.116952.

**C-DA-2:** Stehlík–Švígler–Volek (2023), Theorem 1.1, DOI 10.1016/j.jmaa.2023.127581.

## Negative searches and limitations

- Exact phrase “double dormancy” remains concentrated around Berec's conceptual lineage.
- Full theorem text of Lan 2025 was not accessible in this pass; claims are limited to publisher metadata/abstract.
- No exhaustive search over every catastrophe-theory monograph was possible; generic saddle-node theory clearly supplies local bifurcation conditions but does not encode component deletion/counterfactual dormancy by itself.
- No direct arbitrary-graph theorem was found whose hypotheses explicitly track two separate dormant component mechanisms.

## Files updated

- `research/web-search/2026-09-28_double-dormancy-network-falsification.md`
- provenance registries;
- corpus/bibliography;
- this RETURN.

## Recommended next search

If C-DA-1 survives Chief review, freeze the mathematical component-composition class first. Then run a final exact-formula search using its shape assumptions.

If C-DA-2 survives, require a theorem statement that contains the component parameters explicitly and demonstrate why Stehlík et al. cannot recover it after collapsing each node to a generic bistable reaction.

## RETURN TO CHIEF

**C-DA-1:** survives, narrowed to an exact composition theorem.

**C-DA-2:** strongly threatened; generic network persistence/extinction is already covered.

**Main novelty threat for C-DA-1:** Lan 2025.

**Main novelty threat for C-DA-2:** Stehlík–Švígler–Volek 2023.

**Most important unresolved issue:** whether a broad but controlled component-function class yields a genuinely reusable exact threshold-composition theorem rather than a restatement of scalar root/fold conditions.