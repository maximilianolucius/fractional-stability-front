# 2026-09-28 — Double Allee Data and Identifiability Audit

**Round:** ROUND-0005  
**Request:** `research/coordination/chief-to-web/ROUND-0005_double-allee-data-identifiability_REQUEST.md`

## 1. Island fox raw-data trace

Primary source:
Angulo, Roemer, Berec, Gascoigne & Courchamp (2007), *Double Allee Effects and Extinction in the Island Fox*, DOI 10.1111/j.1523-1739.2007.00721.x.

### Searches performed

Searched exact title, DOI, authors, “dataset/data/supplementary”, Dryad, Zenodo, Figshare, OSF, NPS/IRMA DataStore, Channel Islands monitoring pages and later island-fox data records.

### Result

**No public machine-readable repository containing the exact 1988–2000 demographic dataset underlying Angulo et al. was located in the searched corpus.**

This is not proof that the data are unavailable. It is a verified failure to locate an open copy.

NPS does maintain a long-running island-fox monitoring program:
- annual abundance is estimated per island from multiple trapping grids;
- grids are trapped for five nights;
- animals are PIT-tagged;
- annual survival/mortality is estimated using radio-collared samples (40+ per island in current monitoring descriptions);
- NPS DataStore contains program reports and monitoring documentation.

However, the pages located do not expose the historical Angulo 1988–2000 individual/annual raw table as a direct download.

### Identifiability limitations of the island-fox system

Even if the historical data are obtained, the system is difficult for fractional-memory inference:
- the 1988–2000 span is short at annual resolution;
- populations/islands differ;
- predation by Golden Eagles is an explicit time-varying driver;
- after 1999, captive breeding, reintroduction, eagle removal, bald-eagle restoration and other management interventions strongly break stationarity;
- survival, reproduction and density are estimated with their own observation errors;
- a memory kernel/order could absorb latent environmental forcing, interventions or autocorrelation.

The system is scientifically excellent for **component-mechanism + demographic threshold** inference, but currently weak for a defensible fractional-order estimate.

## 2. Alternative empirical systems

### D-ALT-1 — Northwest Atlantic cod (open)

Dryad DOI: **10.5061/dryad.r4xgxd2dg**  
Article: Perälä, Hutchings & Kuparinen, *Allee effects and the Allee-effect zone in northwest Atlantic cod*, Biology Letters (2022), DOI 10.1098/rsbl.2021.0439.

**Access:** open; Dryad reports CC0.  
**Files:** CSV plus analysis/code provenance; data extracted from the 2021 stock assessment of NAFO Subdivision 3Ps cod.  
**Variables:** spawning-stock biomass and recruitment.  
**Strength:** directly designed for low-abundance Allee/threshold inference and Bayesian uncertainty.  
**Weakness:** aggregate stock–recruitment data; component mechanisms such as mate limitation/predation are not separately observed.  
**Memory suitability:** long time series is better than island fox, but environmental/fishing forcing and stock-assessment smoothing make a fractional-memory interpretation highly confounded.

**Verdict:** strong threshold/model-selection dataset; weak multiple-component dataset.

### D-ALT-2 — Atlantic herring, nine populations (open supplementary data)

Perälä & Kuparinen (2017), DOI **10.1098/rspb.2017.1284**.

**Access:** article open; supplementary XLS contains the data used in the manuscript.  
**Structure:** nine Atlantic herring populations; stock–recruitment time series spanning different abundance ranges.  
**Analysis:** Bayesian comparison of compensatory/depensatory stock–recruitment models.  
**Key methodological result:** evidence for an Allee effect deteriorates sharply when low-abundance observations are removed; the paper explicitly demonstrates that low-density coverage is essential for discrimination.

**Strength:** ideal benchmark for practical identifiability/model-selection under varying low-density coverage.  
**Weakness:** aggregate stock/recruitment observations; does not separately measure two component Allee mechanisms.

**Verdict:** strong identifiability benchmark, not a double-dormancy dataset.

### D-ALT-3 — Freshwater mussel fertilization (open Dryad)

Terui et al. (2015), dataset DOI **10.5061/dryad.bb75p**; article DOI 10.1098/rsos.150034.

**Access:** open Dryad; `RSOSdata_final.xlsx` + README.  
**Sampling:** 10 populations, 2012–2013; 99 gravid females sampled, 91 usable for fertilization analysis.  
**Variables:** local/population conspecific density, fertilization rate, water-flow/spatial covariates and individual/population context.  
**Mechanism:** sperm limitation/fertilization component Allee effect modulated by local spatial conditions.  
**Strength:** individual/component-level response plus spatial covariates; directly demonstrates scale-dependent detectability.  
**Weakness:** only two years; not a longitudinal population-dynamics series; one main component mechanism.

**Verdict:** excellent component-effect identification dataset; unsuitable for fractional memory.

### D-ALT-4 — Spongy/gypsy moth mate finding (real experimental data; raw repository not verified)

Robinet et al. (2008), DOI **10.1111/j.1365-2656.2008.01417.x**.

**Data:** release–recapture experiments in 2003–2004; 5967 adult males released, 684 recaptured; spatial distance and temporal emergence offsets were manipulated/recorded.  
**Mechanism:** mate-finding failure driven jointly by spatial and temporal dispersion; model yields an Allee threshold.  
**Access:** article is freely accessible, but no stable raw-data repository was located in this search.

