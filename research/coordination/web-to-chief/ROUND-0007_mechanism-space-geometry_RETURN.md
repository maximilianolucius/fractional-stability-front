# ROUND-0007 — WEB SEARCH RETURN

**From:** WEB SEARCHER  
**To:** CHIEF RESEARCHER  
**Date:** 2026-09-28  
**Answers:** `research/coordination/chief-to-web/ROUND-0007_mechanism-space-geometry_REQUEST.md`  
**Status:** COMPLETE

## Executive finding

No direct theorem was found that makes the strengthened P2–P4 ecological package redundant.

But the round substantially narrows what may be claimed as mathematical novelty.

- **P2 convexity / half-space geometry:** standard convex and semi-infinite programming.
- **P3 radial phase window:** standard consequence of that monotone geometry; the ecological two-boundary interpretation is distinct.
- **P4 weighted low-density coalition:** standard weighted threshold-game mathematics.
- **P4 antichain/Sperner:** standard.
- **P4 chain-contiguity:** standard order-convex poset structure.
- **P4 persistence-filtered coalition:** no resolving prior theorem found.
- **P5 boundary normal:** exactly Danskin/envelope theory.

Thus P2–P4 survive as an **integrated ecological phase theorem**, not as a bundle of independently novel mathematical facts.

## Verdict — THM-P2 convex phase geometry

**Decision category:** **MATHEMATICALLY STANDARD BUT ECOLOGICAL SYNTHESIS DISTINCT.**

### Direct mathematical prior art

López & Still (2007), *Semi-infinite programming*, DOI **10.1016/j.ejor.2006.08.045**, treats feasible sets described by infinitely many linear inequalities. Such a feasible region is an intersection of closed halfspaces and is closed and convex.

For

[
M(lambda)=max_x[b(x)-lambdacdot g(x)],
]

convexity is the standard fact that a supremum of affine functions is convex.

Therefore P2A–P2C should not be promoted as new convex analysis.

### Population-mathematics analogue

Delmas–Dronnier–Zitt, *The effective reproduction number: Convexity, concavity and invariance*, JEMS 27 (2025), DOI **10.4171/JEMS/1431**, studies convex/concave geometry of a population persistence quantity under a vector of vaccination/intervention intensities.

This is not an Allee model, but it blocks any broad statement that convex intervention-strength persistence geometry is new in mathematical population biology.

### Residual ecological statement

No source found gives simultaneously:

[
mathcal L
=
{lambda:F(0;lambda)<0},
]

[
mathcal E
=
{lambda:max_x F(x;lambda)le0},
]

and

[
mathcal A
=
mathcal Lsetminusmathcal E
]

as an exact strong-Allee phase classification separating **low-density failure** from **global loss of persistence**.

That combined interpretation is distinct.

## Verdict — THM-P3 radial threshold window

**Decision category:** **MATHEMATICALLY STANDARD BUT ECOLOGICAL SYNTHESIS DISTINCT.**

Once P2 is established, intersecting the two boundaries with a ray (lambda=tu) gives scalar critical values directly:

[
t_0=b(0)/(ucdot g(0)),
]

and the extinction value from the supremum of the ratio (b(x)/(ucdot g(x))), with zero-denominator conventions.

The interval structure follows from monotonicity.

Delmas–Dronnier–Zitt also have an “optimal rays” vaccination line (arXiv:2209.07381), but it concerns scaling optimal intervention strategies and does not provide this low-density-failure / persistence-extinction pair of boundaries.

No direct two-boundary multiple-Allee radial theorem was found.

**Recommendation:** retain P3 as a strong ecological corollary, not as deep standalone mathematics.

## Verdict — THM-P4 minimal threshold-generating coalitions

**Decision category:** **CLOSE PRIOR ART — NARROW.**

### Low-density part is directly standard

With

[
w_i=arlambda_i g_i(0),
]

the inequality

[
sum_{iin S} w_i>b(0)
]

defines a weighted threshold game. Requiring deletion of any member to lose is exactly the definition of a **minimal winning coalition**.

Alturki & Rushdi (2016), DOI **10.7603/s40632-016-0007-1**, explicitly develops weighted voting systems as threshold Boolean functions and identifies minimal winning coalitions with prime implicants.

Thus:
- the weighted-quota reformulation;
- immediate-deletion minimality;
- pivotal mechanisms;
- antichain/Sperner structure

are direct prior mathematics.

### Reliability dual is also standard

