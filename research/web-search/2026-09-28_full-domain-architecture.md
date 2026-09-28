# 2026-09-28 — Full-Domain Architecture and Coverage Audit

**Round:** ROUND-0008  
**Request:** `research/coordination/chief-to-web/ROUND-0008_full-domain-architecture_REQUEST.md`  
**Mission:** breadth-first theorem-level map of **Dynamical Systems and Stability Theory — Fractional Differential Equations**.  
**Rule:** this report surfaces candidate frontiers; it does not select a final research direction.

## 1. Executive architecture

| Branch | Canonical / strongest anchor | Field maturity signal | Repo coverage after ROUND-0008 | Main limitation/frontier | Double Allee relevance |
|---|---|---|---|---|---|
| D1 Linear commensurate spectral | Matignon 1998; exact/equivalent LMI formulations through 2026 | mature | MODERATE | structured/uncertain/operator-general extensions rather than fixed-matrix criterion | PLAUSIBLE BRIDGE |
| D2 Incommensurate / multi-order | Sabatier et al. 2013; Diethelm et al. 2024 | substantially stronger than seed map implied | MODERATE | global nonlinear, structural/robust multi-order dynamics | VERY CLOSE |
| D3 Nonlinear local / linearization | Cong et al. 2016/2017; Diethelm et al. 2024 | solid local theory | MODERATE | boundary/center cases, nonhyperbolic bifurcation, operator/order generality | DIRECT/VERY CLOSE |
| D4 Lyapunov / ML / global | Li et al.; Gallegos–Duarte-Mermoud 2019; Guo et al. 2025 | converse theory now substantial | MODERATE | general converse/robust/global theory across nonconstant-order/nonautonomous classes | VERY CLOSE |
| D5 Structured matrices | D-stability/diagonal/Metzler/acyclic/conic corpus | mature in several subclasses | MODERATE-DEEP | exact conic results for biologically forced nontrivial classes | PLAUSIBLE BRIDGE |
| D6 Robustness / uncertainty | Zheng 2017; Zhang–Lu 2023; descriptor interval 2023 | exact linear robust results are strong | MODERATE | nonlinear threshold/persistence robustness; simultaneous order+state uncertainty | VERY CLOSE |
| D7 Delay / neutral | Tuan–Trinh 2018; Zhang et al. 2025 | linear delay-independent exactness improving quickly | MODERATE | exact delay-dependent, neutral, incommensurate and nonlinear criteria | VERY CLOSE |
| D8 Switched / impulsive / stochastic / hybrid | current Lyapunov/dwell-time/switching-law literature | fragmented, mostly sufficient | SEED | unified exact/converse robustness theory | PLAUSIBLE BRIDGE |
| D9 Networks / consensus / synchronization | large controller-specific literature | rich but application-heavy | SEED | topology-explicit exact nonlinear stability/persistence rather than sufficient consensus LMIs | VERY CLOSE |
| D10 Bifurcation / multistability / tipping | Tavazoei–Haeri 2009; Doan–Kloeden 2022 | conceptually delicate | MODERATE | rigorous nonlocal bifurcation semantics beyond ODE-style “Hopf” claims | **VERY CLOSE** |
| D11 Persistence / extinction | integer-order permanence theory strong; fractional results mostly model-specific in searched corpus | underdeveloped abstractly | SEED | general fractional permanence/persistence/invasion theory | **DIRECT/VERY CLOSE** |
| D12 Variable / distributed order | Fernández-Anaya et al. 2017; Lenka 2025; Wu et al. 2026 | rapidly developing | SEED | exact/converse/bifurcation/persistence theory for changing/distributed memory | PLAUSIBLE–VERY CLOSE |
| D13 Identifiability / inverse problems | Alavi 2015; Varalda–Pequito 2026; inverse PDE literature | mature in several formulations | MODERATE | threshold-aware nonlinear ecological identifiability, not generic SI | VERY CLOSE |
| D14 Time-fractional reaction–diffusion | Douaifia et al. 2020; Ahmad–Cygan–Karch 2025 preprint | generic linearization theory is advancing | MODERATE | global nonlinear/Turing/bifurcation/persistence theory | **VERY CLOSE** |
| D15 Double / Multiple Allee lens | repository rounds 0002–0007 | repo-deep, field crowded for cosmetic extensions | DEEP | must couple to a deeper FDE frontier rather than merely fractionalize a model | DIRECT |

