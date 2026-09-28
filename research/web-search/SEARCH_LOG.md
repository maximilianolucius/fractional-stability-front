# Web Search Log

**Role:** WEB SEARCHER  
**Project:** Fractional Stability Front  
**Initialized:** 2026-09-28

This log records reproducible search activity. Negative searches are evidence about the searched corpus, not proof of absence.

## 2026-09-28 — ROUND-0001 fractional-stability seed

**Research question.** Establish the exact finite-dimensional linear fractional stability core, distinguish commensurate/incommensurate results, and try to falsify the hypothesis that positive diagonal scaling relative to a fractional stability sector is an open bridge.

**Sources searched.**
- primary publisher/journal pages;
- Crossref/DOI-indexed metadata surfaced through web search;
- PubMed where applicable;
- arXiv and legal author/preprint copies;
- citation and author-follow-up searches;
- proceedings metadata for conference papers.

**Representative exact queries.**
- `fractional order linear system necessary sufficient stability Matignon`
- `Matignon stability theorem generalized fractional differential systems 1998`
- `Caputo Matignon theorem boundary eigenvalues index stability`
- `incommensurate fractional system exact stability criterion`
- `non-commensurate fractional order systems necessary sufficient stability Sabatier`
- `fractional sector stable matrix diagonal scaling`
- `fractional D-stability matrix`
- `D-stable matrices sector stability positive diagonal scaling`
- `generalized D-stability conic sector LMI region diagonal scaling`
- `diagonal stability fractional positive linear systems`
- `robust fractional interval system necessary sufficient correction quadratic stability`
- `2026 fractional LTI exact LMI stability necessary sufficient`

**Notable positive results.**
1. Matignon's exact commensurate sector criterion was recovered from the original publication/author copy and later clarification literature.
2. Brandibur–Garrappa–Kaslik (2021) clarifies the Caputo state-space theorem, including boundary stability and the eigenvalue-index condition.
3. Sabatier–Farges–Trigeassou (2013) gives a necessary-and-sufficient BIBO stability test for non-commensurate systems.
4. Kushel–Pavani (2022) directly studies multiplicative generalized D-stability in unbounded LMI regions, including conic sectors and positive diagonal left scaling.
5. Kushel–Pavani (2021) develops generalized diagonal dominance for LMI regions and explicitly connects conic-region results to fractional-order stability.
6. Zhang–Huang (2017) gives a necessary-and-sufficient criterion for their extension of diagonal stability in continuous-time fractional positive systems.
7. Recent 2026 LTI fractional papers continue to develop exact/equivalent LMI formulations, indicating that the unstructured finite-dimensional LTI core is mature rather than an open novelty target.
8. The 2008 interval-system “necessary and sufficient robust stability” claim has a later clarification (2014) narrowing the exact interpretation to quadratic stability; this is retained as a warning against over-promoting robust LMI claims.

**Negative/falsification searches.**
- Searches for a general finite, quantifier-free characterization of multiplicative conic-sector D-stability did not identify one in the seed corpus. This is not an absence proof; Kushel–Pavani already give exact criteria that remain universal in the positive diagonal scaling parameter.
- Searches using the exact phrase “fractional D-stability” are terminology-sensitive because some control papers use “D-stability” to mean pole placement in a region D rather than classical multiplicative D-stability.
- No claim that the sector-scaling bridge is unstudied survives this round.

**Citation expansion.**
Backward/forward and same-author follow-up searches were used around Matignon, Sabatier, Kushel/Pavani, Zhang/Huang, and interval-uncertainty papers. Exact citation counts were not recorded because they are not needed for theorem verification.

**Round-specific note:** `research/web-search/2026-09-28_fractional-stability-seed.md`

---

## 2026-09-28 — ROUND-0002 Double/Multiple Allee terminology seed

**Research question.** Reconcile competing meanings of Double/Multiple Allee effects, identify theorem-level analytical prior art, and check fractional, spatial/network, and mathematically equivalent two-threshold formulations.

**Sources searched.**
- primary ecology and mathematical-biology journal pages;
- PubMed for foundational biological terminology;
- publisher pages for mathematical models;
- arXiv/legal author copies where available;
- citation/author follow-ups around foundational terminology and analytical models.

