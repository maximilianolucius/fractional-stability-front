# Double Allee — Dataset Inventory

**Status:** evidence-backed access/identifiability audit completed in ROUND-0005 (2026-09-28).

The inventory separates:
- an **open reusable dataset**;
- an **empirical system/data lead** with unverified raw access;
- a **methodological benchmark** that may not contain multiple component mechanisms.

Fractional-memory suitability is assessed independently from Allee suitability.

## D-001 — Island fox demographic system

**Primary study:** Angulo, Roemer, Berec, Gascoigne, Courchamp (2007), *Double Allee Effects and Extinction in the Island Fox*, DOI 10.1111/j.1523-1739.2007.00721.x.

**Species/system:** island fox populations on the California Channel Islands.

**Study period analyzed:** 1988–2000.

**Observed/analyzed variables:**
- fox density;
- adult and pup survival;
- proportion of breeding adult females;
- Golden Eagle presence/predation context;
- per-capita population trends.

**Multiple mechanisms:** yes. Survival/predation and reproduction/breeding components are separately analyzed.

**Threshold relevance:** strong. The paper reports a demographic effect and suboptimal growth below roughly 7 foxes/km².

**Raw access audit:** **NOT VERIFIED OPEN.**

ROUND-0005 searched:
- exact title/DOI/author combinations;
- supplementary-material queries;
- Dryad;
- Zenodo;
- Figshare;
- OSF;
- NPS/IRMA DataStore;
- Channel Islands National Park monitoring pages;
- later island-fox datasets/reuse.

No machine-readable repository containing the exact 1988–2000 Angulo dataset was identified.

**Current NPS data structure:** NPS describes annual island-wide abundance estimation from multiple trapping grids (five nights/grid, PIT tagging) and annual survival/mortality estimation from continuing monitoring of radio-collared foxes. Program reports are available through NPS DataStore. This establishes a realistic agency-data path, not open access to the historical raw table.

**Interventions/confounding:** especially severe after 1999: captive breeding/reintroduction, Golden Eagle removal, Bald Eagle restoration and other management actions.

**Suitability for one-vs-two component discrimination:** potentially high if raw survival/reproduction data and uncertainty are obtained.

**Suitability for fractional memory:** **low with current evidence**. Annual depth, external predation, interventions, observation error and between-island heterogeneity make memory strongly confounded.

**Current classification:** **high-value empirical system; data access unresolved.**

---

## D-002 — Northwest Atlantic cod — OPEN

**Article:** Perälä, Hutchings, Kuparinen (2022), *Allee effects and the Allee-effect zone in northwest Atlantic cod*, DOI 10.1098/rsbl.2021.0439.

**Dataset:** Dryad DOI **10.5061/dryad.r4xgxd2dg**.

**Access/licence:** open; indexed as **CC0-1.0**.

**Raw/processed status:** reusable stock/recruitment table (`Data.csv`) derived from the 2021 NAFO Subdivision 3Ps cod assessment; analysis/code provenance is documented.

**Measured variables:** spawning-stock biomass and recruitment.

**Low-density coverage:** explicitly central to the published analysis; threshold/Allee-zone inference is the scientific target.

**Multiple mechanisms separately observed:** no.

**Threshold estimation:** **high suitability.**

**Memory estimation:** moderate temporal potential but scientifically confounded by fishing, environment and stock-assessment processing.

**Use in this project:** open benchmark for threshold inference and uncertainty, not direct evidence of double dormancy.

---

## D-003 — Atlantic herring, nine populations — OPEN SUPPLEMENTARY DATA

**Article:** Perälä & Kuparinen (2017), DOI **10.1098/rspb.2017.1284**.

**Access:** open article; data are included as an electronic supplementary **XLS**.

**System:** nine Atlantic herring populations.

**Variables:** spawning-stock abundance/biomass and recruitment time series from stock assessments.

**Low-density coverage:** variable across stocks; the source deliberately deletes low-abundance data to quantify inferential degradation.

**Major methodological result:** without observations at low abundance, compensation versus depensation cannot be objectively discriminated and uncertainty expands sharply.

**Multiple mechanisms separately observed:** no.

**Threshold estimation/model selection:** **high benchmark value.**

**Memory estimation:** not recommended as a first use; aggregate fisheries forcing creates substantial confounding.

**Use in this project:** practical-identifiability and experimental-design benchmark.

---

## D-004 — Freshwater mussel fertilization — OPEN DRYAD

**Article:** Terui et al. (2015), *A cryptic Allee effect: spatial contexts mask an existing fitness-density relationship*, DOI 10.1098/rsos.150034.

**Dataset:** Dryad DOI **10.5061/dryad.bb75p**.

**Files:** `RSOSdata_final.xlsx` + README.

**Sampling:** 2012–2013; 10 populations; 99 gravid females sampled and 91 usable in the fertilization analysis.

**Variables:** fertilization rate, local/population conspecific density, spatial scale, flow/water-depth/environmental covariates.

**Mechanism:** sperm limitation/fertilization component Allee effect whose detectability depends on spatial context.

**Multiple mechanisms:** not two component Allee mechanisms in the required sense; spatial environment modifies the component effect.

**Threshold/component estimation:** excellent for component-effect observation design.

