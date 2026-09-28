# 2026-09-28 — Fractional Bifurcation Semantics and Architecture

**Round:** ROUND-0010  
**Request:** `research/coordination/chief-to-web/ROUND-0010_fractional-bifurcation-semantics_REQUEST.md`  
**Role:** WEB SEARCHER  
**Mission:** reconstruct theorem-level bifurcation architecture for continuous-time fractional differential systems and identify operator-correct residual frontiers near Double/Multiple Allee dynamics.

## Executive result

The naive statement

> “fractional bifurcation theory is missing”

is false.

There is already rigorous theory for:
- stable and center-stable manifolds for Caputo-type systems;
- finite-dimensional Caputo center manifolds;
- Caputo Lyapunov–Schmidt reduction;
- center-manifold and Lyapunov–Schmidt reduction for Caputo–Hadamard systems;
- model-/class-specific saddle-node, transcritical and pitchfork bifurcations;
- attractor bifurcation for structured Caputo systems;
- an exact nonexistence theorem for nonconstant periodic solutions in autonomous finite-lower-terminal Caputo systems;
- classical center-manifold and Hopf theory for broad Volterra convolution equations under kernel hypotheses that do **not** automatically include the canonical Caputo power-law kernel.

The residual frontier is not a single gap. It splits into three high-information subproblems:

1. **Caputo memory-state nonhyperbolic bifurcation:** center-manifold/normal-form/bifurcation theory for the infinite-dimensional singular Volterra semiflow naturally associated with canonical finite-terminal Caputo equations.
2. **Operator-correct recurrent bifurcation:** periodic-orbit/Floquet/Hopf theory for formulations that actually admit exact periodic solutions (e.g. infinite-past/Liouville–Weyl-type models), clearly separated from finite-terminal Caputo stability-sector crossings.
3. **Incommensurate nonhyperbolic reduction:** general center-manifold/normal-form theory for genuinely multi-order Caputo systems; no resolving general theorem was identified.

For Double/Multiple Allee models, the key correction is fundamental:

> If the fractional order changes only the left-hand derivative while the vector field (f(x,mu)) is unchanged, then the set and algebraic location of equilibria—including ordinary fold/cusp geometry of (f=0)—do not depend on the fractional order.

The intrinsically fractional questions concern stability sectors, memory-state basins, attractor structure, transient threshold crossing and operator-correct recurrent dynamics.

---

# A. Invariant and center manifolds

## A1. Hyperbolic stable manifolds — direct prior

Cong, Doan, Siegmund & Tuan, *On stable manifolds for fractional differential equations in high dimensional spaces*, Nonlinear Dynamics 86 (2016), DOI **10.1007/s11071-016-3002-z**.

**System:** finite-dimensional fractional differential equations near a hyperbolic equilibrium.

**Result:** existence of stable manifolds in arbitrary finite dimension.

**Method:** Lyapunov–Perron / Mittag–Leffler estimates.

**Caution:** an erratum (DOI 10.1007/s11071-016-3039-z) corrects part of Proposition 9; theorem use should follow the corrected version.

## A2. Caputo center manifold — direct prior

Ma & Li, *Center Manifold of Fractional Dynamical System*, Journal of Computational and Nonlinear Dynamics 11(2) (2016), article 021010, DOI **10.1115/1.4031120**.

The paper explicitly establishes a local fractional center manifold for a finite-dimensional fractional ordinary dynamical system with Caputo derivative and gives approximation examples.

**Implication:** “Caputo center manifolds do not exist” is false.

## A3. Caputo center-stable manifolds — direct prior

Peng, Wang & Yu, *On the center-stable manifolds for some fractional differential equations of Caputo type*, Nonlinear Analysis: Modelling and Control 23(5) (2018), 642–663, DOI **10.15388/NA.2018.5.2**.

The source proves center-stable-manifold existence for planar Caputo-type equations with a relaxation factor using a Lyapunov–Perron operator and also considers higher dimension.

Wang, Fečkan & Zhou, *Center stable manifold for planar fractional damped equations*, Applied Mathematics and Computation 296 (2017), 257–269, DOI **10.1016/j.amc.2016.10.014**, gives an additional planar fractional-damped center-stable theorem.