**Representative exact queries.**
- `"double Allee effect" mathematical model`
- `"multiple Allee effects" component demographic`
- `Allee effect component demographic strong weak definition`
- `"two threshold" population dynamics Allee`
- `Allee saddle-node fold hysteresis multiple threshold`
- `double Allee predator prey bifurcation limit cycles`
- `double Allee fractional Caputo`
- `double Allee incommensurate fractional`
- `double Allee discrete fractional`
- `double Allee reaction diffusion spatial`
- `Allee metapopulation network topology threshold dispersal`
- `multiple Allee effects empirical data mate limitation pollination`
- `Allee parameter estimation identifiability inverse problem`

**Notable positive results.**
1. Foundational ecology distinguishes component versus demographic Allee effects and weak versus strong demographic consequences.
2. Berec–Angulo–Courchamp (2007) uses “multiple Allee effects” for simultaneous component mechanisms; it does not imply two demographic thresholds.
3. Mathematical “double Allee” papers use several non-equivalent model structures. In a common predator–prey form, the prey growth contains both a strong-threshold factor and a low-density saturating factor; this is not equivalent to two positive demographic critical densities.
4. Direct fractional Double Allee prior art exists from at least 2021 (Caputo), with later local/global analyses, incommensurate-order work, and a 2026 discrete fractional model.
5. Direct spatial reaction–diffusion Double Allee prior art exists.
6. Strong Allee metapopulation/network theory already contains analytical topology-dependent persistence/extinction results even when it does not use “Double Allee”.
7. Direct empirical Double-Allee evidence exists: Angulo et al. (2007) analyzed island-fox demographic data from 1988–2000 and found simultaneous component effects on survival and breeding-female proportion leading to a demographic effect; they reported suboptimal growth below roughly 7 foxes/km^2. This is a strong real-data lead, but it does not estimate fractional memory or establish two demographic thresholds.
8. Despite that empirical result, the searched seed corpus did not identify a real-data-calibrated fractional Double-Allee model that jointly establishes multi-threshold/fractional-memory identifiability.

**Negative/falsification searches.**
- The candidate claim “Double Allee + fractional memory is new” is falsified.
- The candidate claim “Double Allee + spatial diffusion is new” is falsified.
- No general graph-theoretic theorem for Double-Allee topology-dependent thresholds was identified in the seed corpus, but adjacent single-Allee metapopulation/network results are strong novelty threats.
- No theorem-level general identifiability result jointly separating multiple Allee thresholds and fractional memory was identified in the seed corpus; a dedicated inverse-problem/data round is required before treating this as a gap.

**Island fox empirical follow-up.** Exact-title and author searches verified Angulo et al., Conservation Biology 21(4):1082–1091, DOI 10.1111/j.1523-1739.2007.00721.x, including the 1988–2000 observation window and component/demographic findings.

**Round-specific note:** `research/web-search/2026-09-28_double-allee-terminology-seed.md`

---

## Provenance discipline

For each source used in a theorem or novelty statement, prefer the original publication or an author manuscript. Abstract-only sources are marked as such in the source registry and should not be promoted to exact theorem evidence without further verification.

---

## 2026-09-28 — ROUND-0003 structured conic D-stability

**Question.** Are finite exact structure-sensitive conic-sector multiplicative D-stability criteria already known?

**Sources searched.** Publisher archives (Elsevier/SIAM/IEEE), NIST historical publications, matrix-analysis reviews, ecological stability reviews, institutional copies.

**Historical/classical passes included:**
- `D-stable matrix necessary sufficient characterization`
- `second third fourth order D-stability`
- `tridiagonal D-stable matrices characterization`
- `acyclic D-stable matrices`
- `D-stability NP-hard structured singular value`
- `Metzler D-stability diagonal stability Hurwitz`
- `qualitative sign D-stability graph`
- `ecological community matrix D-stability`
- `conic sector relative D-stability acyclic tridiagonal Metzler`

**Decisive results.**
- Johnson 1974: explicit low-dimensional conditions (2–4).
- Carlson–Datta–Johnson 1982: exact tridiagonal D-stability.
- Berman–Hershkowitz 1984: exact acyclic D-stability.
- Chen–Fan–Yu 1995: real-structured-singular-value iff formulation; general checking may be NP-hard.
- Narendra–Shorten 2009: strong Metzler Hurwitz/diagonal-stability structure.
- Complete qualitative/sign stability graph theory predates the current project.

**Negative search.** No finite exact conic-sector analogue for a nontrivial cyclic/non-Metzler ecological/sign class was identified.