## 2. Cross-domain foundation

A useful architecture source is Diethelm, Kiryakova, Luchko, Machado & Tarasov (2022), *Trends, directions for further research, and some open problems of fractional calculus*, DOI **10.1007/s11071-021-07158-9**. It confirms that fractional dynamics remains a rapidly developing area with unresolved foundational and operator-level questions. It is broad fractional-calculus guidance, not a substitute for branch-specific theorem auditing.

A recurring methodological issue across the map is that the word **stability** is overloaded. The corpus must continue to distinguish:
- asymptotic state stability;
- Lyapunov stability;
- Mittag-Leffler stability;
- BIBO stability;
- input-to-state stability;
- finite-time stability;
- robust/quadratic stability;
- admissibility of descriptor systems;
- Hyers–Ulam stability.

Hyers–Ulam results should not be counted as substitutes for dynamical asymptotic/persistence theory.

---

# 3. Branch-by-branch evidence

## D1 — Linear commensurate spectral stability

### Foundation
Matignon (1998), DOI **10.1051/proc:1998004**, gives the canonical sector criterion for commensurate finite-dimensional fractional linear systems.

Brandibur–Garrappa–Kaslik (2021), DOI **10.3390/math9080914**, provides a modern Caputo clarification including boundary/Jordan-index distinctions.

### Strongest/current direction
Recent 2026 work in ISA Transactions and Applied Mathematics and Computation gives equivalent necessary-and-sufficient real LMI formulations for fixed LTI fractional systems.

### Dominant limitations
For the unstructured fixed commensurate matrix, the basic stability question is mature. Remaining interest is not another equivalent Matignon reformulation but:
- uncertainty;
- structure;
- descriptor systems;
- delays;
- noncommensurate order;
- nonlinear/nonlocal phenomena.

### Frontier classification
**MATURE CORE.**

### Double Allee relevance
**PLAUSIBLE BRIDGE.** Local Jacobian stability in fractional ecological models reduces to this theory, but this alone is not a fertile Double-Allee gap.

### Repo coverage
**MODERATE.**

---

## D2 — Incommensurate / multi-order stability

### Foundation
Sabatier–Farges–Trigeassou (2013), DOI **10.1016/j.sysconle.2013.04.008**, gives a necessary-and-sufficient BIBO stability test for noncommensurate systems.

### Major modern strengthening
Diethelm, Hashemishahraki, Thai & Tuan (2024), DOI **10.1016/j.jmaa.2024.128642**, materially changes the frontier assessment:
- necessary-and-sufficient stability criterion for rational incommensurate orders;
- fractional-spectrum rational approximation for general, not necessarily rational, orders;
- equivalence of the true fractional spectrum and rational approximation;
- constructive analysis;
- linearized nonlinear stability in arbitrary finite dimension.

Therefore the naive gap “irrational incommensurate stability lacks a general theory” does not survive.

Brandibur & Kaslik (2023), DOI **10.3390/fractalfract7020117**, reviews and extends multi-term constant-coefficient stability/instability, including arbitrary numbers of fractional derivatives for order-independent results.

A 2024 IFAC paper, DOI **10.1016/j.ifacol.2024.08.204**, develops Lyapunov sufficient conditions for nonlinear incommensurate systems.

### Dominant limitations
The modern exact results are strongest for linear/local questions. Less mapped are:
- global nonlinear stability;
- persistence/permanence;
- robust uncertainty jointly in orders and nonlinear parameters;
- nonhyperbolic/bifurcation questions;
- structured ecological multi-order systems.

### Double Allee relevance
**VERY CLOSE.** Distinct biological mechanisms/species can naturally carry distinct memory orders.

### Repo coverage
**MODERATE.**

---

## D3 — Nonlinear local stability and linearization

### Foundation / exact local direction
Cong, Doan, Siegmund & Tuan (2016), DOI **10.14232/ejqtde.2016.1.39**, proves linearized asymptotic stability for nonlinear Caputo systems: stable linearization implies asymptotically stable equilibrium under the stated hypotheses.

The same authors (2017), DOI **10.3934/dcdsb.2017164**, prove the complementary instability theorem when the linearization has an eigenvalue in the unstable Matignon sector.

Diethelm et al. (2024) extends constructive local linearized stability into the incommensurate setting.

