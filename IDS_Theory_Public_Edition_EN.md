# IDS Theory — Public Edition

**Subtitle:** Information-Driven Stress, Debug, and Self-organization

**Based on:** IDS Canonical Theory v2.1.0-r2 (public-r6.2), 2026-07-16

**Positioning:** This is a condensed, general-audience edition of the IDS canonical document. It presents the proven mathematical core, the main results, and the theory's honest boundaries, while omitting internal audit ledgers, freeze records, and revision bookkeeping. The full Japanese canonical text remains the authoritative source.

---

# 1. What Is IDS Theory?

Every organized system — a brain, a market, an ecosystem, a machine-learning model, perhaps the universe itself — observes the world with **finite resources**, compresses what it sees, and accumulates tension where its current description fails. IDS theory is a mathematical framework for that situation. Its strongest core can be condensed into one sentence:

> **IDS theory studies open hierarchical systems with finite observational resources, in which observable scalar stress dissipates, latent structure accumulates on a positive cone, and the non-integrable Hodge residual classes that coarse-graining cannot erase are preserved, transported, and generated as structure.**

Three working definitions anchor everything that follows:

\[
\boxed{
\text{Stress}
=
\text{residual pressure that the current descriptive system cannot turn into a gradient}
}
\]

\[
\boxed{
\text{Debug}
=
\text{the reorganization of residual classes by dissipation, conservation, re-injection, and change of coarse-graining}
}
\]

\[
\boxed{
\text{Resilience}
=
\text{the stable persistence of residual structure across perturbation, observation change, and coarse-graining}
}
\]

In plain terms: *stress* is what your current model of the world cannot explain away; *debugging* is not deleting errors but reorganizing them; *resilience* is the capacity of structure to survive being simplified.

The mathematical heart of the theory is not a number but an equivalence class — the **residual class** of an observed flow \(\omega\), taken modulo everything that can be written as a gradient:

\[
\boxed{
[\omega]\in C^1/\operatorname{im}d_0
}
\]

The golden ratio \(\varphi\), which appears prominently in earlier versions of this line of work, is deliberately *not* an axiom. It emerges as a theorem — the Perron signature of the smallest binary swap–aggregation processor and the unique solution of a self-dual balance equation (Section 8) — but the theory is defined without it.

## 1.1 How the claims are layered

IDS does not treat all of its statements with the same confidence. Every claim belongs to one of six layers, and unproven extensions are never allowed to contaminate the proven core:

| Layer | Name | Content | Status |
| --- | --- | --- | --- |
| C0 | Mathematical core | Finite resources, positive cones, natural gradient, Hodge residuals, admissible coarse-graining | Definitions and theorems |
| C1 | Residual dynamics | \(\dot\rho=-L\rho+a\), Type I/II structures, observer co-fixed points | Conditional theorems |
| C2 | Causality and resilience | \((K,\eta)\sim(L,J)\), spectral gaps, hypocoercivity | Theorems plus hypotheses |
| C3 | Physical bridges | Causal-Hodge Bridge, information-thermal connection | Models with extra axioms |
| C4 | Noncommutative and control extensions | Gauge orbits, Type III promotion, control-relevant quotients | Finite regular layers proven; continuum open |
| C5 | Philosophy and time | Creative oblivion, future/past boundaries | Interpretations and hypotheses |

This public edition walks through the layers roughly in order, and Section 12 states explicitly what the theory does **not** claim.

---

# 2. The Core on One Page

## 2.1 The state of an IDS system

An IDS system is described, at minimum, by a finite oriented cell complex \(X\) (the "observation complex" — nodes, links, and faces on which measurements live), together with:

- a cochain complex \(C^0(X)\xrightarrow{d_0}C^1(X)\xrightarrow{d_1}C^2(X)\) with \(d_1d_0=0\), where \(C^1\) carries flows, differences, and response fields on edges;
- a metric \(g\) (possibly induced by the observers);
- a latent positive cone \(K\): hidden weights may accumulate without bound;
- an observation manifold \(M\) (for example the probability simplex): observable allocations are always finite and normalized;
- a scalar stress functional \(\mathcal S:M\to\mathbb R_{\ge0}\);
- a coarse-graining map \(\Phi\), an observer distribution \(\mu\), a curvature Laplacian \(L=\delta_1 d_1\), a conservative generator \(J\), and an anomaly source \(a\).