**Classification.** F-002 = **OPEN ONLY FOR A SHARPLY SPECIFIED SUBCLASS**.

**Dated note:** `research/web-search/2026-09-28_conic-d-stability-structured.md`.

---

## 2026-09-28 — ROUND-0004 double dormancy + network falsification

**Question.** Is a general double-dormancy composition theorem or network transformation theorem already subsumed by adjacent theory?

**Query families included:**
- `double dormancy Allee mathematical model`
- `two component Allee effects threshold theorem`
- `emergent Allee threshold weak component effects`
- `stage specific predation emergent Allee`
- `component Allee demographic aggregation`
- `bistable network persistence extinction graph`
- `source sink dynamics network bistable`
- `graph Laplacian Allee threshold`
- `metapopulation rescue Allee threshold`

**Decisive results.**
- Berec 2007 already gives a concrete two-component model and partial analytical threshold logic for double dormancy.
- Lan 2025 directly studies a stochastic single-species system with two component Allee effects and rigorous threshold dynamics.
- de Roos et al. 2003 / van Kooten et al. 2005 prove emergent-Allee conditions under stage/trophic mechanisms.
- Jorge–Martinez-Garcia 2024 structurally links a component effect to a demographic effect through aggregation.
- Stehlík–Švígler–Volek 2023 gives arbitrary-connected-graph persistence/extinction thresholds for heterogeneous logistic/bistable local dynamics.

**Classifications.**
- C-DA-1: **PARTIAL/CLOSE PRIOR ART; survives only as a sharp component-function composition theorem.**
- C-DA-2: **CLOSE PRIOR ART; generic graph persistence/extinction route is largely covered.**

**Dated note:** `research/web-search/2026-09-28_double-dormancy-network-falsification.md`.

---

## 2026-09-28 — ROUND-0005 data + identifiability

**Question.** Can real data support component/threshold/memory identification, and is the island-fox dataset openly reusable?

**Island fox trace.** Exact-title/DOI/author searches plus Dryad/Zenodo/Figshare/OSF/NPS/IRMA searches found monitoring documentation and reports but **no open machine-readable copy of the exact 1988–2000 Angulo dataset**.

**Alternative data search.**
- Atlantic herring: open supplementary XLS; nine stocks.
- Northwest Atlantic cod: open Dryad CC0 dataset.
- Freshwater mussel fertilization: open Dryad individual/component data.
- Spongy moth: real release–recapture mechanism experiment; raw repository not verified.
- Crested Ibis: empirical survival + reproduction component effects; raw repository not verified.

**Identifiability search.**
- ecological Allee model discrimination/data deletion;
- structural identifiability for fractional models;
- fractional network structural identifiability;
- integer/fractional/time-delay model comparison;
- simultaneous fractional-order + delay identification under colored/measurement noise.

**Key result.** The literature does not justify claiming fractional order and delay/noise are intrinsically inseparable; controlled identification can estimate them jointly. The problem for this project is observational design: passive field data have weak excitation and strong latent/intervention confounding.

**Classification.** C-DA-3 = **WEAKENED, NOT KILLED**. Component/threshold identifiability remains credible; fractional memory is not currently supported as the empirical core.

**Dated note:** `research/web-search/2026-09-28_double-allee-data-identifiability.md`.

---

## 2026-09-28 — ROUND-0006 — mechanism-resolved final novelty gate

**Question.** Does prior theory subsume the frozen program combining mechanism-resolved threshold composition with hidden-factor identifiability and minimal observation design?

**Forward search families.**
- `survival fecundity product threshold population theorem`
- `density dependent survival fecundity Allee threshold`
- `multiple component Allee effects exact threshold`
- `double dormancy theorem Allee`
- `two weak Allee effects strong threshold`
- `synergistic Allee effects survival reproduction`
- `multiple life stage density regulation equilibria`
- `demographic compensation survival fecundity Allee`
- `fitness component product density dependence`
- exact DOI/citation chase for Pavlová–Berec–Boukal 2010 and Berec et al. 2007.

**Inverse/identifiability search families.**
- `factorized nonlinear model structural identifiability`
- `product identifiable combinations structural identifiability`
- `gauge symmetry structural identifiability ODE`
- `Lie symmetry parameter nonidentifiability biological model`
- `minimal outputs structural identifiability nonlinear systems`
- `integrated population model survival reproduction identifiability`
- `abundance only survival fecundity identifiability`
- `nonparametric product unknown functions identifiability`
- `network structural identifiability hidden local parameters`
- `fractional model symmetry identifiability`