### Dominant limitations
The local hyperbolic-like sector picture is comparatively strong. The difficult frontier is where linearization is inconclusive:
- eigenvalues on/near the fractional stability boundary;
- zero eigenvalues at folds/transcritical/pitchfork points;
- center-manifold/normal-form analogues;
- memory-sensitive nonlocal bifurcation.

### Double Allee relevance
**DIRECT/VERY CLOSE.** Strong Allee creation/destruction is fundamentally a nonhyperbolic equilibrium bifurcation problem.

### Repo coverage
**MODERATE.**

---

## D4 — Lyapunov / Mittag-Leffler / global stability

### Foundation
Li–Chen–Podlubny (2009) introduced the Mittag-Leffler stability framework for nonlinear fractional systems.

### Converse theory
Gallegos & Duarte-Mermoud (2019), DOI **10.3906/mat-1808-75**, prove converse theorems characterizing Lyapunov and Mittag-Leffler stability for Caputo systems and establish a hierarchy of ML convergence rates. In particular, order below one excludes ordinary exponential stability in the relevant sense.

Guo, Wei, Zhang, Mao, Zhou & Cao (2025), DOI **10.1016/j.jfranklin.2024.107414**, develops fractional-order input-to-state stability and a converse Lyapunov theorem, closing a gap explicitly identified by the authors.

### Dominant limitations
Converse/Lyapunov theory exists; the frontier is no longer “does a converse theorem exist?” in the broad Caputo setting.

Potentially harder extensions:
- incommensurate global/converse stability;
- variable/distributed order;
- delay/hybrid systems;
- robust persistence rather than equilibrium stability;
- state constraints/positive cones.

### Double Allee relevance
**VERY CLOSE.** Global basin separation and threshold survival/extinction demand more than local Jacobian criteria.

### Repo coverage
**MODERATE.**

---

## D5 — Structured matrices: D-, diagonal-, positive-, Metzler-, sign stability

### Foundation and exact subclasses
Rounds 0001 and 0003 already mapped:
- low-dimensional exact D-stability;
- tridiagonal and acyclic exact D-stability;
- Metzler/Hurwitz/diagonal-stability structure;
- qualitative/sign stability;
- generalized conic/LMI-region multiplicative D-stability.

Kushel–Pavani (2022), DOI **10.1007/s10884-020-09891-y**, is the principal conic-region bridge.

### Dominant limitations
A residual exact problem can exist only for a **specific biologically forced** cyclic/non-Metzler class. Generic structured D-stability is not an open blank slate.

### Double Allee relevance
**PLAUSIBLE BRIDGE**, but high risk of reverse-engineering an ecological model to fit a matrix problem.

### Repo coverage
**MODERATE-DEEP** for the D-stability subbranch.

---

## D6 — Robustness and uncertainty

### Exact linear results are stronger than the original map suggested
Zheng (2017), DOI **10.1016/j.sysconle.2016.11.001**, gives necessary-and-sufficient graphical criteria for interval uncertainty in coefficients and fractional orders.

Zhang & Lu (2023), DOI **10.1016/j.cnsns.2023.107511**, gives necessary-and-sufficient robust stability conditions for (0<alpha<1) systems with **mixed multi-parameter and norm-bounded uncertainties**, plus robust stability bounds.

Di, Zhang & Zhang (2023), DOI **10.1016/j.amc.2023.128076**, gives necessary-and-sufficient admissibility criteria for nominal descriptor fractional systems and quadratic admissibility/robust stabilization when uncertainty also enters derivative matrices.

### Dominant limitations
Much of the strongest exact theory is linear/descriptor/frequency-domain.

Under-mapped:
- nonlinear equilibrium/global stability under simultaneous order/parameter uncertainty;
- robust threshold/persistence regions;
- uncertainty in memory architecture itself;
- robust incommensurate nonlinear systems.

### Double Allee relevance
**VERY CLOSE.** Allee thresholds are management-critical precisely because uncertain parameter/order values can move persistence/extinction boundaries.

### Repo coverage
**MODERATE.**

---

## D7 — Delay and neutral systems

### Nonlinear local foundation
Tuan & Trinh (2018), DOI **10.1109/TAC.2018.2791485**, extends linearized asymptotic stability to nonlinear fractional delay systems under the source assumptions.

