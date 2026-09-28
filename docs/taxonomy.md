# Working Taxonomy

**Status:** protocol-v1 taxonomy, refined by Chief on 2026-09-28.  
Material changes after pilot extraction must be logged in STATUS.md.

## 1. System class

linear autonomous; linear time-varying; nonlinear autonomous; nonlinear time-varying; delayed; neutral; stochastic; impulsive; switched/hybrid; discrete fractional; networked/multi-agent; reaction-diffusion/spatial; metapopulation/dispersal.

## 2. Fractional structure

### Operator
Caputo; Riemann–Liouville; Grünwald–Letnikov; multi-term; variable order; distributed order; uncertain order; discrete fractional; other.

### Order architecture
scalar commensurate; vector incommensurate; rationally commensurable orders; irrational/non-rational order ratios; order intervals/uncertainty.

### Order range
Record the admissible order range explicitly, especially when the stability geometry changes across alpha in (0,1), alpha in (0,2), or broader formulations.

## 3. Stability notion

asymptotic; Mittag-Leffler; Lyapunov; finite-time; input-to-state; BIBO; robust; synchronization; consensus; D-stability; diagonal Lyapunov stability; structural/sign stability; persistence/extinction when the ecological problem requires it.

Do not treat D-stability and diagonal stability as synonyms.

## 4. Stability-region geometry

Record the actual spectral/root region when the theorem is spectral:

- open left half-plane;
- Matignon sector / sector complement;
- disk;
- conic sector;
- general LMI or prescribed region;
- characteristic-root region for incommensurate systems.

For sector criteria record the angle and its dependence on fractional order.

This category is essential for detecting whether a purported “fractional D-stability” problem is already a special case of a more general regional-stability theory.

## 5. Representation / proof method

Jacobian/spectral; characteristic equation; augmented/lifted system; state-space; LMI; Lyapunov function; diagonal Lyapunov certificate; comparison principle; frequency domain; matrix measure; graph/Laplacian; monotone/positive systems; qualitative matrix; bifurcation/normal form; topological degree; monotone dynamical systems; invariant-region argument.

## 6. Matrix structure

dense; sparse; positive/nonnegative; Metzler; M-matrix-related; P-matrix-related; diagonally stable; D-stable; sign constrained; qualitative class; interval/uncertain; block structured; diagonally dominant; symmetrizable.

## 7. Matrix transformation / robustness action

Record exactly what is varied:

- positive left diagonal scaling DA;
- positive right diagonal scaling AD;
- positive diagonal similarity DAD^{-1};
- diagonal additive perturbation A + D;
- interval/entrywise uncertainty;
- norm-bounded uncertainty;
- structured block uncertainty.

Do not conflate diagonal similarity, which preserves the spectrum, with D-stability-type scaling.

For square A and nonsingular D, DA and AD are spectrally equivalent; still record the convention used by the source.

## 8. Network structure

Laplacian/diffusive; directed; undirected; signed; weighted; switching; multilayer; temporal; pinning/control; dispersal/metapopulation; adjacency-driven interaction; state-dependent network.

Record whether the theorem genuinely exploits topology or merely stacks uncoupled systems.

## 9. Result strength

exact characterization; necessary-and-sufficient; necessary; sufficient; exact under restricted assumptions; conservative computational test; asymptotic approximation; perturbative; numerical evidence; counterexample; impossibility result; conjectural.

Never promote a certificate into a characterization unless a converse is proved.

## 10. Theorem scope

scalar; fixed low dimension; arbitrary finite dimension; topology-specific; matrix-class-specific; local nonlinear; global nonlinear; parameter-local; uniform over uncertainty set.

## 11. Frontier gap

existence; generalization; necessity/exactness; structural unification; bridge; robustness; computational complexity; proof/regularity; counterexample/sharpness; identifiability; data-theory mismatch.

## 12. Allee mechanism

weak; strong; component; demographic; multiple/double; mate limitation; cooperative growth; predator-mediated; harvesting-induced; spatial/network-induced; stochastic/environmental; mechanism-composed.

## 13. Allee equilibrium/threshold geometry

Record separately from ecological terminology:

- number of biologically admissible equilibria;
- number of positive unstable thresholds;
- ordering of extinction / threshold / carrying or coexistence states;
- bistability versus multistability;
- hysteresis;
- saddle-node/fold origin;
- transcritical/pitchfork/Hopf interaction where relevant;
- whether multiple thresholds are intrinsic to local dynamics or induced by coupling/spatial structure.

Two papers using “Double Allee” should not be treated as mathematically equivalent unless this geometry and mechanism agree.

## 14. Empirical structure

observed state variables; temporal resolution; spatial replication; interventions/harvesting; observation error; process noise; known mechanism; parameter identifiability; threshold identifiability; memory/fractional-order identifiability; out-of-sample validation availability.
