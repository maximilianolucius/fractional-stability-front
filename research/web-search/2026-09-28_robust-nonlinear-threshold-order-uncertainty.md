# 2026-09-28 — Robust Nonlinear Threshold / Order-Uncertainty Audit

**Round:** ROUND-0013  
**Request:** research/coordination/chief-to-web/ROUND-0013_robust-nonlinear-threshold-order-uncertainty_REQUEST.md  
**Role:** WEB SEARCHER

## 1. Research target

Audit the literature around uncertainty-uniform global dynamics for

\[
{}^C D^\alpha x=f(x;\theta)
\]

and multi-order variants, with \((\alpha,\theta)\) or \((\boldsymbol\alpha,\theta)\) ranging over a prescribed uncertainty set.

The object is not controller robustness. The object is a global statement about uncontrolled nonlinear dynamics:
- extinction;
- survival;
- persistence;
- basin inclusion;
- threshold robustness;
- multistability;
- bifurcation/tipping.

## 2. Main conclusion

The search reveals a clear hierarchy.

### Mature

- linear robust stability under coefficient uncertainty;
- uncertain fractional order;
- coupled order/parameter robust bounds;
- incommensurate robust stability;
- nonlinear class-specific robust equilibrium stability;
- fractional viability;
- classical robust permanence;
- classical robust regions of attraction.

### Not resolved in the searched corpus

A general theorem combining:
- positive nonlinear Caputo dynamics;
- parameter uncertainty;
- fractional-order uncertainty;
- global survival/extinction geometry;
- persistence relative to a survival basin;
- incommensurate order boxes.

The residual is therefore a bridge/frontier, not a blank literature.

---

## 3. Linear/order uncertainty

### Senol et al. 2014

DOI 10.1016/j.isatra.2013.09.004.

Uncertainty in both characteristic coefficients and fractional orders. Numerical robust-stability procedure based on corner/edge/root-region analysis.

### Yang & Hou 2019

DOI 10.1016/j.jfranklin.2018.12.024.

Structured matrix perturbations plus uncertain order \(0<\alpha<2\). Cylindrical algebraic decomposition produces robust parameter regions/bounds and is presented as non-conservative for the stated linear class.

This directly falsifies any candidate based merely on:
> simultaneous uncertainty in \(\alpha\) and model parameters.

### Tavazoei & Asemani 2020

DOI 10.1016/j.cnsns.2020.105344.

Robust stability of incommensurate pseudo-state-space systems via generalized Nyquist. Multiple uncertainty structures treated.

DOI 10.1016/j.jfranklin.2020.09.044 treats time-varying interval uncertainty and irrational incommensurate orders using small-gain/M-matrix methods.

### Zhang & Lu 2023

DOI 10.1016/j.cnsns.2023.107511.

Mixed multi-parameter and norm-bounded uncertainty, robust bounds and conditions.

### Result

Linear/order uncertainty is a closed novelty route except for sharply specified unsolved structures.

---

## 4. Nonlinear robust stability

### Direct open-loop result

Song, Wu & Wang 2017, DOI 10.1186/s13662-017-1298-8:
global robust Mittag-Leffler stability for uncertain fractional neural networks using a Lur'e-Postnikov Lyapunov construction.

### Delayed interval nonlinear result

DOI 10.1016/j.jfranklin.2018.08.017:
global asymptotic stability of a class of interval fractional nonlinear systems with delay via fractional Razumikhin/LMI criteria.

### Interpretation

These are genuine open-loop robust global stability theorems, not merely controllers. They substantially raise the novelty bar.

But their property is essentially:

\[
\forall \Delta\in\mathcal U,\quad x(t)\to x^*.
\]

The target Allee property is instead multibasin and set-valued:

\[
x_0\in S
\implies
\forall(\alpha,\theta)\in\mathcal A\times\Theta,\quad
\text{survival},
\]

or a corresponding robust extinction statement.

That is not the same theorem.

---

## 5. Uniformity in order

Linear papers explicitly treat \(\alpha\) as an uncertain parameter.

Nonlinear global papers generally use a fixed order or a fixed order regime. A common algebraic Lyapunov inequality can sometimes be independent of the exact order, but the searched sources did not promote this into general:
- robust survival;
- basin inclusion;
- persistence;
- extinction
uniformly over an order interval.

No resolving result found for this stronger global property.

---

## 6. Robust permanence as the main classical killer

### Schreiber 2000

DOI 10.1006/jdeq.1999.3719.