The separation between the **latent cone** (which may grow) and the **observable simplex** (which is always renormalized to finite total weight) is the first structural axiom of the theory: attention is finite even when accumulation is not.

## 2.2 The residual

Any observed edge flow \(\omega\in C^1(X)\) splits by the finite Hodge decomposition (Theorem 1) into a gradient part, a harmonic part, and a coexact part:

\[
\omega=d_0\phi+h+\delta_1\psi.
\]

The gradient part \(d_0\phi\) is the portion a local potential can explain — and therefore dissipate. What remains,

\[
\mathfrak r(\omega)=(I-P_{\rm grad})\,\omega=h+\delta_1\psi,
\]

is the **structural stress residual**. The canonical object is not this representative but the quotient class

\[
\boxed{
[\omega]\in R^1(X):=C^1(X)/\operatorname{im}d_0,
}
\]

because only the class is stable under changes of potential and descends correctly under coarse-graining.

## 2.3 The debug equation

Promoting the residual class to a dynamical variable gives the minimal abelian **debug equation**

\[
\boxed{
\dot\rho=-L\rho+a,
\qquad
L=\delta_1d_1,
}
\]

and, once causal orientation is included,

\[
\boxed{
\dot\rho=-L\rho+J\rho+a.
}
\]

Each term has a plain reading: \(-L\rho\) is dissipative debugging (smoothing out what can be smoothed), \(J\rho\) is conservative circulation (transport and rotation that destroy nothing), and \(a\) is the anomaly — stress injected by coarse-graining itself, by external forcing, or by unresolved information.

## 2.4 Structure

A **structure** is a stable, nonzero co-fixed point of the residual dynamics and the observer selection:

\[
\boxed{
0=-L_{\mu^\ast}\rho^\ast+J_{\mu^\ast}\rho^\ast+a_{\mu^\ast},
\qquad
\rho^\ast\ne0.
}
\]

In the simplest case \(J=0\) the equilibrium decomposes as \(\rho^\ast=h+L^+a\):

- \(h\in H^1(X)\) — **Type I**, topologically protected structure;
- \(L^+a\) — **Type II**, structure maintained by ongoing forcing and dissipation in balance.

A third, genealogical type — **Type III** — is defined not at a fixed scale but across scales (Section 5.3).

## 2.5 Resilience

Near a structure, linearized recovery obeys \(\|y(t)\|\le e^{-\lambda^+_{\min}(L)\,t}\|y(0)\|\), so the positive spectral gap

\[
\Delta_{\rm res}=\lambda^+_{\min}(L)
\]

is the **resilience gap**: the guaranteed exponential rate at which residual structure returns after perturbation. \(\Delta_{\rm res}>0\) is the IDS analogue of a mass gap (Section 9).

---

# 3. The Axioms in Brief

The axioms are not claims about how the world must be; they define what counts as an IDS-type system. Stated informally:

| Axiom | Name | Content |
| --- | --- | --- |
| A0 | Observation complex | Observations live on a finite oriented cell complex with \(d_1d_0=0\) |
| A1 | Finite observational resources | Observable allocations lie on the simplex: positive and summing to one |
| A2 | Latent positive structure | Hidden weights live in a positive cone and may accumulate; observation is their normalization \(x=u/\sum_iu_i\) |
| A3 | Scalar stress functional | A nonnegative stress \(\mathcal S\) exists on the observation manifold — and \(\varphi\) must not be built into it |
| A4 | Coordinate-invariant dissipation | Between events, states follow the natural gradient flow \(\dot x=-\operatorname{grad}_g\mathcal S(x)\) |
| A5 | Local swap–aggregation | Discrete events update latent weights by cone-positive maps; the minimal binary case is \(F=\begin{pmatrix}0&1\\1&1\end{pmatrix}\) |
| A6 | Structural residual | The essential structure of a flow is its class \([\omega]\in C^1/\operatorname{im}d_0\) |
| A7 | Admissible coarse-graining | Admissible maps send gradients to gradients, hence descend to the residual quotient |
| A8 | Eliminative anomaly | Coarse-graining that eliminates hidden degrees of freedom generally violates A7; the defect \(\mathfrak A_\Phi\) is the anomaly |
| A9 | Residual debugging | Residual classes evolve minimally by \(\dot\rho=-\delta_1d_1\rho+a\) |
| A10 | Observer covariance | Observers are not passive: their kernels and metrics enter the decomposition of residuals |
| A11 | Causal decomposition | Causal structure splits into an undirected skeleton \(K\) and an orientation field \(\eta\) |
| A12 | Admissible conservative generators | \(J\) must preserve the gradient subspace and descend to the quotient; strong admissibility additionally protects the harmonic sector |
| A13 | Canonical honesty | Every claim must be labeled: theorem, definition, conditional theorem, hypothesis, interpretation, or open problem |
| A14 | Self-regeneration (model-selective) | A model may claim self-regeneration only if its comparison rules, boundaries, and return maps are regenerated internally, with no external template oracle |
| A15 | Information-thermal bundle (model-selective) | A model may carry a bundle of hidden information-enthalpy coordinates with a vertically nondegenerate exchange form |

