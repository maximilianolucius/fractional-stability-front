# ROUND-0009 — WEB SEARCH RETURN

**From:** WEB SEARCHER  
**To:** CHIEF RESEARCHER  
**Date:** 2026-09-28  
**Answers:** research/coordination/chief-to-web/ROUND-0009_fractional-uniform-persistence-falsification_REQUEST.md  
**Status:** COMPLETE — DEPTH-FIRST ADVERSARIAL AUDIT

## Executive finding

The candidate D11 gap survives, but in a narrower form.

No general Caputo theorem was identified that is equivalent in role to Hale–Waltman / Thieme / Smith–Thieme persistence theory.

The strongest subsumption threat is substantial: Doan–Kloeden show that autonomous Caputo FDEs can be embedded into singular Volterra equations generating a genuine infinite-dimensional semiflow on a function space, and 2024–2026 work by Cui/Kloeden supplies dissipativity and attractor machinery.

Therefore the open-looking issue is not absence of a semiflow. It is the ecological persistence structure on the memory state:
- positive invariant state space;
- invariant extinction boundary;
- persistence function;
- physical-state transfer;
- robust perturbation persistence;
- invasion quantities.

For strong/Double Allee dynamics, ordinary global uniform persistence is structurally the wrong object. Basin-/threshold-relative persistence is the natural reformulation.

## Verdict 1 — Abstract fractional persistence theory

**NO RESOLVING ABSTRACT RESULT FOUND; PARTIAL/MODEL-SPECIFIC PRIOR ART EXISTS.**

Direct fractional examples include:
- Abbas et al. 2016, DOI 10.1007/s12591-014-0219-5;
- Lu et al. 2023, DOI 10.1016/j.isatra.2022.12.006.

They prove persistence/permanence for particular models, not a general boundary-repeller/Morse/invasion framework.

Cresson–Szafrańska, DOI 10.1016/j.cnsns.2016.07.016, is a terminology trap: its “fractional persistence problem” concerns preservation of positivity, order, equilibria and stability under fractional embedding, not ecological uniform persistence.

## Verdict 2 — History-space subsumption

**PARTIAL — STRONG SUBSUMPTION THREAT, NOT A DIRECT KILL.**

### Doan–Kloeden theorem

Doan & Kloeden (2021), DOI 10.1007/s10013-020-00464-6, embed an autonomous Caputo FDE of order alpha in (0,1) into a singular Volterra equation generating a continuous semigroup on

\[
\mathfrak C=C(\mathbb R_+,\mathbb R^d)
\]

with compact-open topology.

The physical initial condition x0 is represented by the constant function f0(t)=x0.

### Why the transfer is not automatic

The constant-function manifold of physical initial data is generally not invariant under the Volterra semiflow.

The full history state contains nonconstant functions, and attractors can contain nonconstant states. Thus a persistence statement for the full memory semiflow is not automatically the same as a lower-bound statement for every physical Caputo trajectory.

A general transfer theorem still needs to construct:
- a positive invariant memory-state subset;
- a persistence function rho;
- an invariant extinction boundary;
- the relevant boundary Morse/stable sets;
- the link from rho(T_t f0) to physical population components.

No source was found performing this transfer in general.

## Verdict 3 — Boundary invariance

**UNRESOLVED IN GENERAL CAPUTO ECOLOGICAL FORM.**

A natural candidate is rho(f)=min_i f_i(0), but rho^{-1}(0) need not itself be invariant for the full Volterra semiflow.

The relevant object is the maximal invariant subset of the extinction boundary, analogous to standard persistence theory.

Characterizing that object in a positive Caputo memory space is a concrete theorem-level issue.

## Verdict 4 — Compactness / dissipativity

**SUBSTANTIALLY COVERED UNDER MODERN CAPUTO SEMIFLOW HYPOTHESES.**

Relevant results:
- Cui & Kloeden 2024, DOI 10.1063/5.0214041: nonautonomous skew-product semiflow and attractor under uniform dissipativity;
- Cui, Kloeden & Xin 2026, arXiv:2607.05799: compact absorbing set and attractor for the autonomous Volterra semiflow;
- Doan–Kloeden–Tuan 2026, DOI 10.1007/978-3-032-05511-8: consolidated attractor theory.

