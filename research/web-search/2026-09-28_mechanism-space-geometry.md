# 2026-09-28 — Mechanism-Space Geometry Falsification

**Round:** ROUND-0007  
**Request:** `research/coordination/chief-to-web/ROUND-0007_mechanism-space-geometry_REQUEST.md`  
**Purpose:** theorem-specific falsification of THM-P2/P3/P4/P5.

## Executive result

No single prior source was identified that already gives the selected ecological theorem package:

[
F(x;lambda)=b(x)-lambdacdot g(x),
]

with both

1. a continuous mechanism-strength phase geometry separating low-density failure, strong-Allee persistence and complete extinction, and
2. a discrete classification of minimal mechanism subsets that cross the low-density failure boundary **while retaining global persistence**.

However, nearly every mathematical ingredient is standard in an adjacent discipline.

The defensible content is therefore the **coupling** of those ingredients in a mechanism-resolved ecological phase theorem, not the individual convexity, coalition, antichain or envelope claims.

---

# 1. THM-P2 — convex mechanism-space extinction geometry

## Verdict

**MATHEMATICALLY STANDARD BUT ECOLOGICAL SYNTHESIS DISTINCT.**

## Generic convex-analysis prior art

For fixed (x),

[
F(x;lambda)=b(x)-lambdacdot g(x)
]

is affine in (lambda). Therefore

[
M(lambda)=sup_x F(x;lambda)
]

is a pointwise supremum of affine functions and hence convex. This is a standard convex-analysis construction.

Likewise,

[
mathcal E
=
{lambda:M(lambda)le0}
=
igcap_x
{lambda:lambdacdot g(x)ge b(x)}
]

is a semi-infinite system of linear inequalities. López & Still (2007), *Semi-infinite programming*, DOI **10.1016/j.ejor.2006.08.045**, explicitly treats feasible regions defined by infinitely many linear constraints and notes that such a feasible set is an intersection of closed halfspaces and therefore closed and convex.

Thus the following are not new mathematical results:
- convexity of (M);
- half-space representation of (mathcal E);
- closed convexity of (mathcal E);
- upward monotonicity when (g_ige0).

## Adjacent population-level parameter geometry

Delmas, Dronnier & Zitt, *The effective reproduction number: Convexity, concavity and invariance*, JEMS 27 (2025), DOI **10.4171/JEMS/1431**, studies convexity/concavity of an epidemiological persistence quantity (R_e(eta)) as a vector of intervention/vaccination intensities varies.

Their setting is not the frozen Allee model and their convexity is spectral rather than an elementary supremum-of-affines construction, but it is strong prior art for:
- population persistence thresholds as geometry in a vector of intervention intensities;
- convex strategy regions/frontiers;
- monotone intervention allocation.

Therefore the phrase “convex persistence/extinction geometry in mechanism space” is not independently novel.

## What was not found

No searched ecological source gives the exact decomposition:

- (mathcal L={lambda:F(0;lambda)<0}), a low-density-failure half-space;
- (mathcal E={Mle0}), the complete-extinction convex upper set;
- strong-Allee phase
  [
  mathcal A=mathcal Lsetminusmathcal E
  ]
  under density-concavity assumptions;
- interpretation of the two boundaries as **different biological failures**: local failure at low density versus loss of any positive persistence state.

That ecological separation is the useful synthesis.

---

# 2. THM-P3 — exact radial phase window

## Verdict

**MATHEMATICALLY STANDARD BUT ECOLOGICAL SYNTHESIS DISTINCT.**

Once P2 is known, restricting the convex/upward mechanism geometry to a ray

[
lambda=tu,quad tge0
]

reduces the semi-infinite inequalities to scalar threshold inequalities.

The formulas

[
t_0=rac{b(0)}{ucdot g(0)}
]

and

[
t_E
=
sup_{x:ucdot g(x)>0}
rac{b(x)}{ucdot g(x)}
]

are direct consequences of solving the linear inequalities along the ray.

Hence the ordering

[
	ext{no low-density failure}
	o
	ext{strong-Allee phase}
	o
	ext{complete extinction}
]

is an immediate one-dimensional consequence of the up/down monotonicity provided the boundary/equality conventions are handled correctly.

## Close epidemiological analogue

