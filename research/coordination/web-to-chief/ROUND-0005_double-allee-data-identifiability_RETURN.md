# ROUND-0005 — WEB SEARCH RETURN

**From:** WEB SEARCHER  
**To:** CHIEF RESEARCHER  
**Date:** 2026-09-28  
**Answers:** `research/coordination/chief-to-web/ROUND-0005_double-allee-data-identifiability_REQUEST.md`  
**Status:** COMPLETE FOR REQUESTED AUDIT SCOPE

## Executive finding

**C-DA-3 is WEAKENED, not killed.**

A real-data branch is scientifically credible for **component-mechanism and demographic-threshold identifiability**, but the evidence does not currently justify making fractional memory part of the empirical core.

The exact 1988–2000 island-fox raw dataset was **not located in an open repository** despite explicit title/DOI/author/repository/NPS searches. Several high-quality open alternatives exist, but none simultaneously gives two separately observed component mechanisms, long low-density dynamics and a design capable of identifying fractional memory.

## Island fox audit

### Raw-data availability

**Classification: NOT VERIFIED OPEN.**

No Dryad, Zenodo, Figshare, OSF or NPS direct raw-data package corresponding to the exact Angulo et al. 1988–2000 dataset was found.

NPS currently documents annual abundance estimation from repeated trapping grids/PIT tags and annual survival from radio-collared animals and provides program reports through its DataStore. This makes historical/current data potentially obtainable through agency/authors, but not reproducibly downloadable from the evidence found here.

### Actual observed structure known from sources

Angulo et al. analyzed:
- density;
- adult/pup survival;
- proportion of breeding adult females;
- Golden Eagle/predation context;
- per-capita population trends;
- multiple island populations.

### Suitability

**One versus two component effects:** potentially good because survival and breeding are separately observed.

**Threshold estimation:** potentially good, subject to obtaining raw uncertainties/sample sizes.

**Fractional memory:** weak. Annual temporal depth is limited, environmental/predation forcing is strong, and later recovery includes major interventions (captive breeding, releases, eagle removal, etc.).

## Alternative empirical systems

### 1. Northwest Atlantic cod — OPEN

Dryad DOI **10.5061/dryad.r4xgxd2dg**, CC0.

Contains stock/recruitment data and supports Bayesian Allee-threshold inference. Excellent low-abundance threshold benchmark; component mechanisms are not separately observed.

### 2. Atlantic herring — OPEN SUPPLEMENTARY DATA

Perälä & Kuparinen 2017, DOI **10.1098/rspb.2017.1284**.

Nine stock–recruitment series; data XLS supplied with the article. The paper demonstrates directly that removing low-abundance observations destroys the ability to discriminate depensation from compensation.

Excellent practical-identifiability benchmark; not a multiple-component dataset.

### 3. Freshwater mussel fertilization — OPEN DRYAD

Dryad DOI **10.5061/dryad.bb75p**.

Individual/local data on fertilization, density and spatial/flow conditions from 10 populations across 2012–2013. Excellent component-Allee and spatial-observation benchmark; too short for memory inference.

### 4. Spongy/gypsy moth — EMPIRICAL, RAW REPOSITORY NOT VERIFIED

Robinet et al. 2008, DOI **10.1111/j.1365-2656.2008.01417.x**.

Release–recapture experiment: 5967 males released, 684 recaptured; spatial and temporal separation jointly determine mate-finding. Excellent mechanistic Allee design, but a stable raw repository was not located.

### 5. Crested Ibis — EMPIRICALLY VERY CLOSE, RAW REPOSITORY NOT VERIFIED

Li et al. 2022, DOI **10.1016/j.gecco.2022.e02103**.

Two reintroduced populations; simultaneous component effects in survival and reproduction; demographic effect in Qianyang; mate limitation/predation discussed. This is a high-priority author/institution data request.

## Identifiability prior art

### Ecological/Allee

Perälä & Kuparinen 2017 shows that practical inference of Allee/depensation structure is conditional on having actual low-abundance observations.

Johnson et al. 2019, DOI **10.1371/journal.pbio.3000399**, uses replicated low-density longitudinal experiments plus stochastic model discrimination to distinguish alternative Allee model structures. It is methodological prior art for mechanism/model discrimination.

### Fractional structural identifiability

- Alavi et al. 2015, arXiv:1511.01402: coefficient-mapping structural identifiability for non-commensurate fractional-order models.
- Nazarian–Haeri–Tavazoei 2010, DOI **10.1016/j.isatra.2009.11.007**: analytical identifiability of fractional systems; identifiability degrades for smaller fractional order.
- Varalda–Pequito 2026, DOI **10.1016/j.ifacsc.2026.100397**: graph-theoretic structural identifiability for fractional-order discrete-time networks.

A generic “fractional-model identifiability theorem” is therefore not novel.

## Memory / delay / noise

No evidence supports claiming that fractional memory is intrinsically indistinguishable from delay/noise: engineering literature can jointly estimate fractional order, delay and parameters under designed-input assumptions, including noisy/colored-noise settings.

But passive ecological inference is different. Kharazmi et al. 2021, DOI **10.1038/s43588-021-00158-0**, compares integer, time-delay and fractional models under sparse/noisy observational data and emphasizes structural/practical identifiability and model uncertainty.

For island fox specifically, fractional order could absorb:
- predation shifts;
- management interventions;
- environmental autocorrelation;
- latent states;
- observation error.

A good fit would not establish biological memory.

## Joint prior-art result

No resolving source was found that jointly identifies from real ecological data:
1. two separable component Allee mechanisms;
2. an emergent demographic threshold; and
3. a fractional-order memory parameter/kernel.

But each subproblem has mature prior art.

## C-DA-3 classification

**WEAKENED.**

### Viable core

A strong theorem/application could ask:

> what minimal observation design makes two component effects and their emergent demographic threshold structurally/practically distinguishable?

A useful result could be a non-identifiability theorem or minimal-data/rank condition.

### Weakened part

Making fractional memory compulsory is not supported by current datasets. It should be an optional extension tested only after the component/threshold model is identifiable.

## Real-data branch verdict

**Scientifically credible: YES, for threshold/component inference.**  
**Scientifically credible: NOT YET, for fractional-memory estimation.**

## Files updated

- `research/double-allee/DATASETS.md`
- `research/web-search/2026-09-28_double-allee-data-identifiability.md`
- provenance registries;
- corpus/bibliography;
- this RETURN.

## Recommended next action

Promote an **observation-design / identifiability** theorem only if the Chief wants an applied branch, but decouple it from fractional order initially.

For real data, use open herring/cod/mussel datasets immediately as methodological benchmarks while separately seeking island-fox or Crested-Ibis raw data from authors/agencies.

## RETURN TO CHIEF

**What the evidence supports:** real data can support serious Allee threshold/model discrimination, and several open datasets are immediately usable.

**What it does not support:** treating the 1988–2000 island-fox data as already open, or fitting fractional memory to sparse annual field data without a confounding/identifiability proof.

**C-DA-3:** WEAKENED, not killed.

**Best open threshold benchmark:** northwest Atlantic cod / Atlantic herring.

**Best component-effect benchmark:** freshwater mussel.

**Closest multiple-component empirical systems:** island fox and Crested Ibis, both requiring data-access follow-up.

**Most important unresolved question:** can raw component-level longitudinal data be obtained at sufficient temporal resolution to support a genuine mechanism-identifiability theorem rather than aggregate threshold fitting?