Classical reliability theory defines **minimal cut sets** as minimal combinations of component failures that cause system failure. This is structurally the same monotone-subset idea.

### What survives: persistence filtering

The ecological threshold-generating condition is not merely a quota crossing:

[
F_S(0)<0<M_S,
qquad
M_S=max_xF_S(x).
]

The first condition is an upset in the subset lattice. The second is a downset.

Their intersection is therefore an **order-convex** subset of the Boolean lattice.

Generic order theory already implies:
- contiguous blocks on inclusion chains;
- minimal elements form an antichain.

So those corollaries are also standard after reformulation.

However, no searched weighted-game, reliability or Allee source classifies the weighted minimal coalitions that survive the independent continuous-state persistence filter (M_S>0).

That is the nontrivial residual P4 object.

### What P4 now needs

A Q1-level mathematical claim should derive something about that filter, for example:
- necessary/sufficient profile-level conditions for a weighted minimal coalition to remain persistent;
- realizability of persistence-filtered antichains;
- sharper bounds than generic Sperner bounds;
- coupling between faces of the continuous (lambda)-boundary and changes in discrete minimal coalitions;
- enumeration/complexity using the full (g_i(x)) profiles rather than only (g_i(0)).

## Verdict — THM-P5 boundary sensitivity

**Decision category:** **COVERED AFTER REFORMULATION.**

Danskin's theorem gives, at a unique maximizing density,

[

abla_lambda M(lambda)
=

abla_lambda F(x^*;lambda)
=
-g(x^*).
]

John M. Danskin, *The Theory of Max-Min and its Application to Weapons Allocation Problems* (1967), DOI **10.1007/978-3-642-46092-0**.

The normal to the smooth extinction level set (M=0) is consequently standard envelope/value-function sensitivity.

The biological interpretation is useful but should be labeled a corollary.

## Strongest adjacent prior-art threats

### Convex phase geometry
López & Still 2007; generic convex analysis; Delmas–Dronnier–Zitt 2025.

### Coalition structure
Weighted voting/simple games; Alturki–Rushdi 2016; classical reliability/minimal-cut-set theory.

### Boundary sensitivity
Danskin 1967.

### Existing multiple-Allee ecology
Berec et al. remains the ecological motivation and explicitly states the unresolved interaction problem, but does not supply this mechanism-space geometry.

## Did a killer source appear?

**NO.**

No source found gives, at comparable ecological generality:

> a convex mechanism-strength phase classification together with minimal mechanism combinations that cross a low-density failure boundary while still satisfying a global positive-persistence condition.

The closest prior art comes from **different literatures whose individual tools are standard**.

## Do P2–P4 together remain defensible as the central contribution?

**YES, WITH A MAJOR POSITIONING CONDITION.**

They remain defensible as an applied-mathematical **synthesis theorem for mechanism-resolved multiple Allee effects**, because the exact ecological coupling was not found.

They are **not** defensible if presented as:
- a new convexity theorem;
- a new weighted-coalition theorem;
- a new Sperner/antichain theorem;
- a new envelope theorem.

The paper needs at least one strengthened result generated specifically by the persistence filter. Otherwise a critical reviewer could accurately describe the work as standard convex analysis plus standard weighted-game combinatorics applied to a new vocabulary.

## Suggested proof-program adjustment

Keep P2/P3 as the continuous phase backbone and P5 as interpretation.

Concentrate originality work on a strengthened P4:

> characterize the geometry/combinatorics of the **persistence-filtered minimal winning coalitions** induced by the density profiles (g_i(x)).

A particularly strong link would connect:
- continuous faces/normals of (partialmathcal E);
- discrete changes in threshold-generating coalitions;
- component-profile shape assumptions.

## Files updated

- `research/web-search/2026-09-28_mechanism-space-geometry.md`
- corpus/bibliography;
- web-search provenance;
- this RETURN.

## RETURN TO CHIEF

**THM-P2:** MATHEMATICALLY STANDARD BUT ECOLOGICAL SYNTHESIS DISTINCT.  
**THM-P3:** MATHEMATICALLY STANDARD BUT ECOLOGICAL SYNTHESIS DISTINCT.  
**THM-P4:** CLOSE PRIOR ART — NARROW; persistence-filtered part survives.  
**THM-P5:** COVERED AFTER REFORMULATION.

**Killer source:** none found.

**Central-program verdict:** survives theorem-specific falsification, but the mathematical novelty burden now lies almost entirely in proving new consequences of the persistence filter and its coupling to continuous mechanism-space geometry.
