# ROUND-0013 — WEB SEARCH RETURN

**From:** WEB SEARCHER  
**To:** CHIEF RESEARCHER  
**Date:** 2026-09-28  
**Answers:** research/coordination/chief-to-web/ROUND-0013_robust-nonlinear-threshold-order-uncertainty_REQUEST.md  
**Status:** COMPLETE

## RETURN TO CHIEF

### Question investigated

Whether nonlinear positive Caputo systems possess a mature theory of **uncertainty-uniform global threshold dynamics** under simultaneous uncertainty in ecological parameters and fractional order(s), specifically for:

- extinction/survival;
- persistence/permanence;
- common invariant or basin regions;
- threshold robustness;
- multistability preservation;
- bifurcation/tipping under uncertainty;

and whether any apparent gap is already subsumed almost verbatim by classical robust permanence, viability/differential-inclusion, robust region-of-attraction, or structural-stability theory.

The search explicitly separated:

1. linear/local robust stability;
2. nonlinear open-loop equilibrium stability;
3. global ecological threshold/persistence statements;
4. controller-dependent robustness.

---

## Executive finding

The candidate **survives**, but only after a major narrowing.

### What is already mature or heavily populated

1. **Linear robust fractional stability is mature.**  
   Direct prior covers:
   - coefficient uncertainty;
   - structured perturbations;
   - uncertain fractional order;
   - simultaneous order + parameter uncertainty;
   - incommensurate orders;
   - time-varying interval uncertainty;
   - mixed parametric/norm-bounded uncertainty;
   - exact, necessary-and-sufficient, or non-conservative bounds in important subclasses.

2. **Nonlinear open-loop robust stability exists for important classes.**  
   There are rigorous global robust Mittag-Leffler/asymptotic stability theorems for uncertain fractional neural-network and interval nonlinear systems. These are usually sufficient Lyapunov/LMI/Razumikhin certificates for convergence to one equilibrium, not general extinction/survival or multibasin theorems.

3. **Fractional viability is direct prior.**  
   Caputo viability and fractional differential-inclusion viability have their own Nagumo-type results. Crucially, the literature shows that classical viability does **not** transfer blindly: the memory domain and initialization matter.

4. **Classical robust permanence and robust ROA are mature.**  
   Schreiber, Garay–Hofbauer, Hofbauer–Schreiber, Patel–Schreiber and robust-ROA literature give strong perturbation-uniform results for ordinary flows/semiflows, invariant measures, Morse decompositions, feedback systems, and polynomial uncertain systems.

### What was not found

No searched source gives a theorem for an autonomous uncontrolled positive Caputo family

\[
{}^C D^{\alpha}x=f(x;\theta),
\qquad
(\alpha,\theta)\in\mathcal A\times\Theta,
\]

or a genuinely incommensurate family

\[
{}^C D^{\alpha_i}x_i=f_i(x;\theta),
\qquad
\boldsymbol\alpha\in\mathcal A,
\]

that simultaneously provides an **uncertainty-uniform global ecological conclusion** such as:

- a common survival region valid for every admissible \((\boldsymbol\alpha,\theta)\);
- a common extinction region;
- robust persistence relative to the survival basin;
- a uniform positive distance from extinction after transients for all admissible models;
- a uniform enclosure of the extinction/survival basin separator;
- preservation/loss of bistability across the uncertainty family;
- exact or sharp threshold bounds combining parameter and order uncertainty.

This is stronger than ordinary robust equilibrium stability.

### Main classification

The broad claim “robust fractional dynamics is unexplored” is false.

The residual candidate is:

> **uncertainty-uniform global threshold geometry and basin-relative persistence for positive nonlinear Caputo systems under simultaneous parameter and fractional-order uncertainty, especially strong/Double-Allee systems and incommensurate multi-species models.**

No result resolving that object was identified in the searched corpus as of 2026-09-28.

---

# 1. Linear / order-uncertainty baseline

## Senol et al. 2014

Bilal Senol, Abdullah Ates, B. Baykant Alagoz, Celaleddin Yeroglu,  
*A numerical investigation for robust stability of fractional-order uncertain systems*, ISA Transactions 53(2):189–198, DOI 10.1016/j.isatra.2013.09.004.

