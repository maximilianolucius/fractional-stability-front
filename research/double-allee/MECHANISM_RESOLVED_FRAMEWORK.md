# Mechanism-Resolved Multiple Allee Framework

**Status:** CHIEF mathematical synthesis, 2026-09-28.  
**Purpose:** freeze the exact candidate model class before final novelty falsification.  
**Primary target:** a reusable theorem program for **emergent strong demographic Allee thresholds from separately interpretable component mechanisms**, with a coupled structural-identifiability theory.

This file does **not** assert novelty. It defines the object that ROUND-0006 must try to kill.

---

# 1. Why this class

The literature already contains:
- multiple component Allee effects;
- double dormancy examples;
- model-specific two-component threshold analyses;
- strong-Allee networks;
- fractional Double-Allee models.

Therefore the project must not ask whether two Allee mechanisms can coexist.

The unresolved candidate question is more precise:

> Can the interaction of separately measurable fitness components be characterized by exact, reusable conditions that determine when a demographic extinction threshold emerges even though no component alone generates one—and can the hidden component decomposition be identified from population observations?

This is a **composition + inverse problem**, not another predator–prey model.

---

# 2. Mechanism-resolved scalar class

Let (xge 0) denote abundance or density.

Write the demographic dynamics as

[
dot x
=
x,M(x;eta),[V_S(x;	heta)-1],
qquad
M(x;eta)>0,
]

where the dimensionless viability ratio is

[
V_S(x;	heta)
=
B(x;	heta_0)
prod_{iin S} A_i(x;	heta_i).
]

Interpretation:

- (B(x;	heta_0)>0): baseline demographic viability after mortality normalization; it contains high-density negative feedback/crowding and any mechanism not being decomposed;
- (A_i(x;	heta_i)>0): separately interpretable density-dependent component-fitness factors;
- (Ssubseteq{1,ldots,m}): active component-mechanism set;
- the sign of per-capita growth is exactly the sign of (V_S-1).

Equivalent non-normalized form:

[
dot x
=
xleft[
R(x;	heta_0)prod_{iin S}A_i(x;	heta_i)-D(x;eta)
ight],
]

with (V_S=Rprod A_i/D).

The normalized form is preferred because thresholds are level crossings:

[
V_S(x)=1.
]

---

# 3. Component deletion as the counterfactual definition

A component mechanism is not defined by the title of a model.

For each (i), define deletion by replacing its normalized limitation factor by its no-limitation reference:

[
A_i(x)mapsto 1.
]

Thus every subset (S) defines a counterfactual demographic law (V_S).

This makes statements such as

> “component (i) alone is dormant”

mathematically testable rather than verbal.

The reference normalization (A_ile 1) is natural when (A_i) represents a limitation probability/fraction such as successful mating, fertilization, breeding participation, or survival multiplier. Other signs/scales can be mapped into the viability ratio when scientifically appropriate.

---

# 4. Strong threshold definition

For an active set (S), call (a_S>0) a **demographic Allee threshold** if:

[
V_S(a_S)=1,
]

with

[
V_S(x)<1 quad 	ext{immediately below }a_S,
]

and

[
V_S(x)>1 quad 	ext{immediately above }a_S.
]

In the scalar ODE this is the positive unstable equilibrium separating extinction from growth toward a higher positive attractor, under the usual transversality condition.

A component-level positive density dependence is not itself a demographic threshold.

---

# 5. Double dormancy in this framework

For two components (A_1,A_2), define:

- component 1 alone: (V_{{1}}=BA_1);
- component 2 alone: (V_{{2}}=BA_2);
- joint action: (V_{{1,2}}=BA_1A_2).

**Double dormancy** means:

1. neither one-component counterfactual possesses a strong demographic threshold;
2. the joint system does possess a strong demographic threshold.

This directly operationalizes the ecological concept without equating “double” with “two positive thresholds.”

---

# 6. Shape-controlled theorem class

The fully unrestricted smooth class is too broad: arbitrary smooth products can have arbitrary root multiplicity.

The leading theorem class will therefore use verifiable shape assumptions.

A useful sufficient structural package is:

1. (A_i(x)>0), (A_i'(x)ge0) over the low-density regime;
2. (A_i(x)le1) after normalization;
3. high-density negative feedback is contained in (B);
4. (V_S(x)	o v_infty<1) at the high-density boundary or as (x	oinfty);
5. the log-slope
   [
   L_S(x)
   =
   rac{d}{dx}log V_S(x)
   =
   rac{B'(x)}{B(x)}
   +
   sum_{iin S}rac{A_i'(x)}{A_i(x)}
   ]
   has controlled zero structure—preferably exactly one zero, e.g. through strict monotonicity of (L_S).

When (L_S) crosses zero once from positive to negative, (V_S) is strictly unimodal.

This is broad enough to include saturating mate-finding/survival components while still permitting exact root-count results.

---

# 7. Candidate Theorem A — exact threshold classification

Under strict unimodality of (V_S) and (V_S) below one at the high-density boundary:

### Regime A
[
V_S(0)ge1.
]

No low-density strong demographic threshold occurs. A weak component/demographic Allee effect may still occur.

### Regime B
[
V_S(0)<1
quad	ext{and}quad
max_{x>0}V_S(x)>1.
]

There are exactly two positive level crossings of (V_S=1):

- a lower unstable Allee threshold;
- a higher stable positive equilibrium.

### Regime C
[
max_{xge0}V_S(x)<1.
]

No positive persistence equilibrium exists.

### Fold boundary
[
max_x V_S(x)=1.
]

At a nondegenerate maximizer (x_ast),

[
V_S(x_ast)=1,
qquad
L_S(x_ast)=0,
qquad
L_S'(x_ast)<0,
]

giving the threshold-creation saddle-node boundary.

The theorem itself must be checked against general scalar bifurcation literature; novelty can only arise from the mechanism-resolved composition and counterfactual structure.

---

# 8. Candidate Theorem B — exact double-dormancy wedge

Assume the one-component systems satisfy the non-strong conditions

[
V_{{1}}(0)ge1,
qquad
V_{{2}}(0)ge1,
]

and the joint system is strictly unimodal.

Then a necessary low-density synergy condition for joint strong behavior is

[
V_{{1,2}}(0)<1.
]

Writing

[
q=rac{1}{B(0)},
]

this becomes

[
A_1(0)A_2(0)<q
le
min{A_1(0),A_2(0)}.
]

With the persistence condition

[
max_x B(x)A_1(x)A_2(x)>1,
]

the joint system has a strong demographic threshold while the one-component deletion systems do not.

The final theorem must state conditions ensuring that the individual counterfactual systems truly have no lower threshold throughout the domain, not merely at (x=0).

---

# 9. Candidate Theorem C — comparative statics via component elasticities

At a transverse threshold (a(	heta)),

[
V_S(a(	heta);	heta)=1.
]

Implicit differentiation gives

[
rac{da}{d	heta_j}
=
-
rac{partial_{	heta_j}log V_S}
{partial_xlog V_S}
Bigg|_{x=a}.
]

At the lower threshold of a unimodal viability curve,

[
partial_xlog V_S>0,
]

so the sign of threshold movement is controlled directly by the component-specific parameter effect.

This can yield exact monotone comparative statics for:
- mate-finding efficiency;
- predation dilution;
- breeding participation;
- survival limitation;
- management intervention on one component.

The theorem target is a general comparative-statics result, not parameter differentiation for one chosen function.

---

# 10. Extension to (m) component mechanisms

For (m) components define the family

[
V_S=Bprod_{iin S}A_i,
qquad
Ssubseteq[m].
]

A subset (S) is **threshold-generating** if its counterfactual system has a strong demographic threshold.

A subset (S) is **minimal threshold-generating** if it is threshold-generating while every proper subset is non-strong.

Double dormancy is the case

[
S={1,2}
]

with both singleton subsets non-strong.

This subset-lattice formulation may permit:
- exact classification of minimal mechanism combinations;
- interaction order;
- super/subadditivity of threshold location;
- robustness of minimal generating sets.

This is a generalization hypothesis and must not be promoted if it reduces to trivial set terminology without new theorems.

---

# 11. Candidate Theorem D — gauge-type structural non-identifiability

Suppose only the aggregate state (x(t)) is observed and the model depends on the component mechanisms through

[
P(x)=prod_{i=1}^{m}A_i(x).
]

For any collection of positive admissible functions (h_i(x)) satisfying

[
prod_{i=1}^{m}h_i(x)=1,
]

define

[
widetilde A_i(x)=A_i(x)h_i(x).
]

Then

[
prod_iwidetilde A_i
=
prod_iA_i
=
P.
]

Therefore the demographic vector field is unchanged.

Consequently, in a nonparametric mechanism class:

> abundance-only trajectories cannot structurally identify the individual component-fitness functions; only their composite product is identifiable.

For two mechanisms this includes the one-function gauge

[
(A_1,A_2)
mapsto
(A_1h,A_2/h).
]

This is an exact impossibility result, subject to admissibility constraints on the transformed component functions.

---

# 12. Candidate Theorem E — minimal observation lifting

The inverse problem changes when component-specific demographic outputs are observed.

For example, if

[
y_1(t)=A_1(x(t))
]

is observed and the composite product (P=A_1A_2) is identified from the demographic dynamics, then

[
A_2(x(t))
=
rac{P(x(t))}{y_1(t)}
]

along the observed state range.

For (m) unrestricted multiplicative factors, aggregate dynamics alone leave an ((m-1))-function gauge freedom. Mechanism-specific outputs can remove this freedom.

The target is a rigorous minimal-output theorem distinguishing:
- nonparametric component functions;
- finite-dimensional parametric component families;
- partial/noisy observations.

This connects directly to empirical systems where survival and breeding are measured separately.

---

# 13. Network extension: identifiability, not generic persistence

Consider

[
mathcal D x_i
=
x_i M_i(x_i)
left[
B_i(x_i)prod_{k=1}^{m_i}A_{ik}(x_i)-1
ight]
+
sum_j C_{ij}(x),
]

where (C_{ij}) is a known coupling law independent of the hidden factorization.

If each nodewise transformation satisfies

[
prod_kwidetilde A_{ik}
=
prod_k A_{ik},
]

then the full network vector field is unchanged.

Therefore:

> known network coupling does not by itself resolve the hidden component decomposition from state trajectories.

This is a stronger and more specific network statement than generic Allee persistence/extinction theory.

The same observation suggests that adding more patches can improve statistical information about the composite demographic law without restoring structural identifiability of the component factorization.

---

# 14. Fractional-memory extension

Replace the ordinary derivative by an operator such as Caputo:

[
{}^C D_t^alpha x_i
=
F_i(x).
]

If the right-hand side is unchanged under the component-factor gauge, then the same structural non-identifiability transformation leaves the fractional model unchanged for fixed (alpha).

Thus the component-decomposition impossibility is potentially **operator-independent**:

[
F(A_1,ldots,A_m)
=
F(widetilde A_1,ldots,widetilde A_m)
]

implies identical model equations under either ordinary or fractional left-hand-side dynamics.

This provides a natural connection to Fractional Stability Front without claiming that fractional memory itself creates novelty.

Whether (alpha) is identifiable simultaneously is a separate problem.

---

# 15. Empirical architecture

The theorem program must not depend on unavailable data.

## Open benchmarks

- herring: low-density threshold/model-selection sensitivity;
- cod: threshold uncertainty;
- freshwater mussel: component-fitness observation and spatial masking.

## Mechanism-resolved target systems

- island fox: survival + breeding component effects; historical raw access unresolved;
- Crested Ibis: survival + reproduction component effects; raw access unresolved.

The theory should predict which extra measurements are needed before requesting/collecting them.

---

# 16. What would make this Q1-level applied mathematics

A strong manuscript would need several pieces simultaneously:

1. a general mechanism-resolved viability formalism;
2. a nontrivial exact threshold-composition theorem beyond one chosen functional form;
3. a double-dormancy classification as a corollary;
4. comparative statics or bifurcation geometry at threshold creation;
5. an exact structural non-identifiability theorem for aggregate data;
6. a minimal-observation/identifiability recovery result;
7. evidence that network coupling and/or fractional memory does not automatically cure the hidden-mechanism ambiguity;
8. empirical or open-data demonstration of the observation-design consequences.

The novelty is the **coupling of forward threshold composition and inverse mechanism identifiability**.

---

# 17. Failure modes

Reject or radically revise this direction if:

1. a prior theorem already gives the same composition characterization for a comparable component-function class;
2. the threshold theorem reduces to a trivial application of a textbook unimodality/root argument with no mechanism-resolved generalization;
3. the gauge non-identifiability result is already standard in ecological demographic decomposition under the same observation setting;
4. the proposed minimal-output theorem is false for realistic parametric families;
5. the ecological component decomposition is not measurable or scientifically interpretable;
6. the only available data observe aggregate abundance and cannot test any mechanism-level consequence.

---

# 18. Immediate research dependency

Before promoting this file to the primary direction, run a final formula-level novelty search on:

- multiplicative survival/fecundity decomposition;
- density-dependent demographic component models;
- nonparametric factor identifiability;
- gauge/symmetry non-identifiability;
- minimal-output observability of factorized nonlinear dynamics;
- multiple/component Allee threshold composition;
- life-cycle and matrix-population analogues.

That is ROUND-0006.