Delmas–Dronnier–Zitt's vaccination program contains:
- vector intervention strategies;
- convex/concave effective-reproduction-number geometry;
- explicit eradication thresholds;
- work on **optimal rays** (arXiv:2209.07381) asking when scaling an intervention strategy preserves optimality.

This is not the same theorem: it does not provide the two biologically distinct boundaries (t_0) and (t_E), nor an intermediate Allee phase.

## Search result

No prior population paper was identified that derives this exact two-boundary radial window for multiple component Allee mechanisms.

Nevertheless P3 should be presented as a **corollary of the phase geometry**, not as deep standalone mathematics.

---

# 3. THM-P4 — minimal threshold-generating coalitions

## Verdict

**CLOSE PRIOR ART — NARROW.**

This claim has two mathematically different layers.

## 3.1 Low-density weighted threshold layer

For fixed strengths,

[
w_i=arlambda_i g_i(0),
]

the low-density failure condition is

[
sum_{iin S}w_i>b(0).
]

A subset (S) that satisfies this inequality but loses it when any member is deleted is exactly a **minimal winning coalition** in a weighted threshold/majority game, up to strict-versus-nonstrict quota convention.

This is fully established theory.

Alturki & Rushdi (2016), DOI **10.7603/s40632-016-0007-1**, formulates weighted voting systems as threshold Boolean functions and identifies prime implicants with minimal winning coalitions.

Standard consequences already include:
- minimal winning coalitions form an antichain/Sperner family;
- immediate-deletion tests characterize minimality;
- weighted quotas determine winning/losing subsets;
- Boolean derivatives identify pivotal components.

Therefore these are not new:
- weighted form of the low-density minimality inequality;
- antichain property;
- Sperner bound by itself;
- interpretation of individual mechanisms as pivotal members.

## 3.2 Reliability dual

Reliability theory has the same combinatorics in dual language:
- a minimal cut set is a minimal collection of component failures that causes system failure;
- minimal path/cut sets are standard monotone-system objects.

Aven (1985), DOI **10.1016/0143-8174(85)90064-2**, is one representative paper using minimal cut sets for coherent-system reliability. The theory is much older and broader than this source.

Thus “smallest collections of mechanisms that cause failure” is not itself novel.

## 3.3 The persistence filter is the distinctive piece

The Allee problem requires more than crossing the low-density quota.

A set is threshold-generating only when

[
F_S(0)<0
quad	ext{and}quad
M_S>0.
]

Because adding limiting mechanisms lowers (M_S):
- low-density failure is an **up-set** on the Boolean lattice;
- persistence (M_S>0) is a **down-set**;
- their intersection is an **order-convex subset** of the subset lattice.

The general poset fact that an intersection of an upset and downset is order-convex is standard order theory. Therefore chain-contiguity itself is not a novel combinatorial theorem.

But no searched weighted-game/reliability source couples:
1. a weighted minimal winning condition at one distinguished state (x=0), and
2. a continuous-state global viability condition (max_x F_S(x)>0),

to define ecologically admissible minimal failure/threshold coalitions.

This **persistence-filtered coalition** is the main residual P4 object.

## Consequence

P4 is defensible only if the paper derives results that depend nontrivially on the persistence filter, such as:
- characterization of which weighted minimal coalitions survive the (M_S>0) filter;
- realizability/non-realizability of antichains as ecological threshold-generating families;
- sharp bounds stronger than generic Sperner bounds under the shape hypotheses;
- interaction between continuous mechanism strengths and discrete coalition changes;
- algorithmic or structural consequences of the (x)-dependent profiles (g_i(x)), not only the weights (g_i(0)).

Merely importing minimal winning coalition terminology would be insufficient.

---

# 4. Boolean-lattice / inclusion-chain ordering

## Verdict

**COVERED AFTER REFORMULATION.**

If low-density failure is an upset and persistence is a downset, their intersection is order-convex. Along any inclusion chain, an order-convex set occurs as a contiguous block.

This is standard poset structure.

Therefore:
- “threshold-generating states form at most one contiguous block along an inclusion chain” is correct but not a new combinatorial theorem;
- “minimal threshold-generating sets form an antichain” is also generic set-minimality/Sperner structure.

Use these as language/tools, not headline novelty.

---

# 5. THM-P5 — boundary normal / sensitivity

## Verdict

**COVERED AFTER REFORMULATION.**

Danskin's max theorem directly applies to