Directly treats uncertainty in both characteristic coefficients and fractional orders.

**Strength:** numerical robust-stability procedure, not the strongest exact result.

## Yang & Hou 2019

Jing Yang and Xiaorong Hou,  
*Robust bounds for fractional-order systems with uncertain order and structured perturbations via Cylindrical Algebraic Decomposition method*, Journal of the Franklin Institute 356(7):4097–4105, DOI 10.1016/j.jfranklin.2018.12.024.

For

\[
D^\alpha x=A(\beta)x,
\]

with uncertain order \(0<\alpha<2\) and structured parameter vector \(\beta\), the paper constructs parameter-space robust bounds using cylindrical algebraic decomposition. The method is presented as non-conservative for the stated class and explicitly resolves the coupled order/parameter robust-stability region.

This is a major killer of any claim that simultaneous parameter + order uncertainty is itself novel.

## Tavazoei & Asemani 2020

*On robust stability of incommensurate fractional-order systems*, CNSNS 90:105344, DOI 10.1016/j.cnsns.2020.105344.

Generalized-Nyquist-based robust stability for incommensurate pseudo-state-space systems and multiple uncertainty structures.

Related 2020 Journal of the Franklin Institute paper, DOI 10.1016/j.jfranklin.2020.09.044, treats incommensurate systems with time-varying interval uncertainties using generalized small-gain and M-matrix machinery.

## Zhang & Lu 2023

*Robust stability of fractional-order systems with mixed uncertainties: The 0<alpha<1 case*, CNSNS 126:107511, DOI 10.1016/j.cnsns.2023.107511.

Mixed multi-parameter and norm-bounded uncertainty with robust-stability conditions and computable robust bounds.

### Verdict 1 — linear/order-uncertainty baseline

**DIRECT PRIOR.**

This branch is mature enough that a new project cannot be motivated by uncertain \(\alpha\), mixed uncertainty, or incommensurate robust linear stability alone.

---

# 2. Nonlinear open-loop robust stability

The nonlinear literature is not empty and is not confined to feedback control.

## Song–Wu–Wang 2017

*Lur’e-Postnikov Lyapunov function approach to global robust Mittag-Leffler stability of fractional-order neural networks*, DOI 10.1186/s13662-017-1298-8.

Provides global robust Mittag-Leffler stability analysis for fractional neural networks with parameter uncertainty.

## Interval nonlinear systems with delay

*Robust asymptotic stability of interval fractional-order nonlinear systems with time-delay*, Journal of the Franklin Institute 355 (2018), DOI 10.1016/j.jfranklin.2018.08.017.

Uses fractional Lyapunov/Razumikhin machinery to give a delay-independent LMI sufficient criterion for global asymptotic stability of a class of interval fractional nonlinear systems.

## Scope warning

The 2025 review by Zhang–Lu–Zhu, DOI 10.1007/s11071-025-11497-2, confirms that robust stability, stabilization, performance and nonlinear robust control form a substantial literature.

But much of that literature is:
- controller-dependent;
- synchronization-oriented;
- equilibrium-centric;
- certificate-based.

It is not automatically a theorem about uncontrolled ecological multistability or extinction/survival basins.

### Verdict 2 — nonlinear open-loop robust stability

**SUBSTANTIAL PARTIAL THEORY.**

Global robust convergence theorems exist for important nonlinear classes, but no general open-loop ecological threshold framework was found.

---

# 3. Uniformity in fractional order

The search found strong linear results explicitly quantifying over order intervals and coupled order/parameter regions.

For nonlinear systems, most global Lyapunov/Mittag-Leffler results inspected fix the order or provide inequalities valid for a specified order regime; they do not formulate the ecological property as

\[
\forall \alpha\in[\alpha_-,\alpha_+]:
\quad
P(\alpha)
\]

for \(P\) equal to survival, extinction, basin inclusion or persistence.

The distinction is important:

- a Lyapunov inequality whose algebraic form is valid for all \(0<\alpha<1\) may yield a common sufficient equilibrium-stability certificate;
- this does not characterize common extinction/survival basins or guarantee robust persistence across the family.

### Verdict 3 — uniform-in-order nonlinear theory

**NO RESOLVING RESULT FOUND.**

