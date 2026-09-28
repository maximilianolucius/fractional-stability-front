# Double Allee — State of the Art

**Status:** theorem-level seed from ROUND-0002, 2026-09-28.  
**Scope:** foundational terminology plus analytical Double-Allee, fractional, spatial and network-adjacent prior art. This is not yet an exhaustive systematic review.

## 1. Executive synthesis

The searched literature does **not** support treating “Double Allee effect” as one standardized mathematical object.

Three layers must be separated:

1. **ecological mechanisms** — one or multiple component Allee effects;
2. **demographic growth geometry** — weak/strong effect and number of positive thresholds/equilibria;
3. **system-level dynamics** — predator–prey coupling, multistability, cycles, diffusion, network rescue, fractional memory, etc.

Several naive novelty directions are already closed by direct prior art:
- Double Allee + Caputo memory;
- Double Allee + incommensurate fractional orders;
- Double Allee + discrete fractional dynamics;
- Double Allee + reaction–diffusion.

## 2. Foundational ecological terminology

### Stephens, Sutherland & Freckleton (1999)

DOI: 10.2307/3547011.

Foundational reference for defining the Allee effect and distinguishing individual/component effects from demographic consequences.

### Courchamp, Clutton-Brock & Grenfell (1999)

DOI: 10.1016/S0169-5347(99)01683-3.

Foundational review of inverse density dependence and population-level Allee dynamics.

### Berec, Angulo & Courchamp (2007)

DOI: 10.1016/j.tree.2006.12.002.

Key result for this project:

> “Multiple Allee effects” refers to multiple component mechanisms acting together, not automatically to two demographic thresholds.

The review also supplies empirical examples and management consequences.

## 3. Analytical Double-Allee predator–prey literature

### González-Olivares et al. (2011)

*Consequences of double Allee effect on number of limit cycles in a predator-prey model.*  
DOI: 10.1016/j.camwa.2011.08.061.

**Contribution:** analytical study of how a Double-Allee prey formulation changes periodic dynamics/limit-cycle multiplicity.

**Restriction:** planar, model-specific functional form.

### Pal & Saha (2015)

*Qualitative analysis of a predator-prey system with double Allee effect in prey.*  
DOI: 10.1016/j.chaos.2014.12.007.

A representative prey equation is

[
dot x=
rac{r x}{x+n}
left(1-rac{x}{K}ight)(x-m)
-rac{cxy}{x+	heta y}.
]

The predator equation uses the same ratio-dependent interaction structure.

**Analytical content identified:**
- equilibrium classification;
- strong/weak-Allee parameter regimes;
- local stability;
- bistability and separatrices;
- saddle-node and Hopf bifurcations;
- higher-codimension structure including Bogdanov–Takens/homoclinic behavior under model assumptions.

**Novelty implication:** substantial analytical Double-Allee bifurcation theory predates the fractional literature.

## 4. Fractional Double-Allee literature

### Rahmi et al. (2021)

*A Modified Leslie–Gower Model Incorporating Beddington–DeAngelis Functional Response, Double Allee Effect and Memory Effect.*  
DOI: 10.3390/fractalfract5030084.

**Operator:** Caputo.

**Analytical content:**
- existence/uniqueness;
- nonnegativity/boundedness;
- local equilibrium stability;
- conditions related to order-driven Hopf behavior;
- Lyapunov-type sufficient global stability.

**Novelty implication:** Double Allee + Caputo memory is direct prior art since at least 2021.

### Ramesh et al. (2025)

DOI: 10.1371/journal.pone.0305179.

**Operator:** Caputo fractional derivative.

**Content:** local/global stability analysis and oscillatory/Hopf behavior in a Double-Allee predator–prey setting.

### Ritwika Mondal et al. (2025)

*Dynamics of a fractional order predator-prey system with double Allee effect and group defense.*  
DOI: 10.1016/j.cjph.2025.09.020.

**Content identified:**
- fractional Double-Allee model;
- incommensurate-order analysis;
- multistability/basin stability;
- group-defense interaction.

**Data:** publisher statement indicates no experimental data were used; the study is model-based.

**Novelty implication:** even “Double Allee + incommensurate fractional order” is already direct prior art.

### Alraddadi, Ahmed & Seol (2026)

DOI: 10.3390/fractalfract10050304.

**Class:** discrete fractional predator–prey Double-Allee model.

**Analytical content:**
- local stability;
- Neimark–Sacker bifurcation;
- period-doubling bifurcation;
- center-manifold/normal-form analysis;
- chaos/control phenomena.

**Novelty implication:** discrete fractionalization is also covered.

## 5. Spatial Double-Allee literature

### Li & Li (2024)

DOI: 10.3934/math.20241309.

**Class:** reaction–diffusion predator–prey system with Double Allee effect.

**Content identified:** analytical coexistence/stability and pattern/bifurcation analysis.

