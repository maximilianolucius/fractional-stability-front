# Fractional Stability Front

**Theorem-level mapping of Dynamical Systems and Stability Theory — Fractional Differential Equations.**

This repository is a research workspace for:

- systematic mapping of fractional differential dynamical systems and stability theory;
- critical comparison of theorem strength and assumptions;
- reconstruction of the mathematical frontier;
- identification and adversarial falsification of fertile research gaps;
- special exploration of opportunities directly involving, or very close to, **Double/Multiple Allee dynamics**;
- possible preparation of a survey/state-of-the-art manuscript once the map is mature.

## Core objective

The project pipeline is:

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
	ext{candidate gaps}
ightarrow
	ext{falsification}
ightarrow
	ext{opportunity portfolio}.
]

The central question is:

> **Where does the current theory of fractional differential dynamical systems and stability actually stop, and which unresolved gaps are fertile enough to motivate future Q1-level mathematical research?**

The project does **not** solve the selected gap. That belongs to a separate future research project.

## Exact domain

> **Dynamical Systems and Stability Theory — Fractional Differential Equations**

Major branches include:

- linear/spectral stability;
- commensurate and incommensurate systems;
- nonlinear stability and Lyapunov/Mittag-Leffler theory;
- structured matrices, D-stability, diagonal stability, positive systems;
- robust/uncertain systems;
- delay, neutral, switched, impulsive and stochastic systems;
- graph/network dynamics;
- bifurcation, multistability, tipping, persistence/extinction;
- ecological/population applications.

## Double Allee lens

The strongest final opportunity should preferably:

1. directly involve a **Double Allee / Multiple Allee model**, or
2. if necessary, lie **very close** to Double Allee dynamics in threshold structure, persistence/extinction, bifurcation, robustness, network coupling, or fractional memory.

The connection must be mathematical, not cosmetic.

## What this project does not do

It does not:

- prove the full new theorem program;
- close the chosen gap;
- write the eventual original-research paper solving it.

Exploratory mathematics is used only to determine whether a candidate gap is substantive.

## Main outputs

| Path | Purpose |
|---|---|
| `docs/PROJECT_CHARTER.md` | Authoritative project mission |
| `CHIEF_INITIAL_PROMPT.md` | Chief Researcher operating instructions |
| `WEB_SEARCHER_INITIAL_PROMPT.md` | Web Searcher operating instructions |
| `STATUS.md` | Current mapping phase and priorities |
| `docs/` | Protocol, taxonomy, search strategy, workflow |
| `corpus/` | Paper-level and theorem-level evidence |
| `bibliography/` | Curated references |
| `research/DOMAIN_MAP.md` | Architecture and coverage of the full domain |
| `research/theorem-map.md` | Strongest theorem/result relationships |
| `research/frontier-map.md` | Verified and candidate frontiers |
| `research/open-problems.md` | Open-problem catalogue |
| `research/OPPORTUNITY_PORTFOLIO.md` | Candidate fertile gaps |
| `research/opportunity-matrix.csv` | Structured comparison of opportunities |
| `research/double-allee/` | Double/Multiple Allee state-of-art and candidates |
| `paper/` | Optional future survey manuscript workspace |

## Unit of analysis

The unit of analysis is the **mathematical result**, not the paper.

For an important theorem/result record:

[
P_i=(S,O,M,N,A,T,R,L),
]

with system class, operator/order structure, structural assumptions, stability/dynamical notion, proof technique, theorem strength, and limitations.

## Frontier categories

The project distinguishes:

- existence gaps;
- generalization gaps;
- exactness/converse gaps;
- structural-unification gaps;
- bridge gaps;
- robustness gaps;
- complexity/computability gaps;
- data-theory/identifiability gaps.

## Current status

The repository is in a **domain-mapping expansion phase**.

Early rounds explored several candidate gaps near Double Allee. One mechanism-space candidate survived direct falsification only in narrowed form, but it is **not a selected primary direction**. It now competes with opportunities emerging from the broader FDE stability map.

See [STATUS.md](STATUS.md).

## Possible survey output

A mature map may support a survey such as:

**Dynamical Systems and Stability Theory for Fractional Differential Equations: A Theorem-Level Map of the Frontier**

## Agent coordination

Chief Researcher ↔ Web Searcher communication is repository-native and Markdown-only:

- `research/coordination/chief-to-web/`
- `research/coordination/web-to-chief/`
- `research/coordination/chief-decisions/`

Git history is part of the provenance chain.


## Project outcome — 2026-09-28

The research-gap discovery phase is complete.

The principal opportunity identified is **deterministic reachable memory-state basin geometry** for positive multidimensional Caputo systems, with strong/Double-Allee dynamics as the preferred direct realization.

The central question is whether two physically reachable fractional-memory states with the same currently observed population vector can belong to different asymptotic basins, especially extinction versus survival/coexistence.

See:
- research/FINAL_RECOMMENDATION.md
- research/FINAL_SHORTLIST.md
- research/coordination/chief-decisions/ROUND-0017_shortlist-final-killer-audit_DECISION.md

Future theorem proving based on this opportunity belongs to a separate project. This repository may still support a state-of-the-art/review paper based on the completed cartography.
