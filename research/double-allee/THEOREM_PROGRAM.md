# Theorem Program — Mechanism-Space Multiple Allee Theory

**Status:** ACTIVE PROOF PROGRAM  
**Chief:** 2026-09-28  
**Primary direction:** research/double-allee/PRIMARY_DIRECTION.md

This file turns the selected research direction into explicit mathematical claims.

Nothing is considered proved until the corresponding proof obligation is closed in PROOF_LEDGER.md.

---

# 0. Base setting

Let

[
xin I=[0,K],
qquad
lambda=(lambda_1,ldots,lambda_m)inmathbb R_+^m.
]

Define

[
F(x;lambda)
=
b(x)-sum_{i=1}^m lambda_i g_i(x).
]

The demographic viability is

[
V(x;lambda)=e^{F(x;lambda)}.
]

The scalar demographic dynamics may be written as

[
dot x
=
x,M_0(x),[V(x;lambda)-1],
qquad
M_0(x)>0.
]

Thus the sign of per-capita growth is the sign of (F).

For subset activation (Ssubseteq[m]) with fixed strengths (arlambda_i), define

[
F_S(x)
=
b(x)
-
sum_{iin S}arlambda_i g_i(x).
]

---

# 1. Standing hypothesis package H

Unless a theorem states otherwise:

### H1 — regularity

[
b,g_iin C^2([0,K]).
]

### H2 — baseline crowding shape

[
b''(x)<0
quadorall xin(0,K),
]

and

[
b(K)<0.
]

### H3 — component penalty shape

For each i,

[
g_i(x)ge0,
qquad
g_i'(x)le0,
qquad
g_i''(x)ge0.
]

Interpretation:
- penalty is nonnegative;
- limitation weakens with density;
- penalty relief has diminishing returns.

### H4 — biologically relevant low-density baseline

Usually

[
b(0)>0,
]

so the baseline system without component penalties is not strongly Allee-limited at zero.

---

# 2. THM-P1 — Derived strict concavity

## Claim

Under H1–H3,

[
F_{xx}(x;lambda)
=
b''(x)-sum_ilambda_i g_i''(x)<0
]

for every (lambdage0).

Therefore (F(cdot;lambda)) is strictly concave on I.

## Consequences

- at most one interior maximizer;
- every superlevel set ({x:F(x;lambda)ge c}) is an interval;
- the equation (F=0) has at most two roots;
- if (F(0)<0), (F(K)<0), and (max F>0), exactly two positive roots exist.

## Novelty role

Scaffolding only.

## Proof obligation

Elementary differentiation + strict concavity argument.

---

# 3. THM-P2 — Convex mechanism-space extinction geometry

Define

[
M(lambda)
=
max_{xin I}F(x;lambda).
]

## Claim A — convexity

(M) is convex in (lambda).

Reason to prove formally:

for fixed x, (F(x;lambda)) is affine in (lambda), and the pointwise supremum of affine functions is convex.

## Claim B — coordinatewise monotonicity

If (mugelambda) coordinatewise, then

[
M(mu)le M(lambda).
]

## Claim C — exact extinction region

Define

[
mathcal E
=
{lambda:M(lambda)le0}.
]

Then

[
mathcal E
=
igcap_{xin I}
left{
lambda:
lambdacdot g(x)ge b(x)
ight}.
]

Hence (mathcal E) is closed, convex, and upward closed.

## Claim D — low-density failure region

Define

[
mathcal L
=
{lambda:F(0;lambda)<0}.
]

Then

[
mathcal L
=
left{
lambda:
lambdacdot g(0)>b(0)
ight}.
]

This is an open half-space intersected with the positive orthant and is upward closed.

## Claim E — exact strong-Allee phase

Under H1–H4,

[
mathcal A
=
mathcal Lcap{M>0}
=
mathcal Lsetminusmathcal E.
]

For every (lambdainmathcal A), the scalar viability equation has exactly two positive level crossings of (V=1):
- lower unstable threshold;
- upper stable positive equilibrium.

## Proof obligations

- convexity proof;
- set equality for E;
- phase classification under strict concavity;
- stability orientation of the two roots.

---

# 4. THM-P3 — Exact radial phase window

Fix a direction

[
uinmathbb R_+^m
]

and write

[
lambda=t u,qquad tge0.
]

Assume

[
ucdot g(0)>0.
]

Define

[
t_0
=
rac{b(0)}{ucdot g(0)}.
]

Define

[
t_E
=
sup_{x:,ucdot g(x)>0}
rac{b(x)}{ucdot g(x)},
]

with the convention that if (ucdot g(x)=0) and (b(x)>0) for some x, then (t_E=+infty).

## Claim

Under H1–H4:

- for (t<t_0), low-density growth is nonnegative, so there is no strong Allee threshold;
- for (t_0<t<t_E), a strong Allee threshold exists;
- for (t>t_E), (M(tu)<0), so no positive persistence equilibrium exists;
- at (t=t_E<infty), the system lies on the persistence/extinction boundary.

Thus the strong-Allee phase along every mechanism mixture ray is a single interval.

## Stronger boundary claim

If the maximizing density at (t_E) is unique and interior, then

[
F(x^ast;t_Eu)=0,
qquad
F_x(x^ast;t_Eu)=0,
]

and strict concavity gives

[
F_{xx}(x^ast;t_Eu)<0.
]

## Proof obligations

- derive t_E from the half-space representation of E;
- verify endpoint cases;
- characterize equality cases;
- establish the exact phase ordering.

