# 2026-09-28 — Structured Conic D-Stability Falsification

**Round:** ROUND-0003  
**Request:** `research/coordination/chief-to-web/ROUND-0003_conic-d-stability-structured_REQUEST.md`

## Question

After generalized multiplicative D-stability in conic/LMI regions is acknowledged, do exact finite structure-sensitive characterizations already exist that would subsume the proposed ecological-Jacobian route?

## Classical D-stability baseline

The classical problem is old and difficult. Johnson (1974), DOI 10.1016/0022-0531(74)90074-X, surveyed thirteen sufficient conditions and explicitly motivated the survey by the lack of an effective general characterization.

Chen, Fan & Yu (1995), DOI 10.1016/0167-6911(94)00036-U, proved that real D-stability is equivalent to a real structured-singular-value condition on an associated complex matrix. Their abstract states that this implies checking D-stability **may in general be NP-hard**. This is strong complexity evidence, but it is not reported here as a formal NP-completeness theorem.

## Exact finite results that already exist

### Low dimension

Charles R. Johnson, *Second, Third, and Fourth Order D-Stability*, Journal of Research of the National Bureau of Standards 78B (1974), pp. 11–13, DOI 10.6028/jres.078B.004, gives explicit conditions for real D-stable matrices in dimensions 2, 3 and 4.

This kills any novelty claim based only on “low-dimensional exact D-stability.”

### Tridiagonal matrices

Carlson, Datta & Johnson (1982), DOI 10.1137/0603030, use a semidefinite Lyapunov theorem to characterize real tridiagonal matrices that are D-stable and totally D-stable.

### Acyclic matrices

Berman & Hershkowitz (1984), DOI 10.1016/0024-3795(84)90201-5, give necessary-and-sufficient conditions for D-stability of acyclic matrices, explicitly subsuming tridiagonal special cases.

This is the strongest direct killer of a generic “graph-sparse ecological Jacobian” novelty claim: sparsity/acyclicity alone is already a classical exact subclass.

### Metzler matrices

Narendra & Shorten (2009), DOI 10.1109/ACC.2009.5160435, exploit the classical fact that a Hurwitz Metzler matrix is diagonally stable and give a recursive necessary-and-sufficient Hurwitz test using lower-dimensional matrices.

For a Metzler (A), positive diagonal left scaling preserves the Metzler sign class. Hence the ordinary Hurwitz D-stability question collapses strongly relative to the generic case: the positive-system class is not a blank frontier.

## Sign / qualitative / ecological structure

Qualitative sign stability has a complete graph-theoretic literature. Jeffries, Klee & van den Driessche, *Qualitative stability of linear systems* (1987), DOI 10.1016/0024-3795(87)90156-X, builds on the earlier complete characterization of sign-stable patterns. The ecological sign-stability literature similarly has complete sign-pattern classes.

This does **not** automatically imply conic-sector multiplicative D-stability: sign stability controls the Hurwitz half-plane uniformly over magnitudes, whereas a fractional/conic criterion requires an angular margin away from the positive real sector boundary.

Modern ecological reviews make the hierarchy explicit:
- diagonal stability is stronger than ordinary D-stability;
- D-stability is directly relevant to generalized Lotka–Volterra community matrices (M=DA);
- total and sign/structural stability form distinct notions.

Therefore an ecological application of ordinary D-stability is not new by itself.

## Conic/relative D-stability

ROUND-0001 already verified Kushel–Pavani's generalized multiplicative D-stability in LMI/conic regions, including exact formulations that may retain a universal quantifier over positive diagonal scalings.

This round searched combinations of:
- conic/sector + acyclic/tridiagonal;
- relative D-stability + graph/sign;
- Metzler + conic D-stability;
- qualitative D-stability + sector;
- ecological D-stability + angular/sector margin.

**No exact finite conic-sector analogue for the classical acyclic/tridiagonal/sign-pattern/ecological classes was identified in the searched corpus.**

This is a scoped negative result, not proof of absence.

## Strong counterexamples / limitations

1. **Stability alone does not imply D-stability.** The classical literature exists precisely because positive diagonal scaling can destabilize a stable matrix.
2. **P-matrix/principal-minor conditions are necessary but not generally sufficient** for ordinary D-stability; ecological/matrix reviews give explicit counterexample families.
3. **Diagonal stability is sufficient but not necessary** for D-stability in general, so replacing the universal scaling property by a diagonal Lyapunov certificate can be conservative.
4. **Sign stability and ordinary D-stability do not give a fractional angular margin.** A Hurwitz-stable family can approach the imaginary axis or have eigenvalue arguments insufficient for a prescribed fractional sector.
5. **Acyclic/tridiagonal/Metzler subclasses are already highly constrained.** Choosing one merely to obtain a finite theorem risks rediscovering classical results rather than sharpening the conic theory.

## F-002 evidence classification

**OPEN ONLY FOR A SHARPLY SPECIFIED SUBCLASS.**

The broad structural question is not open:
- low dimension: exact classical criteria exist;
- tridiagonal/acyclic: exact classical criteria exist;
- Metzler: ordinary Hurwitz/D/diagonal stability largely collapse;
- sign stability: graph-theoretic classifications exist;
- general conic regional D-stability: framework exists.

The searched corpus did **not** identify a finite exact criterion for **multiplicative conic-sector D-stability** on a nontrivial, cyclic, non-Metzler ecological/sign/graph class.

## Consequence for C-DA-4

C-DA-4 survives only if the matrix class is fixed *before* theorem search and satisfies all of:
1. biologically natural;
2. not acyclic/tridiagonal in a way already covered;
3. not Metzler/positive in a way that trivializes ordinary D-stability;
4. genuinely requires a conic angular margin, not merely Hurwitz stability;
5. admits a new finite exact characterization sharper than Kushel–Pavani.

A generic “ecological Jacobian + D-stability” paper should be rejected.

## Strongest theorem capable of killing C-DA-4

**Berman & Hershkowitz (1984)** for acyclic graph classes, combined with **Kushel–Pavani (2022)** for conic regional D-stability.

Together they show that both halves of the proposed bridge already have substantial exact theory; novelty can survive only in their nontrivial intersection.

## Recommended next search

Only after the Chief proposes a concrete ecological Jacobian class:
- derive its sign/cycle structure;
- test whether diagonal similarity/scaling reduces it to an acyclic, Metzler, sign-stable, symmetrizable or generalized-diagonally-dominant class;
- then search that exact class + conic/relative D-stability.

Do not search for a class merely to manufacture novelty.