### Strong modern linear exact result
Zhang, Jin, Lu & Zhu (2025), DOI **10.1109/LCSYS.2025.3620881**, gives a **necessary-and-sufficient delay-independent** stability condition for fractional-order time-delay systems, then transforms it to LMIs via generalized KYP without added conservatism; the result covers order in ((0,2)).

### Neutral/multi-derivative frontier
Wang, Xie, Deng & Hu (2024), DOI **10.3934/dcdss.2024023**, treats neutral functional equations with multiple Caputo derivatives and infinite delay, obtaining existence, Hyers–Ulam and finite-time stability results. These are useful but not exact asymptotic N&S criteria.

### Dominant limitations
The broad gap “fractional delay stability is only sufficient” is false. But likely frontiers remain in:
- exact **delay-dependent** stability rather than delay-independent stability;
- neutral systems;
- nonlinear systems;
- incommensurate/multi-order delays;
- threshold bifurcations with delay.

### Double Allee relevance
**VERY CLOSE.** Reproduction/maturation delays and low-density mechanisms naturally coexist.

### Repo coverage
**MODERATE.**

---

## D8 — Switched / impulsive / stochastic / hybrid systems

### Modern representative results
Feng, Wang & Chen (2025), DOI **10.3390/fractalfract9020094**, derives sufficient finite-time stability conditions for switched fractional systems and an average-dwell-time condition.

Hong, Thuan & Thanh (2025), DOI **10.1016/j.cnsns.2024.108352**, develops sufficient conditions and state-dependent switching laws for regularity, impulse-free behavior and Mittag-Leffler stability of nonlinear switched singular fractional systems.

The 2025 paper explicitly notes how sparse prior nonlinear Mittag-Leffler theory was for switched singular fractional systems.

### Architecture assessment
This literature is broad but fragmented across:
- switched;
- impulsive;
- Markov/stochastic;
- singular;
- delayed;
- event-triggered/control-specific systems.

The dominant theorem mode remains **sufficient Lyapunov/LMI/dwell-time criteria** for specific architectures.

### Inferred frontier
A unified exact/converse stability framework comparable with mature integer-order switched/hybrid theory was not identified in the breadth search.

### Double Allee relevance
**PLAUSIBLE BRIDGE.** Seasonal forcing, management pulses, regime switching and catastrophes are biologically natural, but any connection must be structural, not decorative.

### Repo coverage
**SEED.**

---

## D9 — Networks, synchronization, consensus and graph topology

### Current literature signal
Recent fractional-network work is abundant in consensus/synchronization/control:
- heterogeneous fractional multi-agent consensus under packet loss/delay;
- signed-graph bipartite consensus;
- reaction-diffusion neural networks on balanced/unbalanced graphs;
- topology identification and synchronization;
- positive fractional multi-agent consensus.

Representative recent papers largely derive **sufficient** LMI/controller/topology conditions for a specified architecture.

### What is mature
Consensus/synchronization as an application genre is crowded. A new paper cannot claim novelty merely by combining “fractional + network + controller”.

### What remains structurally interesting
- exact topology-aware nonlinear stability thresholds;
- persistence/extinction on graphs;
- graph changes to multistability/basin geometry;
- robust consensus/persistence under order heterogeneity.

### Double Allee relevance
**VERY CLOSE**, but direct Allee network/dispersal prior art is already substantial (Lanchier; Nagatani–Ichinose; Stehlík–Švígler–Volek; Tsai).

### Repo coverage
**SEED** for general fractional network theory; deeper for the Allee-adjacent network subbranch.

---

## D10 — Bifurcation, multistability, tipping and resilience

### Foundational obstruction
Tavazoei & Haeri (2009), DOI **10.1016/j.automatica.2009.04.001**, proves that autonomous time-invariant Caputo fractional systems with a finite lower terminal cannot generate nonconstant exactly periodic solutions; the result includes commensurate and incommensurate systems.

Yazdani & Salarieh (2011), DOI **10.1016/j.automatica.2011.04.013**, clarifies that periodic steady-state behavior may be recovered only under a limiting memory interpretation where the lower terminal is taken arbitrarily far into the past.

This makes careless transplantation of classical Hopf/limit-cycle language dangerous.

### Rigorous positive result
Doan & Kloeden (2022), DOI **10.1007/s13540-022-00030-6**, constructs attractors for Caputo systems with triangular vector fields and establishes scalar saddle-node and pitchfork bifurcations under their assumptions.