## A4. Modern center manifold work

Liao, Wu & Li, *Center manifold theorem of fractional differential equations and machine learning under weak data*, Physica D 489 (2026), 135122, DOI **10.1016/j.physd.2026.135122**.

The paper:
- proves center-manifold existence by constructing function spaces and fixed-point maps;
- emphasizes that ordinary chain-rule-based ODE calculations cannot simply be transferred;
- develops a neural-network approximation procedure for the center manifold.

The exact operator/model class must be cited from the theorem statement when used; the abstract establishes existence for the source's fractional-order system but should not be overgeneralized to every operator.

## A5. Caputo–Hadamard center manifold

Ma & Shu, *Center Manifold Reduction for Caputo–Hadamard Fractional Differential System*, Journal of Computational and Nonlinear Dynamics 20(9) (2025), DOI **10.1115/1.4068728**.

The source defines a local Hadamard fractional center manifold relative to the (delta)-derivative, proves existence/approximation and analyzes stability.

## Verdict — invariant/center manifolds

**SUBSTANTIAL PARTIAL THEORY.**

The branch is real and nontrivial. What is missing is not existence of center manifolds in fractional systems generally; the unresolved question is the coverage and coherence of the theory across:
- canonical finite-terminal Caputo memory-state semiflows;
- genuinely incommensurate systems;
- operator classes;
- reduced dynamics/normal forms rather than manifold existence alone.

---

# B. Lyapunov–Schmidt and normal-form reduction

## B1. Caputo Lyapunov–Schmidt — direct prior

Li & Ma, *Lyapunov–Schmidt Reduction for Fractional Differential Systems*, Journal of Computational and Nonlinear Dynamics 11(5) (2016), article 051022, DOI **10.1115/1.4033607**.

The paper explicitly extends Lyapunov–Schmidt reduction to fractional ordinary differential systems with Caputo derivatives, using Fredholm/projection machinery and reduced finite-dimensional equations.

This directly kills a broad claim that fractional systems lack Lyapunov–Schmidt reduction.

## B2. Caputo–Hadamard Lyapunov–Schmidt — direct prior

Ma & Shu, *Lyapunov-Schmidt reduction for Caputo-Hadamard fractional differential system*, Nonlinear Dynamics 113 (2025), 29107–29122, DOI **10.1007/s11071-025-11651-w**.

The source establishes an operator-adapted Lyapunov–Schmidt reduction and analyzes reduced equations; its examples include pitchfork structure.

## B3. Fundamental one-parameter Caputo bifurcations

Qian & Chen, *Analysis the Fundamental Bifurcations of the Fractional Differential Systems with the Parameters*, Journal of Dynamics and Control 11(3) (2013), 211–220, DOI **10.6052/1672-6553-2013-053**.

The source analyzes one-parameter Caputo systems using Lyapunov stability, Taylor expansion and classical implicit-function/topological-equivalence tools and treats:
- fold;
- transcritical;
- pitchfork bifurcation.

## B4. Caputo–Hadamard fold normal form

Ma & Huang, *Asymptotic stability and fold bifurcation analysis in Caputo–Hadamard type fractional differential system*, Chinese Journal of Physics 88 (2024), 171–197, DOI **10.1016/j.cjph.2024.01.028**.

The source derives sufficient stability criteria and a fold normal form under its operator-specific assumptions.

## Verdict — LS / normal form

**SUBSTANTIAL PARTIAL THEORY.**

There is direct rigorous reduction theory. No single broad normal-form theorem family was identified that simultaneously covers:
- canonical Caputo memory-state dynamics;
- all standard codimension-one/two nonhyperbolic cases;
- incommensurate orders;
- correct recurrent-object semantics.

The gap is fragmentation/generality, not absence.

---

# C. Equilibrium bifurcations: what is algebraic and what is fractional?

Consider

[
{}^C D_t^alpha x=f(x,mu),
]

with (alpha) appearing only in the derivative operator.

Every equilibrium satisfies

[
f(x,mu)=0.
]

