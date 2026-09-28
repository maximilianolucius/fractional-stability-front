# Double Allee — Terminology

**Status:** source-backed seed from ROUND-0002, 2026-09-28.

This file separates ecological mechanism terminology from mathematical equilibrium/threshold geometry. The term **Double Allee effect is not treated as a unique mathematical object**.

## 1. Allee effect

At population level, an Allee effect refers to positive density dependence over a low-density range: some measure of individual fitness or population growth improves as density increases from low values.

Foundational terminology sources:
- Stephens, Sutherland & Freckleton (1999), DOI 10.2307/3547011.
- Courchamp, Clutton-Brock & Grenfell (1999), DOI 10.1016/S0169-5347(99)01683-3.

## 2. Component Allee effect

A **component Allee effect** is positive density dependence in a component of individual fitness, such as:
- mate finding;
- pollination;
- cooperative defense;
- predator dilution;
- cooperative feeding;
- thermal/social benefits.

A component effect does not automatically imply negative total population growth below a threshold.

## 3. Demographic Allee effect

A **demographic Allee effect** concerns the net demographic response, typically per-capita population growth.

The project must not infer demographic threshold structure solely from the presence of one or more component mechanisms.

## 4. Strong versus weak Allee effect

### Strong Allee effect

There is a positive critical density/abundance below which net population growth is negative and extinction is locally favored.

A common scalar normal form contains a factor like

[
x(x-A)left(1-rac{x}{K}ight),
qquad 0<A<K.
]

The positive unstable equilibrium (A) is an Allee threshold.

### Weak Allee effect

Per-capita growth increases with density over a low-density range, but there is no positive critical density below which deterministic net growth becomes negative.

Thus:

[
	ext{weak Allee} 
eq 	ext{strong Allee with a small threshold}.
]

## 5. Multiple Allee effects

Berec, Angulo & Courchamp (2007), DOI 10.1016/j.tree.2006.12.002, uses **multiple Allee effects** for the simultaneous action of multiple **component** Allee mechanisms.

Therefore:

[
oxed{	ext{multiple component Allee effects}

otRightarrow
	ext{multiple demographic thresholds}.}
]

The combined mechanisms can strengthen the demographic effect, but the number of mechanisms and the number of unstable positive equilibria are distinct quantities.

## 6. Double Allee effect

The phrase **Double Allee effect** is not standardized across the mathematical literature.

A recurrent predator–prey formulation uses a prey growth term of the form

[
g(x)
=
rac{r x}{x+n}
left(1-rac{x}{K}ight)(x-m).
]

For (m>0):
- ((x-m)) creates a strong-Allee threshold;
- (x/(x+n)) suppresses intrinsic growth at low density.

This form is used in the Double-Allee model family studied analytically by papers such as Pal & Saha (2015), DOI 10.1016/j.chaos.2014.12.007.

However, it does **not** imply two distinct positive demographic thresholds. “Double” here refers to compounded low-density mechanisms/formal factors.

Other papers may use the phrase differently. Every source must therefore be classified from its equations, not its title.

## 7. Two-threshold / multiple-threshold dynamics

For this project, **two-threshold dynamics** is a mathematical descriptor, not a synonym for Double Allee.

A genuine two-threshold local population model should explicitly identify:
- the number of biologically admissible equilibria;
- which equilibria are unstable thresholds;
- their ordering;
- the sign of population growth between intervals;
- whether the thresholds are created by distinct folds/saddle-nodes or another mechanism.

For example, a candidate with two positive unstable thresholds is structurally different from the common single-threshold Double-Allee growth law above.

## 8. Depensation

**Depensation** is historically common in fisheries/population-dynamics literature for reduced productivity at low abundance and can overlap conceptually with strong Allee dynamics.

It must not be treated as exact mathematical equivalence without inspecting:
- the growth law;
- the sign of per-capita growth;
- the number of thresholds;
- whether the source uses deterministic or stochastic definitions.

## 9. Bistability, multistability, hysteresis

These are dynamical consequences/structures, not synonyms for Allee mechanisms.

- **Bistability:** two attracting invariant sets/equilibria coexist.
- **Multistability:** more than two attracting states coexist.
- **Hysteresis:** state transition depends on parameter/history path, often through folds.
- **Saddle-node/fold:** a local bifurcation that can create/destroy equilibria.

A strong Allee threshold often produces bistability between extinction and persistence, but bistability can arise without an Allee mechanism.

## 10. Spatial/network-induced thresholds

Coupling/dispersal can:
- move thresholds;
- create rescue effects;
- alter persistence/extinction;
- produce topology-dependent critical behavior.

Such thresholds must be marked as **coupling-induced** or **network-modified**, distinct from thresholds intrinsic to the local node dynamics.

Lanchier (2013), DOI 10.1239/aap/1386857863, is a key adjacent source showing that patch geometry/dispersal can alter strong-Allee persistence/extinction.

## 11. Fractional memory

A fractional derivative is a memory model and is **not itself an Allee mechanism**.

Direct Double-Allee + Caputo prior art exists:
- Rahmi et al. (2021), DOI 10.3390/fractalfract5030084;
- later 2025–2026 continuous/incommensurate/discrete fractional extensions.

Therefore a future model must explain what ecological memory process is represented and why the fractional order is identifiable or structurally relevant.

## 12. Controlled terminology for the project

Every future Double-Allee record should specify at least:

| Field | Required description |
|---|---|
| component_mechanism_count | how many low-density mechanisms are represented |
| demographic_allee_type | none / weak / strong / other |
| positive_unstable_threshold_count | explicit integer where determinable |
| positive_equilibrium_count | explicit integer where determinable |
| threshold_origin | intrinsic local / predation-mediated / harvesting / coupling / spatial / stochastic / other |
| bifurcation_origin | saddle-node / transcritical / other / unknown |
| bistability_multistability | exact attractor structure |
| hysteresis | proved / numerical / absent / unknown |
| fractional_memory | operator/order and biological interpretation |
| network_effect | topology modifies/creates threshold or merely couples nodes |

## 13. Core warning

Do not write:

> “Double Allee means a population has two Allee thresholds.”

unless the source/model equations actually establish two thresholds.

Do not write:

> “Multiple Allee effects means multiple demographic thresholds.”

The foundational ecological usage does not support that equivalence.

## Sources

- Stephens, P. A.; Sutherland, W. J.; Freckleton, R. P. (1999). *What Is the Allee Effect?* DOI 10.2307/3547011.
- Courchamp, F.; Clutton-Brock, T.; Grenfell, B. (1999). *Inverse density dependence and the Allee effect.* DOI 10.1016/S0169-5347(99)01683-3.
- Berec, L.; Angulo, E.; Courchamp, F. (2007). *Multiple Allee effects and population management.* DOI 10.1016/j.tree.2006.12.002.
- Pal, P. J.; Saha, T. (2015). *Qualitative analysis of a predator-prey system with double Allee effect in prey.* DOI 10.1016/j.chaos.2014.12.007.
- Lanchier, N. (2013). *The Role of Dispersal in Interacting Patches Subject to an Allee Effect.* DOI 10.1239/aap/1386857863.