**Strength:** experimentally resolved mechanism with low-density relevance and controlled spatial/temporal factors.  
**Weakness:** short experimental design and no verified downloadable raw table.

**Verdict:** realistically obtainable/replicable mechanism dataset, but not yet an approved open dataset.

### D-ALT-5 — Crested Ibis reintroduction (empirical multiple component effects; raw access uncertain)

Li et al. (2022), DOI **10.1016/j.gecco.2022.e02103**.

Two spatially isolated reintroduced populations were followed with time-series demographic data. The study reports simultaneous component Allee effects in survival and reproduction; in Qianyang, reduced adult survival and per-female breeding probability generated a demographic Allee effect. Mate limitation and predation are proposed mechanisms.

**Strength:** extremely close biological analogue to island fox and double-component demography.  
**Access:** article is open access; no open raw dataset was verified in this round.

**Verdict:** high-priority author/institution data-request candidate; not presently reproducible from a verified repository.

## 3. Identifiability prior art

### Allee model discrimination is already an active inference problem

Johnson et al. (2019), PLOS Biology, DOI **10.1371/journal.pbio.3000399**, used longitudinal low-density cell-population experiments, stochastic models, parameter estimation and model comparison to discriminate exponential versus weak/strong Allee structures. Data/code are linked through the publication/GitHub.

This is not field ecology, but it is strong methodological prior art against claiming that Allee-model discrimination itself is new.

Perälä & Kuparinen (2017) provides direct ecological evidence that practical identifiability of depensation is controlled by low-abundance observations and model choice.

### Fractional structural identifiability already has general theory

Alavi et al. (2015), arXiv:1511.01402, develops coefficient-mapping structural-identifiability analysis for general non-commensurate fractional-order models and proves identifiability for specified fractional battery-model classes.

Nazarian, Haeri & Tavazoei (2010), DOI **10.1016/j.isatra.2009.11.007**, analytically studies model-structure and parameter identifiability of fractional-order systems from input/output frequency content and shows identifiability degrades markedly as fractional order decreases, even with rich inputs.

Varalda & Pequito (2026), DOI **10.1016/j.ifacsc.2026.100397**, proves a graph-theoretic structural-identifiability result for fractional-order discrete-time networks: network identifiability is characterized via identifiable subsystems and input-output reachability.

Therefore “structural identifiability for a fractional network” is itself not a fresh concept.

## 4. Memory / delay / noise confounding

The literature shows two complementary facts.

### Controlled system-identification settings can estimate them jointly

Recent engineering work estimates fractional order and time delay simultaneously even with measurement/colored noise, e.g.:
- Liu, Wang & Zhang (2025), DOI 10.1016/j.jfranklin.2024.107444;
- Wang et al. (2025), DOI 10.1016/j.ymssp.2024.111930.

Thus it would be incorrect to claim that fractional order and delay/noise are intrinsically mathematically indistinguishable.

### Passive ecological data are much less informative

Kharazmi et al. (2021), DOI **10.1038/s43588-021-00158-0**, compares integer-order, time-delay and fractional epidemiological models and emphasizes structural/practical identifiability, sparse/noisy data and model uncertainty. Different model classes can fit observed trajectories while using time-varying parameters, delays or fractional operators to absorb history.

For island fox, there are no designed inputs, and the strongest memory-like signals coincide with known external drivers and interventions. Therefore a fractional-order parameter would require a model-selection/identifiability proof, not merely a good fit.

## 5. Joint component + threshold + fractional-order prior art

**No paper was identified in the searched corpus that jointly proves structural/practical identifiability of:**
1. two separately parameterized component Allee mechanisms;
2. their emergent demographic threshold; and
3. a fractional memory order/kernel

from a real ecological longitudinal/spatial dataset.

However, each piece separately has significant prior art, which raises the quality bar substantially.

## 6. C-DA-3 classification

**WEAKENED, NOT KILLED.**

The full four-way empirical ambition is presently too strong:
- island-fox raw data are not verified open;
- the best open ecological datasets usually observe either aggregate demographic threshold behavior or one component mechanism, not two;
- available passive field series do not justify fractional memory without an explicit confounding analysis;
- generic fractional identifiability theory already exists.

A scientifically credible branch remains if it is reframed as:

> identify the **minimal observation design** needed to distinguish two component mechanisms and an emergent demographic threshold, and prove when adding a memory parameter becomes non-identifiable or identifiable.

The most valuable theorem may be a **non-identifiability/minimal-data result**, with fractional memory treated as an optional stress test rather than a required biological feature.

## 7. Real-data branch credibility

**Credible for threshold/component identifiability; not yet credible for fractional memory.**

Best open resources now:
1. Atlantic herring supplementary data — model-selection/low-density benchmark;
2. northwest Atlantic cod Dryad — threshold inference benchmark;
3. freshwater mussel Dryad — component-mechanism/spatial benchmark.

Best biologically close but access-uncertain systems:
1. island fox;
2. Crested Ibis;
3. spongy moth release–recapture.

## Recommended next action

If C-DA-3 survives Chief review:
1. do **not** start by fitting a fractional model;
2. formalize an observation model for abundance + survival + reproduction;
3. derive structural identifiability/non-identifiability for one versus two component effects;
4. use herring/cod/mussel datasets as calibration/benchmark cases;
5. pursue island-fox or Crested-Ibis raw data through authors/agencies;
6. introduce memory only after a proof or diagnostic shows it can be separated from delays/latent environmental forcing.