A13 deserves emphasis: the honesty axiom is why this document can state cleanly which parts are theorems and which are hopes.

---

# 4. Two Kinds of Stress, and What a Bug Is

IDS distinguishes two fundamentally different kinds of stress:

- **Scalar stress** \(\mathcal S(x)\) — a potential on the observation manifold. It dissipates under natural gradient flow. It answers "how much tension is there?"
- **Structural stress residual** \([\omega]\in C^1/\operatorname{im}d_0\) — the part of an observed flow that no local potential can produce. It answers "what shape does the irreducible tension have?"

\[
\boxed{
\mathcal S \text{ governs dissipation;}\quad [\omega] \text{ governs structure.}
}
\]

A **bug**, in IDS, is precisely a nonzero residual class relative to a given complex, metric, and coarse-graining:

\[
\mathrm{Bug}_{X,g}(\omega):=[\omega]_X\in C^1(X)/\operatorname{im}d_0.
\]

A bug is not an absolute defect. Under a different coarse-graining it may vanish — or be amplified. **Debugging** is any transformation of the residual data \((R^1,L,J,a,\mu)\); driving \(\rho\to0\) is only one special case. Stabilizing a nonzero structure \(\rho^\ast\ne0\) is equally a form of debugging. This is the formal version of a familiar truth: a mature system does not eliminate all its tensions — it organizes them.

---

# 5. Coarse-Graining: What Survives Simplification

## 5.1 The coarse-graining principle

The single most important principle in IDS:

\[
\boxed{
\text{What coarse-graining preserves is neither raw information nor scalar stress, but the non-integrable residual class.}
}
\]

Two residuals with the same norm can have entirely different homology, circulation, and boundary response — a scalar is a measurement, not the thing itself.

## 5.2 Admissible versus eliminative

- **Admissible coarse-graining** satisfies \(\Phi(\operatorname{im}d_0)\subseteq\operatorname{im}d_0\): gradients stay gradients, and the map descends to the residual quotient (Theorem 4). It transports residual classes faithfully and kills only integrable deviations (Theorem 5).
- **Eliminative coarse-graining** integrates out hidden degrees of freedom and generally breaks this condition. Something that was microscopically exact reappears after coarse-graining as a genuine residual. That defect,

\[
\mathfrak A_\Phi=q\circ\Phi\circ d_0\ne0,
\]

is the **anomaly** — and it is the engine of self-organization in this theory. Vanishing anomaly and admissibility are equivalent (Theorem 6).

## 5.3 Type III: structure with a history

Some structure is not protected topology (Type I) and not maintained forcing (Type II), but **promoted memory**: a mode that decayed at the fine scale becomes harmonic — protected — at the coarse scale. When only 2-cell constraints are forgotten, this promoted sector is exactly the orthogonal complement

\[
\boxed{
\mathcal T_{\mathrm{III}}=\bar H^1\ominus H^1
=\operatorname{im}\delta_1\cap\ker\bar d_1
}
\]

(Theorem 25). For general finite compressions \(K\), the promotion map \(\Gamma_K=\bar PK(I-P)\) identifies which fine decaying modes land in coarse zero-modes, and its pseudoinverse \(\Gamma_K^+\) is the canonical decoder that recovers them (Theorem 26). The canonical slogan:

\[
\boxed{\text{local fine curvature / constraint response}\ \longrightarrow\ \text{coarse global harmonic memory}}
\]