### Modern frontier signal
A large applied literature nevertheless reports “Hopf bifurcation” from fractional eigenvalue-sector crossings. The exact dynamical meaning depends on derivative definition, lower-terminal convention and notion of periodic/asymptotically periodic behavior.

### Inferred frontier
A rigorous multidimensional/incommensurate bifurcation architecture that distinguishes:
- equilibrium stability-boundary crossing;
- genuine invariant-set bifurcation;
- transient/asymptotically periodic oscillation;
- impossible finite-memory exact periodic orbit

appears substantially less mature than the volume of applied papers suggests.

### Double Allee relevance
**VERY CLOSE.** Allee effects naturally involve saddle-node/fold, cusp, hysteresis, multistability and basin changes.

### Repo coverage
**MODERATE**, after this round; requires a dedicated depth-first audit.

---

## D11 — Persistence, extinction and population dynamics

### Adjacent integer-order benchmark
Fonda & Gidoni (2015), DOI **10.1016/j.na.2014.10.011**, gives a necessary-and-sufficient permanence condition for a local dynamical system on a suitable topological space.

Modern integer-order ecological dynamics has additional frameworks based on invasion criteria, boundary invariant sets and persistence theory.

### Fractional breadth-search result
The search found many **model-specific** fractional epidemic, predator–prey, food-chain and network papers proving positivity, boundedness, local/global stability and persistence/extinction thresholds.

It did **not** identify a comparably general fractional analogue of abstract permanence/uniform-persistence theory in the searched corpus.

This is a negative search result, not an absence theorem.

### Why this matters
Caputo systems do not fit ordinary local-semiflow intuition without care; the memory state may have to be enlarged. A generic persistence theory therefore cannot simply be copied from ODEs.

### Double Allee relevance
**DIRECT/VERY CLOSE.** Persistence/extinction is the natural mathematical endpoint of strong Allee dynamics.

### Repo coverage
**SEED.**

---

## D12 — Variable-order and distributed-order stability

### Distributed-order foundation
Fernández-Anaya, Nava-Antonio, Jamous-Galante, Muñoz-Vega & Hernández-Martínez (2017), DOI **10.1016/j.cnsns.2017.01.020**, partially extends the fractional Lyapunov direct method to nonlinear distributed-order time-varying systems and obtains sufficient asymptotic stability results.

### Time-varying order modern frontier
B. K. Lenka (2025), DOI **10.1016/j.chaos.2025.116935**, develops a Lyapunov stability theory for non-autonomous time-varying-order Caputo systems, introduces time-varying-order Mittag-Leffler stability notions and proves global stability/non-blow-up conditions.

### Latest distributed-order development
Wu, Pu & Yang (2026), DOI **10.1016/j.cnsns.2026.109995**, develops a unified Lyapunov/Barbalat framework for nonlinear distributed-order systems in continuous and discrete domains, including external disturbances and boundedness/attractivity.

### Architecture assessment
This branch is advancing quickly, but the dominant results remain Lyapunov sufficient frameworks. Exact spectral/converse/global bifurcation/persistence theory is much less consolidated than for constant-order Caputo systems.

### Double Allee relevance
**PLAUSIBLE–VERY CLOSE.** Variable/distributed memory could represent changing or heterogeneous ecological memory, but it must be biologically motivated.

### Repo coverage
**SEED.**

---

## D13 — Identifiability and inverse problems

### Existing theory
The repository already contains:
- Nazarian–Haeri–Tavazoei (2010): fractional system structure/parameter identifiability;
- Alavi et al. (2015): structural identifiability for noncommensurate fractional models;
- Varalda–Pequito (2026): graph-theoretic structural identifiability for fractional-order networks;
- Kharazmi et al. (2021): practical/structural identifiability and model uncertainty in integer/fractional/delay epidemiological models.

Time-fractional PDE inverse problems additionally have uniqueness/stability theory for recovering orders, coefficients and sources under specified boundary observations.

### Frontier
Generic “fractional identifiability” is not a novelty claim. More credible gaps involve:
- nonlinear threshold systems;
- simultaneous mechanism attribution and stability-boundary inference;
- realistic ecological observation operators;
- model-class discrimination: fractional memory versus delay/latent forcing.

### Double Allee relevance
**VERY CLOSE** as a supporting/inference branch, but not the most obviously deep standalone gap.

### Repo coverage
**MODERATE.**

---

