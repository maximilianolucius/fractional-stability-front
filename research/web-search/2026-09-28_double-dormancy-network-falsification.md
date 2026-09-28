# 2026-09-28 — Double Dormancy and Network Falsification

**Round:** ROUND-0004  
**Request:** `research/coordination/chief-to-web/ROUND-0004_double-dormancy-network-falsification_REQUEST.md`

## 1. Core definition rechecked

Berec, Angulo & Courchamp (2007), DOI 10.1016/j.tree.2006.12.002, define **double dormancy** as two component Allee effects that individually do not yield a demographic Allee threshold (or only weak effects) but jointly produce a strong threshold.

Their Box 1 is already more than terminology:
- it writes an explicit single-species population model with reproduction and survival component effects;
- switches components on/off;
- derives local stability of (N=0);
- distinguishes weak/no demographic effect analytically in one regime;
- states that when the origin is stable the model can have zero or two positive equilibria;
- explicitly says no analytical expression was available to separate those latter parameter regions, so numerical exploration was used.

Thus the 2007 source itself identifies a real analytical gap, but only for its particular functional form.

Exact-phrase and citation searches found relatively little later work using the term “double dormancy” itself. Keyword scarcity is not treated as novelty evidence.

## 2. Strongest direct two-component prior art

Guijie Lan (2025), *Threshold dynamics of a stochastic single species model with two component Allee effects*, Chaos, Solitons & Fractals 200(P2):116952, DOI 10.1016/j.chaos.2025.116952.

The paper:
- explicitly models **two component Allee effects**;
- rigorously proves existence and stability of equilibria in the deterministic model;
- introduces a stochastic net reproductive threshold (R_0^s);
- proves almost-sure extinction for (R_0^s<1) and strong stochastic permanence for (R_0^s>1);
- reports that environmental noise can eliminate the deterministic Allee threshold.

This is direct, recent prior art and substantially narrows C-DA-1. From the publisher-accessible abstract, it is not established that Lan proves a general necessary-and-sufficient **composition theorem across a function class** for two individually dormant effects. Full theorem-level inspection is still desirable before claiming that distinction.

## 3. Equivalent emergent-threshold theory outside “double dormancy”

### Stage-structured emergence

de Roos, Persson & Thieme (2003), DOI 10.1098/rspb.2002.2286, prove conditions under which an Allee effect emerges in a top predator from structured prey dynamics. In their model class, overcompensatory maturation in a regulating juvenile stage is required; predator size selection determines whether the emergent Allee effect occurs.

van Kooten, de Roos & Persson (2005), DOI 10.1016/j.jtbi.2005.03.032, analyzes parameter conditions under which stage-specific predation creates an emergent Allee effect and bistability under broad conditions.

These are strong warnings: “emergent threshold from interacting mechanisms” is not itself new. C-DA-1 must specifically exploit **composition of separately measurable component fitness functions**, not merely emergence of bistability.

### Spatial aggregation converts component to demographic effects

Jorge & Martinez-Garcia (2024), DOI 10.1098/rsif.2024.0042, construct a bottom-up spatial framework in which individual-level component Allee effects plus aggregation/spatial structure determine whether a demographic Allee effect occurs. This is a recent structural bridge between component and demographic levels.

Again, it does not directly solve the two-component double-dormancy composition problem, but it destroys any broader claim that mapping component effects to demographic effects is unexplored.

## 4. Network/metapopulation prior art

### General arbitrary-network source–sink theorem

Stehlík, Švígler & Volek (2023), *Source-sink dynamics on networks: Persistence and extinction*, JMAA 528(2):127581, DOI 10.1016/j.jmaa.2023.127581.

This is the strongest theorem found against C-DA-2.

For a connected undirected graph with (C^1) local per-capita growth laws, generalized graph-Laplacian migration, diffusion strength and migration-survival probability, Theorem 1.1 gives threshold conditions separating:
- uniform persistence; and
- local extinction.

The framework explicitly allows combinations of logistic (source-like) and bistable/strong-Allee (sink-like) local reactions, and the persistence/extinction threshold depends on diffusion, migration survival, network structure and the sum/distribution of local per-capita growth rates.

