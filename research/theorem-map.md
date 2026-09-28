# Theorem Map

**Status:** first verified/qualified nodes promoted by Chief after ROUND-0001 and ROUND-0002.

Represent the field by logical relationships among results, not chronology alone.

## Fractional-stability core

### T-001 — Commensurate fractional spectral-sector criterion

**Source:** Matignon (1998), DOI 10.1051/proc:1998004  
**System class:** finite-dimensional linear autonomous generalized fractional system  
**Assumptions:** scalar commensurate order in the source framework; admissible order range as stated by source  
**Statement:** asymptotic stability is characterized by exclusion of the relevant characteristic/eigenvalue roots from the fractional instability sector.  
**Result strength:** necessary and sufficient  
**Proof method:** spectral/complex analysis  
**Generalizes:** integer-order left-half-plane geometry via fractional sector geometry  
**Specializes to:** ordinary Hurwitz condition at the integer-order limit  
**Sharpness/counterexample:** boundary requires separate treatment  
**Unresolved extension:** simple structural analogues for broad incommensurate and structured families  
**Verification status:** primary/full  
**Chief note:** do not silently relabel the original operator/initial-condition formulation as a modern Caputo theorem.

### T-002 — Caputo strict-sector and boundary/Jordan clarification

**Source:** Brandibur, Garrappa, Kaslik (2021), DOI 10.3390/math9080914  
**System class:** linear Caputo fractional systems  
**Assumptions:** source-specific commensurate order setting  
**Statement:** strict sector placement gives asymptotic stability; boundary stability requires the appropriate eigenvalue-index/Jordan condition.  
**Result strength:** exact characterization in stated setting  
**Proof method:** Mittag-Leffler matrix-function/spectral analysis  
**Generalizes:** clarifies T-001 in a modern Caputo setting  
**Sharpness/counterexample:** corrects common boundary/multiplicity imprecision  
**Unresolved extension:** multi-order/incommensurate structure is more complicated  
**Verification status:** review/full

### T-003 — Non-commensurate BIBO stability test

**Source:** Sabatier, Farges, Trigeassou (2013), DOI 10.1016/j.sysconle.2013.04.008  
**System class:** linear non-commensurate fractional systems  
**Assumptions:** recursive realization and transfer-system framework of source  
**Statement:** BIBO stability is equivalent to the authors' recursive Cauchy/root-counting test.  
**Result strength:** necessary and sufficient for BIBO stability  
**Proof method:** recursively defined closed-loop realization + Cauchy theorem  
**Generalizes:** exact algorithmic testing beyond the simple one-matrix commensurate sector test  
**Limitations:** not a simple finite structural matrix characterization; does not by itself settle every state-stability notion  
**Verification status:** publisher abstract/metadata; theorem-level assumptions pending full-text audit

## Structured-matrix bridge

### T-010 — Generalized multiplicative D-stability in LMI regions

**Source:** Kushel, Pavani (2022), DOI 10.1007/s10884-020-09891-y  
**System class:** matrix regional stability  
**Assumptions:** source's unbounded LMI-region framework; multiplicative positive diagonal perturbations  
**Statement:** preservation of spectral localization in an LMI region under positive diagonal multiplication is formulated and characterized through exact boundary-avoidance/equivalent criteria.  
**Result strength:** exact at the stated generalized/regional level  
**Proof method:** continuity/boundary arguments; determinant and additive-compound machinery  
**Generalizes:** classical multiplicative D-stability  
**Specializes to:** conic-sector relative D-stability, directly relevant to fractional stability geometry  
**Sharpness/counterexample:** general criteria may retain a universal quantifier over positive diagonal scalings  
**Unresolved extension:** finite/quantifier-free exact tests for structured classes  
**Verification status:** primary/full  
**Chief consequence:** broad “fractional D-stability is missing” hypothesis is rejected.

### T-011 — Conic-region generalized diagonal dominance implies regional D-stability

**Source:** Kushel, Pavani (2021), DOI 10.1016/j.laa.2021.08.004  
**System class:** matrix regional stability  
**Assumptions:** generalized diagonal-dominance conditions relative to an LMI/conic region  
**Statement:** source-specific diagonal dominance gives a tractable sufficient certificate for regional multiplicative D-stability; conic cases are explicitly connected to fractional-order systems.  
**Result strength:** sufficient  
**Proof method:** Gershgorin/generalized dominance and matrix inequalities  
**Generalizes:** classical diagonal-dominance stability certificates  
**Unresolved extension:** identify classes where the certificate becomes exact  
**Verification status:** primary/full