**Novelty implication:** adding spatial diffusion is not by itself novel.

## 6. Network/metapopulation adjacent literature

### Lanchier (2013)

*The Role of Dispersal in Interacting Patches Subject to an Allee Effect.*  
DOI: 10.1239/aap/1386857863.

**Class:** stochastic interacting-patch process with a strong Allee effect.

**Mathematical significance:**
- persistence/extinction depends on dispersal and Allee threshold;
- geometry/topology of patch interactions matters;
- analytical results are obtained for specified structures such as complete/ring-like cases.

**Novelty implication:** topology-dependent Allee thresholds already exist outside the “Double Allee” phrase.

A future arbitrary-network Double-Allee theorem must be compared against:
- interacting particle systems;
- metapopulation rescue/extinction theory;
- bistable network dynamics;
- monotone/cooperative network systems;
- reaction–diffusion/graph Laplacian threshold results.

## 7. What is proved versus simulated in fractional Double-Allee papers

The seed corpus includes actual analytical results, not merely simulations:
- local spectral stability;
- sufficient global Lyapunov criteria;
- Hopf/bifurcation conditions;
- center-manifold/normal-form bifurcation results in discrete fractional models.

However, most results remain **model-specific**. No general theorem discovered in this seed classifies arbitrary Double-Allee systems by threshold geometry, topology and fractional memory simultaneously.

## 8. Real-data status

### What is established

Ecological literature documents systems where several component Allee mechanisms can plausibly coexist. Berec et al. (2007) reviews examples involving combinations such as:
- pollination + inbreeding;
- mate limitation + predator dilution;
- cooperative defense/social mechanisms.

Other promising empirical search leads include Crested Ibis reintroduction, gray wolves and gypsy moth low-density dynamics.

### What is not established by this seed

No searched source was found that simultaneously:
1. fits a genuinely multi-threshold demographic Allee model to real repeated observations;
2. identifies a fractional memory order;
3. proves or seriously diagnoses joint parameter identifiability;
4. validates the inferred thresholds out of sample.

This is a **search result, not an absence theorem**.

## 9. Recurrent restrictions in the seed corpus

- two-dimensional predator–prey state spaces;
- highly specific nonlinear functional responses;
- local Jacobian criteria;
- sufficient rather than exact global stability conditions;
- continuum diffusion rather than arbitrary graphs;
- simulated/model-generated trajectories;
- no structural identifiability theorem for threshold count + memory order;
- “Double Allee” terminology that does not uniquely encode threshold geometry.

## 10. Strongest novelty threats to future directions

| Candidate direction | Seed assessment | Main prior art |
|---|---|---|
| Double Allee + Caputo derivative | DIRECT PRIOR RESULT | Rahmi et al. 2021 |
| Double Allee + incommensurate fractional orders | DIRECT PRIOR RESULT | Mondal et al. 2025 |
| Double Allee + discrete fractional order | DIRECT PRIOR RESULT | Alraddadi et al. 2026 |
| Double Allee + reaction diffusion | DIRECT PRIOR RESULT | Li & Li 2024 |
| Double Allee + rich bifurcation theory | CLOSE/DIRECT PRIOR ART | Pal & Saha 2015; González-Olivares et al. 2011 |
| topology-dependent Allee thresholds | CLOSE PRIOR ART | Lanchier 2013 |
| multiple component mechanisms | ESTABLISHED ECOLOGICAL CONCEPT | Berec et al. 2007 |
| joint real-data identification of multi-threshold geometry + fractional memory | NO PRIOR RESULT FOUND IN SEARCHED SEED | requires dedicated search |

## 11. Candidate bridge questions that remain search hypotheses

The following survived only at **seed-search hypothesis** level:

1. **Arbitrary-network threshold theorem:** Can one classify when coupling creates, destroys or shifts multiple positive thresholds for a precisely defined local multi-threshold population class?
2. **Structured stability bridge:** Can the Jacobian families produced by multi-threshold ecological networks be characterized by exact conic-sector/relative D-stability results rather than model-specific eigenvalue calculations?
3. **Identifiability bridge:** Under what observation designs can threshold count/location and fractional memory order be structurally/practically distinguished?
4. **Data-theory bridge:** Is there a real spatial/longitudinal population dataset rich enough to discriminate one-threshold, multi-mechanism and genuinely multi-threshold models?

None of these is yet accepted as novel.

## 12. Required next search

Before generating a primary research direction, issue dedicated follow-up rounds for:

- graph/network/metapopulation/bistable systems without relying on “Double Allee” keywords;
- inverse problems/structural identifiability for Allee thresholds and fractional order;
- raw ecological datasets with sufficient low-density transitions and spatial replication.

## Sources

See:
- `research/web-search/SOURCE_REGISTRY.md`
- `research/web-search/2026-09-28_double-allee-terminology-seed.md`
- `corpus/papers.csv`
- `corpus/theorems.csv`