There is substantial nearby stability theory, but no general uncertainty-uniform global threshold/persistence theorem was identified.

---

# 4. Classical robust permanence baseline

## Schreiber 2000

*Criteria for C^r Robust Permanence*, JDE 162:400–426, DOI 10.1006/jdeq.1999.3719.

For dissipative ecological ODE flows on the positive cone, robust permanence is characterized by invariant-measure / average per-capita-growth conditions, with a Morse-decomposition sufficient criterion.

## Garay & Hofbauer 2003

*Robust Permanence for Ecological Differential Equations, Minimax, and Discretizations*, SIAM JMA 34:1007–1039, DOI 10.1137/S0036141001392815.

Average-Lyapunov/minimax robust permanence framework.

## Hofbauer & Schreiber 2010

*Robust permanence for interacting structured populations*, JDE 248:1955–1971, DOI 10.1016/j.jde.2009.11.010.

Strong invasion-exponent/invariant-measure theory for structured populations.

## Patel & Schreiber 2018

*Robust permanence for ecological equations with internal and external feedbacks*, J Math Biol 77:79–105, DOI 10.1007/s00285-017-1187-5.

Extends robust permanence to systems with internal/external feedbacks using average Lyapunov functions and Morse decompositions, including nonautonomous and structured examples.

### Why this does not kill the fractional candidate verbatim

The classical theory assumes a dynamical-system framework with properties that must be reconstructed carefully after the Caputo lift. More importantly, “perturbing the vector field” in an ODE is not automatically equivalent to perturbing:
- fractional order \(\alpha\);
- a vector of incommensurate orders;
- the power-law memory kernel;
- the reachable memory-state geometry.

ROUND-0012 already established the need to distinguish physical and history state.

Also, **global permanence is structurally mismatched with strong Allee dynamics**: strong Allee systems intentionally contain positive initial states in an extinction basin. The relevant robust object is therefore conditional/basin-relative persistence or a common robust survival region, not permanence of every positive state.

### Verdict 4 — robust fractional permanence/persistence

**NO RESOLVING RESULT FOUND.**

Classical robust permanence is the strongest subsumption threat, but no general Caputo order/parameter-robust counterpart was identified.

---

# 5. Fractional viability / differential-inclusion subsumption

## Girejko–Mozyrska–Wyrwas 2011

*A sufficient condition of viability for fractional differential equations with the Caputo derivative*, JMAA 381:146–154, DOI 10.1016/j.jmaa.2011.04.004.

Gives a sufficient condition for viability of locally closed sets under nonlinear Caputo dynamics; positivity is an example.

## Carja–Donchev–Rafaqat–Ahmed 2014

*Viability of fractional differential inclusions*, Applied Mathematics Letters 38:48–51, DOI 10.1016/j.aml.2014.06.012.

Gives sufficient conditions for viable solutions of Caputo differential inclusions and explicitly corrects earlier formulations.

## Girejko–Mozyrska–Wyrwas 2015

*On memo-viability of fractional equations with the Caputo derivative*, DOI 10.1186/s13662-015-0403-0.

Develops necessary/sufficient viability conditions via initialization in a **memory domain** and explicitly explains why the fractional Nagumo-type necessity is nontrivial.

### Critical distinction

Viability usually means:

> there exists at least one solution/selection that remains in the constraint set.

A robust survival region for an uncertainty family requires the stronger universal property:

> every admissible realization / every relevant uncertain trajectory remains viable and survives.

Thus set-valued viability is important machinery, but it does not automatically give a common robust survival basin.

### Verdict 6 — robust basin / invariant-region theory

**SUBSTANTIAL PARTIAL THEORY.**

Direct fractional viability exists, while classical robust-ROA theory is strong. No searched theorem delivers the required uncertainty-uniform Caputo survival/extinction basin object.

---

# 6. Robust extinction / survival thresholds near Allee dynamics

Direct searches for:
- robust Allee threshold;
- uncertain Allee threshold;
- fractional Allee parameter uncertainty;
- fractional-order uncertainty + persistence/extinction;
- common survival basin;
- interval Double-Allee systems;

did not locate a theorem resolving the requested problem.

## Closest direct fractional ecological uncertainty paper