### T-012 — Extended diagonal stability for fractional positive systems

**Source:** Zhang, Huang (2017), DOI 10.1016/j.laa.2017.06.018  
**System class:** continuous-time fractional positive linear systems  
**Assumptions:** positive/Metzler structure and source-defined extended diagonal-stability notion  
**Statement:** necessary-and-sufficient conditions are given for the source's extended diagonal stability/stabilization property.  
**Result strength:** necessary and sufficient for that defined property  
**Proof method:** Metzler/diagonal stability + LMI structure  
**Limitations:** not automatically equivalent to unrestricted multiplicative D-stability  
**Verification status:** publisher abstract/metadata; definition-level full-text comparison pending

## Double/Multiple Allee core

### T-101 — Multiple component Allee effects and double dormancy framework

**Source:** Berec, Angulo, Courchamp (2007), DOI 10.1016/j.tree.2006.12.002  
**System class:** ecological population dynamics / conceptual-model framework  
**Assumptions:** multiple component fitness mechanisms  
**Statement:** multiple Allee effects are defined through simultaneous component Allee effects; the paper explicitly introduces interaction classes including double dormancy, where two component effects individually fail to create a strong demographic threshold but jointly create one.  
**Result strength:** conceptual/analytical modeling framework, not yet a general theorem  
**Proof method:** ecological synthesis + illustrative population model  
**Sharpness/counterexample:** mechanism count is not threshold count  
**Unresolved extension:** general composition theorem for threshold emergence/location  
**Verification status:** full-text/preview corroborated

### T-102 — Planar Double-Allee predator–prey bifurcation structure

**Source:** Pal, Saha (2015), DOI 10.1016/j.chaos.2014.12.007  
**System class:** 2D nonlinear predator–prey ODE  
**Assumptions:** specific compounded Double-Allee prey growth and predator interaction law  
**Statement:** equilibrium regimes, bistability/separatrices, and codimension-one/two bifurcation structure are characterized under model assumptions.  
**Result strength:** exact/model-specific analytical results  
**Proof method:** planar dynamical systems, nullclines, Jacobian and bifurcation analysis  
**Limitations:** not a general multiple-component or arbitrary-network theorem  
**Verification status:** primary/full excerpt

### T-103 — Strong-Allee interacting-patch persistence/extinction

**Source:** Lanchier (2013), DOI 10.1239/aap/1386857863  
**System class:** stochastic interacting-patch/metapopulation process  
**Assumptions:** strong local Allee effect; source-specific patch process and graph settings  
**Statement:** dispersal and interaction geometry affect long-run expansion/extinction; analytical results are proved for specified structures including complete-graph and ring cases.  
**Result strength:** exact/restricted analytical results  
**Proof method:** interacting particle systems/probabilistic coupling  
**Limitations:** single strong-Allee mechanism, not a general multiple-component Double-Allee theorem  
**Verification status:** primary/full  
**Chief consequence:** naive claim that topology-dependent Allee thresholds are new is rejected.

### T-104 — Caputo Double-Allee predator–prey stability

**Source:** Rahmi et al. (2021), DOI 10.3390/fractalfract5030084  
**System class:** 2D nonlinear Caputo predator–prey system  
**Assumptions:** model-specific Leslie–Gower/Beddington–DeAngelis and Double-Allee formulation  
**Statement:** well-posedness/positivity/boundedness plus local stability and sufficient global-stability conditions are derived.  
**Result strength:** mixed exact local + sufficient global  
**Proof method:** fractional spectral conditions + Lyapunov analysis  
**Limitations:** model-specific; no field identification of fractional order  
**Verification status:** primary/full  
**Chief consequence:** “Double Allee + Caputo” is not a novelty route.

## Relationship rules now established

- T-010 **subsumes the broad mathematical object** originally imagined as fractional-sector multiplicative D-stability.
- T-011 is a **sufficient structured certificate**, not a converse to T-010.
- T-012 is **not yet identified as equivalent** to T-010.
- T-103 is an **adjacent topology theorem**, not a direct generalization of T-101.
- T-104 is a **model-specific fractional application**, not a structural theorem about multiple component effects.

Never add an implication edge without checking assumptions on both endpoints.
