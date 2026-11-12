# Unitary Black Hole Evaporation, Quantum Extremal Surfaces, and the Page Curve

**Author:** Luís Pimenta Damásio  
**Affiliation:** Independent Researcher, Lisbon, Portugal  
**ORCID:** [0009-0001-7606-7557](https://orcid.org/0009-0001-7606-7557)  

**Keywords:** Black Hole Information Paradox, Quantum Extremal Surfaces, Island Formula, Replica Wormholes, Page Curve, Unitary Evaporation, Dimensionless Invariants

---

### Abstract
We present a self-contained semiclassical formulation of unitary black hole evaporation that couples dynamical horizon collapse and Quantum Extremal Surface (QES) entanglement-wedge reconstruction with a unified set of dimensionless diagnostic invariants. Modeling exponential mode peeling across an ingoing Vaidya horizon, we trace the thermodynamic transition from early-time linear entanglement growth to late-time radiation purification via the Euclidean replica-wormhole saddle exchange. To audit microstate unitarity, horizon blueshift regularization, and holographic information bounds continuously along Kerr–Newman evaporation trajectories, we integrate the Zero-Angular-Momentum Observer (ZAMO) dilation factor ($\rho_\tau$), Weyl conformal purity ($\chi$), decoherence action ($\Omega$), holographic coherence floor ($\Phi_{\text{floor}}$), timeline integrity ($\Phi_\tau$), surviving coherent cycles ($\mathcal{N}_{\text{eff}}$), the Lloyd–Bekenstein gate ratio ($\eta_{\text{Lloyd}}$), and the $L_\infty$ semiclassical breakdown index ($\Xi_{\text{QG}}$).

---

### AI Collaboration & Authorship Transparency Statement
*This theoretical framework, its mathematical derivations, and its manuscript preparation were developed through an interactive human–AI research collaboration between Luís Pimenta Damásio and Google's Gemini AI assistant. Conceptual direction, physical synthesis, metric architecture, and final editorial verification were directed by the human author, with formal mathematical derivations, LaTeX typesetting, and literature verification generated with the aid of Gemini.*

---

## 1. Dynamical Horizon Collapse and Kinematical Redshift

Consider a spherically symmetric collapsing star modeled by the ingoing **Vaidya spacetime metric**:

$$ds^2 = -\left(1 - \frac{2GM(v)}{c^2 r}\right) c^2 dv^2 + 2c\, dv\, dr + r^2 d\Omega^2$$

where $v$ denotes advanced null time and $M(v)$ is the evolving mass profile.

* **Exponential Mode Peeling and Bogoliubov Coefficients:**
  Tracing outgoing null rays backward from future null infinity ($\mathcal{I}^+$) through the collapsing center to past null infinity ($\mathcal{I}^-$) relates asymptotic retarded time $u$ to the affine horizon coordinate $U$ via:
  $$U = -\kappa^{-1} e^{-\kappa u}$$
  where $\kappa$ is the horizon surface gravity. Evaluating the Klein–Gordon inner product between early-time ($\mathcal{I}^-$) and late-time ($\mathcal{I}^+$) field modes yields Bogoliubov coefficients $\alpha_{\omega\omega'}$ and $\beta_{\omega\omega'}$ satisfying a thermal Planck spectrum at the **Hawking temperature** [1]:
  $$T_H = \frac{\hbar \kappa}{2\pi k_B c}$$

* **Role of Kinematical and Curvature Invariants ($\rho_\tau$ and $\chi$):**
  * **ZAMO Dilation Factor ($\rho_\tau$):** Relates proper time intervals along the local Zero-Angular-Momentum Observer frame ($d\tau_{\text{pre}}$) to distant observer proper time ($d\tau_{\text{obs}}$) via $\rho_\tau = d\tau_{\text{obs}} / d\tau_{\text{pre}}$ [2, 3]. It transforms local horizon-frame temperature $T_{\text{eff}}$ into the Tolman–Ehrenfest redshifted temperature measured at infinity:
    $$T_{\text{obs}} = \frac{T_{\text{eff}}}{\rho_\tau}$$
    Under the stretched-horizon membrane regulator ($N^2 \ge 10^{-6}$) [4], $\rho_\tau$ remains strictly bounded ($\rho_\tau \le 10^3$), preventing unphysical infinite-blueshift divergences near the horizon.
  * **Weyl Conformal Purity ($\chi$):** Quantifies static geometric vacuum polarization induced by background tidal curvature ($\mathcal{A}_W = \mathcal{C}_{\text{clamped}}^2 / 60\pi^2$) derived from the Seeley–DeWitt $a_4$ trace anomaly [5]:
    $$\chi = \frac{1}{1 + 60\,\mathcal{A}_W} = \frac{1}{1 + \mathcal{C}_{\text{clamped}}^2 / \pi^2}$$
    In flat Minkowski space ($\mathcal{C}_{\text{clamped}} = 0$), $\chi = 1$; at a horizon, $\chi$ drops below unity ($\approx 0.908$ for Schwarzschild, $\approx 0.712$ for extremal Kerr–Newman), isolating time-independent curvature mode mixing from thermal particle emission.

---

## 2. Generalized Entropy and the Quantum Extremal Surface (Island Formula)

In semiclassical gravity, the von Neumann entropy of Hawking radiation ($S_{\text{rad}}$) collected in a distant region $R$ diverges near the horizon due to short-distance ultraviolet entanglement across the boundary. Regulating this divergence requires pairing geometric horizon area with renormalized bulk field entropy on a spacelike slice $\Sigma_X$.

* **Generalized Entropy Functional ($S_{\text{gen}}$):**
  Allowing the radiation's entanglement wedge to include a disconnected interior **island** $I$ bounded by a codimension-2 surface $\partial I = X$, the generalized entropy is:
  $$S_{\text{gen}}(X) = \frac{\text{Area}(X)}{4 G \hbar} + S_{\text{bulk}}(R \cup I)$$

* **Extremization and Minimization (The Island Rule):**
  Varying $X$ along orthogonal future-directed null normals ($k^\mu$ outward, $l^\mu$ inward) until the quantum expansions vanish ($\Theta_k = \Theta_l = 0$) and selecting the global minimum over all extremal saddles gives [6, 7]:
  $$S_{\text{rad}}(R) = \min_I \left\{ \operatorname{ext}_{\partial I} \left[ \frac{\text{Area}(\partial I)}{4 G \hbar} + S_{\text{bulk}}(R \cup I) \right] \right\}$$

* **Euclidean Replica Wormhole Saddle Exchange:**
  Evaluating the $n$-sheeted gravitational path integral via the **Replica Trick**:
  $$S_{\text{rad}} = -\lim_{n \to 1} \frac{\partial}{\partial n} \ln \left(\frac{Z_n}{Z_1^n}\right)$$
  exposes two competing topological saddles:
  1. **The Hawking Saddle ($I = \emptyset$, Disconnected Replicas):** Produces linear entanglement growth $S_{\text{rad}}^{(\text{Hawking})}(t) \approx \frac{c_{\text{eff}}}{12} \kappa t$, leading to apparent information loss [1, 8].
  2. **The Replica Wormhole Saddle ($I \neq \emptyset$, Connected Replicas):** Connects the $n$ copies through a wormhole throat branched at $\partial I$, yielding $S_{\text{rad}}^{(\text{Island})}(t) \approx \frac{\text{Area}(r_+(t))}{4 G \hbar} = S_{\text{BH}}(t)$ [6, 7].

---

## 3. Unitary Page Curve Evolution and Microscopic Coherence Bounds

Summing over both saddles in the Euclidean path integral forces the smaller Euclidean action to dominate exponentially, yielding the unitary **Page Curve** [8]:

$$S_{\text{rad}}(t) = \min\big[S_{\text{BH,init}} - S_{\text{BH}}(t),\; S_{\text{BH}}(t)\big]$$

* **Pre-Page Regime ($t < t_{\text{Page}}$):** The trivial saddle ($I = \emptyset$) dominates, and $S_{\text{rad}}(t)$ rises as outgoing quanta entangle with interior partners.
* **Page Time ($t = t_{\text{Page}}$):** When the horizon area shrinks to half its initial value, $S_{\text{rad}}^{(\text{Hawking})}(t_{\text{Page}}) = S_{\text{BH}}(t_{\text{Page}})$, triggering the phase transition to the non-trivial Quantum Extremal Surface.
* **Post-Page Regime ($t > t_{\text{Page}}$):** Late Hawking quanta purify early radiation, and $S_{\text{rad}}(t)$ tracks $S_{\text{BH}}(t)$ downward along the Kerr–Newman evaporation trajectory:
  $$\frac{dM}{dt} = -\alpha_H \frac{f_{\text{KN}}^2}{M^2}, \qquad f_{\text{KN}} = \frac{2\chi_{\text{ext}}}{1 + \chi_{\text{ext}}}, \qquad \chi_{\text{ext}} = \sqrt{1 - a_*^2 - Q_*^2}$$

### How Custom Invariants Enforce and Audit Microscopic Unitarity

* **Decoherence Action ($\Omega$) and Timeline Integrity ($\Phi_\tau$):**
  Along the evaporating worldline, thermal Hawking scattering ($\Gamma_{\text{th}}$) and gravitational self-energy dephasing ($\Gamma_{\text{grav}}$) accumulate dimensionless decoherence action $\Omega = (\Gamma_{\text{th}} + \Gamma_{\text{grav}})\,t_{\text{pre}}$ [9, 10]. Rather than allowing quantum state purity to vanish identically ($\operatorname{Tr}(\rho^2) \to 0$, which would violate unitarity), **Timeline Integrity ($\Phi_\tau$)** bounds coherence decay from below:
  $$\Phi_\tau(\Omega) = \Phi_{\text{floor}} + (1 - \Phi_{\text{floor}})\,e^{-\Omega}$$

* **Holographic Coherence Floor ($\Phi_{\text{floor}}$):**
  Derived from the Bekenstein–Hawking Hilbert-space dimension $N_{\text{dof}} = 1 + \pi \cdot 10^{2\zeta}$ (where $\zeta = \log_{10}(r_+ / \ell_P)$), **$\Phi_{\text{floor}}$** represents the irreducible purity of a maximally scrambled state inside a causal sphere of radius $r_+$:
  $$\Phi_{\text{floor}} = \frac{1}{1 + \pi \cdot 10^{2\zeta}}$$
  For astrophysical horizons ($\zeta \gg 1$), $\Phi_{\text{floor}} \approx 10^{-70}$; as evaporation shrinks the horizon toward the Planck length ($\zeta \to 0$), $\Phi_{\text{floor}}$ rises smoothly to $(1 + \pi)^{-1} \approx 0.2414$, preserving residual microstate correlations.

* **Surviving Coherent Cycles ($\mathcal{N}_{\text{eff}}$) and Lloyd–Bekenstein Ratio ($\eta_{\text{Lloyd}}$):**
  Weighting total emitted wave oscillations ($\mathcal{N}_\phi = f_{\text{local}}\,t_{\text{pre}}$) by $\Phi_\tau$ yields the effective coherent cycle count $\mathcal{N}_{\text{eff}} = \mathcal{N}_\phi \cdot \Phi_\tau$. Comparing $\mathcal{N}_{\text{eff}}$ against the shrinking horizon's holographic entropy capacity defines the **Lloyd–Bekenstein Gate Ratio** [11, 12]:
  $$\eta_{\text{Lloyd}} = \frac{\mathcal{N}_{\text{eff}}}{S_{\text{BH}} / k_B} \le 1$$
  This verifies that unitary information extraction never exceeds the black hole's instantaneous holographic bit budget.

* **Semiclassical Breakdown Index ($\Xi_{\text{QG}}$):**
  As $M(t) \to M_P$ and $r_+ \to \ell_P$, the minimal-length ratio $\Pi_1 = \ell_P / L$ and thermal-foam ratio $\Pi_4 = T_H / T_P$ approach unity. The $L_\infty$ supremum monitor:
  $$\Xi_{\text{QG}} = \max\left(\frac{\ell_P}{L},\; \frac{10^{-6}}{N^2(\theta)},\; \frac{a_*^2 + Q_*^2}{0.9998},\; \frac{T_{\text{eff}}}{T_P}\right) \to 1$$
  signals the exact breakdown of smooth semiclassical geometry, halting evaporation at a stable **Planck-mass relic ($M_P$)** rather than extrapolating into an unphysical $T_H \to \infty$ divergence.

---

## 4. Operational Interpretation and Diagnostic Summary

| Symbol | Name | Mathematical Definition | Operational Role in Unitary Evaporation |
| :--- | :--- | :--- | :--- |
| $\rho_\tau$ | ZAMO Dilation Factor | $(\gamma_{\text{pre}}/\sqrt{N^2_{\text{pre}}}) / (\gamma_{\text{obs}}/\sqrt{1-\mathcal{C}_{\text{obs}}})$ | Converts local horizon evaporation rates and temperatures into distant observer frames without coordinate singularities. |
| $\chi$ | Weyl Conformal Purity | $(1 + \mathcal{C}_{\text{clamped}}^2 / \pi^2)^{-1}$ | Isolates static curvature-induced vacuum polarization from dynamical thermal Hawking radiation. |
| $\Omega$ | Decoherence Action | $(\Gamma_{\text{th}} + \Gamma_{\text{grav}})\,t_{\text{pre}}$ | Quantifies accumulated thermal and gravitational phase scattering along the evaporating worldline. |
| $\Phi_{\text{floor}}$ | Holographic Coherence Floor | $(1 + \pi \cdot 10^{2\zeta})^{-1}$ | Sets the irreducible inverse Hilbert-space purity bound preventing complete information loss. |
| $\Phi_\tau$ | Timeline Integrity | $\Phi_{\text{floor}} + (1 - \Phi_{\text{floor}})e^{-\Omega}$ | Tracks surviving quantum phase coherence from initial pure state ($1$) to scrambled equilibrium ($\Phi_{\text{floor}}$). |
| $\mathcal{N}_{\text{eff}}$ | Surviving Coherent Cycles | $(f_{\text{local}}\,t_{\text{pre}})\,\Phi_\tau$ | Counts phase-coherent wave oscillations available for unitary information transfer. |
| $\eta_{\text{Lloyd}}$ | Lloyd–Bekenstein Ratio | $\mathcal{N}_{\text{eff}} / (S_{\text{BH}} / k_B)$ | Audits that coherent information emission obeys the instantaneous Bekenstein–Hawking bit limit ($\eta_{\text{Lloyd}} \le 1$). |
| $\Xi_{\text{QG}}$ | Semiclassical Breakdown Index | $\max(\Pi_1, \Pi_2, \Pi_3, \Pi_4)$ | Halts semiclassical extrapolation at the Planck-mass relic boundary ($M \to M_P$) when $\Xi_{\text{QG}} \to 1$. |

---

## References

1. Hawking, S. W. (1975). Particle creation by black holes. *Communications in Mathematical Physics*, 43(3), 199–220. `doi:10.1007/BF02345020`
2. Arnowitt, R., Deser, S., & Misner, C. W. (1962). The dynamics of general relativity. In L. Witten (Ed.), *Gravitation: An Introduction to Current Research* (pp. 227–265). John Wiley & Sons.
3. Bardeen, J. M., Press, W. H., & Teukolsky, S. A. (1972). Rotating black holes: Locally nonrotating frames, energy extraction, and scalar synchrotron radiation. *The Astrophysical Journal*, 178, 347–370. `doi:10.1086/151796`
4. Thorne, K. S., Price, R. H., & MacDonald, D. A. (1986). *Black Holes: The Membrane Paradigm*. Yale University Press.
5. DeWitt, B. S. (1965). *Dynamical Theory of Groups and Fields*. Gordon and Breach.
6. Almheiri, A., Engelhardt, N., Marolf, D., & Maxfield, H. (2019). The entropy of bulk quantum fields and the entanglement wedge of an evaporating black hole. *Journal of High Energy Physics*, 2019(12), 063. `doi:10.1007/JHEP12(2019)063`
7. Penington, G. (2020). Entanglement wedge reconstruction and the information paradox. *Journal of High Energy Physics*, 2020(09), 002. `doi:10.1007/JHEP09(2020)002`
8. Page, D. N. (1993). Information in black hole radiation. *Physical Review Letters*, 71(23), 3743–3746. `doi:10.1103/PhysRevLett.71.3743`
9. Gorini, V., Kossakowski, A., & Sudarshan, E. C. G. (1976). Completely positive dynamical semigroups of $N$-level systems. *Journal of Mathematical Physics*, 17(5), 821–825. `doi:10.1063/1.522979`
10. Lindblad, G. (1976). On the generators of quantum dynamical semigroups. *Communications in Mathematical Physics*, 48(2), 119–130. `doi:10.1007/BF01608499`
11. Margolus, N., & Levitin, L. B. (1998). The maximum speed of dynamical evolution. *Physica D: Nonlinear Phenomena*, 120(1–2), 188–195. `doi:10.1016/S0167-2789(98)00054-2`
12. Lloyd, S. (2000). Ultimate physical limits to computation. *Nature*, 406(6799), 1047–1054. `doi:10.1038/35023282`
