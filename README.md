# Fractional Stability Front

**Mapping the frontier of stability theory for fractional-order dynamical systems.**

This repository is a research workspace for a systematic, critical, and frontier-oriented survey of fractional-order stability theory. The goal is not merely to collect papers, but to reconstruct the mathematical structure of the field, identify exact and partial results, expose unresolved gaps, and convert those gaps into a rigorous research agenda.

## Research objective

The project follows the chain

[
\text{literature}
\rightarrow
\text{taxonomy}
\rightarrow
\text{theorem map}
\rightarrow
\text{frontier}
\rightarrow
\text{open problems}
\rightarrow
\text{research program}.
]

The central question is:

> **Which general mathematical results are still missing in fractional-order stability theory, and which of them could subsume substantial parts of the existing literature?**

The initial scope is deliberately broader than fractional D-stability. The core domain is:

> **Stability theory of fractional-order dynamical systems and networks**

with special attention to the intersection of fractional dynamics, spectral stability, structured matrices, D-stability/diagonal stability, network topology, robustness, and mathematically structured applications.

## Research layers

The literature is studied at four levels:

1. **Applications** — model-specific stability studies and numerical demonstrations.
2. **Methods** — Lyapunov, LMI, spectral, frequency-domain, comparison, and computational techniques.
3. **General results** — reusable theorems valid for classes of systems.
4. **Foundational/structural results** — exact characterizations, equivalences, invariance principles, dimension-independent criteria, and results from which many special cases follow.

Priority is given to levels 3–4.

## Repository map

| Path | Purpose |
|---|---|
| `docs/` | Scope, research questions, protocol, taxonomy, and screening rules |
| `corpus/` | Structured literature corpus and extraction schema |
| `bibliography/` | Bibliographic sources and BibTeX |
| `research/` | Theorem map, frontier map, open problems, terminology |
| `data/` | Raw, processed, and exported research data |
| `scripts/` | Reproducible search, cleaning, deduplication, and analysis code |
| `paper/` | Material for the eventual survey/review manuscript |
| `STATUS.md` | Current project stage, decisions, and next milestones |

## Core analytical unit

A paper is not treated merely as a citation. Each relevant result should be reduced to a structured mathematical record, conceptually of the form

[
P_i=(S,O,M,N,A,T,R,L),
]

where:

- (S): system class;
- (O): fractional operator/order structure;
- (M): matrix or network structure;
- (N): stability notion;
- (A): assumptions;
- (T): analytical technique;
- (R): main result;
- (L): limitations/open extensions.

The working data schema is documented in `corpus/README.md` and instantiated in `corpus/papers.csv`.

## Frontier logic

The project distinguishes several kinds of gaps:

- **existence gaps** — a problem appears unstudied;
- **generalization gaps** — known only in restricted dimension, topology, operator, or matrix class;
- **necessity gaps** — sufficient criteria exist without necessary-and-sufficient characterizations;
- **structural gaps** — many isolated results may be manifestations of one missing general theorem;
- **bridge gaps** — mature literatures appear mathematically connected but weakly integrated;
- **robustness gaps** — exact deterministic results lack perturbation, uncertainty, switching, or time-varying extensions.

A high-value research direction is one where the missing result would explain or subsume many existing special cases.

## Initial research questions

The first-pass questions are maintained in `docs/research-questions.md`. At a high level:

- What are the dominant notions of stability in fractional-order systems?
- Which criteria are exact, and which are only sufficient?
- Where do dimensional restrictions remain?
- Which matrix structures admit stronger results?
- How do graph/network constraints alter fractional stability conditions?
- How mature is the connection with D-stability, diagonal stability, positive systems, robust control, and qualitative matrix theory?
- Which open problems are explicitly stated by the literature, and which emerge only after cross-comparison?
- Which missing theorem would make the largest family of current results corollaries?

## Workflow

1. Define scope and research questions.
2. Build transparent search strings and source logs.
3. Collect and deduplicate the candidate corpus.
4. Screen by explicit inclusion/exclusion criteria.
5. Extract structured mathematical metadata.
6. Build the taxonomy and theorem map.
7. Identify contradictions, assumptions, and unresolved extensions.
8. Construct the frontier/open-problem catalogue.
9. Prioritize a research agenda by mathematical depth and potential generality.
10. Draft the survey only after the knowledge map is stable.

See `docs/protocol.md` and `docs/workflow.md`.

## Current status

Repository initialized. The immediate task is to freeze the survey protocol and build the seed corpus before drawing conclusions about the research frontier.

See [STATUS.md](STATUS.md).

## Working title

**Mapping the Frontier of Fractional-Order Stability Theory**

This title is provisional. The repository is intended to remain useful even if the final survey adopts a narrower title or scope.