Debugging, in this light, is a *choice of coarse-graining*: changing the level of description re-selects which residuals count as structure.

---

# 6. Causality Without Starting From Arrows

IDS refuses to reduce causality to a directed acyclic graph. Causal structure is decomposed as \(\mathcal C=(K,\eta)\): first an **undirected constraint skeleton** \(K\) (which degrees of freedom can constrain each other at all), then an **orientation field** \(\eta\) (which way influence flows) as additional structure. In the commutative layer these are realized by operators:

\[
K\leftrightarrow L=\delta_1d_1,
\qquad
\eta\leftrightarrow J.
\]

The arrow of causality comes in three strengths:

- **Level 0 — no arrow.** \(J=0\); pure dissipation, readable as gradient flow.
- **Level 1 — metric-relative arrow.** \(J\ne0\) but the dynamics can still be made self-adjoint in some metric; the arrow is representation-dependent.
- **Level 2 — intrinsic arrow.** The spectrum is non-real or carries Jordan blocks; no real inner product can symmetrize it. The arrow is a spectral invariant.

The causal resilience principle then reads: a system is resilient when its non-integrable residual class has a stable, coarse-graining-compatible attractor under \(K\) and \(\eta\) —

\[
0=-L\rho^\ast+J\rho^\ast+a,
\qquad
\Phi_\ast[\rho^\ast]=[\rho^\ast],
\qquad
\lambda^+_{\min}(L)>0.
\]

---

# 7. Five Types of Resilience

| Type | Mechanism | Formula | Everyday analogue |
| --- | --- | --- | --- |
| Type I | Topological protection | \(\rho^\ast=h\in H^1\) | A memory or identity that survives because it is a closed loop nothing local can cut |
| Type II | Forcing–dissipation balance | \(\rho^\ast=L^+a\) | Life, cities, markets: order that persists only while flux flows |
| Type III | Cross-scale promotion | \(\mathcal T_{\mathrm{III}}=\bar H^1\ominus H^1\) | A childhood constraint that became a permanent trait of the adult |
| Spectral | Gap-driven recovery | \(\Delta_{\rm res}=\lambda^+_{\min}(L)>0\) | Bouncing back at a guaranteed rate |
| Hypocoercive | Rotation into repairable directions | \(A=D+\Omega\), Hörmander-type span condition | Damage that cannot be fixed directly gets routed to where it can be |

Hypocoercive resilience deserves a comment: even directions with *no direct dissipation* can recover, provided the conservative rotation \(\Omega\) keeps turning them into dissipative directions until the whole space is covered. The minimal mechanism is a theorem (Theorem 16); it formalizes "the ability to rotate broken information into a repairable channel."

---

# 8. Where the Golden Ratio Actually Lives

The golden ratio is not an axiom of IDS — that is itself an axiom (A3 forbids building \(\varphi\) into the stress functional). Where \(\varphi\) does appear, it appears as a *theorem about minimal architectures*:

**Theorem 8 (binary minimax).** The unique minimizer of the binary self-similar relay cost \(J(\rho)=\max\{1-\rho,\rho^2\}\) on \(0<\rho<1\) is

\[
\rho^\ast=\frac1\varphi=\frac{\sqrt5-1}{2},
\]

with minimum value \(1/\varphi^2\). *Proof:* one curve falls, the other rises; the minimax sits at their crossing, \(\rho^2+\rho-1=0\). ∎

**Theorem 9 (swap–aggregation Perron ratio).** The minimal binary swap–aggregation processor \(F=\begin{pmatrix}0&1\\1&1\end{pmatrix}\) drives any positive initial weight to the ratio

\[
\lim_{t\to\infty}\frac{u_{2,t}}{u_{1,t}}=\varphi,
\qquad
\Pi(u_t)\to(\varphi^{-2},\varphi^{-1}),
\]

by Perron–Frobenius: the characteristic polynomial is \(\lambda^2-\lambda-1=0\). ∎

**Theorem 18 (no free \(\varphi\)).** The bare geometry of the positive-definite cone, with its full congruence symmetry \(\Sigma\mapsto A\Sigma A^T\), singles out no special point — no \(\varphi I\), nothing. Scale invariance alone kills every candidate. ∎