**Citation expansion.**
Backward/forward and related-method searches were run from:
- Yates–Evans–Chappell 2009;
- Meshkat–Anderson–DiStefano 2011;
- Joubert–Stigter–Molenaar 2018;
- structural-identifiability symmetry reviews;
- integrated population model literature;
- Berec 2007 and direct component-effect follow-ups.

**Decisive findings.**
1. Multiple survival/fecundity density-regulation and explicit multiplicative demographic decomposition predate the project.
2. No searched source gives the frozen general component-deletion double-dormancy theorem across a reusable function class.
3. The proposed gauge is an output-preserving symmetry and therefore falls under established structural-identifiability theory.
4. Minimal output selection is an established structural-identifiability problem.
5. Network/fixed-fractional preservation of an exactly unchanged RHS is a direct corollary rather than independent novelty.
6. The frozen forward unimodality/fold and implicit-comparative-statics lemmas are standard calculus/bifurcation tools.

**Round verdict.**
The integrated program survives only with **forward mechanism-resolved composition** as the novelty core, and only if strengthened beyond assuming the product is unimodal.

**Dated note:** `research/web-search/2026-09-28_mechanism-resolved-final-novelty.md`.

---

## 2026-09-28 — ROUND-0007 — mechanism-space geometry falsification

**Question.** Are THM-P2/P3/P4/P5 already standard under convex viability, threshold-game, reliability, epidemiological-intervention or tipping terminology?

**Query families.**
- `semi infinite programming intersection halfspaces convex feasible set`
- `population persistence region convex parameter space`
- `extinction region intervention vector convex`
- `effective reproduction number convex vaccination strategy`
- `optimal rays vaccination strategy`
- `minimal winning coalition weighted threshold game`
- `minimal cut sets coherent reliability system`
- `Sperner antichain minimal winning coalitions`
- `intersection upset downset order convex poset`
- `Danskin theorem max value gradient unique maximizer`
- `ecological tipping surface parameter sensitivity envelope theorem`
- `log concavity survival fecundity density dependent product`

**Decisive results.**
1. P2 convexity and half-space representation are generic convex/semi-infinite-programming facts.
2. Vector intervention/persistence geometry already appears in mathematical epidemiology through effective reproduction-number optimization.
3. P3 is a ray restriction of P2; no exact two-boundary multiple-Allee analogue was found.
4. The low-density part of P4 is exactly weighted-threshold/minimal-winning-coalition mathematics.
5. Minimal winning coalitions/antichains/Sperner structure and reliability minimal-cut-set language are standard.
6. Low-density failure is an upset and persistence is a downset; their intersection is order-convex, so chain-contiguity is standard order theory.
7. No searched source classifies the **persistence-filtered** weighted coalitions defined by simultaneous (F_S(0)<0<M_S).
8. P5 is an immediate application of Danskin/envelope theory.

**Round verdict.**
No killer source for the full ecological package. P2/P3 are mathematically standard but the low-density-vs-global-persistence synthesis is distinct; P4 survives only in the persistence-filtered part; P5 is standard.

**Dated note:** `research/web-search/2026-09-28_mechanism-space-geometry.md`.

---

## 2026-09-28 — ROUND-0008 — full-domain architecture

**Mission.** Breadth-first theorem-level audit of Dynamical Systems and Stability Theory — Fractional Differential Equations across fifteen branches.

**Search architecture.**
Searches were deliberately spread beyond the existing Double-Allee vocabulary and included:
- commensurate/incommensurate spectral stability;
- multi-term fractional equations;
- nonlinear linearization and instability;
- converse Lyapunov / Mittag-Leffler / ISS;
- D-stability / positive / descriptor / robust uncertainty;
- interval uncertainty in both coefficients and orders;
- mixed parameter + norm-bounded uncertainty;
- delay-independent versus delay-dependent stability;
- neutral/multi-Caputo functional equations;
- switched/singular/impulsive/hybrid fractional stability;
- heterogeneous multi-agent consensus and signed graphs;
- periodic-orbit nonexistence and fractional bifurcation;
- abstract permanence/uniform persistence;
- variable-order and distributed-order Lyapunov theory;
- structural identifiability/inverse problems;
- time-fractional reaction–diffusion and Turing instability.

