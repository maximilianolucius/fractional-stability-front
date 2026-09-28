# 2026-09-28 — Double/Multiple Allee Terminology Seed

**Round:** ROUND-0002  
**Request:** `research/coordination/chief-to-web/ROUND-0002_double-allee-terminology-seed_REQUEST.md`

## 1. Question investigated

What does “Double/Multiple Allee effect” actually mean across ecology and mathematical biology, what theorem-level prior art exists, and which seemingly novel fractional/spatial/network combinations are already covered?

## 2. Foundational terminology

### Component versus demographic Allee effects

Stephens–Sutherland–Freckleton (1999), DOI 10.2307/3547011, and the late-1990s foundational literature distinguish an Allee effect at the level of a **component of individual fitness** from its **demographic** consequence for total/per-capita population growth.

Operationally for this project:
- **component Allee effect:** some fitness component improves with density over a low-density range;
- **demographic Allee effect:** the combined demographic response yields positive density dependence in population growth;
- **strong demographic Allee effect:** there is a critical density below which net/per-capita growth is negative;
- **weak demographic Allee effect:** low-density positive density dependence exists but does not create a positive critical extinction threshold.

Courchamp–Clutton-Brock–Grenfell (1999), DOI 10.1016/S0169-5347(99)01683-3, is another foundational source for inverse density dependence/Allee dynamics.

## 3. “Multiple Allee effects” is not “two demographic thresholds”

Berec–Angulo–Courchamp (2007), DOI 10.1016/j.tree.2006.12.002, uses **multiple Allee effects** for the simultaneous action of two or more component Allee mechanisms.

This can strengthen demographic consequences, but the terminology does not itself imply:
- two unstable positive equilibria;
- two critical demographic thresholds;
- two folds;
- two hysteresis loops.

The review reports real examples/putative mechanisms involving combinations such as pollination, inbreeding, mate limitation, predator dilution, cooperative defense, thermal protection, etc.

**Corpus rule:** represent separately:
1. number of component mechanisms;
2. number of positive equilibria/unstable thresholds;
3. origin of each threshold;
4. demographic consequence.

## 4. “Double Allee effect” in mathematical predator–prey models

A recurrent prey-growth law has the schematic form

[
dot x =
rac{r x}{x+n}
left(1-rac{x}{K}ight)(x-m)
-	ext{predation}.
]

Here:
- ((x-m)) supplies a strong threshold when (m>0);
- (x/(x+n)) suppresses intrinsic growth at low density.

Calling this “double Allee” does **not** make the scalar prey growth a generic two-positive-threshold system.

González-Olivares et al. (2011), DOI 10.1016/j.camwa.2011.08.061, already studies consequences of a Double Allee effect for the number of predator–prey limit cycles.

Pal–Saha (2015), DOI 10.1016/j.chaos.2014.12.007, gives substantial qualitative/bifurcation analysis, including strong/weak cases, bistability/separatrices, saddle-node/Hopf and higher-codimension behavior.

**Terminology conclusion:** “Double Allee” is a model-family label, not a canonical equilibrium geometry.

## 5. Fractional Double Allee prior art

### Caputo continuous-time

Rahmi et al. (2021), DOI 10.3390/fractalfract5030084, explicitly combines:
- a modified Leslie–Gower predator–prey model;
- Beddington–DeAngelis functional response;
- Double Allee effect;
- Caputo fractional memory.

The paper analyzes existence/uniqueness, nonnegativity/boundedness, local equilibrium stability, order-related Hopf conditions, and Lyapunov-type sufficient global stability.

Therefore:

> “Add a Caputo derivative to a Double-Allee predator–prey model”

is already direct prior art and is not a viable novelty claim by itself.

### 2025–2026 extensions

Further direct prior art includes:
- Ramesh et al. (2025), DOI 10.1371/journal.pone.0305179: fractional Double-Allee predator–prey dynamics with local/global analysis and Hopf behavior.
- R. Mondal et al. (2025), DOI 10.1016/j.cjph.2025.09.020: fractional-order Double-Allee + group defense; includes incommensurate-order dynamics, multistability and basin analysis; the publisher states that no experimental data were used.
- Alraddadi–Ahmed–Seol (2026), DOI 10.3390/fractalfract10050304: discrete fractional predator–prey Double-Allee dynamics with local stability and Neimark–Sacker/period-doubling bifurcation analysis.

**Novelty consequence:** fractional order, even incommensurate or discrete, is not enough.

## 6. Spatial and network-adjacent prior art

### Direct Double-Allee spatial model

Li–Li (2024), DOI 10.3934/math.20241309, studies a diffusive predator–prey system with Double Allee effect, including analytical coexistence/pattern results.

