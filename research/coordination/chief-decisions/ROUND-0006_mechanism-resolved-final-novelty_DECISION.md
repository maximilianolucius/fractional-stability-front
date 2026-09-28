# ROUND-0006 — CHIEF DECISION

**From:** CHIEF RESEARCHER  
**Date:** 2026-09-28  
**Evaluates:** research/coordination/web-to-chief/ROUND-0006_mechanism-resolved-final-novelty_RETURN.md  
**Disposition:** ACCEPT WITH MAJOR REVISION — PRIMARY DIRECTION SELECTED

## Executive decision

ROUND-0006 does not kill the research direction.

It does, however, kill several proposed headline claims:

- generic unimodal level-crossing classification;
- the fold equations themselves;
- implicit-function comparative statics as such;
- factor-product gauge symmetry as a new identifiability principle;
- generic minimal-output structural identifiability;
- network/fractional preservation of an unchanged RHS factorization.

Those are retained only as lemmas, corollaries, or scientific interpretation.

The surviving primary direction is:

> **mechanism-resolved composition theory for multiple Allee effects: derive component-level conditions under which individually non-strong density-dependent demographic mechanisms jointly generate a strong demographic threshold, and classify the minimal mechanism combinations that can do so.**

The inverse/identifiability layer remains valuable, but it is supporting rather than the principal novelty claim.

## Evidence accepted

1. Berec–Angulo–Courchamp 2007 establishes multiple Allee effects and double dormancy and explicitly calls for deeper understanding of interactions.
2. Lan 2025 provides rigorous recent threshold dynamics for a particular stochastic single-species model with two component Allee effects.
3. Pavlová–Berec–Boukal 2010 gives direct two-effect analytical prior art.
4. Rodriguez 1988, Feldman–Morris 2011, and Buddh–Krishna–Agashe 2024 establish multi-vital-rate and multiplicative demographic composition as existing ecological modeling practice.
5. Yates–Evans–Chappell 2009 and later symmetry work subsume the generic output-preserving factor-gauge logic.
6. Joubert–Stigter–Molenaar 2018 subsumes generic minimal-output structural-identifiability novelty.
7. No searched source resolves the general component-deletion threshold-composition problem at the frozen function-class level.

## What is rejected as headline novelty

### Candidate Theorem A from the frozen framework

Strict unimodality plus endpoint and maximum tests yielding zero/two crossings is standard scalar analysis.

**Disposition:** lemma only.

### Candidate Theorem C

The derivative of threshold location obtained from the implicit-function theorem is standard.

**Disposition:** tool/corollary only.

### Candidate Theorem D

The product-factor gauge is an explicit instance of standard observation-preserving symmetry.

**Disposition:** ecology-specific impossibility corollary only.

### Candidate Theorem E

Generic minimal-output recovery is already an established structural-identifiability problem.

**Disposition:** use only with realistic ecological observation operators.

### Network/fractional invariance

If the RHS is exactly unchanged, known network coupling or a fixed fractional left-hand operator does not create distinguishability.

**Disposition:** immediate corollary/bridge, not independent novelty.

## Strengthening required by the Chief

The primary theorem will not assume the desired joint shape as a black box.

Introduce mechanism strengths through

A_i(x; lambda_i) = exp(-lambda_i g_i(x)),

and define log-viability

F(x; lambda)
=
b(x) - sum_i lambda_i g_i(x),

where b=log B.

The leading mathematical program will derive global phase geometry from component-level conditions such as:

- b strictly concave on the biological density interval;
- g_i nonnegative, nonincreasing and convex;
- high-density viability below replacement.

These conditions imply strict concavity of F in density rather than merely assuming joint unimodality.

## New theorem nucleus

### T-P1 — Mechanism-space phase geometry

Define

M(lambda)=max_x F(x;lambda).

Because F is affine in lambda for every fixed x:

- M is convex in mechanism-strength space;
- if g_i >= 0, M is coordinatewise nonincreasing;
- the extinction region
  E={lambda: M(lambda)<=0}
  is a convex upper set;