Defines \(C^r\)-robust permanence for dissipative flows on the positive cone. Invariant-measure average growth rates give necessary/sufficient-type criteria; Morse decomposition gives sufficient conditions.

### Garay–Hofbauer 2003

DOI 10.1137/S0036141001392815.

Robust permanence, minimax and discretizations.

### Hofbauer–Schreiber 2010

DOI 10.1016/j.jde.2009.11.010.

Structured populations and dominant Lyapunov/invasion exponents.

### Patel–Schreiber 2018

DOI 10.1007/s00285-017-1187-5.

Robust permanence with internal and external feedbacks. Average Lyapunov functions and Morse decompositions; nonautonomous/structured/eco-evolutionary examples.

### Why the transfer is not automatic

A Caputo IVP is not a finite-dimensional flow on current populations.

After a Volterra lift one obtains a memory-state semidynamical system, but perturbing:
- \(\alpha\);
- \(\boldsymbol\alpha\);
- the kernel;
- the admissible memory state

is not transparently the same perturbation class as a small \(C^r\) vector-field perturbation.

Additionally, strong Allee systems deliberately violate global permanence on all positive states because an interior extinction basin exists.

Hence the relevant notion is robust **conditional/basin-relative** persistence.

---

## 7. Fractional viability and inclusions

### Girejko et al. 2011

DOI 10.1016/j.jmaa.2011.04.004.

Sufficient Caputo viability condition for locally closed sets.

### Carja et al. 2014

DOI 10.1016/j.aml.2014.06.012.

Sufficient conditions for viable solutions of Caputo fractional differential inclusions; corrects earlier results.

### Girejko et al. 2015

DOI 10.1186/s13662-015-0403-0.

Necessary/sufficient memo-viability development. The paper explicitly handles initialization and the memory domain because a naive classical Nagumo transfer is insufficient.

### Viability vs robust invariance

This is critical.

Viability:
\[
\exists \text{ an admissible solution staying in }K.
\]

Robust strong invariance:
\[
\forall \text{ admissible uncertain realizations, solution stays in }K.
\]

The first does not supply the second.

Therefore fractional differential inclusions are close prior art, but not a complete killer.

---

## 8. Robust regions of attraction

Topcu et al. 2010, DOI 10.1109/TAC.2009.2033751:
parameter-independent Lyapunov functions and invariant subsets for robust ROA of polynomial uncertain systems.

Later work includes uncertainty-dependent equilibrium locations and invariant-set/SOS methods.

Thus “common basin subset under uncertainty” is mature mathematics outside fractional systems.

A fractional contribution must add something nontrivial:
- memory state;
- order uncertainty;
- positivity/extinction boundary;
- persistence;
- Allee multistability;
- sharpness or maximality.

---

## 9. Direct ecological fractional uncertainty prior

Narayanamoorthy et al. 2019, DOI 10.1049/iet-syb.2019.0055, is the closest direct title.

Detailed inspection shows:
- fuzzy initial conditions;
- numerical modified fractional Euler method;
- selected fractional orders/parameter values.

It does not establish parameter/order-uniform threshold or basin theorems.

Direct fractional Allee papers from prior rounds already show order-dependent model dynamics and basins, but not robust set guarantees across uncertainty families.

---

## 10. Threshold geometry

Separate two cases.

### Order uncertainty only

For fixed \(f\),
\[
f(x;\theta)=0
\]
defines equilibria independently of \(\alpha\).

Therefore varying \(\alpha\) alone cannot create/move an equilibrium branch algebraically, although it can alter stability and memory-state basin geometry.

### Parameter uncertainty

Varying \(\theta\) can:
- move equilibria;
- create/destroy equilibria;
- cross saddle-node/cusp surfaces;
- move the integer-order or fractional stability boundary;
- change bistability.

### Combined uncertainty

This is the scientifically strongest setting because the family can cross both:
- equilibrium-catastrophe boundaries in \(\theta\);
- stability/memory boundaries involving \(\alpha\).

---

## 11. Uncertain bifurcation

Yang et al. 2022, DOI 10.1016/j.chaos.2021.111714, uses cylindrical algebraic decomposition to partition multiparameter space and identify stable regions / critical hypersurfaces for a nonlinear fractional system.

This is direct prior against any novelty claim based merely on “multiparameter fractional bifurcation regions”.

It remains local/Jacobian driven and does not provide:
- common survival sets;
- robust extinction sets;
- global basin separator enclosures;
- basin-relative persistence.

Retain ROUND-0010's warning that a Matignon-sector crossing must not automatically be called a classical periodic-orbit Hopf bifurcation for finite-terminal Caputo systems.