Therefore:
- equilibrium existence;
- equilibrium branch location;
- fold conditions in the algebraic root equation;
- transcritical/pitchfork branch intersection;
- cusp degeneracy of the equilibrium equation

are properties of (f) and do not move merely because (alpha) changes.

Fractional order can change **stability of those same equilibria** because the admissible spectral sector changes.

## Direct rigorous prior

Doan & Kloeden, *Attractors of Caputo fractional differential equations with triangular vector fields*, Fractional Calculus and Applied Analysis 25 (2022), 720–734, DOI **10.1007/s13540-022-00030-6**.

For a structured triangular Caputo class, the paper constructs attractors and establishes scalar saddle-node and pitchfork bifurcations.

Qian–Chen 2013 gives fold/transcritical/pitchfork analysis in a one-parameter Caputo setting.

## Cusp / Bogdanov–Takens language

Many applied papers report cusp or Bogdanov–Takens-type structures for fractional models. But if the claimed cusp is only a degeneracy of (f(x,mu)=0), the branch geometry is the same algebraic object as in the ODE.

A genuinely fractional cusp/BT contribution must additionally characterize:
- stability on branches under fractional spectral geometry;
- reduced memory-state dynamics;
- attractor or basin reorganization;
- recurrent dynamics in an operator-consistent formulation.

No general theorem family covering those features for broad Caputo systems was identified.

## Verdict — equilibrium bifurcations

- **Fold/transcritical/pitchfork equilibrium geometry:** **DIRECT PRIOR RESULT FOUND** and often algebraically ODE-identical.
- **General cusp/codimension-two memory-state dynamics:** **CLOSE PRIOR ART / NO GENERAL RESOLVING RESULT FOUND**.

---

# D. “Hopf” and periodicity semantics

This is the most important terminology correction in D10.

## D1. Finite-lower-terminal autonomous Caputo: exact periodicity obstruction

Tavazoei & Haeri, *A proof for non existence of periodic solutions in time invariant fractional order systems*, Automatica 45 (2009), 1886–1890, DOI **10.1016/j.automatica.2009.04.001**.

The theorem shows that the autonomous time-invariant fractional systems considered there, using the Caputo derivative, cannot generate a nonconstant exactly periodic signal. The result explicitly includes commensurate and incommensurate systems.

Therefore a classical Hopf bifurcation in the strict sense

> equilibrium loses stability and a nearby family of nonconstant periodic orbits is born

cannot be asserted for this finite-terminal autonomous Caputo setting.

Tavazoei (2010), *A note on fractional-order derivatives of periodic functions*, further extends the periodicity obstruction to wider Caputo/Riemann–Liouville/Grünwald–Letnikov settings.

## D2. Steady-state / infinite-memory qualification

Yazdani & Salarieh, *On the existence of periodic solutions in time-invariant fractional order systems*, Automatica 47 (2011), 1834–1837, DOI **10.1016/j.automatica.2011.04.013**.

The source distinguishes finite-interval nonperiodicity from periodic behavior in an appropriate steady-state/infinite-memory interpretation.

This is not a contradiction with Tavazoei–Haeri once the lower-terminal/memory convention is stated explicitly.

## D3. Infinite-past formulation that admits exact periodic solutions

Haacker, Leine, Chaudhary, Diethelm, Schmidt, Hashemishahraki et al., *Hill-type stability analysis of periodic solutions of fractional-order differential equations*, Nonlinear Dynamics 114 (2026), article 334, DOI **10.1007/s11071-025-12196-8**.

The paper states explicitly that classical Caputo-type FODEs do not admit exact periodic solutions and proposes a **Liouville–Weyl-type** framework that does admit them.

It also states that a rigorous fractional Floquet theory is lacking. Their Hill-type extension captures exponentially growing perturbations but not the algebraically decaying modes typical of stable fractional systems.

This source is especially important because it turns the semantic issue into a mathematically precise frontier:
- if exact periodic orbits are desired, choose a compatible operator/history convention;
- then the stability theory of those periodic solutions is itself incomplete.

## D4. Asymptotically periodic is a different object