[
M(lambda)=max_x F(x;lambda).
]

At a unique maximizer (x^*(lambda)),

[

abla_lambda M(lambda)
=

abla_lambda F(x^*;lambda)
=
-g(x^*).
]

This is precisely the standard derivative formula for a max-value function.

Danskin's original monograph is:
John M. Danskin, *The Theory of Max-Min and its Application to Weapons Allocation Problems*, Springer, 1967, DOI **10.1007/978-3-642-46092-0**.

Thus neither the gradient identity nor the fact that it gives a normal to the smooth level set (M=0) is mathematically new.

The ecological interpretation—boundary normal as the vector of mechanism penalties evaluated at the critical density—may be useful, but it is an interpretation/corollary.

---

# 6. Shape hypotheses

Searches for log-concave/log-convex demographic products, density-dependent fecundity × survival, and life-history models found extensive vital-rate shape literature but no source using the exact package

[
b''<0,quad
g_ige0,quad
g_i'le0,quad
g_i''ge0
]

to derive the selected multiple-Allee mechanism-space phase theorem.

Buddh–Krishna–Agashe (2024), DOI **10.1111/oik.10813**, remains the most relevant empirical multiplicative decomposition:
- fecundity and survival are separately fit;
- their product predicts population growth;
- component functions are nonlinear.

This supports feasibility but does not preempt P2–P4.

---

# 7. Strongest adjacent “killer” candidates

## 7.1 Semi-infinite programming

López & Still (2007), DOI 10.1016/j.ejor.2006.08.045.

Kills the mathematical novelty of:
- representing (mathcal E) as infinitely many linear constraints;
- closed convexity of (mathcal E).

## 7.2 Weighted threshold games

Alturki & Rushdi (2016), DOI 10.7603/s40632-016-0007-1, together with the established simple/weighted-game literature.

Kills novelty of:
- quota crossing by weighted subsets;
- minimal winning coalitions;
- pivotality;
- antichain structure.

## 7.3 Reliability/minimal cut sets

Classical coherent-system reliability theory.

Kills novelty of:
- minimal combinations causing system failure as an abstract concept.

## 7.4 Danskin

Danskin (1967).

Kills novelty of:
- (
abla M=-g(x^*));
- normal/sensitivity derived from the value function at a unique maximizer.

## 7.5 Epidemiological intervention geometry

Delmas–Dronnier–Zitt, JEMS 2025, DOI 10.4171/JEMS/1431, plus their optimal-vaccination work.

Strongly narrows claims that vector intervention-strength convex geometry is new in population mathematics.

None of these individually or jointly in the searched literature reproduces the **Allee-specific two-boundary phase + persistence-filtered coalition** theorem.

---

# 8. Final assessment of P2–P4 as a central contribution

## Individual theorem novelty

- **P2A–P2C:** standard convex/semi-infinite programming.
- **P2E:** ecological synthesis distinct; no direct resolving prior result found.
- **P3:** standard geometric consequence with a distinct ecological two-boundary interpretation.
- **P4 low-density weighted coalition:** direct prior mathematics.
- **P4 antichain/Sperner:** standard.
- **P4 chain-contiguity:** standard order-convex poset property.
- **P4 persistence-filtered coalition family:** no resolving result found in searched corpus.
- **P5:** standard Danskin/envelope theorem.

## Combined program

**P2–P4 together remain defensible as a central applied-mathematical synthesis, but not yet as a collection of individually novel mathematical theorems.**

To support a strong mathematical paper, the proof program should add at least one result that genuinely uses the continuous (x)-dependent persistence filter and cannot be obtained by placing convex analysis next to weighted voting terminology.

The most promising strengthening is P4:
- characterize the persistence-filtered minimal coalition family;
- derive sharper combinatorial restrictions from (g_i(x)), concavity and (M_S);
- relate discrete coalition transitions to faces/curvature of the continuous extinction boundary.

That would turn the synthesis into new mathematics rather than a clean translation of two standard toolkits.

---

# Search limitation

This round searched Allee/ecological terms plus convex viability, tipping, vaccination/epidemiological intervention geometry, reliability/minimal cut sets, weighted games, monotone Boolean systems, poset convexity, density-dependent life-history models and Danskin/envelope theory.

No result of absence is absolute. The verdict is scoped to the searched corpus as of 2026-09-28.
