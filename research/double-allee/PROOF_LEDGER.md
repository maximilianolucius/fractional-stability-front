# Proof Ledger — Mechanism-Space Multiple Allee Theory

**Date opened:** 2026-09-28  
**Status labels:** TODO / DRAFT-PROVED / VERIFIED / PARTIAL / FALSE / PRIOR-ART

| Claim | Status | Current basis | Main remaining risk |
|---|---|---|---|
| P1 strict concavity from component shapes | DRAFT-PROVED | direct second derivative | hypothesis relevance |
| P2A convexity of M(lambda) | DRAFT-PROVED | supremum of affine functions | none substantial |
| P2B coordinate monotonicity | DRAFT-PROVED | g_i >= 0 | sign-changing mechanisms |
| P2C half-space representation of extinction region | DRAFT-PROVED | M<=0 iff F(x)<=0 for all x | denominator/edge cases only |
| P2E exact strong phase under strict concavity | DRAFT-PROVED | endpoint signs + strict concavity | boundary cases |
| P3 radial t_E formula | DRAFT-PROVED | half-space intersection along ray | zero denominators |
| P3 ordered phase sequence | DRAFT-PROVED | t0 + tE monotonicity | equality/degenerate cases |
| P4A persistence monotonicity under deletion | DRAFT-PROVED | pointwise ordering | assumes purely limiting factors |
| P4B immediate-deletion minimality test | DRAFT-PROVED | monotonicity + low-density test | formal proof needed |
| P4 chain-contiguity | DRAFT-PROVED | upward sets for low-density failure/extinction | formal statement |
| P4 antichain property | DRAFT-PROVED | poset minimality | novelty not claimed |
| P5 boundary normal | TODO | Danskin theorem | regularity/boundary maximizers |
| P6 robust uncertainty | TODO | monotonicity idea | may be too trivial |
| nonconvex-g counterexample | TODO | expected | construct explicit example |
| nonconcave-b multiple-threshold counterexample | TODO | expected | construct explicit example |
| empirical shape check on Tribolium | TODO | open data exists | data import/parameterization |

---

# Draft proof notes

## P1

From

[
F(x;lambda)=b(x)-sum_ilambda_i g_i(x),
]

differentiate twice:

[
F_{xx}
=
b''-sum_ilambda_i g_i''.
]

If (b''<0), (g_i''ge0), and (lambda_ige0), then

[
F_{xx}<0.
]

Hence strict concavity.

No novelty claim.

## P2A

For (	hetain[0,1]),

[
F(x;	hetalambda+(1-	heta)mu)
=
	heta F(x;lambda)+(1-	heta)F(x;mu).
]

Therefore

[
M(	hetalambda+(1-	heta)mu)
=
max_x
[	heta F(x;lambda)+(1-	heta)F(x;mu)]
]

is bounded above by

[
	heta M(lambda)+(1-	heta)M(mu).
]

Hence M is convex.

## P2C

[
M(lambda)le0
]

iff

[
F(x;lambda)le0
quad
orall x.
]

Since

[
F(x;lambda)=b(x)-lambdacdot g(x),
]

this is equivalent to

[
lambdacdot g(x)ge b(x)
quad
orall x.
]

Thus

[
mathcal E
=
igcap_x
{lambda:lambdacdot g(x)ge b(x)}.
]

Each set is a closed half-space.

## P2E

If:
- (F(0)<0);
- (F(K)<0);
- (M>0);
- F is strictly concave;

then the positive superlevel set

[
{x:F(x)>0}
]

is a nonempty open interval strictly inside ((0,K)).

Its two boundary points are the only zeros.

Strict concavity implies the lower zero has positive slope and the upper zero negative slope unless a nontransverse degeneracy occurs; under M>0 the roots cannot coincide.

## P3

Along (lambda=tu), extinction means

[
t,ucdot g(x)ge b(x)
quad
orall x.
]

For every x with (ucdot g(x)>0),

[
tge
rac{b(x)}{ucdot g(x)}.
]

Thus the least extinction strength is the supremum of these ratios, subject to special treatment when the denominator is zero.

The low-density sign changes at

[
t_0=b(0)/(ucdot g(0)).
]

Since x=0 is included in the supremum defining t_E,

[
t_Ege t_0
]

whenever both are finite and the ratio convention applies.

Therefore the strong interval can only occur between the two boundaries.

## P4B

Suppose S is threshold-generating.

Then (M_S>0).

For any (Tsubset S),

[
F_Tge F_S
]

pointwise, hence

[
M_Tge M_S>0.
]

Therefore no proper subset can fail threshold-generation because of complete extinction.

A proper subset T fails to be threshold-generating iff

[
F_T(0)ge0.
]

Because deleting mechanisms raises (F(0)), it is enough to check the maximal proper subsets (Ssetminus{i}).

This gives the immediate-deletion criterion.

## P4 chain-contiguity

Along any inclusion chain

[
S_0subset S_1subsetcdotssubset S_r,
]

both:

- the indicator of (F_S(0)<0);
- the indicator of (M_Sle0);

are monotone from false to true.

Because extinction implies (F_S(0)le0), the possible generic phase sequence is:

no-low-density-failure -> threshold-generating -> extinct.

Neither transition can reverse along the chain.

---

# Required independent checks

Before upgrading any DRAFT-PROVED claim to VERIFIED:

1. write epsilon-level proofs for all boundary/equality cases;
2. test with symbolic/numerical counterexamples;
3. check whether K finite is essential;
4. formulate an infinite-domain coercive version;
5. compare P2–P4 with convex-viability and threshold-game literature in ROUND-0007.
