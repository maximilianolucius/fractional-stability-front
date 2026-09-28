# Double Allee — Primary Research Direction

**Status:** SELECTED by CHIEF RESEARCHER on 2026-09-28 after ROUND-0006.  
**Working title:** **Mechanism-Space Geometry of Multiple Allee Effects: Threshold-Generating Coalitions, Phase Boundaries, and Mechanism Attribution**

## Problem statement

Multiple Allee effects are ecologically established, but the mathematical literature is dominated by model-specific combinations of two mechanisms, planar predator–prey systems, stochastic special cases, or generic bistable/network dynamics.

The selected problem is to develop a **mechanism-resolved composition theory**.

Let density be (xin[0,K]). Write demographic viability as

[
V(x;lambda)
=
B(x)prod_{i=1}^{m} A_i(x;lambda_i),
]

where:

- (B(x)>0) is baseline viability including high-density negative feedback;
- each (A_i) is a separately interpretable density-dependent component mechanism;
- (lambda_ige0) is its strength.

Use the exponential-penalty representation

[
A_i(x;lambda_i)
=
exp[-lambda_i g_i(x)]
]

and define

[
F(x;lambda)
=
log V(x;lambda)
=
b(x)-sum_{i=1}^{m}lambda_i g_i(x),
qquad
b=log B.
]

A demographic threshold is a positive crossing of (F=0) from negative to positive.

The central question is:

> How do separately non-strong component mechanisms combine to generate a strong demographic threshold, and what is the global geometry of the corresponding mechanism-strength region?

## Mathematical significance

The main object is not one ecological ODE but a family indexed by mechanism strength.

The target is to derive:

1. exact phase regions in (lambda)-space;
2. convexity/monotonicity of extinction boundaries;
3. explicit threshold windows along rays in mechanism space;
4. a classification of minimal threshold-generating mechanism subsets;
5. sensitivity of the phase boundary to individual mechanisms;
6. robustness extensions under uncertain mechanism profiles.

This converts “multiple Allee effects interact” into a reusable geometric and combinatorial theory.

## Applied significance

The framework distinguishes:

- detecting a demographic Allee effect;
- identifying which component mechanisms generate it;
- determining whether several individually weak effects combine into a strong threshold;
- identifying the smallest mechanism combinations that can trigger collapse.

This is directly relevant to systems where survival, reproduction, mate finding, predation dilution, fertilization, or other fitness components are measured separately.

## Strongest neighboring results

The primary threats already audited are:

- Berec, Angulo & Courchamp (2007): multiple Allee effects and double dormancy;
- Pavlová, Berec & Boukal (2010): interacting reproduction/predation Allee effects;
- Lan (2025): rigorous threshold dynamics with two component Allee effects;
- Rodriguez (1988): density regulation in survival and fecundity across life stages;
- Feldman & Morris (2011): countervailing survival/fecundity density dependence;
- Buddh, Krishna & Agashe (2024): multiplicative survival × fecundity density dependence;
- generic scalar fold/unimodality theory.

No searched result provides the selected general mechanism-space theorem program at comparable scope.

## Exact gap

The gap is **not**:

> two Allee mechanisms have never been modeled together.

The gap is:

> no resolving result was identified that starts from separately interpretable component-level density responses and derives a global, reusable classification of the strong-threshold region, extinction region, and minimal threshold-generating mechanism combinations for arbitrary (m), while retaining explicit component-deletion counterfactuals.

This statement remains search-qualified as of 2026-09-28.

## Novelty evidence

ROUND-0001 through ROUND-0006 progressively eliminated:

- generic fractionalization;
- incommensurate/discrete fractional variants;
- diffusion-only extensions;
- broad network-threshold claims;
- broad fractional D-stability;
- generic structural-identifiability symmetry claims;
- generic minimal-output claims;
- unimodal root counting and IFT comparative statics as headline novelty.

The surviving nucleus is the **forward mechanism-composition geometry**.

A narrow ROUND-0007 is required only to falsify the strengthened convex/coalition formulation, not to reopen direction selection.

## Proposed theorem program

### Theorem 1 — Component-level concavity implies one-peak demographic viability

Assume:

[
b''(x)<0,
qquad
g_i(x)ge0,
qquad
g_i'(x)le0,
qquad
g_i''(x)ge0.
]

Then

[
F''(x;lambda)
=
b''(x)-sum_ilambda_i g_i''(x)<0
]

for every (lambdage0).

Hence (F(cdot;lambda)) is strictly concave and possesses at most one interior maximum.

This theorem is structural scaffolding rather than the main novelty.

### Theorem 2 — Mechanism-space phase geometry

Define

[
M(lambda)=max_{xin[0,K]}F(x;lambda).
]

Then:

- (M) is convex in (lambda);
- (M) is coordinatewise nonincreasing;
- the extinction region
  [
  mathcal E={lambda:M(lambda)le0}
  ]
  is a convex upper set;
- the low-density-failure region
  [
  mathcal L={lambda:F(0;lambda)<0}
  ]
  is an upper half-space;
- under the shape conditions above and (b(K)<0), the strong-Allee region is exactly
  [
  mathcal A=mathcal Lsetminusmathcal E.
  ]

This is the first central theorem target.

### Theorem 3 — Exact radial threshold window

For a fixed mixture direction (uge0), let (lambda=tu).

Define

[
t_0=rac{b(0)}{ucdot g(0)}
]

when the denominator is positive.

The extinction boundary satisfies

[
t_E
=
sup_{x:,ucdot g(x)>0}
rac{b(x)}{ucdot g(x)},
]