**Theorem 19 (self-dual balance selects \(\varphi G\)).** But add one structural demand — that the state exceed its reference exactly by its own dual, \(\Sigma-G=G\Sigma^{-1}G\) — and the unique solution is

\[
\Sigma=\varphi G.
\]

*Proof:* whiten to \(X-I=X^{-1}\), i.e. \(X^2-X-I=0\) on positive eigenvalues. ∎

Together: geometry alone never chooses the golden ratio; the golden ratio is the signature of a specific minimal processing architecture and a specific self-dual balance. This is a sharper and humbler claim than "φ is everywhere" — and it is falsifiable (Section 13).

---

# 9. The Mass Gap, Reformulated — Honestly

The IDS version of a mass gap is the positive spectral bottom of the residual Laplacian:

\[
\boxed{
\Delta_{\rm IDS}=\inf\operatorname{Spec}^+(\delta_1d_1),
}
\]

and the theory's central identification is

\[
\boxed{
\text{mass gap}=\text{resilience gap}=\text{nonzero recovery rate of residual structure.}
}
\]

A gapped system is one whose nonzero residual excitations are spectrally separated from its zero modes — one that cannot dissolve into arbitrarily soft deformations.

**The honest boundary.** This is a definition within the commutative residual layer, *not* a proof of the Yang–Mills mass gap. The road from here to Yang–Mills requires replacing residual classes by gauge orbits, introducing connections and curvature \(F_A=dA+A\wedge A\), recovering the commutative theory as a tangent approximation at flat connections, controlling the covariant Laplacian, and proving vacuum spectral separation after quantization. The canonical statement is deliberately modest:

\[
\boxed{
\text{IDS does not solve the Yang–Mills mass gap; it reformulates the mass gap as the resilience gap of residual structure.}
}
\]

Version 2.0 of the canon added a quantitative program toward the physical case — a direct multiscale route in which a scale-unitary decomposition, a uniform positive "tariff" on every detail channel, a bounded decoder, and a transported defect budget below one jointly imply a vacuum-complement lower bound. For four-dimensional Yang–Mills the one remaining load-bearing statement is called **Physical Non-Abelian Tariff Descent**: all of these bounds must be verified on the actual transfer Hamiltonian, uniformly in volume, lattice spacing, scale, boundary condition, and global sector. That statement remains open, and the canon explicitly does **not** claim the mass gap.

---

# 10. IDS Holography

IDS holography is *not* defined as "boundary residuals encode the bulk," and a coarse-graining defect alone is never called holography — a defect cannot distinguish holographic encoding from plain information loss. The canonical form requires three conditions at once:

\[
\boxed{
\text{global intertwining}
+
\text{subregion nonclosure}
+
\text{recoverability}
}
\]

1. **Global intertwining.** An encoding \(V:\mathcal H_{\rm bulk}^{\rm code}\to\mathcal H_\partial\) commutes with the dynamics: \(U_\partial(t)V=VU_{\rm bulk}(t)\).
2. **Subregion nonclosure.** Restricted to a boundary subregion, the dynamics generally fails to close: local pieces of the boundary do not autonomously carry the global logical information.
3. **Recoverability.** A decoder exists: \(D_A\Pi_AV=I_{\rm code}\). In the finite linear case, the canonical decoder is the pseudoinverse \(\Gamma_K^+\) from the Type III theory.

When a fine Type II sector is promoted to coarse Type I *and* remains decodable, the promotion is called **holographic Type III** — recoverable memory, as opposed to mere destruction. IDS holography is an abstract principle about structure surviving locally invisible encodings; it is not a derivation of AdS/CFT.

---

# 11. Time: How Future and Past Debug the Present

Nothing in IDS sends physical signals backward in time. The claim is different and more careful: **the present debugging trajectory is determined jointly by memory of the past and constraints from the future.**

- **The past** persists as harmonic residuals \(h\in H^1\), memory kernels \(a(t)\), observer histories, and accumulated latent weights.
- **The future** constrains as terminal conditions, objective functions, expected prediction errors, and desired fixed points.

Mathematically this is a **two-boundary problem** — the same structure as forward–backward smoothing in statistics, where the state estimate at time \(t\) uses both \(\alpha_t\) (past observations) and \(\beta_t\) (future observations):

