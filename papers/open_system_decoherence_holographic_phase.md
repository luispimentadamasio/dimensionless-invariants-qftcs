# Open-System Decoherence and Holographic Phase Dynamics

**Author:** Luís Pimenta Damásio  
**Affiliation:** Independent Researcher, Lisbon, Portugal  
**ORCID:** [0009-0001-7606-7557](https://orcid.org/0009-0001-7606-7557)  

**Keywords:** Open Quantum Systems, GKSL Master Equation, Caldeira–Leggett Decoherence, Penrose–Diósi Collapse, Holographic Entropy Bound, Margolus–Levitin Speed Limit

> **AI Collaboration & Transparency Statement:** *This theoretical framework, its mathematical derivations, and its manuscript preparation were developed through an interactive human–AI research collaboration between Luís Pimenta Damásio and Google's Gemini AI assistant. Conceptual direction, physical synthesis, metric architecture, and final editorial verification were directed by the human author, with formal mathematical derivations, LaTeX typesetting, and literature verification generated with the aid of Gemini.*

---

## Abstract

We derive a dimensionless, holographically bounded parameterization of open-system quantum decoherence along curved spacetime worldlines. Combining the Gorini–Kossakowski–Sudarshan–Lindblad (GKSL) master equation with Caldeira–Leggett thermal photon scattering and Penrose–Diósi gravitational self-energy dephasing, we construct the cumulative **Decoherence Action** ($\Omega$). To prevent unphysical vanishing of quantum state purity near causal horizons, we impose the Bekenstein–Hawking holographic Hilbert-space dimensionality bound to establish an irreducible **Holographic Coherence Floor** ($\Phi_{\text{floor}}$) and define **Timeline Integrity** ($\Phi_\tau$). Finally, coupling $\Phi_\tau$ to the Margolus–Levitin orthogonalization rate yields the count of **Surviving Coherent Cycles** ($\mathcal{N}_{\text{eff}}$) and the dimensionless **Lloyd–Bekenstein Gate Ratio** ($\eta_{\text{Lloyd}}$).

---

## 1. First-Principles Mathematical Derivations

### 1.1 Open Quantum Evolution and Decoherence Action ($\Omega$)

Consider a quantum system of characteristic radius $L$ and effective mass $M_{\text{eff}}$ interacting with an ambient thermal and gravitational environment along its proper worldline ($\tau_{\text{pre}}$). Under the Born–Markov approximation, the reduced density matrix $\rho_S(\tau_{\text{pre}}) = \operatorname{Tr}_E[\rho_{\text{tot}}]$ evolves according to the **Gorini–Kossakowski–Sudarshan–Lindblad (GKSL)** master equation:

$$\frac{d\rho_S}{d\tau_{\text{pre}}} = -\frac{i}{\hbar}[H_S, \rho_S] + \sum_k \Gamma_k \left( L_k \rho_S L_k^\dagger - \frac{1}{2}\{L_k^\dagger L_k, \rho_S\} \right)$$

For a spatial or energy superposition between two orthogonal states $|1\rangle$ and $|2\rangle$, off-diagonal coherence decays exponentially with the integrated environmental scattering rate:

$$|\rho_{12}(\tau_{\text{pre}})| = |\rho_{12}(0)| \cdot \exp\left(-\int_0^{t_{\text{pre}}} \Gamma_{\text{tot}}(\tau)\,d\tau\right)$$

The total dephasing rate $\Gamma_{\text{tot}} = \Gamma_{\text{th}} + \Gamma_{\text{grav}}$ comprises two competing physical channels:

1. **Caldeira–Leggett Thermal Scattering ($\Gamma_{\text{th}}$):** Scattering of blackbody quanta at local effective temperature $T_{\text{eff}}$ (with reduced thermal wavelength $\text{\itshape\textcrlambda}_{\text{th}} = \hbar c / (k_B T_{\text{eff}})$) across cross-sectional area $A \sim L^2$ yields:
   $$\Gamma_{\text{th}} = \frac{L^2 (k_B T_{\text{eff}})^3}{(\hbar c)^2 \hbar} = \frac{c\,L^2}{\text{\itshape\textcrlambda}_{\text{th}}^3}$$

2. **Penrose–Diósi Gravitational Self-Energy Rate ($\Gamma_{\text{grav}}$):** A mass distribution $M_{\text{eff}}$ displaced across scale $L$ carries gravitational self-energy uncertainty $\Delta E_{\text{grav}} \sim G M_{\text{eff}}^2 / L = (M_{\text{eff}}/M_P)^2 (\hbar c / L)$, giving the gravitational dephasing rate:
   $$\Gamma_{\text{grav}} = \frac{\Delta E_{\text{grav}}}{\hbar} = \left(\frac{M_{\text{eff}}}{M_P}\right)^2 \frac{c}{L}$$

Integrating $\Gamma_{\text{tot}}$ over elapsed proper time $t_{\text{pre}} = t_{\text{obs}} / \rho_\tau$ defines the dimensionless **Decoherence Action ($\Omega$)**:

$$\Omega \equiv \int_0^{t_{\text{pre}}} (\Gamma_{\text{th}} + \Gamma_{\text{grav}})\,d\tau = (\Gamma_{\text{th}} + \Gamma_{\text{grav}})\,t_{\text{pre}}$$

### 1.2 Holographic Hilbert-Space Dimension and Residual Coherence Floor ($\Phi_{\text{floor}}$)

In naive infinite-dimensional quantum mechanics, $\lim_{\Omega \to \infty} e^{-\Omega} = 0$, implying complete erasure of quantum state purity. However, within a causal spherical boundary of radius $L$, the **Bekenstein–Hawking holographic entropy bound** ($S_{\max} / k_B = A / 4\ell_P^2$) restricts the physical Hilbert space to a finite effective dimension $N_{\text{dof}}$.

Let $\zeta = \log_{10}(L / \ell_P)$ denote the logarithmic radius in Planck units ($L / \ell_P = 10^\zeta$). The bounding surface area in Planck units is $A / \ell_P^2 = 4\pi (L / \ell_P)^2 = 4\pi \cdot 10^{2\zeta}$, yielding the effective number of orthogonal boundary microstates:

$$N_{\text{dof}} = 1 + \frac{A}{4\ell_P^2} = 1 + \pi \cdot 10^{2\zeta}$$

When an initially pure quantum state ($\operatorname{Tr}(\rho_S^2) = 1$) completely thermalizes into a maximally mixed state over $N_{\text{dof}}$ accessible microstates ($\rho_{\text{mix}} = \hat{I} / N_{\text{dof}}$), its purity reaches the irreducible inverse-dimension **Holographic Coherence Floor ($\Phi_{\text{floor}}$)**:

$$\Phi_{\text{floor}} \equiv \operatorname{Tr}(\rho_{\text{mix}}^2) = \frac{1}{N_{\text{dof}}} = \frac{1}{1 + \pi \cdot 10^{2\zeta}}$$

At the Planck scale ($L = \ell_P, \zeta = 0$), $\Phi_{\text{floor}} = (1 + \pi)^{-1} \approx 0.2414$; at macroscopic laboratory scales ($L = 1\text{ m}, \zeta \approx 34.79$), $\Phi_{\text{floor}} \sim 10^{-70}$, smoothly recovering classicality while strictly preserving unitarity.

### 1.3 Timeline Integrity ($\Phi_\tau$)

Interpolating smoothly between initial pure coherence ($\Phi_\tau(0) = 1$) and maximally mixed holographic equilibrium ($\Phi_\tau(\infty) = \Phi_{\text{floor}}$) under GKSL exponential damping defines **Timeline Integrity ($\Phi_\tau$)**:

$$\Phi_\tau(\Omega) = \Phi_{\text{floor}} + (1 - \Phi_{\text{floor}})\,e^{-\Omega}$$

This function satisfies $\Phi_\tau(0) = 1$, $\lim_{\Omega \to \infty} \Phi_\tau(\Omega) = \Phi_{\text{floor}} > 0$, and strict monotonicity $d\Phi_\tau / d\Omega = -(1 - \Phi_{\text{floor}})e^{-\Omega} \le 0$ for all $L \ge \ell_P$.

### 1.4 Surviving Coherent Cycles ($\mathcal{N}_{\text{eff}}$) and Lloyd–Bekenstein Gate Ratio ($\eta_{\text{Lloyd}}$)

By the **Margolus–Levitin quantum speed limit**, a quantum system with local energy $E = h f_{\text{local}}$ requires a minimum orthogonalization interval $\Delta\tau_\perp = h / (4E) = (4 f_{\text{local}})^{-1}$, accumulating $\mathcal{N}_\phi = f_{\text{local}}\,t_{\text{pre}}$ unscattered phase cycles over proper duration $t_{\text{pre}}$. Weighting raw cycles by $\Phi_\tau$ yields the **Surviving Coherent Cycles ($\mathcal{N}_{\text{eff}}$)**:

$$\mathcal{N}_{\text{eff}} \equiv \mathcal{N}_\phi \cdot \Phi_\tau = (f_{\text{local}}\,t_{\text{pre}}) \cdot \big[\Phi_{\text{floor}} + (1 - \Phi_{\text{floor}})e^{-\Omega}\big]$$

Comparing $\mathcal{N}_{\text{eff}}$ against the system's maximum holographic information capacity ($S_{\text{BH}} / k_B = A / 4\ell_P^2$) defines the dimensionless **Lloyd–Bekenstein Gate Ratio ($\eta_{\text{Lloyd}}$)**:

$$\eta_{\text{Lloyd}} \equiv \frac{\mathcal{N}_{\text{eff}}}{S_{\text{BH}} / k_B}$$

---

## 2. Plain-Language Physical and Operational Interpretation

* **Decoherence Action ($\Omega$):** Acts as a dimensionless environmental scattering counter. When $\Omega \ll 1$, the quantum wavepacket evolves without significant environmental disturbance; once $\Omega > 1$, phase-randomizing collisions accumulate rapidly, driving the transition toward classical behavior.
* **Holographic Coherence Floor ($\Phi_{\text{floor}}$):** Ensures that quantum information never drops to absolute zero purity. Even inside a thermalized black hole horizon, $\Phi_{\text{floor}}$ preserves the exact minimum microstate correlation ($1 / N_{\text{dof}}$) required by unitary holographic physics.
* **Timeline Integrity ($\Phi_\tau$):** Measures the surviving fraction of a system's initial quantum superposition. It starts at $1.0000$ ($100\%$ pure coherence) and decays exponentially toward $\Phi_{\text{floor}}$ as $\Omega$ increases.
* **Surviving Coherent Cycles ($\mathcal{N}_{\text{eff}}$):** Counts how many usable, phase-coherent quantum oscillations occur before environmental noise washes out interference. Once $\Phi_\tau$ saturates at $\Phi_{\text{floor}}$, coherent cycle growth halts.
* **Lloyd–Bekenstein Gate Ratio ($\eta_{\text{Lloyd}}$):** Benchmarks coherent dynamical evolution against holographic bit capacity. Values $\eta_{\text{Lloyd}} \le 1$ confirm adherence to black hole information bounds, whereas $\eta_{\text{Lloyd}} > 1$ identifies delocalized elementary particles in flat space operating far outside their Schwarzschild radius.

---

## References

1. Gorini, V., Kossakowski, A., & Sudarshan, E. C. G. (1976). Completely positive dynamical semigroups of N-level systems. *Journal of Mathematical Physics*, 17(5), 821–825. https://doi.org/10.1063/1.522979
2. Lindblad, G. (1976). On the generators of quantum dynamical semigroups. *Communications in Mathematical Physics*, 48(2), 119–130. https://doi.org/10.1007/BF01608499
3. Caldeira, A. O., & Leggett, A. J. (1983). Path integral approach to quantum Brownian motion. *Physica A: Statistical Mechanics and its Applications*, 121(3), 587–616. https://doi.org/10.1016/0378-4371(83)90013-4
4. Diósi, L. (1989). Models for universal reduction of macroscopic quantum fluctuations. *Physical Review A*, 40(3), 1165–1174. https://doi.org/10.1103/PhysRevA.40.1165
5. Penrose, R. (1996). On gravity's role in quantum state reduction. *General Relativity and Gravitation*, 28(5), 581–600. https://doi.org/10.1007/BF02105068
6. Margolus, N., & Levitin, L. B. (1998). The maximum speed of dynamical evolution. *Physica D: Nonlinear Phenomena*, 120(1–2), 188–195. https://doi.org/10.1016/S0167-2789(98)00054-2
7. Lloyd, S. (2000). Ultimate physical limits to computation. *Nature*, 406(6799), 1047–1054. https://doi.org/10.1038/35023282
8. Bekenstein, J. D. (1973). Black holes and entropy. *Physical Review D*, 7(8), 2333–2346. https://doi.org/10.1103/PhysRevD.7.2333