Narayanamoorthy et al. 2019,  
*Analysis for fractional-order predator–prey model with uncertainty*, IET Systems Biology 13(6):277–289, DOI 10.1049/iet-syb.2019.0055.

Despite the title, the uncertainty treatment is primarily **fuzzy initial conditions** plus numerical fractional-Euler approximation. It does not provide:
- parameter/order-uniform basin theorems;
- robust Allee thresholds;
- common survival/extinction sets.

## Existing fractional Allee literature

The direct Allee papers already catalogued in ROUND-0011 vary fractional orders and compute stability/basins for selected parameter choices. None of the inspected work upgrades this to a guarantee holding for all \((\alpha,\theta)\) in an uncertainty set.

### Parameter versus order uncertainty

If the right-hand side \(f(x;\theta)\) is fixed, changing \(\alpha\) alone does not move equilibrium locations: equilibria still solve

\[
f(x;\theta)=0.
\]

Order uncertainty can change:
- local stability sectors;
- transient memory;
- multidimensional basin geometry.

Parameter uncertainty in \(\theta\) can also change:
- equilibrium locations;
- number of equilibria;
- fold/cusp geometry;
- bistability versus monostability.

Thus the genuinely strong robust-threshold question is the combined family.

### Verdict 5 — robust extinction/survival thresholds

**NO RESOLVING RESULT FOUND.**

---

# 7. Robust basin / region-of-attraction baseline outside fractional systems

Topcu–Packard–Seiler–Balas 2010, DOI 10.1109/TAC.2009.2033751, computes invariant subsets of robust regions of attraction for polynomial nonlinear systems with bounded parameter uncertainty using parameter-independent Lyapunov functions.

Later uncertain-ROA literature extends this to uncertainty-dependent equilibria and robust invariant-set formulations.

This is strong adjacent prior art and means that:

> “common region of attraction under parametric uncertainty”

is not itself a new mathematical concept.

The fractional novelty burden is:
- memory-state dynamics;
- fractional-order uncertainty;
- extinction-boundary/persistence structure;
- strong-Allee multibasin geometry;
- preferably sharp rather than purely conservative inner approximations.

---

# 8. Uncertain bifurcation / catastrophe

Yang–Hou–Li–Luo 2022,  
*A parameter space method for analyzing Hopf bifurcation of fractional-order nonlinear systems with multiple-parameter*, Chaos, Solitons & Fractals 155:111714, DOI 10.1016/j.chaos.2021.111714.

Uses cylindrical algebraic decomposition to obtain stable parameter regions and critical hypersurfaces in a multiparameter nonlinear fractional system.

This establishes substantial prior art for parameter-space stability/bifurcation boundaries.

However:
- it is local/Jacobian-based;
- it is not an uncertainty-uniform global survival/extinction basin theorem;
- the project must retain the periodicity/Hopf semantic cautions from ROUND-0010 for finite-terminal Caputo systems.

Classical uncertain/robust bifurcation and robust ROA theory also contain parameter-set descriptions of saddle-node or attraction regions.

### Verdict 7 — uncertain bifurcation/catastrophe

**SUBSTANTIAL PARTIAL THEORY.**

The general idea is not novel; robust global threshold-set theory for Caputo Allee families was not found.

---

# 9. Incommensurate order uncertainty

Linear incommensurate robust stability is direct prior:
- Tavazoei–Asemani 2020;
- interval/time-varying uncertainty extensions;
- related parameter-space and robust-bound literature.

What was not identified:
- a general nonlinear positive-system theorem;
- a common persistence/extinction region over a box
  \[
  \boldsymbol\alpha\in
  [\alpha_1^-,\alpha_1^+]\times\cdots\times
  [\alpha_n^-,\alpha_n^+];
  \]
- an uncertainty-uniform Double-Allee basin theorem.

### Verdict 8 — incommensurate order uncertainty

**SUBSTANTIAL PARTIAL THEORY.**

Linear/local theory is strong; nonlinear global ecological theory remains thin.

---

# 10. Fractional-order estimation makes order uncertainty scientifically real

Nazarian–Haeri–Tavazoei 2010, DOI 10.1016/j.isatra.2009.11.007, shows that fractional-order model and parameter identifiability can degrade markedly at smaller \(\alpha\), and measurement noise worsens practical distinguishability.