---

## 12. Incommensurate uncertainty

Linear robust stability is mature.

No general theorem was found for a nonlinear positive system under a rectangular order uncertainty set

\[
\mathcal A=
\prod_{i=1}^n[\alpha_i^-,\alpha_i^+]
\]

that guarantees extinction/survival/persistence uniformly over all \(\boldsymbol\alpha\in\mathcal A\).

This is especially natural for multi-species ecology.

---

## 13. Order identification and scientific uncertainty

Nazarian–Haeri–Tavazoei 2010, DOI 10.1016/j.isatra.2009.11.007, analytically studies fractional-system identifiability and reports substantial degradation in practical identifiability as \(\alpha\) decreases; noise worsens it.

Hence treating \(\alpha\) as uncertain is scientifically justified.

The gap is not order estimation itself. It is propagation of that uncertainty into rigorous nonlinear ecological conclusions.

---

## 14. Candidate theorem objects

A future original-research project, if selected later, could distinguish four levels.

### A. Common robust survival set

Find \(S\) such that

\[
x_0\in S
\implies
\operatorname{dist}(x(t),\partial X_+)\ge\eta
\]

eventually, for every admissible \((\boldsymbol\alpha,\theta)\).

### B. Common robust extinction set

Find \(E\) such that every admissible model initialized in \(E\) tends to the extinction attractor.

### C. Robust basin-relative persistence

Uniform persistence only on the uncertainty-robust survival side, rather than on all positive states.

### D. Robust bistability / threshold topology

Characterize the subset of \(\mathcal A\times\Theta\) on which:
- extinction and survival attractors coexist;
- their separator remains well defined;
- a common inner survival/extinction enclosure exists.

No searched source resolves this package.

---

## 15. Strongest killer analysis

### Killer 1
General nonlinear Caputo robust persistence/extinction theorem over parameter+order uncertainty.

**Does not fire.**

### Killer 2
Classical differential-inclusion/viability theorem applies directly.

**Does not fire.** Fractional viability has memory-specific theory; viability is existential rather than universal robust invariance.

### Killer 3
Classical robust permanence transfers verbatim after Caputo lift.

**Does not fire.** Very close prior art, but perturbation/state hypotheses do not transfer trivially and strong Allee requires conditional persistence.

### Killer 4
Fractional Allee literature already gives uncertainty-uniform basin/threshold theorem.

**Does not fire.**

---

## 16. Required verdicts

1. linear/order uncertainty — **DIRECT PRIOR**.
2. nonlinear open-loop robust stability — **SUBSTANTIAL PARTIAL THEORY**.
3. uniform-in-order nonlinear global theory — **NO RESOLVING RESULT FOUND**.
4. robust fractional permanence/persistence — **NO RESOLVING RESULT FOUND**.
5. robust extinction/survival thresholds — **NO RESOLVING RESULT FOUND**.
6. robust basin/invariant-region theory — **SUBSTANTIAL PARTIAL THEORY**.
7. uncertain bifurcation/catastrophe — **SUBSTANTIAL PARTIAL THEORY**.
8. incommensurate order uncertainty — **SUBSTANTIAL PARTIAL THEORY**.
9. Double-Allee-specific robust theory — **NO RESOLVING RESULT FOUND**.
10. classical-theory subsumption — **CLOSE PRIOR ART**.

---

## 17. Narrow novelty boundary

Covered:
- robust fractional linear stability;
- uncertain order;
- mixed uncertainty;
- incommensurate robust linear stability;
- nonlinear robust equilibrium stability in several classes;
- fractional viability;
- classical robust ROA;
- classical robust permanence;
- multiparameter fractional stability/bifurcation regions.

Search-qualified residual:

\[
\boxed{
\text{uncertainty-uniform global threshold geometry}
+
\text{basin-relative persistence}
}
\]

for positive nonlinear Caputo systems under simultaneous parameter/order uncertainty.

Double/Multiple Allee is a natural realization because it forces the theory to confront multistability rather than collapse to one-equilibrium robust stability.

---

## 18. Negative-search limitation

The correct claim is:

> No result resolving common survival/extinction regions and basin-relative persistence uniformly over simultaneous parameter and fractional-order uncertainty was identified in the searched corpus for autonomous uncontrolled positive Caputo systems as of 2026-09-28.

This is not proof of nonexistence.

A subsequent round, if requested, should target abstract robust persistence for semiflows and strong invariance for fractional inclusions, not broad fractional-control keywords.
