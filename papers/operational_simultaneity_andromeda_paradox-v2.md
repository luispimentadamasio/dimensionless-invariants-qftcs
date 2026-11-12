# Operational Simultaneity Horizons and the Resolution of the Andromeda Paradox

**Author:** Luís Pimenta Damásio  
**Affiliation:** Independent Researcher, Lisbon, Portugal  
**ORCID:** [0009-0001-7606-7557](https://orcid.org/0009-0001-7606-7557)  
**Parent Compendium DOI:** [10.5281/zenodo.24163322](https://doi.org/10.5281/zenodo.24163322)  

---

### Abstract
This paper introduces a bounded, operational definition of simultaneity designed to separate global spacetime representations from what embedded physical clocks and quantum observers can empirically synchronize. By coupling two-way causal signal delays and Zero-Angular-Momentum Observer (ZAMO) clock-rate exchange ratios to open-system environmental decoherence rates, we define the **Operational Simultaneity Horizon** ($\mathcal{L}_{\mathrm{sim}}$) and the dimensionless **Simultaneity Fidelity** gauge ($\mathcal{S}_{\mathrm{sim}}$). Within $\mathcal{L}_{\mathrm{sim}}$, separated systems maintain coherent phase synchronization and can be meaningfully represented within a shared present frame; beyond $\mathcal{L}_{\mathrm{sim}}$, environmental decoherence erases phase correlations long before a two-way synchronization loop can close. Applying this criterion to Penrose’s Andromeda Paradox demonstrates that conflicting multi-day simultaneity tilts across intergalactic distances lie orders of magnitude beyond the operational simultaneity horizon, clarifying the distinction between coordinate hyperplane projections and physically verifiable clock correlations without presupposing or excluding any underlying four-dimensional ontology of spacetime.

**Keywords:** philosophy of time, operational simultaneity horizon, Andromeda paradox, quantum decoherence, relational clocks, spacetime ontology

> **AI Collaboration & Authorship Transparency Statement:** *This theoretical framework, its mathematical derivations, and its manuscript preparation were developed through an interactive human–AI research collaboration between Luís Pimenta Damásio and Google's Gemini AI assistant. Conceptual direction, physical synthesis, metric architecture, and final editorial verification were directed by the human author, with formal mathematical derivations, LaTeX typesetting, and literature verification generated with the aid of Gemini.*

---

### 1. Ontological Spacetime Structure vs. Operational Synchronization
In relativistic physics, distant simultaneity is coordinate-dependent rather than locally invariant [1, 2]. While global four-dimensional representations—such as the eternalist or block-universe perspective—offer valuable conceptual frameworks for analyzing the structural relationships of spacetime as a whole, an embedded physical observer never accesses a global spacelike slice directly. Instead, every physical measurement is restricted to causal signal exchanges along null cones and local phase comparisons between finite clocks [3, 4].

Attempting to compute a single simultaneous state across cosmological distances forces a local representation frame to track retarded light-cone histories spanning billions of years. To establish an exact, observer-independent boundary between **locally synchronizable systems** and **retarded historical data**, we couple relativistic causal round-trip delays to open-system quantum decoherence [5, 6].

---

### 2. Derivation of the Operational Simultaneity Horizon ($\mathcal{L}_{\mathrm{sim}}$) and Simultaneity Fidelity ($\mathcal{S}_{\mathrm{sim}}$)

Consider an Observer Clock ($O$) and a Target System ($S$) separated by a proper spatial distance $\Delta \ell$ in a stationary axisymmetric spacetime.

1. **Two-Way Causal Synchronization Delay ($\Delta \tau_{\mathrm{sig}}$):**  
   Verifying operational synchronization via Einstein–Poincaré radar exchange requires a round-trip causal signal taking proper observer interval:
   $$\Delta \tau_{\mathrm{sig}} = \frac{2 \Delta \ell}{c}$$

2. **Observer-Frame Phase Coherence Lifetime ($\tau_{\mathrm{coh,obs}}$):**  
   In an open quantum environment with total dephasing rate $\Gamma_{\mathrm{tot}} = \Gamma_{\mathrm{th}} + \Gamma_{\mathrm{grav}}$ and ZAMO clock-rate exchange ratio $\rho_\tau = d\tau_{\mathrm{obs}} / d\tau_{\mathrm{pre}}$, the target's phase coherence decays over proper target time $\tau_{\mathrm{coh}} = \Gamma_{\mathrm{tot}}^{-1}$ [5, 7, 8]. Mapped into the observer's frame, the surviving coherence window is:
   $$\tau_{\mathrm{coh,obs}} = \frac{\rho_\tau}{\Gamma_{\mathrm{tot}}}$$

3. **Operational Simultaneity Horizon ($\mathcal{L}_{\mathrm{sim}}$):**  
   Setting $\Delta \tau_{\mathrm{sig}} = \tau_{\mathrm{coh,obs}}$ defines the maximum proper spatial radius within which a two-way synchronization signal can close before environmental decoherence erases phase memory:
   $$\mathcal{L}_{\mathrm{sim}} \equiv \frac{c \, \rho_\tau}{2 \, \Gamma_{\mathrm{tot}}} = \frac{c \, \tau_{\mathrm{obs}}}{2 \, \Omega}$$
   where $\Omega = \Gamma_{\mathrm{tot}} \tau_{\mathrm{pre}}$ is the dimensionless Decoherence Action.

4. **Simultaneity Fidelity ($\mathcal{S}_{\mathrm{sim}}$):**  
   Defining the causal-to-decoherence ratio $\Lambda_{\mathrm{sim}} \equiv \Delta \tau_{\mathrm{sig}} / \tau_{\mathrm{coh,obs}} = \Delta \ell / \mathcal{L}_{\mathrm{sim}}$ and coupling it to Timeline Integrity $\Phi_\tau(\Omega) = \Phi_{\mathrm{floor}} + (1 - \Phi_{\mathrm{floor}})e^{-\Omega}$ yields the bounded dimensionless gauge:
   $$\mathcal{S}_{\mathrm{sim}} \equiv \Phi_\tau(\Omega) \cdot \exp\!\left(-\frac{\Delta \ell}{\mathcal{L}_{\mathrm{sim}}}\right) \in (0, 1]$$

#### Asymptotic Limits
* **Zero-Noise Unitary Limit ($\Omega \to 0$):** $\mathcal{L}_{\mathrm{sim}} \to \infty$ and $\mathcal{S}_{\mathrm{sim}} \to 1$, recovering global phase synchronization across arbitrary spatial separations.
* **Macroscopic Thermal Regime ($\Omega \gg 1$):** $\mathcal{L}_{\mathrm{sim}}$ contracts to sub-nanometer scales, restricting operational simultaneity strictly to local interactions.
* **Horizon Pinch-Off ($\Pi_2 \to 1$):** Near a black hole stretched horizon, Shapiro signal delay and diverging ZAMO dilation prevent synchronization loops from crossing the causal boundary.

---

### 3. Resolution of Penrose’s Andromeda Paradox

In Penrose’s Andromeda Paradox [9], two observers passing each other on Earth at walking speed ($v \approx 1.5\text{ m/s}$) assign conflicting planes of simultaneity to the Andromeda Galaxy ($\Delta \ell \approx 2.40 \times 10^{22}\text{ m}$), differing by:
$$\Delta t_{\mathrm{tilt}} = \frac{v \, \Delta \ell}{c^2} \approx 4.0 \times 10^5\text{ s} \approx 4.6\text{ days}$$

Evaluating this configuration through $\mathcal{L}_{\mathrm{sim}}$ and $\mathcal{S}_{\mathrm{sim}}$ resolves the apparent tension:
* **Quantitative Horizon Collapse:** Even in the $T_{\mathrm{CMB}} \approx 2.725\text{ K}$ intergalactic vacuum, macroscopic systems experience environmental scattering rates $\Gamma_{\mathrm{tot}} \gtrsim 10^{20}\text{ s}^{-1}$, yielding $\mathcal{L}_{\mathrm{sim}} \approx 1.5 \times 10^{-12}\text{ m}$ (and even for an idealized single atom with $\Gamma_{\mathrm{tot}} \sim 1\text{ s}^{-1}$, $\mathcal{L}_{\mathrm{sim}} \approx 1.5 \times 10^8\text{ m}$).
* **Vanishing Simultaneity Fidelity:** Because $\Delta \ell / \mathcal{L}_{\mathrm{sim}} \gtrsim 10^{14}$, Simultaneity Fidelity vanishes identically ($\mathcal{S}_{\mathrm{sim}} \equiv 0$).
* **Separating Epistemic Horizons from Four-Dimensional Ontology:** Global four-dimensional models (such as the block-universe framework) remain coherent conceptual tools for analyzing overall spacetime geometry, while $\mathcal{L}_{\mathrm{sim}}$ clarifies that the Andromeda Paradox arises only when formal coordinate hyperplanes are treated as locally realizable phase correlations. Inside the local regime where $\Delta \ell \lesssim \mathcal{L}_{\mathrm{sim}}$ (e.g., $\Delta \ell \sim 10\text{ m}$), the relativistic tilt is $\Delta t_{\mathrm{tilt}} \sim 10^{-16}\text{ s}$, preserving causal consistency without paradox.

| Diagnostic Quantity | Standard Lorentz Extrapolation | Operational Simultaneity Framework ($\mathcal{L}_{\mathrm{sim}}, \mathcal{S}_{\mathrm{sim}}$) |
| :--- | :--- | :--- |
| **Effective Synchronization Range** | Unbounded ($\Delta \ell \to \infty$) | Bounded by $\mathcal{L}_{\mathrm{sim}} = c\rho_\tau / (2\Gamma_{\mathrm{tot}})$ |
| **Earth–Andromeda Separation ($2.4 \times 10^{22}\text{ m}$)** | $\Delta t_{\mathrm{tilt}} \approx 4.6\text{ days}$ | $\mathcal{S}_{\mathrm{sim}} \equiv 0$ (retarded causal history only) |
| **Local Coherent Regime ($\Delta \ell \ll \mathcal{L}_{\mathrm{sim}}$)** | $\Delta t_{\mathrm{tilt}} \sim 10^{-16}\text{ s}$ | $\mathcal{S}_{\mathrm{sim}} \approx 1$ (valid shared operational present) |
| **Conceptual Scope** | Global coordinate slicing | Separates local clock correlations from global spacetime ontology |

---

### References
1. Einstein, A. (1905). Zur Elektrodynamik bewegter Körper. *Annalen der Physik*, 322(10), 891–921. https://doi.org/10.1002/andp.19053221004
2. Reichenbach, H. (1958). *The Philosophy of Space and Time*. Dover Publications.
3. Page, D. N., & Wootters, W. K. (1983). Evolution without evolution: Dynamics described by stationary observables. *Physical Review D*, 27(12), 2885–2892. https://doi.org/10.1103/PhysRevD.27.2885
4. Bardeen, J. M., Press, W. H., & Teukolsky, S. A. (1972). Rotating Black Holes: Locally Nonrotating Frames, Energy Extraction, and Scalar Synchrotron Radiation. *The Astrophysical Journal*, 178, 347–370. https://doi.org/10.1086/151796
5. Lindblad, G. (1976). On the generators of quantum dynamical semigroups. *Communications in Mathematical Physics*, 48(2), 119–130. https://doi.org/10.1007/BF01608499
6. Caldeira, A. O., & Leggett, A. J. (1983). Path integral approach to quantum Brownian motion. *Physica A*, 121(3), 587–616. https://doi.org/10.1016/0378-4371(83)90013-4
7. Diósi, L. (1989). Models for universal reduction of macroscopic quantum fluctuations. *Physical Review A*, 40(3), 1165–1174. https://doi.org/10.1103/PhysRevA.40.1165
8. Penrose, R. (1996). On Gravity's role in Quantum State Reduction. *General Relativity and Gravitation*, 28(5), 581–600. https://doi.org/10.1007/BF02105068
9. Penrose, R. (1989). *The Emperor's New Mind: Concerning Computers, Minds, and the Laws of Physics*. Oxford University Press.