Therefore an interval or posterior uncertainty for \(\alpha\) is not merely artificial robust-control notation.

For ecological applications, the scientifically stronger question is:

> can extinction/survival conclusions remain valid over the uncertainty set generated by order estimation?

No searched Double-Allee paper provided such an uncertainty-propagation theorem.

---

# 11. Classical-theory subsumption audit

Three mature adjacent theories threaten novelty:

1. **robust permanence / invasion rates;**
2. **viability / differential inclusions;**
3. **robust region of attraction / invariant sets.**

None was found to kill the candidate almost verbatim.

Reasons:

- Caputo dynamics requires memory-aware state construction;
- fractional viability itself required modified memory-domain tangency theory;
- viability is existential, while uncertainty-robust survival is universal;
- order/kernel perturbations are not ordinary finite-dimensional vector-field perturbations;
- strong Allee requires basin-relative persistence rather than global permanence;
- incommensurate order vectors change the memory architecture.

### Verdict 10 — classical-theory subsumption

**CLOSE PRIOR ART.**

A future theorem should explicitly build on these theories; it cannot present robust invariance or robust permanence as new ideas. But a direct routine transfer was not identified.

---

# 12. Required verdict summary

| Item | Verdict | Reason |
|---|---|---|
| 1. linear/order-uncertainty baseline | **DIRECT PRIOR** | mature robust bounds, uncertain order, mixed and incommensurate uncertainty |
| 2. nonlinear open-loop robust stability | **SUBSTANTIAL PARTIAL THEORY** | global robust ML/asymptotic stability exists for specific nonlinear classes |
| 3. uniform-in-order nonlinear theory | **NO RESOLVING RESULT FOUND** | no general global survival/persistence/basin theorem uniform in order interval located |
| 4. robust fractional permanence/persistence | **NO RESOLVING RESULT FOUND** | classical robust permanence mature; general Caputo/order-robust analogue not found |
| 5. robust extinction/survival thresholds | **NO RESOLVING RESULT FOUND** | no rigorous common Allee survival/extinction threshold theory located |
| 6. robust basin/invariant-region theory | **SUBSTANTIAL PARTIAL THEORY** | Caputo viability + classical robust ROA, but not the target global family theorem |
| 7. uncertain bifurcation/catastrophe | **SUBSTANTIAL PARTIAL THEORY** | parameter-space fractional bifurcation and classical robust bifurcation exist |
| 8. incommensurate order uncertainty | **SUBSTANTIAL PARTIAL THEORY** | strong linear theory; nonlinear global ecology unresolved |
| 9. Double-Allee-specific prior art | **NO RESOLVING RESULT FOUND** | model-specific basin/order studies exist, no uncertainty-uniform theorem |
| 10. classical-theory subsumption | **CLOSE PRIOR ART** | strong building blocks, but no verbatim transfer found |

---

## Foundational sources

- Schreiber 2000 — C^r robust permanence.
- Garay & Hofbauer 2003 — robust permanence/minimax/discretization.
- Hofbauer & Schreiber 2010 — structured-population robust permanence.
- Patel & Schreiber 2018 — robust permanence with internal/external feedbacks.
- Girejko et al. 2011/2015 — Caputo viability and memory-domain viability.
- Carja et al. 2014 — Caputo fractional differential inclusions.
- Topcu et al. 2010 — robust region-of-attraction estimation.

## Strongest-known results

- non-conservative/exact robust bounds for important linear uncertain-order classes;
- robust incommensurate linear stability;
- global robust Mittag-Leffler stability in class-specific nonlinear fractional systems;
- fractional viability and inclusion theory;
- classical invariant-measure/Morse robust permanence;
- robust ROA inner approximations under parameter uncertainty.

## Recent frontier sources

- Zhang–Lu–Zhu 2025 robust fractional-control review, DOI 10.1007/s11071-025-11497-2;
- current robust-ROA work with uncertainty-dependent equilibria;
- 2025–2026 fractional ecology and bifurcation literature already recorded in prior rounds.

## Explicit open problems

No source inspected stated the exact Double-Allee uncertainty-uniform problem verbatim.

The main gap is inferred by crossing:
- mature linear robust fractional stability;
- mature classical robust permanence;
- direct fractional viability;
- thin general fractional persistence theory;
- direct model-specific fractional Allee multistability.