## D14 — Time-fractional reaction–diffusion and spatial dynamics

### Generic stability foundation
Douaifia, Abdelmalek & Bendoukha (2020), DOI **10.1016/j.cnsns.2019.104982**, derives sufficient asymptotic stability/instability criteria for generic autonomous time-fractional reaction–diffusion systems using Laplacian eigenfunction expansions, addresses commensurate/incommensurate linear cases and nonlinear linearization.

### Modern abstract frontier
Ahmad, Cygan & Karch (2025), arXiv:**2507.02094**, proves a linearization principle for abstract time-fractional reaction–diffusion equations and derives a fractional counterpart of Turing instability.

### Dominant limitations
- strongest published generic 2020 criteria are sufficient;
- abstract nonlinear theory is still moving;
- global pattern selection, nonlinear persistence and bifurcation remain less unified;
- exact relation between memory, diffusion-driven instability and nonlocal dynamical objects remains active.

### Double Allee relevance
**VERY CLOSE.** Spatial strong-Allee thresholds, invasion failure, critical patches and pattern formation are natural bridges. Direct Double-Allee + diffusion papers already exist, so novelty must be structural.

### Repo coverage
**MODERATE.**

---

## D15 — Double / Multiple Allee cross-cutting lens

### What the repository already established
The repo now has comparatively deep evidence on:
- terminology: component vs demographic, strong vs weak, multiple vs “double”;
- classical analytical Double-Allee models;
- continuous Caputo Double-Allee prior art from 2021;
- incommensurate and discrete fractional Double-Allee work;
- reaction–diffusion Double-Allee work;
- network/metapopulation adjacent theory;
- empirical multiple-component systems;
- identifiability/data constraints;
- mechanism-space candidate geometry.

### Mature/closed routes
Do not treat as frontier:
- “Double Allee + Caputo”;
- incommensurate/discrete fractionalization alone;
- adding diffusion alone;
- generic network coupling alone;
- generic structural identifiability;
- standard fold/Hopf labels without rigorous fractional dynamics.

### Correct role
Double Allee is now best used as a **frontier lens** through which to test deeper FDE questions:
- rigorous nonlocal bifurcation;
- abstract persistence/extinction;
- robust uncertain-order thresholds;
- delay/neutral threshold stability;
- variable/distributed memory;
- spatial invasion/persistence.

### Repo coverage
**DEEP** relative to the other branches.

---

# 4. Cross-branch observations

## 4.1 The exact linear core is more mature than the initial map suggested

Three breadth findings materially reduce several naive gap hypotheses:

1. Diethelm et al. 2024 gives a constructive modern theory for general incommensurate stability and nonlinear linearization.
2. Zhang–Lu 2023 gives N&S robust stability for mixed uncertainty.
3. Zhang et al. 2025 gives N&S delay-independent stability with an exact LMI transformation.

Therefore future opportunities should not be based on the assumption that fractional linear systems are generally limited to sufficient tests.

## 4.2 Nonlinear and genuinely dynamical questions remain structurally harder

The weaker branches are those that require more than spectral decay:
- invariant sets;
- persistence;
- bifurcation;
- basin structure;
- hybrid memory;
- variable memory architecture.

This is where the nonlocal character of fractional dynamics becomes mathematically substantive rather than a modified stability sector.

## 4.3 “Hopf” is a terminology and theorem-risk zone

The periodic-orbit obstruction for finite-memory autonomous Caputo systems means the large application literature using “Hopf bifurcation” needs theorem-level reconciliation.

A survey that does not distinguish:
- spectral crossing,
- sustained numerical oscillation,
- asymptotically periodic behavior,
- exact periodic orbit

would be unreliable.

## 4.4 Persistence theory is conspicuously less abstract on the fractional side

The breadth search found general N&S permanence theory in ordinary dynamical systems but mostly model-by-model fractional persistence/extinction results.

This asymmetry is potentially important and deserves a dedicated falsification round.

## 4.5 Variable/distributed order is moving too fast for a static 2022 picture

The 2025 time-varying-order Lyapunov theory and 2026 unified distributed-order framework show that this branch should receive a fresh dedicated search before any gap statement.

## 4.6 Network and hybrid literature has high publication volume but low theorem unification

Many results are controller-specific sufficient conditions. Publication density should not be confused with a mature exact structural theory.

---

# 5. Evidence-backed candidate frontier hypotheses