This is an **arbitrary-network theorem**, not a small-graph simulation.

### Direct graph Allee paper

Nagatani & Ichinose (2019), DOI 10.1016/j.physa.2019.01.037, studies diffusively coupled Allee dynamics on heterogeneous/homogeneous graphs. It treats small graphs plus star and complete graphs with (N) nodes and shows strong topology dependence. It is more model-specific and partly numerical than Stehlík et al.

### Metapopulation threshold emergence

Zhou & Wang (2004), DOI 10.1016/j.mbs.2003.06.001, shows how a local Allee effect can induce an Allee-like occupancy threshold at metapopulation scale, with the threshold strongly affected by migration, migration survival and initial occupied-patch population size.

Lanchier (2013) remains important stochastic interacting-patch prior art.

## 5. C-DA-1 classification

**PARTIAL / CLOSE PRIOR ART; SURVIVES ONLY IN A SHARP FUNCTION-CLASS FORM.**

No source found in the searched corpus gives the exact proposed theorem:

> for a broad explicitly separable class (g(x)=G(g_1(x),g_2(x),x)), necessary-and-sufficient shape/parameter conditions characterize when two individually non-strong component effects jointly create a strong demographic threshold, with uniqueness/multiplicity and comparative statics.

But:
- Berec 2007 already develops the defining model and identifies unresolved parameter separation;
- 2025 direct two-component threshold theory exists;
- general emergent-Allee theorems exist under stage/spatial mechanisms.

The candidate is not a keyword-level novelty. Its novelty would have to be **function-class composition exactness**.

### Single strongest prior result against C-DA-1

**Lan (2025), DOI 10.1016/j.chaos.2025.116952**, because it is explicitly a rigorous threshold study of a single-species model with two component Allee effects.

The strongest *conceptual/generalization threat* is Jorge & Martinez-Garcia (2024), because it derives component-to-demographic emergence structurally rather than merely naming an effect.

## 6. C-DA-2 classification

**CLOSE PRIOR ART / SURVIVES ONLY IF THE INTERNAL COMPONENT COMPOSITION REMAINS THE THEOREM VARIABLE.**

A broad theorem of the form “network topology and dispersal determine persistence/extinction for local bistable/Allee reactions” is already covered.

To remain distinct, C-DA-2 must prove something that cannot be obtained after replacing each local double-dormancy mechanism by a generic bistable (f_i). Examples:
- how *component strengths separately* enter the network threshold;
- whether coupling creates double dormancy when no isolated node has a strong threshold;
- exact comparative statics of the network threshold with respect to the component decomposition;
- graph conditions distinguishing mechanism composition from a generic local bistable reaction.

### Single strongest theorem against C-DA-2

**Stehlík, Švígler & Volek (2023), Theorem 1.1, DOI 10.1016/j.jmaa.2023.127581.**

It gives persistence/extinction thresholds on connected arbitrary graphs for mixed local growth types and is therefore much closer to the desired generality than small-graph Allee papers.

## 7. Minimal assumptions for a nontrivial surviving composition theorem

A useful C-DA-1 theorem likely needs:
1. a controlled decomposition of per-capita growth into separately interpretable component terms;
2. sign/monotonicity/curvature assumptions on each component;
3. a high-density negative-feedback condition ensuring boundedness/carrying behavior;
4. a precise definition of “individually dormant” under component deletion;
5. a transversality/nondegeneracy condition at threshold creation;
6. conditions strong enough to bound the number of positive zeros but weak enough to include more than one named model.

Without shape restrictions, arbitrary smooth components can generate arbitrarily many roots, so no useful universal uniqueness theorem is possible.

## Recommended next move

If retained, formulate C-DA-1 before adding networks. Prove a scalar composition result whose hypotheses are directly interpretable as survival/reproduction component effects. Only then ask which parts survive under graph coupling.

For C-DA-2, explicitly compare every proposed network theorem to Stehlík et al. (2023); generic persistence/extinction under bistable local dynamics is not enough.