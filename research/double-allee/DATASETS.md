# Double Allee — Dataset Inventory

**Status:** evidence-backed access/identifiability audit completed in ROUND-0005 and updated by Chief after ROUND-0006.

The inventory separates:
- an **open reusable dataset**;
- an **empirical system/data lead** with unverified raw access;
- a **methodological benchmark** that may not contain multiple component mechanisms.

Fractional-memory suitability is assessed independently from Allee suitability.

## D-001 — Island fox demographic system

**Primary study:** Angulo, Roemer, Berec, Gascoigne, Courchamp (2007), *Double Allee Effects and Extinction in the Island Fox*, DOI 10.1111/j.1523-1739.2007.00721.x.

**Species/system:** island fox populations on the California Channel Islands.

**Study period analyzed:** 1988–2000.

**Observed/analyzed variables:** fox density; adult and pup survival; proportion of breeding adult females; Golden Eagle/predation context; per-capita population trends.

**Multiple mechanisms:** yes.

**Raw access:** **NOT VERIFIED OPEN.**

**Current classification:** high-value biological target; data access unresolved.

---

## D-002 — Northwest Atlantic cod — OPEN

**Article:** Perälä, Hutchings, Kuparinen (2022), DOI 10.1098/rsbl.2021.0439.  
**Dataset:** Dryad DOI 10.5061/dryad.r4xgxd2dg.  
**Role:** open threshold-inference benchmark; aggregate demographic data rather than separate component mechanisms.

---

## D-003 — Atlantic herring, nine populations — OPEN SUPPLEMENTARY DATA

**Article:** Perälä & Kuparinen (2017), DOI 10.1098/rspb.2017.1284.  
**Role:** strong benchmark for the necessity of low-density observations in Allee/depensation model discrimination.

---

## D-004 — Freshwater mussel fertilization — OPEN DRYAD

**Article:** Terui et al. (2015), DOI 10.1098/rsos.150034.  
**Dataset:** Dryad DOI 10.5061/dryad.bb75p.  
**Role:** component-Allee measurement benchmark with spatial covariates.

---

## D-005 — Spongy/gypsy moth mate finding

**Article:** Robinet et al. (2008), DOI 10.1111/j.1365-2656.2008.01417.x.  
**Role:** strong mechanistic low-density experiment; raw repository not verified.

---

## D-006 — Crested Ibis reintroduction

**Article:** Li et al. (2022), DOI 10.1016/j.gecco.2022.e02103.  
**Multiple components:** survival + reproduction.  
**Role:** high-value biological target; raw access unresolved.

---

## D-007 — BT-474 low-density population experiments

**Article:** Johnson et al. (2019), DOI 10.1371/journal.pbio.3000399.  
**Role:** methodological benchmark for replicated low-density model discrimination.

---

## D-008 — Multiple-Allee meta-analysis raw table

**Dataset:** Muir, Lajeunesse & Kramer (2024), Dryad DOI 10.5061/dryad.2ngf1vhvj.  
**Role:** source-discovery and cross-mechanism evidence resource.

---

## D-009 — Tribolium castaneum mechanism-resolved density dependence — OPEN DATA/CODE

**Article:** Buddh, Krishna & Agashe (2024), *Density dependent survival drives variation in density dependent population growth of an insect pest*, Oikos, DOI 10.1111/oik.10813.

**Why this dataset is strategically important:** the paper explicitly models density-dependent population growth as the **product of density dependence in fecundity and survival**, and experimentally estimates both component functions.

This is almost exactly the observational architecture needed to test the mechanism-resolved formalism, even though the published system is not presented as a Double-Allee/double-dormancy case.

**Data/code access:** the publisher states that data and R code are available through Figshare:
- DOI 10.6084/m9.figshare.26413420
- DOI 10.6084/m9.figshare.26413462

**Measured structure:** density-dependent fecundity and survival across experimental habitats/population conditions.

**Multiple components separately observed:** yes — fecundity and survival.

**Threshold relevance:** indirect. The published question is density dependence rather than a strong Allee threshold, so the project must not relabel the empirical result.

**Mechanism-space value:** **very high.**

Planned use:
1. reproduce the fitted component functions;
2. convert them into penalty profiles g_i(x) where appropriate;
3. test convexity/monotonicity/shape hypotheses;
4. estimate a mechanism-strength phase diagram;
5. demonstrate how altering component strength could move the system toward or away from an Allee threshold;
6. clearly separate observed inference from counterfactual extrapolation.

**Current classification:** best immediately open **mechanism-resolved** dataset for the selected theory.

---

# Dataset acceptance assessment

| Dataset | Open raw/reusable? | Components separately observed? | Threshold value | Mechanism-space value | Current role |
|---|---|---:|---:|---:|---|
| Island fox | not verified open | yes | high | very high | prime Double-Allee biological target |
| Cod | yes | no | high | medium | threshold benchmark |
| Herring | yes | no | high | medium | model-selection benchmark |
| Freshwater mussel | yes | one main component | component-level | high | component benchmark |
| Spongy moth | raw repo not verified | mechanism detail | high | high | experimental lead |
| Crested Ibis | not verified open | yes | high | very high | prime alternative biological target |
| BT-474 cells | linked data/code | model alternatives | high | medium | methods benchmark |
| Tribolium | yes, Figshare | yes: fecundity + survival | indirect | **very high** | primary open mechanism-resolved benchmark |

# Current data strategy

1. **Tribolium first** for immediate mechanism-resolved reproduction.
2. **Herring/cod** for threshold/model-selection methodology.
3. **Freshwater mussel** for component-level observation issues.
4. Pursue raw **island fox** and **Crested Ibis** data as higher-biological-specificity targets.
5. Do not require fractional-memory estimation for the primary paper.