These are **candidates only**. None is certified novel.

## GAP-08-A — Rigorous nonlocal bifurcation architecture near Allee thresholds

### Mathematical formulation
For autonomous Caputo or incommensurate systems
[
{}^C D^{alpha_i}x_i=f_i(x,mu),
]
develop rigorous local/global bifurcation criteria at nonhyperbolic equilibria that distinguish equilibrium bifurcation, attractor change and admissible oscillatory/asymptotically periodic phenomena without importing an impossible finite-memory periodic orbit.

### Strongest neighboring results
- Tavazoei–Haeri 2009 periodic-orbit nonexistence;
- Cong et al. local linearization/instability;
- Doan–Kloeden 2022 scalar/triangular saddle-node and pitchfork.

### Why it might matter
It addresses a foundational mismatch between rigorous nonlocal dynamics and widespread applied “Hopf” terminology.

### Killer literature to search next
Fractional center manifolds, nonlocal semiflows, attractor bifurcation, asymptotically periodic solutions, functional-state embeddings.

### Double Allee proximity
**VERY CLOSE.**

### Evidence still missing
Dedicated theorem-level bifurcation survey/citation expansion.

---

## GAP-08-B — Abstract fractional persistence / permanence theory

### Mathematical formulation
For positive nonlinear Caputo systems on an invariant cone, establish general criteria for uniform persistence/permanence in terms of boundary invariant sets, invasion quantities or a suitable memory-state dynamical system.

### Strongest neighboring theorem
Fonda–Gidoni 2015 gives N&S permanence for local dynamical systems in the integer/local setting; searched fractional ecology is predominantly model-specific.

### Why it might matter
Persistence/extinction is more directly relevant to ecology than equilibrium stability and would unify many model-specific proofs.

### Killer literature to search next
Infinite-dimensional/history-space semiflows, Volterra equations, monotone nonlocal systems, persistence of hereditary systems, fractional cocycles.

### Double Allee proximity
**DIRECT / VERY CLOSE.**

### Evidence still missing
A dedicated search explicitly using hereditary/Volterra persistence vocabulary, not only “fractional permanence”.

---

## GAP-08-C — Robust nonlinear threshold/persistence under uncertain fractional order

### Mathematical formulation
Given
[
{}^C D^{alpha}x=f(x,	heta),
qquad
alphainmathcal A, 	hetainTheta,
]
characterize robust persistence/extinction or robust nonlinear stability uniformly over order and parameter uncertainty.

### Strongest neighboring result
Linear interval/order uncertainty has exact N&S results (Zheng 2017); mixed linear uncertainty has N&S robust stability (Zhang–Lu 2023).

### Why it might matter
It moves exact robust theory from linear spectral stability to nonlinear ecological thresholds.

### Killer literature to search next
Robust nonlinear FDE, differential inclusions, polytopic fractional systems, uncertain-order Lyapunov methods, interval nonlinear population models.

### Double Allee proximity
**VERY CLOSE.**

### Evidence still missing
Systematic nonlinear uncertainty audit.

---

## GAP-08-D — Variable/distributed-order nonlinear stability, persistence and bifurcation

### Mathematical formulation
Develop stability/converse/persistence or bifurcation theory for
[
{}^C D^{alpha(t)}x=f(x)
]
or distributed-order dynamics
[
int c(alpha),{}^C D^alpha x,dalpha=f(x),
]
beyond sufficient Lyapunov criteria.

### Strongest neighboring results
- Fernández-Anaya et al. 2017 distributed-order Lyapunov theory;
- Lenka 2025 time-varying-order Lyapunov theory;
- Wu–Pu–Yang 2026 unified distributed-order Lyapunov framework.

### Why it might matter
Memory architecture itself becomes dynamic/heterogeneous.

### Killer literature to search next
generalized fractional operators, resolvent families, distributed-order semigroups, variable-order control/stability.

### Double Allee proximity
**PLAUSIBLE–VERY CLOSE** if ecological memory changes with density/environment.

### Evidence still missing
Exact/converse frontier audit after the 2025–2026 papers.

---

## GAP-08-E — Exact delay-dependent nonlinear / neutral fractional stability near ecological thresholds

### Mathematical formulation
Move beyond delay-independent linear exactness toward sharp delay-dependent criteria for nonlinear, neutral or incommensurate fractional systems, ideally including nonhyperbolic threshold transitions.