**Memory estimation:** **not suitable**; only two sampling years.

**Use in this project:** open benchmark for component-level identifiability and spatial masking.

---

## D-005 — Spongy/gypsy moth mate finding — EMPIRICAL; RAW REPOSITORY NOT VERIFIED

**Article:** Robinet et al. (2008), DOI **10.1111/j.1365-2656.2008.01417.x**.

**Design:** release–recapture experiments during 2003–2004 with controlled/recorded spatial and temporal separation.

**Sample:** 5967 adult males released; 684 recaptured.

**Measured mechanism:** probability of male mate-location as a function of spatial and temporal offsets; temporal asynchrony and spatial dispersion jointly affect mating success.

**Threshold relevance:** mechanistic model derived from experiments yields an Allee threshold.

**Raw access:** full article accessible; **no stable machine-readable raw repository located in ROUND-0005**.

**Multiple mechanisms:** interacting spatial and temporal contributors to one mate-finding mechanism, not clearly two independent demographic component effects.

**Memory suitability:** poor; short experimental design.

**Use:** strong mechanistic lead; author/USDA/Forest Service data request could be worthwhile.

---

## D-006 — Crested Ibis reintroduction — MULTIPLE-COMPONENT LEAD; RAW ACCESS UNCERTAIN

**Article:** Li et al. (2022), DOI **10.1016/j.gecco.2022.e02103**.

**Access:** article open access.

**System:** two spatially isolated reintroduced Crested Ibis populations in Shaanxi Province, China.

**Measured/analyzed variables:** time-series population size, survival and reproductive rates/per-female breeding probability.

**Multiple mechanisms:** simultaneous component Allee effects in survival and reproduction are reported; in Qianyang their combination produces a demographic effect. Mate limitation and predation are discussed as candidate mechanisms.

**Raw access:** **no verified open repository located in this round.**

**Suitability for component/threshold inference:** potentially very high.

**Memory suitability:** unknown and should not be presumed.

**Current classification:** closest alternative empirical system to island fox; high-priority data-request target.

---

## D-007 — BT-474 low-density population experiments — METHODOLOGICAL BENCHMARK

**Article:** Johnson et al. (2019), DOI **10.1371/journal.pbio.3000399**.

**System:** controlled in-vitro breast-cancer cell populations at multiple very low initial densities.

**Access:** article links data/code via the project repository.

**Design:** replicated longitudinal trajectories; stochastic population modeling.

**Inference task:** compares exponential and Allee model structures and estimates parameters under demographic stochasticity.

**Ecological status:** not a field ecological population. It is retained only because it demonstrates a strong low-density observation design and model-discrimination workflow.

**Use:** methodological prior art for C-DA-3; not the eventual ecological application.

---

## D-008 — Multiple-Allee meta-analysis raw table — OPEN DISCOVERY RESOURCE

**Dataset:** Muir, Lajeunesse & Kramer (2024), Dryad DOI **10.5061/dryad.2ngf1vhvj**.

**Files:** literature table, effect-size table and raw-data workbook.

**Use:** excellent source-discovery and cross-mechanism evidence resource.

**Limitation:** meta-analytic compilation, not one longitudinal dynamic system; unsuitable as the direct calibration dataset for a memory/threshold model.

---

# Dataset acceptance assessment

| Dataset | Open raw/reusable? | Component mechanism observed? | Multiple components separately? | Low-density threshold value | Longitudinal memory value | Current role |
|---|---|---|---|---|---|---|
| Island fox | No open raw copy located | yes | yes | high | low/uncertain | prime biological lead |
| Cod | yes, CC0 | aggregate demographic | no | high | moderate but confounded | threshold benchmark |
| Herring | yes, supplementary XLS | aggregate demographic | no | high | moderate but confounded | model-selection benchmark |
| Freshwater mussel | yes, Dryad | yes, fertilization | no | component-level high | none | component benchmark |
| Spongy moth | raw repo not verified | yes, mate finding | interacting submechanisms | high | low | experimental lead |
| Crested Ibis | raw repo not verified | survival + reproduction | yes | high | unknown | prime alternative biological lead |
| BT-474 cells | linked data/code | cooperative birth/growth | model alternatives | high | controlled time series | methods benchmark |

# Identifiability conclusion from ROUND-0005

The available evidence supports a real-data branch centered on:

[
	ext{observation design}
	o
	ext{component mechanism discrimination}
	o
	ext{demographic threshold identifiability}.
]

It does **not** yet support making fractional memory a required empirical parameter.

A fractional-memory extension should pass an additional gate:
1. component/threshold parameters structurally identifiable without memory;
2. temporal depth sufficient;
3. delay/colored-noise/latent-driver competitors explicitly fitted;
4. fractional parameter remains identifiable under realistic observation noise/intervention structure;
5. out-of-sample prediction or independent demographic variables improve materially.

# Recommended data strategy

1. Use **herring/cod** immediately to benchmark threshold/model-selection methodology.
2. Use **freshwater mussel** to benchmark component-level observation/design issues.
3. Pursue raw **island fox** and **Crested Ibis** data through authors/agencies.
4. Treat spongy-moth experiments as a mechanism-design reference.
5. Do not fit fractional memory to sparse annual conservation series before a formal identifiability/confounding analysis.