Zhang & Li, *S-asymptotically periodic fractional functional differential equations with off-diagonal matrix Mittag-Leffler function kernels*, Mathematics and Computers in Simulation 193 (2022), 331–347, DOI **10.1016/j.matcom.2021.10.006**.

This is an example of a rigorous non-periodic/asymptotically-periodic solution concept that should not be conflated with an exact limit cycle.

## D5. Applied semantic example near Allee dynamics

Pippal & Sati, *Fractional predator-prey system under Allee effect and anti-predator feedback*, Open Journal of Mathematical Sciences 10 (2026), 1162–1194, DOI **10.30538/oms2026.0339**.

This recent ecological paper explicitly distinguishes:
- the classical (alpha=1) Hopf candidate;
- a Matignon-sector stability transition for (0<alpha<1);
- numerical memory-driven oscillatory transients;
- absence of exact nonconstant periodic solutions in the autonomous Caputo setting.

This is unusually careful semantics and should be treated as a benchmark for future ecological reporting.

## Verdict — Hopf / periodicity

**DIRECT PRIOR RESULT FOUND for the finite-terminal periodicity obstruction.**

The global statement “fractional Hopf bifurcation exists/does not exist” is **AMBIGUOUS / OPERATOR-DEPENDENT**.

Recommended controlled vocabulary:

| Situation | Recommended term |
|---|---|
| finite-terminal autonomous Caputo, eigenvalues cross Matignon sector | stability-sector transition / Hopf-like stability crossing |
| numerical oscillations without periodic-orbit theorem | oscillatory transient / sustained numerical oscillation |
| (S)-asymptotic periodicity theorem | (S)-asymptotically periodic solution |
| infinite-past/Liouville–Weyl periodic solution | exact periodic solution in that operator convention |
| history-state periodic orbit theorem | periodic orbit of the stated memory-state semiflow |
| delay system with periodic orbit | delay-induced periodic orbit under its history formulation |

Do not write “Hopf” without specifying which object bifurcates.

---

# E. History-state / Volterra bifurcation

## E1. Classical Volterra theory is already strong

Diekmann & van Gils, *Invariant manifolds for Volterra integral equations of convolution type*, Journal of Differential Equations 54(2) (1984), 139–180, DOI **10.1016/0022-0396(84)90156-6**.

They develop:
- a local semiflow;
- variation-of-constants;
- stable/unstable/center manifolds;
- Hopf bifurcation;
- population-biology applications.

This is a major killer threat to any claim that “memory systems have no center-manifold or Hopf theory.”

### Why it does not automatically solve canonical Caputo

Inspection of the source shows that the kernel class is taken in an (L^2)-type convolution framework with finite-support assumptions in the principal construction.

The canonical Caputo Volterra kernel

[
(t-s)^{alpha-1}/Gamma(alpha),qquad 0<alpha<1,
]

is weakly singular and has noncompact algebraic memory. Therefore the 1984 theorem cannot simply be cited as a Caputo theorem without proving that its hypotheses are met or extending the function-space/kernel setting.

## E2. Global Volterra Hopf

Fiedler, *Global Hopf Bifurcation for Volterra Integral Equations*, SIAM Journal on Mathematical Analysis 17(4) (1986), 911–932, DOI **10.1137/0517065**.

This source proves a global bifurcation result for periodic orbits in parameterized convolution Volterra equations under a kernel integrability condition with exponential weight.

Again, that hypothesis is not automatically compatible with a slowly decaying power-law Caputo memory kernel.

## E3. Modern Caputo history-state semiflow

Doan & Kloeden (2021) and subsequent work from ROUND-0009 show that autonomous Caputo FDEs can be embedded as singular Volterra equations generating an infinite-dimensional semidynamical system on a function space.

Cui–Kloeden–Xin (2026 preprint) adds compact absorbing-set/attractor machinery.

What was **not** identified is a general theorem transporting the classical Volterra center-manifold/Hopf architecture to this singular Caputo memory-state semiflow.

## Verdict — history-state bifurcation

**CLOSE PRIOR ART — NO RESOLVING CAPUTO-SINGULAR-KERNEL RESULT FOUND.**