**Most consequential positive findings.**
1. Diethelm et al. 2024: modern constructive general incommensurate stability + nonlinear linearization.
2. Gallegos–Duarte-Mermoud 2019 and Guo et al. 2025: converse fractional Lyapunov theory is substantive.
3. Zhang–Lu 2023: N&S mixed-uncertainty robust linear stability.
4. Zhang–Jin–Lu–Zhu 2025: N&S delay-independent fractional time-delay stability.
5. Tavazoei–Haeri 2009 versus Doan–Kloeden 2022: rigorous periodicity/bifurcation theory is conceptually nontrivial.
6. Fonda–Gidoni 2015 supplies an abstract local-dynamical-system permanence benchmark; no comparably general fractional persistence theorem was identified in the breadth search.
7. Lenka 2025 and Wu–Pu–Yang 2026 show variable/distributed-order stability theory is rapidly evolving.
8. Ahmad–Cygan–Karch 2025 preprint advances abstract fractional reaction-diffusion linearization/Turing theory.

**Scoped negative findings.**
- No unified exact/converse switched/hybrid fractional stability architecture was identified.
- No general fractional permanence theorem comparable in scope to abstract local-dynamical-system persistence theory was identified.
- No general multidimensional fractional bifurcation framework was identified that fully reconciles finite-memory periodicity obstruction with widespread applied Hopf terminology.
- No claim of absence is made; these are depth-round targets.

**Candidate frontier hypotheses surfaced.**
- rigorous fractional bifurcation near threshold systems;
- abstract fractional persistence/permanence;
- nonlinear robust threshold/persistence under uncertain order;
- variable/distributed-order nonlinear stability/persistence/bifurcation;
- exact delay-dependent/neutral nonlinear fractional stability;
- global nonlinear incommensurate stability/persistence.

**Dated report:** `research/web-search/2026-09-28_full-domain-architecture.md`.

---

## 2026-09-28 — ROUND-0009 — fractional uniform-persistence falsification

**Question.** Does an abstract uniform-persistence/permanence theory already exist for positive Caputo/nonlocal systems, or is it subsumed by history-space/hereditary persistence theory?

**Search families.**
- fractional uniform persistence / permanence / boundary repeller / persistence attractor;
- Caputo semiflow / history space / singular Volterra semigroup;
- Caputo skew-product / dissipativity / compact absorbing set / attractor;
- Hale–Waltman persistence in infinite-dimensional systems;
- Thieme nonautonomous persistence/permanence;
- infinite-delay functional differential equation persistence;
- robust permanence / invariant measures / Lyapunov exponents / invasion rates;
- conditional persistence + Allee effect;
- persistence relative to a subset / persistence function / invariant boundary.

**Decisive findings.**
1. Doan–Kloeden 2021 provides a legitimate infinite-dimensional semiflow for autonomous Caputo FDEs via singular Volterra representation on C(R_+,R^d).
2. Cui–Kloeden 2024 provides nonautonomous skew-product/attractor machinery; Cui–Kloeden–Xin 2026 adds a compact absorbing set and attractor.
3. Hale–Waltman 1989 already supplies persistence theory for asymptotically smooth infinite-dimensional C0-semigroups. Thieme 2000 and Faria 2016 show nonautonomous/history/infinite-delay persistence theory is mature.
4. No source was found carrying out the full general Caputo ecological transfer from memory-state positivity/boundary to physical uniform lower bounds.
5. Direct fractional persistence/permanence results exist but are model-specific (Abbas et al. 2016; Lu et al. 2023).
6. Robust permanence/invasion-rate theory is mature for ordinary ecological semiflows but no general fractional-memory analogue was identified.
7. Strong Allee bistability makes unconditional uniform persistence structurally inappropriate; conditional/basin-relative persistence is the natural formulation. Conditional persistence itself already exists in Allee literature.

**Round verdict.**
D11 survives only in narrowed form: positive Caputo persistence on the Volterra memory state with explicit physical-state transfer, robust/invasion extensions, and basin-relative versions for strong-Allee systems.

**Dated report:** research/web-search/2026-09-28_fractional-uniform-persistence-falsification.md.

---

## 2026-09-28 — ROUND-0010 — fractional bifurcation semantics

**Question.** What rigorous bifurcation architecture exists for continuous-time fractional differential systems, and what remains after distinguishing equilibrium bifurcation, stability crossing, attractor change, exact periodicity and history-state recurrence?