with the appropriate convention if (ucdot g(x)=0).

If

[
t_0<t_E,
]

then increasing total mechanism strength passes through a unique ordered sequence:

[
	ext{no strong threshold}
longrightarrow
	ext{strong Allee phase}
longrightarrow
	ext{extinction/no positive persistence}.
]

The strong phase is one contiguous interval in (t).

### Theorem 4 — Minimal threshold-generating coalitions

Fix mechanism strengths (arlambda_i) and activate a subset (Ssubseteq[m]).

Let

[
F_S(x)
=
b(x)
-
sum_{iin S}arlambda_i g_i(x)
]

and

[
M_S=max_xF_S(x).
]

If (S) is persistent, then every subset (Tsubset S) is also persistent because deleting limiting mechanisms raises (F) pointwise.

Therefore (S) is a **minimal threshold-generating set** iff:

[
F_S(0)<0,
qquad
M_S>0,
]

and

[
F_{Ssetminus{i}}(0)ge0
quad
orall iin S.
]

With

[
w_i=arlambda_i g_i(0),
]

the low-density condition becomes the minimal weighted-threshold coalition rule

[
sum_{iin S}w_i>b(0),
]

while

[
sum_{iin Ssetminus{j}}w_ile b(0)
quad
orall jin S.
]

Double dormancy is the (m=2) special case.

The theorem program will investigate the resulting antichain/Boolean-lattice structure and the effect of the persistence filter (M_S>0).

### Theorem 5 — Boundary sensitivity

At a unique interior maximizer (x^ast(lambda)),

[

abla_lambda M(lambda)
=
-g(x^ast(lambda))
]

by envelope/Danskin theory.

This gives mechanism-specific normals and sensitivities of the extinction boundary.

This is a supporting theorem unless stronger order or curvature consequences are derived.

### Theorem 6 — Robust mechanism uncertainty

For uncertain mechanism profiles or strength sets, derive inner/outer robust phase regions and sharp worst-case persistence/extinction conditions.

This is expected to provide additional mathematical depth after Theorems 2–4 are secured.

## Candidate dataset and identifiability

### Open mechanism-resolved benchmark

Buddh, Krishna & Agashe (2024), Oikos, explicitly model population growth as the product of density-dependent fecundity and survival and provide data/code through Figshare.

This is immediately usable to demonstrate the mechanism-space formalism, even though the system is not itself a canonical Double-Allee example.

### Open threshold/component benchmarks

- Atlantic herring;
- Northwest Atlantic cod;
- freshwater mussel fertilization.

### High-value multiple-component biological targets

- island fox;
- Crested Ibis.

Raw historical data access remains unresolved for the latter two.

### Identifiability position

The project will not claim that output-preserving factor symmetry is a new general identifiability principle.

Instead, established structural-identifiability theory will be used to state the practical warning:

> demographic threshold detection does not imply unique attribution to component mechanisms.

If realistic component-specific observation models yield a nontrivial new result, that can become a secondary theorem/application section.

## Computational plan

1. Symbolically verify Theorems 1–4 under the declared hypotheses.
2. Generate counterexamples when any hypothesis is removed.
3. Map (mathcal L), (mathcal E), and (mathcal A) in 2- and 3-mechanism examples.
4. Enumerate minimal threshold-generating subsets for (m)-mechanism systems.
5. Test robustness under parameter/profile uncertainty.
6. Fit or reconstruct mechanism profiles from open mechanism-resolved data.
7. Compare mechanism-space predictions with direct simulation of the demographic dynamics.
8. Add network/fractional examples only as corollaries if they illuminate the theory.

## Failure modes

Abandon or substantially revise the program if:

1. ROUND-0007 finds an existing theorem matching the convex phase-geometry + minimal-coalition formulation;
2. Theorem 2 reduces to a repackaging with no new ecological or mathematical consequence;
3. Theorem 4 yields only trivial weighted-threshold terminology and no useful persistence/combinatorial results;
4. biologically relevant component functions systematically violate the shape class;
5. the robust extension adds no substantive theorem;
6. data cannot estimate even approximate mechanism profiles.

## Dependencies

Immediate dependencies:

- exact proof validation for Theorems 1–4;
- targeted theorem-specific prior-art search ROUND-0007;
- counterexample construction;
- assessment of the Figshare Tribolium dataset;
- later journal-specific novelty and positioning audit.

## Expected manuscript architecture

1. Introduction: multiple Allee mechanisms and the composition problem.
2. Mechanism-resolved viability formalism.
3. Component-level shape assumptions.
4. Mechanism-space phase theorem.
5. Radial threshold windows and fold geometry.
6. Minimal threshold-generating coalitions.
7. Robustness and uncertainty.
8. Mechanism attribution/identifiability consequence.
9. Empirical mechanism-resolved demonstration.
10. Discussion: double dormancy, management, network/fractional extensions.

## Natural journal audience

Depending on final theorem depth and empirical content:

- Journal of Mathematical Biology;
- Bulletin of Mathematical Biology;
- Mathematical Biosciences;
- Nonlinear Analysis: Real World Applications;
- theoretical/applied ecology venues with strong mathematical content.

Quartile/status must be checked at submission time.

## Current Chief assessment

This is now the primary research direction.

The research claim is intentionally narrower than the original project ambition, but mathematically stronger:

> not “fractional Double Allee,” not “Double Allee on a network,” and not another special predator–prey model, but a general phase-and-coalition theory for how multiple demographic mechanisms jointly create extinction thresholds.