---

# 5. THM-P4 — Minimal threshold-generating coalitions

Fix positive mechanism strengths (arlambda_i).

For S subset [m], write

[
F_S(x)
=
b(x)
-
sum_{iin S}arlambda_i g_i(x),
]

[
M_S=max_x F_S(x).
]

Call S **threshold-generating** if

[
F_S(0)<0<M_S.
]

Call S **minimal threshold-generating** if S is threshold-generating and no proper subset is threshold-generating.

## Claim A — persistence monotonicity under deletion

If (Tsubseteq S), then

[
F_T(x)ge F_S(x)
quadorall x,
]

hence

[
M_Tge M_S.
]

Therefore any subset of a persistent S is also persistent.

## Claim B — exact minimality test

A persistent S is minimal threshold-generating iff

[
F_S(0)<0
]

and

[
F_{Ssetminus{i}}(0)ge0
quad
orall iin S.
]

It is enough to test immediate deletions.

## Weighted form

Define

[
w_i=arlambda_i g_i(0).
]

Then minimality is equivalent to

[
sum_{iin S}w_i>b(0)
]

and

[
sum_{iin Ssetminus{j}}w_ile b(0)
quad
orall jin S,
]

together with

[
M_S>0.
]

## Corollaries to investigate

1. Minimal threshold-generating sets form an antichain.
2. Along every inclusion chain of mechanism subsets, the threshold-generating states form at most one contiguous block.
3. Double dormancy is exactly the m=2 minimal-coalition case.
4. For equal low-density weights, minimal coalition size has a closed cardinality rule.
5. Sperner-type bounds may control the number of minimal threshold-generating sets, subject to the persistence filter.

## Novelty role

Central.

## Proof obligations

- prove immediate-deletion equivalence;
- prove chain-contiguity;
- determine which antichain bounds remain sharp after the persistence filter;
- construct examples achieving multiple minimal coalitions.

---

# 6. THM-P5 — Mechanism-space boundary normal

Assume the maximizer

[
x^ast(lambda)
=
argmax_x F(x;lambda)
]

is unique.

## Claim

By Danskin's theorem,

[

abla_lambda M(lambda)
=
-g(x^ast(lambda)).
]

At a smooth point of

[
partialmathcal E={M=0},
]

the outward normal is determined by the mechanism-penalty vector evaluated at the critical density.

## Biological reading

The geometry of the extinction boundary directly identifies which mechanisms are active at the density most vulnerable to collapse.

## Novelty role

Supporting geometry.

## Proof obligations

- verify hypotheses of Danskin;
- handle boundary maximizers;
- derive local boundary sensitivity.

---

# 7. THM-P6 — Robust uncertainty extension

Let mechanism profiles satisfy uncertainty envelopes

[
g_i^-(x)le g_i(x)le g_i^+(x).
]

Potential targets:

### Robust persistence

Find conditions guaranteeing

[
M(lambda;g)>0
]

for every admissible profile g.

### Robust extinction

Find conditions guaranteeing

[
M(lambda;g)le0
]

for every admissible profile g.

### Desired exact reduction

Exploit monotonicity in g to identify extremal profiles whenever the uncertainty set is order-interval structured.

## Novelty role

Potential second central theorem if exact.

## Proof obligations

Not started.

---

# 8. Identifiability consequence — not headline novelty

If only

[
P(x)=prod_i A_i(x)
]

enters the demographic vector field, individual factors are not nonparametrically identifiable from aggregate trajectories without restrictions/additional outputs.

This is an instance of standard output-preserving symmetry logic.

Use established identifiability theory.

Do not advertise as a new general theorem.

Potential ecology-specific work:
- realistic survival observation;
- breeding observation;
- mark–recapture operator;
- detection error;
- partial density range.

---

# 9. Empirical benchmark

## Tribolium castaneum — Buddh, Krishna & Agashe 2024

Why it matters:

- density-dependent population growth is modeled as product of fecundity and survival components;
- both components are experimentally estimated;
- open data/code are linked through Figshare.

Use:
- estimate mechanism penalty profiles;
- visualize mechanism-strength phase geometry;
- test whether fitted profiles satisfy H2/H3-like conditions;
- demonstrate what the theory predicts even outside a canonical Double-Allee regime.

Do not claim the empirical system itself is a double-dormancy example unless data establish it.

---

# 10. Counterexample agenda

Construct explicit counterexamples for:

1. g_i not convex -> F can gain multiple local maxima;
2. b not concave -> more than two threshold crossings;
3. g_i changing sign -> extinction region need not be upward closed;
4. deleting a mechanism that is not purely limiting -> persistence monotonicity can fail;
5. noncompact density domain without coercivity -> M may fail to attain its maximum.

These counterexamples are required to demonstrate sharpness.

---

# 11. Immediate proof order

P0:
1. THM-P1.
2. THM-P2.
3. THM-P3.
4. THM-P4.

P1:
5. THM-P5.
6. counterexamples.

P2:
7. THM-P6.
8. empirical benchmark.
9. realistic identifiability observation model.

---

# 12. Publication gate

Do not draft the paper until:

- P1–P4 are formally proved or sharply corrected;
- at least two nontrivial counterexamples are available;
- ROUND-0007 returns no direct theorem subsuming P2–P4;
- one empirical mechanism-resolved dataset is reproduced;
- the main result is stronger than root-counting under assumed unimodality.