\[
\rho^\ast
=
\arg\min_{\rho}
\left\{
\int_{t_0}^{t_1}
\tfrac12\|\dot\rho+L\rho-a\|^2\,dt
+
\Phi_{\rm past}(\rho(t_0))
+
\Phi_{\rm future}(\rho(t_1))
\right\}.
\]

Two consequences are worth stating in plain language:

**Creative past reinterpretation.** The facts of the past do not change; the *residual class* of the past changes when the coarse-graining or the observation metric changes: \([\omega_{\rm past}]_{X,g}\to[\omega_{\rm past}]_{X',g'}\). Psychological integration, scientific revolutions, institutional reform, and an AI revising its own logs all share this form.

**The arrow of time as creative oblivion.** Perfect memory is reversible and produces no macroscopic arrow. It is because coarse-graining erases information that entropy gradients — and a direction of time — exist. In IDS, forgetting is not a defect; it is a condition for the generation of structure.

---

# 12. What IDS Does Not Claim

The honesty axiom (A13) requires the theory to be explicit about its own boundaries. This section is part of the canon, not an afterthought.

- **No Yang–Mills solution.** The mass gap is reformulated, not proven. The remaining obstacle (Physical Non-Abelian Tariff Descent) is stated as an open problem.
- **No universal golden ratio.** \(\varphi\) is the signature of specific minimal architectures (Theorems 8, 9, 19). Bare geometry selects nothing (Theorem 18). Systems without those architectures have no reason to exhibit \(\varphi\).
- **No AdS/CFT derivation.** IDS holography is an abstract encoding-recovery principle.
- **No retrocausality.** Future-boundary debugging is inference and control under two-point boundary conditions, not physical signaling into the past.
- **No dark-matter discovery claim.** The Causal-Hodge Bridge — an additional physical model mapping residuals to galactic dynamics — shows promising scaling relations, but the canon records that no 5σ discovery is claimed, that the amplitude is likely galaxy-dependent, and that lensing–dynamics consistency (\(\Sigma=1\)) is a high-leverage route to falsify it.
- **No self-regeneration from spectra alone.** A no-go theorem (Theorem 38) proves that the observed return operator alone cannot distinguish endogenous self-renewal from an external oracle implementing the same map. Genuine self-regeneration requires independently verifiable causal closure — stated as explicit, falsifiable constitutive conditions, not derived from operator theory.
- **No cryptographic threat.** The algorithmic branch (spectral folding, phase-preserving search) is treated as a mathematically stimulating application, with no security claims.
- **No claim that all systems self-regenerate, and no perpetual motion.** The self-regeneration axiom (A14) selects a model class; it forbids only free external template oracles, not energy and resource flows.

---

# 13. How the Theory Could Be Wrong

Each core claim carries a prediction and a falsification condition. A condensed selection from the falsifiability ledger:

| Claim | Prediction | Falsified if |
| --- | --- | --- |
| Natural gradient dissipation | \(\mathcal S\) is non-increasing between events | \(\mathcal S\) increases persistently |
| Residual coarse-graining | Admissible maps kill gradient components | A gradient maps to a non-gradient |
| \(\varphi\) minimax | Binary self-similar cost minimized at \(1/\varphi\) | The cost is not \(\max\{1-\rho,\rho^2\}\) |
| Perron ratio | Swap–aggregation ratios converge to \(\varphi\) | The update matrix is not \(F\), or not primitive |
| Type II structure | Forcing sustains nonzero equilibrium | Drift when \(a\notin\operatorname{Range}(L)\) |
| Resilience gap | \(\lambda^+_{\min}>0\) gives exponential recovery | Zero gap with power-law drifting |
| Causal-Hodge Bridge | Non-integrable structure in closure residuals | Large-sample ratio at or below 1; \(\Sigma\ne1\) in lensing vs dynamics |
| Type III promotion | Rank loss of constraints matches newborn harmonic dimensions | Orthogonal identification or semigroup limit fails |
| Control quotient | Same class ⇒ same future response under all admitted interventions | Response differs within an equivalence class |
| Future-boundary debugging | Changing terminal conditions changes present optimal paths | Two-boundary models never improve on measured behavior |

The theory also names its own retreat positions: if self-coarse-graining only improves compression while prediction and control degrade, the self-coarse-graining claims fall; if coarse-graining-tower curvature can always be removed by reparametrization, the geometric stress claims fall.