This is one of the strongest surviving D10 subfrontiers.

A precise future question is:

> Under which kernel, spectral and regularity assumptions does the Caputo Volterra semiflow admit a center-manifold/reduction theory strong enough to classify nonhyperbolic attractor changes, and what recurrent objects are admissible there?

---

# F. Genuinely incommensurate nonhyperbolic systems

The hyperbolic/local-stability side is now strong (Diethelm et al. 2024 and earlier rational/common-denominator methods).

The nonhyperbolic side is much less unified.

## Existing evidence

- Tavazoei–Haeri periodicity obstruction includes incommensurate autonomous Caputo systems.
- Model-specific incommensurate ecological/chaotic studies exist.
- Liu, Li & Huang, *Stability, bifurcation and characteristics of chaos in a new commensurate and incommensurate fractional-order ecological system*, Mathematics and Computers in Simulation 236 (2025), 248–269, DOI **10.1016/j.matcom.2025.04.015**, derives stability/bifurcation conditions for one incommensurate ecological model and reports order-dependent changes of a “Hopf” threshold.

Such papers do not constitute a general center-manifold/normal-form theorem for multi-order systems.

## Negative search

No resolving theorem was identified that gives, for a broad genuinely incommensurate Caputo system:
- a center manifold at a nonhyperbolic equilibrium;
- a reduced normal form;
- codimension-one/two classification;
- an operator-correct treatment of recurrent dynamics.

## Verdict — incommensurate nonhyperbolic bifurcation

**NO RESOLVING GENERAL RESULT FOUND IN SEARCHED CORPUS.**

This is a high-value D10 residual, especially because hyperbolic/local incommensurate stability has become comparatively mature.

---

# G. Double / Multiple Allee relevance

## G1. Equilibrium thresholds do not move with order if the RHS is unchanged

For

[
{}^C D_t^alpha x=f(x;mu),
]

the equilibrium set is always

[
f(x;mu)=0.
]

Therefore changing (alpha) alone does not change:
- equilibrium locations;
- existence of an Allee threshold equilibrium;
- algebraic saddle-node/fold location in parameter space;
- cusp geometry of the root equation.

This is a decisive filter on novelty claims.

## G2. What memory can change

Fractional memory can alter:
- local stability of a fixed equilibrium via spectral-sector geometry;
- rate and form of convergence/decay;
- transient overshoot across an Allee threshold;
- attraction in the enlarged memory state;
- basin geometry / threshold-relative persistence;
- global attractor organization;
- admissible recurrent behavior under the chosen operator/history convention.

These are genuinely fractional targets.

## G3. Existing fractional Double-Allee bifurcation papers

Mondal et al., *Dynamics of a fractional order predator-prey system with double Allee effect and group defense*, Chinese Journal of Physics 98 (2025), 613–632, DOI **10.1016/j.cjph.2025.09.020**, includes:
- local Matignon stability;
- saddle-node and “Hopf” terminology;
- multistability and basin-stability calculations;
- incommensurate orders.

This is direct prior art against a generic “fractional Double-Allee bifurcation” topic.

Pippal–Sati 2026 is notable for more careful Hopf semantics.

## G4. Residual Double-Allee frontier

No general theorem was identified connecting **Double/Multiple Allee threshold dynamics** to the rigorous Caputo memory-state bifurcation architecture in a way that distinguishes:

1. unchanged algebraic threshold/fold geometry;
2. fractional-order stability-sector changes;
3. memory-state basin/separatrix reorganization;
4. transient crossings of the ecological threshold;
5. attractor bifurcation;
6. operator-consistent recurrent dynamics.

A particularly natural future problem is:

> **Nonhyperbolic and basin bifurcation near strong/Double-Allee thresholds in the Caputo memory-state semiflow, with explicit separation of algebraic equilibrium catastrophe from memory-induced stability/attractor changes.**

For incommensurate predator–prey or multi-species Double-Allee models, the gap is even sharper because no general multi-order center-manifold/normal-form framework was identified.

## Verdict — Double-Allee-specific frontier