Thus “Double Allee + diffusion” is not a new combination.

### Strong Allee topology theory outside Double terminology

Lanchier (2013), DOI 10.1239/aap/1386857863, studies interacting patches subject to a strong Allee effect. The geometry/topology of the patch system affects persistence versus extinction, and the work provides analytical threshold results for specific graph structures.

This is a major adjacent-literature threat to any claim that topology-dependent Allee thresholds are fundamentally new merely because the proposed system is called “Double Allee.”

## 7. Outside-vocabulary equivalence risk

Two-threshold/multistable population mathematics can appear under:
- bistability/multistability;
- saddle-node/fold bifurcations;
- hysteresis/resilience;
- depensation;
- rescue thresholds;
- ignition/bistable reaction–diffusion equations;
- patch/metapopulation persistence;
- cooperative population dynamics.

No future novelty claim should be searched only with “Allee”.

## 8. Empirical evidence and datasets

### Island fox: direct empirical Double-Allee evidence

Angulo, Roemer, Berec, Gascoigne & Courchamp (2007), *Double Allee Effects and Extinction in the Island Fox*, Conservation Biology 21(4):1082–1091, DOI 10.1111/j.1523-1739.2007.00721.x, is a particularly important empirical source.

The study analyzed demographic data collected from **1988 to 2000** across California Channel Island fox populations. It tested density dependence in survival, reproduction, interaction with Golden Eagle presence, and per-capita population trends. The authors reported:
- simultaneous component Allee effects in survival (adults/pups) and the proportion of breeding adult females;
- an adult-survival effect driven by Golden Eagle predation;
- a resulting demographic Allee effect;
- suboptimal population growth below roughly **7 foxes/km²**.

This is a serious real-data lead because it directly connects multiple low-density mechanisms to demographic observations. It is **not**, however, evidence for two positive demographic thresholds, nor does it identify a fractional memory order.

### Broader empirical leads

Berec et al. (2007) synthesizes real systems where several component Allee mechanisms may act simultaneously. Examples discussed in that literature include plant pollination/inbreeding and animal mate-limitation/cooperative-defense mechanisms.

Additional search leads include:
- reintroduced Crested Ibis populations with simultaneous component Allee effects in survival/reproduction;
- gray-wolf demographic/component Allee analyses;
- gypsy-moth mate-finding and critical-patch-size work.

However, in this seed search:

> **No real-data-calibrated fractional Double-Allee study was identified that jointly establishes a multi-threshold demographic structure and identifies fractional memory from observations.**

This is not an absence proof. Dataset suitability and identifiability require a dedicated round.

## 9. Strongest novelty threats

1. “Multiple Allee effects” already has an established mechanism-level meaning.
2. “Double Allee” is not a universal two-threshold object.
3. Caputo Double-Allee models exist since at least 2021.
4. Incommensurate fractional Double-Allee models exist by 2025.
5. Discrete fractional Double-Allee models exist by 2026.
6. Reaction–diffusion Double-Allee models exist.
7. Topology-dependent strong-Allee metapopulation theory exists outside the Double-Allee phrase.

## 10. Seed-level frontier still worth testing

No general result resolving the following was identified in the searched seed corpus as of 2026-09-28:

- a graph-theoretic exact threshold theorem for a precisely defined **genuinely multi-threshold** local Allee mechanism over arbitrary networks;
- a structural identifiability theorem separating multiple threshold parameters from fractional memory using realistic ecological observations;
- an exact structured-matrix criterion connecting local multi-threshold ecological Jacobians to multiplicative sector D-stability across a meaningful uncertainty class.

These are only search hypotheses, not accepted open problems.

## 11. Search limitation statement

The terminology literature is broad and application-specific. This round establishes a reliable seed and kills several naive directions but does not close all spatial, stochastic, metapopulation, inverse-problem, or tipping-literature searches.

## RETURN TO CHIEF

### Strongest evidence
“Multiple” and “Double” do not define one mathematical object; fractional and spatial Double-Allee models already exist.

### Closest prior art
Pal–Saha 2015 for analytical Double-Allee bifurcation structure; Rahmi et al. 2021 for Caputo memory; Lanchier 2013 for topology-dependent Allee thresholds.

### Evidence against novelty
Simple fractionalization, incommensurate fractionalization, discrete fractionalization, or adding diffusion are already covered.

### Remaining uncertainty
Whether a precisely defined graph/multithreshold structural theorem or data-identifiability theorem remains genuinely open.

### Recommended next search
Split follow-up into two independent rounds:
1. arbitrary-network/metapopulation multi-threshold theory under non-Allee vocabulary;
2. real ecological datasets + structural/practical identifiability of threshold geometry and memory.