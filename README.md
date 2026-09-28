# Fractional Stability Front

**Mapping the mathematical frontier of fractional-order stability theory and turning that map into a research program.**

This repository is a research workspace for a combined:

- **systematic mapping study** of fractional-order stability theory;
- **critical mathematical survey** of the strongest known results;
- **theorem/frontier map** identifying exactness, generalization, robustness, and bridge gaps;
- **open-problem catalogue and research agenda**;
- focused exploration of a **Double Allee** research direction with strong applied-mathematics content and, where scientifically justified, real data.

The project is not intended to be a bibliography dump. Its unit of analysis is the **mathematical result**.

## Core objective

The working logic is

[
	ext{literature}
ightarrow
	ext{taxonomy}
ightarrow
	ext{theorem map}
ightarrow
	ext{frontier}
ightarrow
	ext{open problems}
ightarrow
	ext{research program}.
]

The central question is:

> **Which general mathematical results are still missing in fractional-order stability theory, and which missing results could explain, sharpen, unify, or subsume substantial parts of the existing literature?**

The initial scope is deliberately broader than fractional D-stability:

> **Stability theory of fractional-order dynamical systems and networks**

with particular interest in fractional dynamics, spectral stability, Matignon-type criteria, D-stability, diagonal stability, structured matrices, positive/Metzler systems, robustness, graph-structured dynamics, nonlinear stability, and ecological applications.

## Double Allee branch

A second mandatory branch asks whether the frontier map exposes a mathematically deep research line involving a **Double Allee effect**.

The target is not “another ecological fractional model.” A viable direction should have:

- defensible novelty;
- theorem-level mathematical depth;
- structural or unifying value;
- potential for a strong applied-mathematics manuscript;
- and preferably a real dataset that genuinely constrains or validates the model.

See [CHIEF_INITIAL_PROMPT.md](CHIEF_INITIAL_PROMPT.md) and [research/double-allee/README.md](research/double-allee/README.md).

## Repository structure

| Path | Purpose |
|---|---|
| `CHIEF_INITIAL_PROMPT.md` | Initialization prompt for the Chief Researcher |
| `STATUS.md` | Current phase, decisions, milestones, and next actions |
| `docs/` | Research questions, protocol, search strategy, taxonomy, screening rules |
| `corpus/` | Paper-level and theorem-level structured evidence |
| `bibliography/` | Curated references and bibliographic provenance |
| `research/` | Theorem map, bridge map, frontier map, open problems |
| `research/double-allee/` | Dedicated Double Allee research branch |
| `data/raw/` | Immutable search/database exports |
| `data/processed/` | Normalized and deduplicated data |
| `data/exports/` | Generated tables, graphs, and manuscript-ready outputs |
| `scripts/` | Reproducible data-cleaning and analysis tooling |
| `paper/` | Eventual survey manuscript workspace |

## Evidence model

For an important result, extract a structured record conceptually of the form

[
P_i=(S,O,M,N,A,T,R,L),
]

where:

- (S): system class;
- (O): fractional operator/order structure;
- (M): matrix, graph, or interaction structure;
- (N): stability notion;
- (A): assumptions;
- (T): technique/proof method;
- (R): result;
- (L): limitations and unresolved extensions.

A single paper may contain several important theorem records.

## Frontier categories

The project distinguishes:

- **existence gaps** — a meaningful problem appears unstudied;
- **generalization gaps** — known only under restrictive dimensions, topology, operator, or matrix class;
- **exactness gaps** — sufficient conditions exist without a necessary-and-sufficient characterization;
- **structural-unification gaps** — many special cases may follow from one missing theorem;
- **bridge gaps** — mature mathematical literatures appear connected but weakly integrated;
- **robustness gaps** — deterministic results lack uncertainty, perturbation, switching, time variation, or stochastic extensions.

The strongest opportunity is not necessarily the least-studied topic. It is often the problem whose solution would convert many existing results into corollaries.

## Workflow

1. Freeze scope and research questions.
2. Register search families, databases, dates, and exact queries.
3. Build and deduplicate a candidate corpus.
4. Screen with explicit inclusion/exclusion rules.
5. Extract theorem-level mathematical metadata.
6. Build the taxonomy and theorem implication map.
7. Audit assumptions, sharpness, contradictions, and non-comparable results.
8. Build the frontier and open-problem catalogue.
9. Develop a research agenda based on mathematical depth and generality.
10. Run the Double Allee branch through the same novelty and rigor standards.
11. Draft the survey only after the knowledge map is sufficiently stable.

## Current status

Repository infrastructure is initialized. The next research phase is to freeze the review protocol and build seed corpora for:

1. foundational fractional-stability theory;
2. adjacent structured-matrix/network theory;
3. Allee and Double Allee mathematics.

See [STATUS.md](STATUS.md).

## Working survey title

**Mapping the Frontier of Fractional-Order Stability Theory**


## Agent coordination

Chief Researcher ↔ Web Searcher communication is **repository-native and Markdown-only**.

All official inter-agent requests, research returns, and Chief decisions are stored under:

- `research/coordination/chief-to-web/`
- `research/coordination/web-to-chief/`
- `research/coordination/chief-decisions/`

Each exchange uses a shared `ROUND-NNNN` identifier. See [research/coordination/README.md](research/coordination/README.md).

This makes every research instruction, search result, novelty challenge, and scientific disposition auditable from Git history.
