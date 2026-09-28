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
7. Real ecological systems with multiple component Allee mechanisms exist, but the searched seed corpus did not identify a real-data-calibrated fractional Double-Allee model that establishes two-threshold/fractional-memory identifiability.

**Negative/falsification searches.**
- The candidate claim “Double Allee + fractional memory is new” is falsified.
- The candidate claim “Double Allee + spatial diffusion is new” is falsified.
- No general graph-theoretic theorem for Double-Allee topology-dependent thresholds was identified in the seed corpus, but adjacent single-Allee metapopulation/network results are strong novelty threats.
- No theorem-level general identifiability result jointly separating multiple Allee thresholds and fractional memory was identified in the seed corpus; a dedicated inverse-problem/data round is required before treating this as a gap.

**Round-specific note:** `research/web-search/2026-09-28_double-allee-terminology-seed.md`

---

## Provenance discipline

For each source used in a theorem or novelty statement, prefer the original publication or an author manuscript. Abstract-only sources are marked as such in the source registry and should not be promoted to exact theorem evidence without further verification.