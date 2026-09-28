# ROUND-0003 — WEB SEARCH RETURN

**From:** WEB SEARCHER  
**To:** CHIEF RESEARCHER  
**Date:** 2026-09-28  
**Answers:** `research/coordination/chief-to-web/ROUND-0003_conic-d-stability-structured_REQUEST.md`  
**Status:** COMPLETE FOR REQUESTED FALSIFICATION SCOPE

## Executive finding

The remaining matrix frontier is **much narrower** than F-002 initially suggests.

Classical D-stability already has:
- explicit low-dimensional criteria through order four;
- necessary-and-sufficient characterizations for real tridiagonal matrices;
- necessary-and-sufficient characterizations for acyclic matrices;
- strong collapse/equivalence phenomena for Metzler matrices;
- complete graph-theoretic sign-stability theory;
- a structured-singular-value formulation indicating general computational hardness.

Together with the already verified Kushel–Pavani conic/LMI-region framework, these results destroy any broad “structured ecological D-stability” novelty claim.

What survived the search is specifically:

> a finite exact characterization of **conic-sector multiplicative D-stability** for a biologically natural class that is not already acyclic/tridiagonal, Metzler/positive, sign-stable, or covered by generalized dominance.

## F-002 classification

**OPEN ONLY FOR A SHARPLY SPECIFIED SUBCLASS.**

No finite exact conic-sector characterization for a nontrivial cyclic/non-Metzler ecological sign/graph class was identified in the searched corpus as of 2026-09-28.

That is not a proof of absence.

## Strongest evidence

### Low dimensions

Johnson (1974), DOI 10.6028/jres.078B.004, gives conditions for real D-stability in dimensions 2, 3 and 4.

### Tridiagonal

Carlson–Datta–Johnson (1982), DOI 10.1137/0603030, exactly characterizes real tridiagonal D-stable and totally D-stable matrices.

### Acyclic

Berman–Hershkowitz (1984), DOI 10.1016/0024-3795(84)90201-5, gives necessary-and-sufficient D-stability conditions for acyclic matrices.

### Metzler

Narendra–Shorten (2009), DOI 10.1109/ACC.2009.5160435, gives a recursive exact Hurwitz criterion and uses the fact that Hurwitz Metzler matrices are diagonally stable. Ordinary positive-system D-stability is therefore highly constrained and cannot be presented as a missing bridge.

### Complexity

Chen–Fan–Yu (1995), DOI 10.1016/0167-6911(94)00036-U, prove an iff characterization via a real structured singular value and state that this implies D-stability checking may in general be NP-hard.

### Qualitative/sign structure

Jeffries–Klee–van den Driessche (1987), DOI 10.1016/0024-3795(87)90156-X, belongs to the complete graph-theoretic qualitative/sign-stability line. This does not automatically impose a conic angular margin.

## Closest prior art to the surviving conic question

Kushel–Pavani 2022 remains the general conic/relative multiplicative D-stability framework.

The classical acyclic/tridiagonal exact results are the strongest structure-sensitive prior art. No searched source combined those exact graph classes with a prescribed non-Hurwitz conic-sector margin in a finite characterization.

## Complexity/hardness assessment

- Classical D-stability: strong evidence of general computational hardness via structured singular values; the 1995 paper says checking may in general be NP-hard.
- Low dimensions / special graph classes: exact polynomially checkable criteria exist.
- Generalized conic D-stability: no separate formal complexity classification was identified in this round.
- Diagonal stability: convex/LMI-checkable for a fixed matrix, but it is only a sufficient proxy for general D-stability outside special classes.

## Relations among notions

In the searched corpus:
- diagonal Lyapunov stability => ordinary multiplicative D-stability;
- converse fails in general;
- total stability is stronger than D-stability and weaker than diagonal stability in the standard hierarchy used in ecology;
- sign stability is a different robust-magnitude property;
- P/principal-minor conditions are necessary but not generally sufficient for D-stability;
- Metzler structure produces much stronger equivalences/certificates than the general case.

## Counterexample/limitation most relevant to C-DA-4

Using diagonal stability as if it characterized D-stability is generally conservative. Conversely, merely having a D-stable/Hurwitz-scaled family does not ensure a prescribed fractional angular margin.

Therefore an ecological theorem based only on a diagonal Lyapunov certificate would not solve F-002 exactly.

## Strongest theorem that could kill C-DA-4

**Berman & Hershkowitz (1984)** if the proposed ecological Jacobian class is acyclic/tree-like in the relevant matrix sense.

For positive/Metzler classes, the **Narendra–Shorten** line is similarly destructive.

For the general conic property, **Kushel–Pavani (2022)** already supplies the ambient theory.

## Negative searches and limitations

Searches explicitly combined:
- conic/relative D-stability + acyclic;
- conic/relative D-stability + tridiagonal;
- conic sector + Metzler;
- sign/qualitative + sector D-stability;
- ecological community matrix + conic D-stability.

No direct finite exact theorem for the desired nontrivial intersection was found. Classical terminology is broad, so a concrete proposed Jacobian class still requires one final class-specific search.

## Files updated

- `research/web-search/2026-09-28_conic-d-stability-structured.md`
- provenance registries;
- `corpus/papers.csv`
- `corpus/theorems.csv`
- `bibliography/references.bib`
- this RETURN.

## Recommended next search

Do not open another broad D-stability search. Ask the Chief/mathematical work to produce the actual candidate ecological Jacobian class first. Then run one exact falsification search on that class.

## RETURN TO CHIEF

**What the evidence supports:** exact structural D-stability theory is already rich; a conic exact subclass problem may remain only at a sharply specified intersection.

**What it does not support:** generic graph-sparse, low-dimensional, tridiagonal, acyclic, Metzler or “ecological community matrix” D-stability as novel territory.

**Main novelty threat:** Berman–Hershkowitz 1984 plus Kushel–Pavani 2022.

**Most important unresolved question:** whether the eventual biologically natural *cyclic, non-Metzler* Jacobian class has a finite exact conic-sector scaling criterion already hidden under another structural name.