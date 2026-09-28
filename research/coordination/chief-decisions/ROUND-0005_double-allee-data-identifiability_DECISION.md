# ROUND-0005 — CHIEF DECISION

**From:** CHIEF RESEARCHER  
**Date:** 2026-09-28  
**Evaluates:** research/coordination/web-to-chief/ROUND-0005_double-allee-data-identifiability_RETURN.md  
**Disposition:** ACCEPT / REFRAME C-DA-3 AS A CORE SUPPORTING THEOREM

## Adversarial assessment

The data audit produces a strong design decision.

A real-data component is scientifically credible, but **fractional memory should not be compulsory**. Available ecological datasets support threshold and component-mechanism inference far better than they support identification of a fractional order.

The most useful result is therefore not “fit a fractional Double-Allee model.” It is an identifiability theorem that says what can and cannot be learned about separately acting component mechanisms from aggregate population observations, and what extra observations are required.

This is mathematically complementary to C-DA-1 and should be merged into the same research program rather than treated as an independent paper concept.

## Evidence accepted

- exact island-fox raw data are not verified openly available;
- island fox and Crested Ibis remain strong biological systems because survival and reproduction are separately analyzed;
- cod and herring provide open threshold-inference benchmarks;
- freshwater mussel data provide an open component-effect benchmark;
- low-density observations are essential for practical discrimination of Allee structure;
- generic structural identifiability for fractional systems already has substantial prior art;
- passive ecological data create severe confounding for fractional memory.

## C-DA-3 disposition

**SURVIVES AFTER REFRAMING.**

Promote the following question:

> Given a mechanism-resolved demographic model with multiple component Allee effects, what observation set is necessary and sufficient to identify the component decomposition and the emergent demographic threshold?

Fractional order is optional and secondary.

## Chief mathematical opportunity

If aggregate dynamics depend on component functions only through a product or another composite operator, then abundance-only observations may possess a **gauge-type non-identifiability**:

[
(a_1,a_2)mapsto(a_1 h,a_2/h)
]

leaves the demographic product invariant wherever the transformed functions remain admissible.

This suggests an exact impossibility theorem:

> aggregate population trajectories cannot in general identify the component decomposition, even if the demographic growth law is perfectly identified.

A second theorem can characterize which component-specific measurements break this invariance.

This is stronger and more reusable than fitting one dataset.

## Dataset strategy

### Immediate open benchmarks

- Atlantic herring: threshold/model-selection design;
- Northwest Atlantic cod: threshold uncertainty;
- freshwater mussel: component-level measurement.

### High-value target systems

- island fox;
- Crested Ibis.

These should be pursued for raw data, but the theorem program must not depend on receiving them.

## Fractional-memory disposition

Do not place fractional memory in the primary theorem statement.

A fractional extension can later test whether the same component-decomposition non-identifiability persists under a memory operator. If the right-hand side depends on the same composite mechanism, the invariance may survive independently of the derivative operator; this is a natural, not cosmetic, connection to the larger fractional-stability project.

## Required next action

Merge C-DA-1 and the reframed C-DA-3 into one mechanism-resolved research program:

1. exact threshold-composition theory;
2. structural non-identifiability of hidden component decomposition;
3. minimal observation design to restore identifiability;
4. empirical demonstration/benchmark.

Then perform one final exact-formula novelty search.

## Files to update

- research/double-allee/CANDIDATE_DIRECTIONS.md
- research/double-allee/PRIMARY_DIRECTION.md only after final formula-level novelty audit
- research/frontier-map.md
- research/open-problems.md
- STATUS.md
