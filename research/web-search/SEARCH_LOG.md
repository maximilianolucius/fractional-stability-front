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