**CLOSE PRIOR ART for model-specific fractional bifurcation.**

**NO RESOLVING GENERAL RESULT FOUND for rigorous memory-state/basin/nonhyperbolic semantics.**

---

# H. Theorem-map verdict table

| Branch | Verdict | Strongest prior result | Residual frontier |
|---|---|---|---|
| Center/invariant manifolds | **SUBSTANTIAL PARTIAL THEORY** | Ma–Li 2016; Cong et al. 2016; Peng et al. 2018; Liao et al. 2026 | memory-state / operator-unified / incommensurate reduction |
| Lyapunov–Schmidt / normal form | **SUBSTANTIAL PARTIAL THEORY** | Li–Ma 2016; Ma–Shu 2025 | general reduced normal forms for canonical Caputo memory dynamics |
| Fold/transcritical/pitchfork | **DIRECT PRIOR RESULT FOUND** | Qian–Chen 2013; Doan–Kloeden 2022 | fractional stability/attractor consequences, not equilibrium algebra |
| Cusp/codim-2 | **CLOSE PRIOR ART / NO GENERAL RESOLVING RESULT** | applied/model-specific literature | memory-state codimension-two classification |
| Finite-terminal Caputo periodic orbit | **DIRECT IMPOSSIBILITY RESULT** | Tavazoei–Haeri 2009 | none under same assumptions |
| “Hopf” semantics | **AMBIGUOUS / OPERATOR-DEPENDENT** | Tavazoei–Haeri 2009; Yazdani–Salarieh 2011; Haacker et al. 2026 | define theorem against chosen recurrent object/operator |
| History-state/Volterra bifurcation | **CLOSE PRIOR ART** | Diekmann–van Gils 1984; Fiedler 1986 | singular power-law Caputo Volterra semiflow |
| Incommensurate nonhyperbolic | **NO RESOLVING GENERAL RESULT FOUND** | model-specific 2025 ecology + hyperbolic theory | general center manifold/normal form/codim classification |
| Double-Allee rigorous fractional bifurcation | **CLOSE PRIOR ART, NARROW FRONTIER SURVIVES** | Mondal et al. 2025; Pippal–Sati 2026 | memory-state basin/nonhyperbolic/attractor semantics |

---

# I. Final D10 opportunity formulation

D10 remains a serious research-opportunity **family**, but it must not be described as “fractional bifurcation theory is undeveloped.”

The strongest search-qualified formulations are:

### D10-A — Caputo singular-memory bifurcation architecture

> No resolving general theorem was identified that transfers center-manifold/normal-form bifurcation theory to the infinite-dimensional Volterra semiflow generated by canonical finite-terminal Caputo equations with weakly singular power-law memory, in a form that classifies nonhyperbolic attractor changes.

### D10-B — Incommensurate nonhyperbolic reduction

> No resolving general center-manifold/normal-form theory was identified for genuinely incommensurate multi-order Caputo systems at nonhyperbolic equilibria.

### D10-C — Periodic/recurrent dynamics under an operator that admits it

> Exact periodic orbits are excluded in the standard finite-terminal autonomous Caputo setting, while infinite-past/Liouville–Weyl-type formulations can admit them; a complete Floquet/bifurcation stability theory for those periodic solutions remains incomplete.

### D10-D — Double-Allee memory-state threshold bifurcation

> No resolving theorem was identified that separates unchanged algebraic Allee-threshold catastrophe geometry from fractional-memory-induced stability, basin, attractor and transient-threshold changes in a general strong/Double-Allee class.

## Opportunity assessment

- **Intrinsic fractional content:** high for D10-A/B/C/D.
- **Double-Allee proximity:** very high for D10-D; high for D10-A/B.
- **Prior-art density:** substantial; terminology must be disciplined.
- **Risk:** many apparent bifurcation results are classical equilibrium algebra plus Matignon stability crossing.
- **Survey value:** very high because the literature uses “Hopf” inconsistently across incompatible memory conventions.

## Search limitation

This is a theorem-level architecture audit, not an exhaustive bibliography of every model-specific bifurcation paper. Negative findings are restricted to the searched corpus as of 2026-09-28.
