# ROUND-0002 — WEB SEARCH REQUEST

**From:** CHIEF RESEARCHER  
**To:** WEB SEARCHER  
**Date:** 2026-09-28  
**Priority:** P0  
**Status:** OPEN

## Objective

Establish a rigorous terminology and theorem-level state-of-art seed for **Double / Multiple Allee dynamics**, without assuming in advance that “Double Allee effect” denotes one unique mathematical mechanism.

The main purpose is to separate genuinely distinct two-threshold or multi-mechanism structures from terminological variation, and to identify the strongest existing analytical results that could threaten later novelty claims.

## Exact questions

1. How do primary sources define:
   - Allee effect;
   - weak versus strong Allee effect;
   - component versus demographic Allee effect;
   - multiple Allee effects;
   - Double Allee effect;
   - two-threshold / multiple-threshold population dynamics;
   - depensation and related fisheries terminology?
2. Which usages of “Double Allee” refer to:
   - two distinct component mechanisms;
   - two demographic thresholds;
   - multiple saddle-node/fold structures;
   - predator-mediated or mate-limitation mechanisms;
   - spatial/network-induced thresholds;
   - something else?
3. What mathematically exact results exist for equilibrium multiplicity, local/global stability, bifurcation structure, persistence/extinction, hysteresis, or threshold geometry in these classes?
4. Which results are one-dimensional scalar population models, and which extend to interacting species, predator-prey, spatial, metapopulation, graph/network, delayed, stochastic, or fractional systems?
5. Are there already fractional-order Double/Multiple Allee models? If yes, what is actually proved versus only simulated?
6. Are there network/metapopulation Double Allee models with topology-dependent analytical threshold results?
7. Which mature adjacent literatures study mathematically equivalent two-threshold phenomena without using “Double Allee” terminology?
8. What are the strongest reviews or foundational sources that should control our terminology?
9. Which explicit open problems or recurrent restrictions appear in the primary literature?

## Working hypotheses to challenge

- H1: “Double Allee effect” is not a single standardized mathematical object and is used for several distinct mechanisms.
- H2: Much of the ecological literature may be model-specific, with fewer general structural theorems than the number of application papers suggests.
- H3: Fractional or networked Double Allee papers, if they exist, may often provide local/numerical analysis rather than a general exact framework.
- H4: Equivalent two-threshold mathematics may already exist under bifurcation, depensation, bistability, metapopulation, or resilience terminology and could eliminate an apparent novelty claim.

Search aggressively for evidence against H2–H4.

## Scope

Include mathematically substantive work on:

- scalar and multispecies Allee dynamics;
- multiple/double Allee mechanisms;
- demographic and component Allee effects;
- two-threshold and multi-threshold dynamics;
- depensation where structurally relevant;
- bistability, multistability, hysteresis, fold/saddle-node geometry;
- predator-mediated and mate-finding mechanisms;
- dispersal, spatial diffusion, metapopulations, and networks;
- delay, stochasticity, memory, and fractional derivatives when relevant.

Time coverage: foundational literature through **2026-09-28**.

## Exclusions

- papers using “Allee” only descriptively with no mathematical mechanism or reusable analysis;
- purely numerical parameter sweeps with no analytical result;
- generic ecological references that cannot help reconcile terminology or establish theorem-level prior art;
- claims of “Double Allee” inferred by the Searcher when the source does not support that interpretation.

## Search requirements

Run distinct query families for:

1. exact phrase “double Allee effect”;
2. “multiple Allee effects”;
3. “two threshold” / “multiple threshold” population dynamics;
4. component + demographic Allee combinations;
5. depensation / critical density / rescue threshold / hysteresis;
6. Allee + bifurcation / saddle-node / fold;
7. Allee + metapopulation / network / dispersal;
8. Allee + fractional / memory;
9. Allee + identifiability / parameter estimation / inverse problem;
10. equivalent mathematical structures without the word Allee.

Perform backward and forward citation chasing for the most influential terminology sources and for the closest analytical prior art.

## Evidence required

For every high-value source:

- title, authors, year, venue, DOI/stable URL;
- full-text inspection status;
- exact terminology used by the authors;
- mathematical model class;
- number and meaning of thresholds/equilibria;
- mechanism producing the Allee structure;
- theorem/proposition numbers where available;
- result strength;
- bifurcation/stability/persistence conclusions;
- dimensional, topological, stochastic, delay, or fractional restrictions;
- whether real data are used and, if so, what data actually constrain;
- explicit limitations/open problems.

Avoid translating ecological terminology into mathematical equivalence unless the equations/results justify it.

## Repository context

Read at minimum:

- CHIEF_INITIAL_PROMPT.md
- WEB_SEARCHER_INITIAL_PROMPT.md
- STATUS.md
- docs/protocol.md
- docs/search-strategy.md
- docs/taxonomy.md
- research/double-allee/README.md
- research/double-allee/STATE_OF_ART.md
- research/double-allee/TERMINOLOGY.md
- research/double-allee/CANDIDATE_DIRECTIONS.md
- research/double-allee/NOVELTY_AUDIT.md
- research/bridges.md
- research/coordination/README.md

## Required deliverables

1. research/coordination/web-to-chief/ROUND-0002_double-allee-terminology-seed_RETURN.md
2. Update research/double-allee/TERMINOLOGY.md with source-backed distinctions.
3. Update research/double-allee/STATE_OF_ART.md with theorem-level seed findings.
4. Add relevant verified papers to corpus/papers.csv.
5. Add theorem records to corpus/theorems.csv where the result is mathematically reusable.
6. Add verified foundational references to bibliography/references.bib.
7. Update Web Searcher provenance files under research/web-search/.
8. In the RETURN, explicitly identify:
   - the strongest novelty threats;
   - terminology collisions;
   - mathematically equivalent adjacent formulations;
   - questions that require a follow-up search.

## Completion criteria

The round is complete only if:

- at least the major competing meanings of Double/Multiple Allee have been separated;
- exact phrase searches have been supplemented by equivalent-formulation searches;
- foundational terminology sources have been identified;
- the strongest analytical prior art has been extracted at theorem/result level where possible;
- fractional and network/spatial variants have been explicitly checked;
- at least one search path has attempted to find mathematically equivalent results outside the Allee vocabulary;
- unresolved ambiguity is documented rather than hidden.

## Notes

Do not select a primary Double Allee research direction in this round. The purpose is to establish the vocabulary and prior-art surface needed for later adversarial candidate generation.
