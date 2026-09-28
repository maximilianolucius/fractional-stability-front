# Double Allee — Candidate Directions

**Status:** Chief-generated candidates after ROUND-0002. None is selected as primary.

Every candidate below is a research hypothesis. Each has an explicit kill criterion.

## C-DA-1 — Double dormancy as an emergent-threshold theorem class

### Precise mathematical question

Let the per-capita demographic growth law be built from two density-dependent component mechanisms,

[
g(x;	heta)=Gig(g_1(x;	heta_1),g_2(x;	heta_2),xig),
]

where each component alone produces no strong demographic Allee threshold on the biologically admissible interval.

Characterize conditions under which the composition:

- creates a positive unstable threshold;
- creates exactly one threshold versus several;
- destroys an existing threshold;
- shifts threshold location monotonically with mechanism strength.

### Closest known literature

- Berec–Angulo–Courchamp 2007: multiple component effects and double dormancy.
- Model-specific Double-Allee predator–prey bifurcation literature.
- General fold/saddle-node and scalar population-growth theory may contain equivalent results under different language.

### Expected theorem program

1. necessary/sufficient threshold-existence criterion for a controlled function class;
2. uniqueness/multiplicity theorem;
3. comparative statics for threshold location;
4. bifurcation classification at threshold creation;
5. robustness under bounded parameter uncertainty.

### Likely obstruction

If the function class is too broad, no nontrivial universal criterion exists.  
If it is too narrow, the theorem becomes algebraic bookkeeping.

### Relation to fractional stability

Secondary, not intrinsic. Fractional memory should be added only if it changes transient basin geometry, identifiability, or network persistence in a mathematically essential way.

### Data opportunity

Island fox and other systems with multiple measured component effects could motivate/calibrate mechanism forms.

### Why this is more than a model variation

The target is a **composition theorem** that explains a family of multiple-Allee models as corollaries.

### Kill criterion

Reject if ROUND-0004 finds a general theorem in population dynamics, catastrophe theory, monotone comparative statics, or related literature that already provides the intended characterization at equal or greater generality.

---

## C-DA-2 — Network transformation of emergent Allee thresholds

### Precise mathematical question

Consider a network of patches

[
dot x_i = f_i(x_i;	heta_i) + sum_j L_{ij} h_{ij}(x_j,x_i),
]

where each local (f_i) contains two component mechanisms whose interaction can create an emergent demographic threshold.

Determine graph/topology conditions under which coupling:

- removes a local extinction threshold;
- creates a global persistence threshold;
- synchronizes or separates threshold crossings;
- produces topology-dependent rescue/extinction regions.

### Closest known literature

- Lanchier 2013 strong-Allee interacting patches;
- metapopulation rescue/extinction theory;
- bistable and monotone network systems;
- graph reaction–diffusion systems.

### Expected theorem program

1. comparison theorem linking local threshold geometry to network persistence;
2. graph-dependent sufficient and, where possible, necessary conditions;
3. exact results on selected graph classes;
4. scaling limits or bounds in terms of degree/spectral quantities;
5. extension to heterogeneous patches.

### Likely obstruction

Existing bistable-network or interacting-particle-system theory may already subsume the deterministic core.

### Relation to fractional stability

Optional second-stage extension. Fractional memory is not part of the novelty claim unless it materially changes the theorem.

### Data opportunity

Spatially replicated conservation or invasion datasets with known patch connectivity.

### Why this is more than a model variation

The target is a graph theorem that explains how an ecologically grounded **emergent threshold mechanism** is transformed by topology.

### Kill criterion

Reject if general bistable-network/metapopulation theorems already deliver the same threshold/topology characterization for a function class broad enough to include double dormancy.

---

## C-DA-3 — Identifiability of multiple component effects versus memory

### Precise mathematical question

Given observations of abundance and selected demographic components, determine when a model with:

- one component Allee mechanism;
- two interacting component mechanisms;
- an emergent demographic threshold;
- and a memory/fractional parameter

is structurally and practically distinguishable from simpler competitors.

### Closest known literature

- empirical multiple-component Allee studies;
- structural/practical identifiability;
- fractional inverse problems;
- ecological state-space models with colored environmental noise.

### Expected theorem/program

1. structural identifiability result for a carefully chosen mechanistic model;
2. proof of non-identifiability in insufficient observation designs;
3. minimal-observation theorem or rank condition;
4. practical identifiability analysis under realistic sampling;
5. real-data model discrimination and out-of-sample validation.

### Likely obstruction

Fractional order may be confounded with latent environmental autocorrelation, time-varying parameters, observation error, or unmeasured predation.

### Relation to fractional stability

Directly relevant only if fractional memory is empirically estimable and changes stability/threshold conclusions.

### Data opportunity

Island fox is a lead; raw-data availability is not yet established. Alternative repeated-measure systems must be searched.

### Why this is more than a model variation

A successful result would state when “memory + multiple Allee effects” is scientifically identifiable rather than merely fit-able.

### Kill criterion

Reject if no accessible dataset has enough independent demographic and temporal information, or if structural identifiability fails under realistic observation schemes.

---

## C-DA-4 — Structured Jacobian theorem for ecological threshold networks

### Precise mathematical question

For ecological networks whose Jacobians inherit sign/sparsity/factorization from threshold mechanisms, determine whether local fractional stability under structured positive diagonal rescaling admits an exact finite criterion.

### Closest known literature

- generalized regional D-stability in conic sectors;
- positive/Metzler diagonal stability;
- qualitative/sign stability;
- ecological community-matrix theory.

### Expected theorem program

1. identify a biologically natural Jacobian class;
2. characterize conic-sector multiplicative D-stability on that class;
3. relate the criterion to graph cycles/sign structure;
4. apply it to a Double-Allee network equilibrium.

### Likely obstruction

The matrix theorem may already exist in qualitative D-stability language, or the ecological Jacobian class may not simplify the general problem enough.

### Relation to fractional stability

Central.

### Data opportunity

Secondary; data would mainly justify parameter/sign structure.

### Why this is more than a model variation

The contribution would be a new structured-matrix theorem with ecology as a non-artificial application.

### Kill criterion

Reject if ROUND-0003 finds an existing exact characterization covering the proposed sign/graph class.

---

## Chief posture after seed round

The project should **not** yet choose a primary direction.

The two concepts that deserve the most aggressive falsification are:

- **emergent threshold from interacting component effects (double dormancy)**;
- **network transformation of that emergent threshold**.

The identifiability branch should proceed in parallel because it may determine whether a real-data component can be scientifically credible.

The structured-Jacobian branch remains attractive only if ROUND-0003 finds a genuinely unresolved matrix subclass.