## Inferred gap

A defensible theorem-level formulation is:

> For a specified class of autonomous positive Caputo systems with strong/Double-Allee multistability, characterize conditions under which there exist common uncertainty-robust survival and extinction sets and basin-relative persistence guarantees uniformly for all \((\boldsymbol\alpha,\theta)\in\mathcal A\times\Theta\), including genuinely incommensurate order boxes; determine when bistability and the threshold structure are preserved or destroyed across the uncertainty family.

A sharper formulation should distinguish:
- sufficient common invariant sets;
- exact/maximal robust survival/extinction sets;
- robustness of persistence constants;
- robust basin separator bounds;
- uncertainty-induced crossing of fold/bistability boundaries.

## Closest prior-art threats

1. classical robust permanence/invasion theory;
2. Caputo memo-viability and fractional inclusions;
3. robust ROA/invariant-set theory for uncertain nonlinear ODEs;
4. global robust ML stability for uncertain nonlinear fractional systems;
5. parameter-space fractional bifurcation;
6. linear uncertain-order/incommensurate robust stability.

## Evidence against candidate novelty

The following cannot support novelty:

- uncertain fractional order by itself;
- simultaneous order + parameter uncertainty in linear systems;
- incommensurate robust linear stability;
- robust equilibrium stability via Lyapunov/LMI certificates;
- generic viability of Caputo systems;
- generic robust region-of-attraction terminology;
- generic multiparameter fractional bifurcation diagrams.

## Double Allee relevance

This frontier is naturally close to Double Allee because:
- parameter uncertainty can move/create/destroy strong-Allee thresholds;
- order uncertainty can alter stability and memory-dependent basin geometry even when equilibria are fixed;
- strong Allee requires survival guarantees conditional on the correct basin rather than global permanence;
- multi-species Double Allee naturally motivates incommensurate order boxes.

The ecological connection is structural, not decorative.

## Remaining uncertainty

1. Whether an abstract robust-persistence theorem for general **semiflows** can be applied to the Doan–Kloeden Caputo lift with less additional work than the searched sources suggest.
2. Whether a fractional differential-inclusion **strong invariance** theorem already supplies universal-in-uncertainty survival sets for the canonical Caputo kernel.
3. Whether specialized interval ecological/FDE literature contains rigorous threshold enclosures under different terminology.
4. How best to parameterize uncertainty in the memory operator for genuinely incommensurate systems.
5. Whether exact/maximal robust basin sets are computable beyond conservative Lyapunov/viability certificates.

## Files updated

- research/coordination/web-to-chief/ROUND-0013_robust-nonlinear-threshold-order-uncertainty_RETURN.md
- research/web-search/2026-09-28_robust-nonlinear-threshold-order-uncertainty.md
- research/web-search/SEARCH_LOG.md
- research/web-search/QUERY_REGISTRY.md
- research/web-search/SOURCE_REGISTRY.md
- research/web-search/NOVELTY_CHECKS.md
- corpus/papers.csv
- corpus/theorems.csv
- bibliography/references.bib

## Recommended next mapping/search wave

If the Chief retains this frontier, the highest-information follow-up is a **subsumption-only** audit around:

1. strong invariance vs viability for Caputo differential inclusions;
2. robust persistence theorems for infinite-dimensional **semiflows** rather than invertible flows;
3. common Lyapunov/persistence functions uniform in \(\alpha\);
4. robust basin-relative persistence for bistable positive systems;
5. incommensurate history-state lifts under order boxes.

Do not move into proving such a theorem in this project.

---

## Searcher's bottom line

The uncertainty frontier is materially stronger than a generic robust-control topic but must be stated narrowly.

\[
\boxed{
\text{No general uncertainty-uniform theorem was identified for}
\;
\text{survival/extinction regions + basin-relative persistence}
\;
\text{of positive nonlinear Caputo systems}
}
\]

under simultaneous parameter and fractional-order uncertainty.

Linear robust stability, uncertain order, fractional viability, nonlinear robust equilibrium stability, robust ROA and classical robust permanence all have substantial prior art.

The residual frontier is the **bridge among them**, especially for strong/Double-Allee multistability and incommensurate memory.