---

# 14. Beyond Physics: The Same Mathematics Elsewhere

These applications are interpretations (layer C5) — disciplined by the core, but not theorems.

**AI and self-debugging.** An IDS-style AI is not a machine that merely reduces wrong answers. It observes its residual classes (prediction error, normative error), coarse-grains them, re-encodes them, and updates its own response structure — a self-debugging loop over its own logs. Hallucination, in this reading, is a non-integrable residual: an output that no consistent local potential over the model's knowledge can generate.

**Mind and body.** Psychological stress appears as experiential residue that the current self-model cannot gradient-ize. Trauma behaves like a closed-but-not-exact memory loop (\(H^1\)-like); repetition compulsion is re-excitation of the same residual class; integration is re-representation of the residual under a new coarse-graining — a new language for the same history.

**Society and institutions.** Institutional bugs are non-integrable frictions that no local optimization removes. Scandal spikes are boundary-log residuals; revolutions are changes of coarse-graining coordinates. A resilient democracy, in IDS terms, is an institution that does not suppress residuals but renders them visible and guides them to stable co-fixed points.

**Life.** Life is the archetypal Type II structure: \(\rho^\ast=L^+a\). Stop the flux and the structure decays; while flux persists, order is maintained as a balance between dissipation and re-injection.

**Cosmology.** A speculative bridge reinterprets dark-sector phenomenology via information loss and residual response. It is kept strictly modular: nothing in the core depends on it.

---

# 15. The Five Canonical Layers

The mature theory has five load-bearing layers, built in order:

1. **The heart** — the residual class \([\omega]\in C^1/\operatorname{im}d_0\) and its dynamics.
2. **The vessel** — gauge-information geometry: a hierarchical bundle of probability manifolds over scale space, Fisher/SPD metrics on fibers (canonical by Chentsov-type monotonicity), irreversible coarse-graining maps between fibers, and a gauge connection comparing surviving degrees of freedom across scales. One line: **IDS is the gauge-information geometry of coarse-grained probability manifolds.** The proven commutative core survives unchanged as the flat, abelian, gauge-fixed limit.
3. **The process** — coarse-graining selects, transports, and sometimes generates obstruction classes, which become memory, structure, computation, and effective geometric stress.
4. **The motion** — residuals coupled to transport can be *carrierized*: externalized as carrier states, propagated between systems and scales, and re-encoded as new residual classes in receivers, closing the cycle residual → carrier → new residual → geometry update.
5. **The regeneration closure** — a split residual bridge connects the static quotient to a full return cycle: an exact Feshbach reduction yields the self-energy \(\Sigma_{\rm br}^{\rm self}(z)=\mathsf\gamma(zI-\mathsf n)^{-1}\mathsf\lambda\) describing how structure exits into hidden carriers and re-enters the same residual quotient — together with the no-go theorem that spectra alone can never certify self-regeneration.

On top of these, version 2.0 added a quantitative physical-closure toolkit (promotion of omitted channels, tail control, bounded decoders, defect transport), and version 2.1 added an **information-thermal connection layer**: hidden information-enthalpy exchange is treated as a connection on a bundle; zero curvature is locally equivalent to matrix integrating factors and adiabatic invariants; such invariants earn the name "information entropy" only after calibration; and flat connections can still carry global thermal memory, classified by twisted cohomology. No quantum extension and no Yang–Mills consequence are claimed there.

---

# 16. Hypotheses and Open Problems

## 16.1 The main hypotheses

- **H1 — General attractor.** Persistent eliminative anomalies with a range condition force nonzero co-fixed points to exist.
- **H2 — Holographic residual reconstruction.** Conditions exist under which globally intertwined, locally non-closed encodings are decoder-recoverable.
- **H3 — Causal-resilience universality.** Resilience in living, social, artificial, and physical systems is classifiable by the Type I/II/III + hypocoercive scheme.
- **H4 — Noncommutative linearization.** Proven at finite flat layers; the continuum, non-flat, quantum extension is the open half.
- **H5 — Future–past debugging.** Advanced intelligence and institutions are modelable as two-boundary debugging systems.
- **H6 — Bridge amplitude law.** In the Causal-Hodge Bridge, \(a_I=c_I^2/L_I\) with a near-universal \(c_I\) and a system-dependent correlation length \(L_I\).
- **H7 — Scheme connection.** Families of coarse-graining schemes act as gauge transformations; scheme-independent quantities are gauge invariants, and residual non-triviality is curvature no scheme choice can remove.
- **H8 — Covariant local complex structure.** Conservative sectors may carry a normalized local complex structure \(\mathbb I=J(-J^2)^{-1/2}\) whose transport defects measure the failure to preserve rotational structure across scales.