**Search blocks.**
- Caputo stable / center-stable / center manifolds;
- fractional center-manifold reduction;
- Lyapunov–Schmidt and normal-form reduction;
- fold / transcritical / pitchfork / cusp / codimension-two;
- exact periodic-solution nonexistence;
- “fractional Hopf” corrections and operator conventions;
- Liouville–Weyl / infinite-past periodic solutions;
- S-asymptotically periodic fractional solutions;
- Volterra center manifolds / local and global Hopf;
- Caputo history-state / singular Volterra semiflow;
- incommensurate center manifold / normal form / bifurcation;
- fractional Double-Allee basin / threshold / bifurcation semantics.

**Decisive findings.**
1. Finite-dimensional Caputo stable, center and center-stable manifold theory exists.
2. Caputo Lyapunov–Schmidt reduction exists; Caputo–Hadamard center-manifold and LS reductions exist.
3. Fold/transcritical/pitchfork equilibrium-bifurcation results exist; equilibrium branch location is still determined by the RHS root equation.
4. Tavazoei–Haeri 2009 excludes nonconstant exact periodic solutions for the finite-terminal autonomous Caputo setting considered, including commensurate and incommensurate systems.
5. Infinite-past/Liouville–Weyl-type formulations can admit exact periodic solutions; rigorous fractional Floquet theory remains incomplete.
6. Classical Volterra equations already have center-manifold/Hopf theory, but inspected kernel hypotheses do not automatically contain the canonical weakly singular, algebraically decaying Caputo kernel.
7. No general incommensurate nonhyperbolic center-manifold/normal-form theorem was identified.
8. Generic fractional Double-Allee bifurcation is crowded; the residual is memory-state basin/attractor/nonhyperbolic semantics rather than recomputation of algebraic folds.

**Round verdict.**
D10 survives as a narrowed opportunity family:
- singular-memory Caputo history-state bifurcation;
- incommensurate nonhyperbolic reduction;
- periodic/Floquet theory under an operator that admits exact periodicity;
- Double-Allee memory-state basin/attractor bifurcation.

**Dated report:** `research/web-search/2026-09-28_fractional-bifurcation-semantics.md`.

---

## 2026-09-28 — ROUND-0011 — Double-Allee basin-memory geometry

**Question.** Which strong/Double-Allee basin properties remain unchanged under Caputo fractionalization, and which genuinely require the memory state?

**Search families.**
- `double Allee basins attraction stable manifold homoclinic limit cycle`
- `scalar Caputo solution separation nonintersection threshold`
- `Caputo comparison principle scalar system 2026`
- `basin attraction Caputo fractional initial conditions`
- `basin stability fractional Allee predator prey`
- `incommensurate fractional Allee basin attraction`
- `Caputo memory state basin stable manifold`
- `Volterra hereditary basin boundary weakly singular kernel`
- `basin stability infinite dimensional delay initial history`
- mandatory DOI/citation searches for Contreras 2018, Ramesh 2025, Mondal 2025, Pippal-Sati 2026 and Wang-Han 2025.

**Decisive findings.**
1. Contreras–Aguirre 2018 gives a mature integer-order Double-Allee basin baseline: thresholds can be stable manifolds, limit cycles or homoclinic objects and rearrange across local/global bifurcations.
2. Scalar Caputo separation/nonintersection closes scalar threshold-shift novelty: an equilibrium trajectory is an uncrossable barrier for distinct solutions.
3. Modern scalar/system comparison theory reinforces order preservation under appropriate assumptions.
4. General multidimensional Caputo physical state is not itself a semiflow; Doan–Kloeden embeds the problem in a function/memory space.
5. Published fractional ecological basin plots generally sample physical initial population vectors and therefore describe a slice of the full memory-state basin.
6. Mondal et al. 2025 and Saha et al. 2026 provide direct commensurate/incommensurate Allee basin numerics, but no rigorous full-memory separatrix theorem was identified.
7. Pippal–Sati's basin-restricted Mittag-Leffler result is a sufficient certificate on a chosen invariant subset, not an exact basin characterization.
8. Classical hereditary/Volterra and fractional stable-manifold theory are strong threats, but no direct theorem was found characterizing the global survival/extinction basin boundary for the canonical singular Caputo kernel.