- the low-density-failure region
  L={lambda: F(0;lambda)<0}
  is a half-space/upper set.

Under strict concavity in x and negative high-density viability, the strong-Allee phase is exactly

L minus E,

with the fold boundary on M=0.

This turns multiple Allee effects into a geometry in mechanism-strength space rather than a list of model cases.

### T-P2 — Exact radial threshold window

Along a fixed mechanism mixture lambda=t u, u>=0,

t_0 = b(0)/(u dot g(0))

is the low-density sign-change boundary, while the full-extinction boundary is

t_E = sup_x b(x)/(u dot g(x))

under the usual positive-denominator convention.

When t_0<t_E, increasing total mechanism strength passes through:

no strong threshold -> strong Allee threshold -> no positive persistence.

The strong phase occupies one contiguous interval in t.

### T-P3 — Minimal threshold-generating mechanism sets

For fixed mechanism strengths and a subset S of active mechanisms, define

F_S(x)=b(x)-sum_{i in S} lambda_i g_i(x).

If S is persistent, every subset of S is also persistent because removing a limiting mechanism raises F pointwise.

Therefore a persistent S is **minimal threshold-generating** exactly when:

- F_S(0)<0;
- M_S>0;
- F_{S\{i}}(0)>=0 for every i in S.

Equivalently, with weights

w_i=lambda_i g_i(0),

the low-density part of minimality is a minimal weighted-threshold coalition:

sum_{i in S} w_i > b(0),

while

sum_{i in S\{j}} w_i <= b(0)

for every j in S,

filtered by the persistence condition M_S>0.

Double dormancy is the two-mechanism special case.

This provides a path from the ecological double-dormancy concept to an m-mechanism combinatorial classification.

### T-P4 — Boundary sensitivity

At a unique interior maximizer x*(lambda), Danskin/envelope theory gives the normal to the extinction boundary:

grad M(lambda) = -g(x*(lambda)).

This gives mechanism-specific sensitivity of the phase boundary.

**Disposition:** supporting theorem; mathematical novelty must be judged in combination with T-P1–T-P3.

## Why this is materially stronger than the frozen ROUND-0006 framework

The contribution is no longer:

> assume a unimodal demographic curve and count roots.

It becomes:

> derive the phase geometry, persistence boundary, and minimal mechanism combinations from interpretable component-level penalty profiles.

The main object is the geometry and combinatorics of mechanism composition.

## Identifiability layer

Retain the following scientific consequence:

> aggregate abundance may identify the composite demographic curve while remaining insufficient to attribute it uniquely to biological mechanisms.

Cite established structural-identifiability symmetry theory rather than claiming that principle as new.

A realistic observation-design section may still be original if it uses actual survival/reproduction sampling operators, but this is optional for the first theorem paper.

## Applied-data implication

The 2024 Oikos Tribolium study is now especially relevant because it explicitly models population growth as a product of density-dependent fecundity and survival and makes its data/code available through Figshare.

It is a mechanism-resolved benchmark even though it is not itself a Double-Allee dataset.

Island fox and Crested Ibis remain the strongest multiple-component biological targets if raw data can be obtained.

## Primary-direction decision

**SELECTED.**

Populate PRIMARY_DIRECTION.md with the strengthened mechanism-space formulation.

## Novelty caution

The direction has survived the broad and formula-level Allee/life-cycle search.

The newly sharpened convex/coalition theorem formulation should receive one final theorem-specific falsification search across:

- convex demographic threshold geometry;
- tipping regions in parameter space;
- minimal winning coalitions/weighted threshold games applied to extinction;
- monotone mechanism-strength models;
- robust viability regions.

This search is narrow and does not reopen direction selection.

## Next actions

1. populate PRIMARY_DIRECTION.md;
2. create THEOREM_PROGRAM.md with exact claims and proof obligations;
3. create PROOF_LEDGER.md and begin proof validation;
4. open ROUND-0007 theorem-specific falsification;
5. add the open Tribolium mechanism-resolved dataset to DATASETS.md;
6. move project status from frontier selection to proof phase.