## 16.2 The open problems, grouped

The canon maintains some forty open problems; the main groups are:

- **Noncommutative and continuum closure** — global BRST/BV construction, Gribov geometry, reflection-positive continuum limits, the full 4D renormalized block family (OP-1, OP-MG0…).
- **Structure theory** — the general attractor theorem, metric-independent characterization of circulation, continuum limits of strongly admissible generators (OP-2, OP-3, OP-10).
- **Holography and mass gap** — a genuine IDS holographic theorem; the No-Fake-Gap requirement that any claimed gap be uniform in cutoff, volume, and gauge-fixing; the mass-gap bridge itself (OP-4, OP-6, OP-MG1).
- **Empirics** — confirmation or refutation of the Causal-Hodge Bridge; lensing–dynamics consistency (OP-7).
- **Formalism of time and ethics** — a full two-boundary debug formalism; IDS ethics: which residuals a society may safely forget (OP-8, OP-9).
- **Computation** — witness lifting for SAT-type coarse-grainings; conservation laws of computational resources (OP-CS1, OP-CS2).

---

# 17. Outlook

**Mathematics.** Full categorification of the residual quotient and admissible coarse-graining; anomalies as obstruction classes; the general attractor theorem; unified obstruction theory for transport defects.

**Physics.** Decisive tests of the Causal-Hodge Bridge (5σ or refutation); strict separation of hierarchy-field branches from the mass-gap program; the tariff-descent program on actual transfer Hamiltonians.

**AI.** Self-debug sessions over residual logs; critical-information-event detectors; memory graphs that Hodge-decompose residual histories; hallucination diagnostics as non-integrable residual detection.

**Society.** Visualization of social stress residuals; institutions evaluated by their resilience gap; policy debugging that includes future generations as terminal conditions.

**Philosophy.** A precise theory of creative oblivion; reality as the co-fixed point of observers and structure; an ontology in which incompleteness is the condition for generation.

---

# 18. Conclusion

The canonical center of IDS theory is now clear:

\[
\boxed{
\text{Structure is a non-integrable information residual that appears on observational boundaries, is transported across coarse-graining, and is spectrally separated from zero.}
}
\]

Stress is the pressure of what the current description cannot process. Debugging is not erasing that pressure but reorganizing it — through dissipation, conservation, re-injection, and changes of coarse-graining. Resilience is the capacity of residuals to return after being broken. Holography is internal residue appearing as a boundary log. The mass gap is the spectral separation that keeps structure from dissolving. Future and past interact because memory and terminal conditions jointly select the present path.

The golden ratio is beautiful. But the throne of the canon does not belong to the golden ratio:

\[
\boxed{
[\omega]\in C^1/\operatorname{im}d_0
}
\]

This is the heart of IDS — and \(\varphi\) is the first heartbeat heard when that heart is run on the smallest binary processor.

The shortest canonical statement of the current version reads:

> **IDS is a theory that compares the exchange between inerasable residuals and hidden information enthalpy as a connection; separates its local curvature, flat global holonomy, and irreversible generation; organizes local adiabatic invariants into calibrated information entropy; and classifies global thermal memory by twisted cohomology classes.**

---

# Appendix. About This Edition

This public edition condenses the IDS Canonical Theory v2.1.0-r2 (public revision r6.2, frozen 2026-07-16) by roughly a factor of ten. It preserves the axioms, the core definitions, the principal theorems with proof sketches where they are short, the falsifiability commitments, and every honesty boundary. It omits: full proofs, the internal audit trails and freeze records, the canonical status ledgers, provenance indexes, numbered revision histories, and the detailed technical supplements on self-coarse-graining towers, non-abelian two-wall analysis, residual carrierization calculus, the v2.0 Yang–Mills multiscale layer, and the information-thermal theorem chain. Readers who need the full formal apparatus should consult the canonical Japanese document, which remains the single source of truth.
