> **Scope notice (2026-09-28):** this is a seed map, not a complete state-of-the-art of the full domain. It must be expanded under `research/DOMAIN_MAP.md` before opportunity selection.

# Bridge Map

Track potentially under-integrated mathematical literatures.

| Fractional-stability side | Adjacent literature | Candidate bridge question | Status |
|---|---|---|---|
| Matignon-sector spectral stability | regional D-stability / D-stability | Is stability under every positive diagonal scaling with respect to a fractional sector already characterized as a special case of regional D-stability? | P0 prior-art search |
| fractional Lyapunov criteria | diagonal Lyapunov stability | When are diagonal certificates exact rather than merely sufficient for fractional sector stability? | investigate |
| fractional networks | graph/Laplacian theory | Which topology yields dimension-independent stability criteria? | investigate |
| structured fractional Jacobians | positive/Metzler systems | Which positivity results sharpen spectral-sector stability characterizations? | investigate |
| uncertain fractional systems | robust control/interval matrices | Which structured robustness tools transfer without excessive conservatism? | investigate |
| ecological interaction networks | qualitative matrix theory | Can sign/topology certify fractional stability or instability? | investigate |
| Double Allee thresholds | bifurcation / resilience theory | Can multi-threshold geometry yield a reusable structural theorem rather than another model-specific criterion? | P0 terminology/prior-art search |
| Double Allee dispersal | metapopulation/network theory | When does coupling create, destroy, or move extinction/persistence thresholds in a topology-dependent way? | investigate after terminology audit |
| Double Allee + memory | inverse problems / identifiability | Can memory order and multiple thresholds be structurally or practically identifiable from realistic ecological observations? | investigate after dataset audit |

## Chief cautions

### Regional stability threat

The central structured-matrix bridge must not assume that “fractional D-stability” is absent merely because that exact phrase is rare.

The relevant mathematical object may already appear in a broader form:

> stability of DA for every positive diagonal D with the spectrum constrained to a prescribed sector or stability region.

ROUND-0001 is explicitly tasked with trying to find such a theory under alternative terminology.

### Fractional-order uncertainty can be trivial in fixed-matrix cases

For a commensurate fixed matrix A under the classical sector criterion, increasing alpha tightens the admissible spectral sector. Therefore robustness over a simple interval alpha in [alpha_min, alpha_max] may collapse to checking the largest admissible order.

Do not treat “uncertain fractional order” as a deep research direction unless additional structure makes the problem genuinely nontrivial.

### Double Allee terminology is not yet mathematical evidence

Until ROUND-0002 returns, “Double Allee” is only a search label. Candidate research lines must eventually be expressed in terms of explicit equilibrium/threshold geometry and biological mechanism.

These are research hypotheses and mathematical cautions, not novelty claims.