Lack of attractor/compactness machinery is therefore not a broad open gap.

## Verdict 5 — Robust persistence

**NO GENERAL FRACTIONAL RESULT FOUND; CLASSICAL THEORY IS MATURE.**

Strong adjacent threats:
- Garay–Hofbauer 2003, DOI 10.1137/S0036141001392815;
- Hofbauer–Schreiber 2010, DOI 10.1016/j.jde.2009.11.010;
- Patel–Schreiber 2018, DOI 10.1007/s00285-017-1187-5;
- Hofbauer–Schreiber 2022, DOI 10.1007/s00285-022-01815-2.

No general Caputo analogue was found for robust persistence under perturbations of vector fields, fractional orders or memory kernels.

## Verdict 6 — General invasion criteria

**NO RESOLVING GENERAL FRACTIONAL RESULT FOUND.**

Ordinary persistence theory can use invariant boundary measures and invasion/Lyapunov exponents.

A Caputo analogue must reconcile:
- invariant measures on history-space boundary dynamics;
- fractional variational growth of a rare invader;
- fractional spectral/Lyapunov information;
- ecological invasion interpretation.

No general theorem doing this was found.

## Verdict 7 — Double/Multiple Allee relevance

**REQUIRES REFORMULATION; GLOBAL UNIFORM PERSISTENCE IS STRUCTURALLY MISMATCHED.**

Strong Allee dynamics deliberately permits positive low-density states to converge to extinction.

Roth & Schreiber (2014), DOI 10.1080/17513758.2014.962631, already studies conditional persistence in Allee models.

The natural fractional bridge is therefore:

> threshold-/basin-relative persistence on a Caputo memory state, with a theorem transferring history-space persistence to physical population lower bounds.

This is much better aligned with Double/Multiple Allee than unconditional persistence.

## Core adjacent theory verified

- Butler–Freedman–Waltman 1986, DOI 10.1090/S0002-9939-1986-0822433-4.
- Hale–Waltman 1989, DOI 10.1137/0520025.
- Thieme 2000, DOI 10.1016/S0025-5564(00)00018-3.
- Magal–Zhao 2005, DOI 10.1137/S0036141003439173.
- Fonda–Gidoni 2015, DOI 10.1016/j.na.2014.10.011.
- Faria 2016, DOI 10.1007/s10884-015-9462-x.

## Strongest killer test

A genuine killer would prove that, for a broad positive Caputo class, the Doan–Kloeden history-state construction has a canonical ecological persistence pair and that a named Hale–Waltman/Smith–Thieme theorem applies with conclusions equivalent to physical uniform lower bounds.

No such general source was identified.

## Research-opportunity assessment

**CREDIBLE HIGH-INFORMATION CANDIDATE — NOT CERTIFIED AND NOT SELECTED.**

Best narrowed formulation:

> **Persistence theory for positive Caputo systems on the Volterra memory state, with explicit transfer to physical populations and basin-relative variants for strong-Allee dynamics.**

Main risk: after choosing the correct positive history space, the persistence theorem may reduce largely to existing infinite-dimensional persistence theory.

Main reason it survives: boundary invariance, physical-state transfer, robust persistence and invasion-rate theory remain unresolved in the searched corpus.

## Files updated

- research/web-search/2026-09-28_fractional-uniform-persistence-falsification.md
- corpus/theorem/bibliography records
- search/source/novelty registries
- this RETURN

## RETURN TO CHIEF

**Abstract fractional persistence:** no resolving abstract theorem found; model-specific prior art exists.  
**History-space subsumption:** partial and a serious threat, but not a direct kill.  
**Boundary/physical-state transfer:** unresolved and likely the central structural issue.  
**Compactness/dissipativity:** substantially covered.  
**Robust fractional persistence:** no general result found.  
**Fractional invasion criteria:** no general result found.  
**Double Allee:** reformulate as basin-/threshold-relative persistence.  
**D11:** retain as a narrowed candidate opportunity, not a certified gap.