**Round verdict.**
Scalar route closed. The search-qualified residual is multidimensional memory-state basin/separatrix geometry and transfer to the canonical physical-initial-data slice, especially for incommensurate strong/Double-Allee systems and basin-relative persistence.

**Dated report:** `research/web-search/2026-09-28_allee-basin-memory-geometry.md`.

## 2026-09-28 — ROUND-0012 reachable memory-state subsumption audit

**Question.** Does the surviving Caputo basin-memory candidate remain nontrivial after restricting from the ambient Volterra function space to states physically reachable from standard Caputo IVPs, and is it already subsumed by hereditary/Volterra or Markovian-lift theory?

**Search blocks.**
- Doan–Kloeden transition-state construction and physical embedding;
- Cong–Tuan scalar/triangular nonintersection versus higher-dimensional trajectory intersection;
- recent Caputo attractor regularity and reachable-state interpretation;
- same-present/different-history and same-present/opposite-basin searches;
- bistable fractional memory/tipping/hysteresis;
- classical Volterra topological dynamics and weakly singular kernels;
- equivalent histories/minimal states;
- Caputo history-state dynamic programming;
- infinite-state/diffusive representations and completely monotone-kernel Markovian lifts;
- monotone/cooperative/competitive comparison;
- Double/Multiple-Allee basin relevance.

**Decisive positive findings.**
1. Doan–Kloeden gives the exact infinite-dimensional semigroup and constant physical embedding.
2. Cong–Tuan gives an explicit d>=2 standard Caputo-IVP trajectory intersection. Combined with Doan–Kloeden, this proves noninjectivity of current-state evaluation on the physically reachable memory set; the effect is not an ambient-state artifact.
3. Cui–Kloeden–Xin 2026 gives compact absorbing-set/attractor and Hölder-regularity results for the ambient Caputo Volterra semiflow.
4. Khalighi et al. 2026 is very close prior art for history-dependent bistable landscapes, rollback, delayed collapse/recovery and hysteresis.
5. Miller–Sell, Miller–Feldstein, minimal-state viscoelasticity and Gomoyunov show that enlarged/minimal history-state machinery is mature well beyond ecological fractional terminology.
6. Trigeassou–Maamri confirms that infinite-dimensional Markovian/frequency-distributed realization is established fractional-systems methodology.
7. Scalar/triangular and monotone comparison theory materially restricts subclasses but does not provide a general multidimensional basin-fiber killer.

**Critical negative search.**
No theorem or explicit example was located satisfying all of:
standard autonomous Caputo IVPs + two physically reachable distinct memory states + identical current physical state + different future continuations + convergence to different asymptotic attractors.

This is not an absence proof.

**Round verdict.**
The ambient-artifact objection is falsified, but the broad memory-landscape narrative is substantially prior art. The search-qualified residual is the fiberwise multibasin question for \(e_0:\mathcal R_\alpha\to X_{\rm phys}\), preferably in positive strong/Double-Allee systems.

**Dated report:** research/web-search/2026-09-28_reachable-memory-state-subsumption.md.

## 2026-09-28 — ROUND-0013 robust nonlinear threshold / order-uncertainty audit

**Question.** Is robust nonlinear persistence/extinction and threshold geometry under parameter and fractional-order uncertainty already mature, a routine translation of classical robust dynamics, or a genuine fractional frontier near Double/Multiple Allee?

**Search architecture.**
- uncertain coefficient/order linear robust stability;
- joint parameter + order robust bounds;
- incommensurate and time-varying interval uncertainty;
- mixed uncertainty;
- nonlinear open-loop robust Mittag-Leffler/global stability;
- uniform-in-order nonlinear global conclusions;
- classical C^r robust permanence and invasion/Morse criteria;
- Caputo viability and fractional differential inclusions;
- memo-viability / memory-domain Nagumo conditions;
- robust ROA and invariant-set methods;
- uncertain/multiparameter fractional bifurcation;
- direct fractional ecological uncertainty;
- Double/Multiple-Allee robust threshold searches;
- fractional-order identifiability and scientific order uncertainty.