### Strongest neighboring results
- Tuan–Trinh 2018 nonlinear delay linearization;
- Zhang et al. 2025 N&S delay-independent linear criterion;
- Wang et al. 2024 neutral multi-Caputo sufficient Ulam/finite-time results.

### Why it might matter
Ecological Allee mechanisms commonly include maturation/reproduction delay.

### Killer literature to search next
fractional quasi-polynomial root theory, argument principle, neutral hereditary systems, exact delay-dependent frequency methods.

### Double Allee proximity
**VERY CLOSE.**

### Evidence still missing
Exhaustive delay-dependent exact literature search.

---

## GAP-08-F — Global nonlinear incommensurate stability/persistence beyond linearization

### Mathematical formulation
For multi-order nonlinear Caputo systems, seek global/converse/persistence criteria that do not reduce solely to local linearized stability.

### Strongest neighboring result
Diethelm et al. 2024 substantially closes the linear/local incommensurate frontier.

### Why it might matter
Mechanism/species-specific memory orders are biologically natural, but local eigenvalue stability alone does not address thresholds/basins/extinction.

### Killer literature to search next
multi-order Lyapunov, generalized comparison, global attractors, monotone multi-order systems.

### Double Allee proximity
**VERY CLOSE.**

### Evidence still missing
Dedicated global multi-order nonlinear map.

---

# 6. Apparently mature / low-value routes

The breadth audit suggests low marginal value in searching for novelty in:

1. another fixed-matrix commensurate spectral criterion;
2. simple LMI reformulations of standard LTI stability;
3. generic “fractional + consensus” controller combinations;
4. generic “fractional + Double Allee” model construction;
5. local stability of a specific predator–prey equilibrium using Matignon only;
6. generic structural identifiability of fractional models;
7. weighted-coalition/convexity reformulations of the mechanism-space candidate without a new persistence theorem.

---

# 7. Coverage imbalance after ROUND-0008

## Stronger / reasonably mapped
- D1 commensurate linear;
- D2 incommensurate linear/local;
- D5 structured/D-stability;
- D6 linear robustness;
- D13 identifiability;
- D15 Double/Multiple Allee.

## Still under-mapped and high-value
- **D8 switched/stochastic/hybrid**;
- **D10 rigorous bifurcation**;
- **D11 abstract persistence/permanence**;
- **D12 variable/distributed order**.

## Under-mapped but narrower
- D7 exact delay-dependent/neutral;
- D9 topology-explicit nonlinear network theory;
- D14 global nonlinear reaction–diffusion.

These branches should drive the next depth-first rounds.

---

# 8. Survey implications

## Branches mature enough to anchor a survey now
- linear commensurate spectral stability;
- incommensurate/multi-term linear stability;
- nonlinear local linearization;
- Lyapunov/Mittag-Leffler foundations;
- structured/robust linear stability;
- Double/Multiple Allee prior-art section.

## Branches requiring more evidence before a credible survey synthesis
- switched/impulsive/stochastic/hybrid;
- rigorous bifurcation and periodicity semantics;
- abstract persistence/permanence;
- variable/distributed order;
- network theorem architecture;
- nonlinear spatial/global dynamics.

## Survey-readiness verdict
**NOT YET READY**, but ROUND-0008 corrects the major repository imbalance and identifies where additional depth is required.

A future survey should make one distinction central:

> exact linear spectral/robust stability has become comparatively mature, whereas genuinely dynamical nonlocal structures—bifurcation, persistence, hybrid memory, changing order and global spatial dynamics—remain much less unified.

---

# 9. Recommended next evidence waves

Without selecting a research winner, the highest-value depth searches are:

1. **Fractional bifurcation / periodicity / attractor theory**.
2. **Abstract persistence and permanence for nonlocal/fractional systems**.
3. **Variable/distributed-order stability and converse theory**.
4. **Switched/stochastic/hybrid fractional stability architecture**.
5. **Exact delay-dependent and neutral fractional stability**.
6. **Global nonlinear incommensurate stability/persistence**.

The first two have the strongest natural proximity to Double/Multiple Allee dynamics.

## Search limitation

This is a breadth-first architecture audit, not an exhaustive systematic review of all fifteen branches. Negative statements are explicitly search-qualified. Every candidate gap above requires a dedicated adversarial round before it can enter the opportunity portfolio as a high-confidence unresolved problem.