**Decisive positive findings.**
1. Linear fractional robust stability is mature: uncertain order, structured perturbations, mixed uncertainties and incommensurate cases all have direct prior art.
2. Nonlinear open-loop robust global equilibrium stability is nonempty and substantial in class-specific fractional neural/interval systems.
3. Fractional viability is direct prior, including fractional differential inclusions.
4. Memo-viability literature explicitly demonstrates that classical Nagumo transfer must account for initialization/memory; this argues against a routine inclusion-theory killer.
5. Classical robust permanence is mature and is the strongest ecological subsumption threat.
6. Classical robust ROA under bounded parameter uncertainty is mature; “common robust basin subset” is not intrinsically new.
7. Multiparameter nonlinear fractional stability/critical-hypersurface analysis already exists.
8. Direct fractional predator-prey “uncertainty” prior is mainly fuzzy initial conditions and numerical propagation, not robust threshold theory.

**Critical negative searches.**
No general theorem was identified for an uncontrolled positive Caputo family that yields common survival/extinction regions or basin-relative persistence uniformly over simultaneous parameter and fractional-order uncertainty. No corresponding Double-Allee theorem was found. No general incommensurate nonlinear persistence/extinction theorem over a box of orders was found.

**Subsumption verdict.**
Classical robust permanence, viability and robust ROA provide strong ingredients but were not found to transfer almost verbatim. Fractional viability itself requires memory-aware modifications, and strong Allee dynamics requires conditional/basin-relative persistence rather than global permanence.

**Round verdict.**
D6 survives as a search-qualified frontier only in a narrowed form: uncertainty-uniform global threshold geometry + basin-relative persistence for positive nonlinear Caputo systems, especially strong/Double Allee and incommensurate order families.

**Dated report:** research/web-search/2026-09-28_robust-nonlinear-threshold-order-uncertainty.md.

## 2026-09-28 — ROUND-0014 variable/distributed-order dynamics audit

**Question.** What theorem-level dynamical-systems and stability theory exists when the fractional memory operator itself varies through time/state or an order distribution, and where does the real frontier begin?

**Search architecture.**
- distributed-order operator taxonomy/reviews;
- fixed-DO abstract Volterra/resolvent/subordination theory;
- characteristic-root and BIBO linear DO stability;
- nonlinear DO Lyapunov/asymptotic stability;
- Prabhakar distributed-order stability;
- variable-order Caputo existence, continuation and Ulam-Hyers stability;
- time-varying-order comparison/Lyapunov/Mittag-Leffler theory;
- state-dependent/nonautonomous variable-order equations;
- process/cocycle/semigroup searches;
- global/pullback attractor, absorbing-set and asymptotic-compactness searches;
- center-manifold, normal-form and Lyapunov-Schmidt searches;
- persistence/permanence/extinction searches;
- direct VO/DO ecology and Allee searches;
- distributed-order inverse uniqueness and VO parameter learning;
- distributed-variable-order/state-dependent-distribution searches.

**Decisive findings.**
1. Fixed distributed order is substantially mature at the abstract-evolution, exact-linear and nonlinear-Lyapunov levels.
2. DO LTI systems already have characteristic/root and BIBO necessary/sufficient theory in important classes.
3. Abstract distributed-order equations admit Volterra reformulations, complete-monotonicity, positivity, subordination and resolvent-family machinery.
4. Variable-order foundations have advanced: continuation/global existence, comparison, Lyapunov and time-varying-order Mittag-Leffler stability now exist.
5. State-dependent/nonautonomous variable-order work remains dominated by existence, uniqueness and uniform stability.
6. No broad nonlinear process/cocycle + attractor theory was identified for VO/state-dependent/DVO systems.
7. No broad center-manifold/normal-form/LS theory was identified for VO or continuous DO.
8. Positivity and model-specific ecological/epidemic threshold results exist; no abstract persistence/permanence framework was located.
9. Variable-order predator-prey and distributed-order predator-prey are direct prior, so application-level novelty is weak.
10. DO weight functions can be uniquely identifiable in selected inverse problems; VO parameters can be learned from data. Cross-operator model distinguishability remains unresolved.
11. No direct variable-/distributed-order Double-Allee theorem program was identified, but terminology absence is not enough to establish a high-value gap.

**Round verdict.**
D14 is a real but heterogeneous frontier. Fixed distributed order is no longer a foundational stability gap. The strongest unresolved layer is global nonlinear dynamics for evolving memory laws: process/cocycle structure, dissipativity/attractors, persistence/extinction and nonhyperbolic reduction. Double-Allee proximity is currently moderate-to-low and requires a mechanistic rather than decorative bridge.

**Dated report:** research/web-search/2026-09-28_variable-distributed-order-dynamics.md.
