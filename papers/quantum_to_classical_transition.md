# The Quantum-to-Classical Transition: Environmental Decoherence and Gravitationally Induced Collapse

**Author:** Luís Pimenta Damásio  
**Affiliation:** Independent Researcher, Lisbon, Portugal  
**ORCID:** [0009-0001-7606-7557](https://orcid.org/0009-0001-7606-7557)  

**Abstract:**  
We formalize the emergence of classical macroscopic definiteness from unitary quantum superpositions by synthesizing open-system environmental decoherence with gravitationally induced objective collapse. Using the Gorini–Kossakowski–Sudarshan–Lindblad (GKSL) master equation and Caldeira–Leggett thermal photon scattering alongside the Penrose–Diósi gravitational self-energy functional and stochastic Schrödinger dynamics, we establish a unified dimensionless diagnostic framework. Specifically, we introduce the Decoherence Action ($\Omega$), Timeline Integrity ($\Phi_\tau$), the Holographic Coherence Floor ($\Phi_{\text{floor}}$), Surviving Coherent Cycles ($\mathcal{N}_{\text{eff}}$), and the Buckingham-$\Pi$ Gravity-to-Thermal Crossover Ratio ($\mathcal{R}_{\text{DP}}$) to map mesoscopic quantum-to-classical boundaries across relativistic worldlines.

**Keywords:** Quantum-to-Classical Transition, Environmental Decoherence, GKSL Master Equation, Caldeira–Leggett Scattering, Penrose–Diósi Collapse, Holographic Coherence Floor

> **AI Collaboration & Transparency Statement:** *This theoretical framework, its mathematical derivations, and its manuscript preparation were developed through an interactive human–AI research collaboration between Luís Pimenta Damásio and Google's Gemini AI assistant. Conceptual direction, physical synthesis, metric architecture, and final editorial verification were directed by the human author, with formal mathematical derivations, LaTeX typesetting, and literature verification generated with the aid of Gemini.*

---

## 1. Open-System Quantum Evolution and Environmental Decoherence ($\Gamma_{\text{th}}$)

In closed quantum mechanics, a pure state $|\psi\rangle$ evolves unitarily under the Schrödinger equation, preserving phase coherence indefinitely. To model how a quantum system of characteristic radius $L$ and effective mass $M_{\text{eff}}$ loses phase coherence when coupled to an ambient thermal bath at local temperature $T_{\text{eff}}$, we trace out the environmental degrees of freedom ($\rho_S = \operatorname{Tr}_E[\rho_{\text{tot}}]$).

### 1.1 Gorini–Kossakowski–Sudarshan–Lindblad (GKSL) Master Equation
Under the Born–Markov approximation, the reduced density matrix $\rho_S$ evolves along the system's proper worldline ($\tau_{\text{pre}}$) according to:
$$\frac{d\rho_S}{d\tau_{\text{pre}}} = -\frac{i}{\hbar}[H_S, \rho_S] + \sum_k \gamma_k \left( L_k \rho_S L_k^\dagger - \frac{1}{2}\{L_k^\dagger L_k, \rho_S\} \right)$$
where $L_k$ denote Lindblad jump operators representing momentum-transfer collisions with ambient thermal quanta and $\gamma_k \ge 0$ are non-negative dissipation rates.

### 1.2 Feynman–Vernon Influence Functional and Caldeira–Leggett Scattering
In the position representation $\rho_S(\mathbf{x}, \mathbf{x}', \tau_{\text{pre}}) = \langle \mathbf{x} | \rho_S | \mathbf{x}' \rangle$, integrating out a bath of blackbody photons or harmonic oscillators produces an exponential off-diagonal damping kernel:
$$\frac{\partial \rho_S(\mathbf{x}, \mathbf{x}', \tau_{\text{pre}})}{\partial \tau_{\text{pre}}} = -\frac{i}{\hbar}\langle \mathbf{x} | [H_S, \rho_S] | \mathbf{x}' \rangle - \Lambda(\Delta x)\,\rho_S(\mathbf{x}, \mathbf{x}', \tau_{\text{pre}})$$
For a spatial superposition separated by $\Delta x \sim L$ immersed in a thermal radiation bath with reduced thermal wavelength $\lambda_{\text{th}} = \hbar c / (k_B T_{\text{eff}})$, dimensional photon-scattering scaling yields the **Caldeira–Leggett thermal decoherence rate**:
$$\Gamma_{\text{th}} = \frac{L^2 (k_B T_{\text{eff}})^3}{(\hbar c)^2 \hbar} = \frac{c\, L^2}{\lambda_{\text{th}}^3}$$

---

## 2. Gravitationally Induced Objective Collapse ($\Gamma_{\text{grav}}$)

Even at absolute zero ($T_{\text{eff}} = 0\text{ K}$) in an ideal vacuum, the **Penrose–Diósi hypothesis** proposes that placing a massive object into a spatial superposition of two distinct mass distributions $\rho_1(\mathbf{x})$ and $\rho_2(\mathbf{x})$ generates an irreducible spacetime curvature tension.

### 2.1 Regularized Gravitational Self-Energy Functional
The gravitational interaction energy difference $\Delta E_{\text{grav}}$ between two superposed mass configurations is governed by the Newtonian Green's function of the Laplacian:
$$\Delta E_{\text{grav}} = -G \iint \frac{\big[\rho_1(\mathbf{x}) - \rho_2(\mathbf{x})\big]\big[\rho_1(\mathbf{y}) - \rho_2(\mathbf{y})\big]}{|\mathbf{x} - \mathbf{y}|}\, d^3x\, d^3y$$
For a localized mass $M_{\text{eff}}$ displaced across its characteristic radius $L$, this self-energy difference scales as:
$$\Delta E_{\text{grav}} \sim \frac{G M_{\text{eff}}^2}{L} = \left(\frac{M_{\text{eff}}}{M_P}\right)^2 \frac{\hbar c}{L}$$
where $M_P = \sqrt{\hbar c / G}$ is the Planck mass.

### 2.2 Stochastic Schrödinger Evolution and Collapse Rate
Introducing continuous non-linear stochastic localization driven by Wiener noise $dW_t$—preserving the Born rule via Girsanov's theorem without superluminal signaling—yields a pure-state collapse timescale $\tau_{\text{DP}} = \hbar / \Delta E_{\text{grav}}$, defining the **Penrose–Diósi gravitational dephasing rate**:
$$\Gamma_{\text{grav}} = \frac{\Delta E_{\text{grav}}}{\hbar} = \left(\frac{M_{\text{eff}}}{M_P}\right)^2 \frac{c}{L}$$

---

## 3. Dimensionless Diagnostic Synthesis

To evaluate phase survival and regime dominance across relativistic worldlines without coordinate ambiguity, we synthesize the competing decoherence rates into dimensionless invariants.

### 3.1 Decoherence Action ($\Omega$) and ZAMO Dilation Factor ($\rho_\tau$)
Converting distant observer stopwatch time $t_{\text{obs}}$ into proper worldline time $t_{\text{pre}} = t_{\text{obs}} / \rho_\tau$ via the **ZAMO Dilation Factor ($\rho_\tau$)**, the accumulated environmental and gravitational phase-scattering depth is defined by the **Decoherence Action**:
$$\Omega = \int_0^{t_{\text{pre}}} (\Gamma_{\text{th}} + \Gamma_{\text{grav}})\,d\tau = (\Gamma_{\text{th}} + \Gamma_{\text{grav}})\,\frac{t_{\text{obs}}}{\rho_\tau}$$

### 3.2 Timeline Integrity ($\Phi_\tau$) and Holographic Coherence Floor ($\Phi_{\text{floor}}$)
Off-diagonal density-matrix coherence decays exponentially with $\Omega$, bounded from below by the inverse Bekenstein–Hawking Hilbert-space dimension $\Phi_{\text{floor}} = (1 + \pi \cdot 10^{2\zeta})^{-1}$ (where $\zeta = \log_{10}(L / \ell_P)$):
$$\Phi_\tau(\Omega) = \Phi_{\text{floor}} + (1 - \Phi_{\text{floor}})\,e^{-\Omega}$$
* **Unitary Quantum Regime ($\Omega \ll 1$):** $\Phi_\tau \approx 1.0000$, preserving coherent interference.
* **Classical Thermalized Equilibrium ($\Omega \gg 1$):** $\Phi_\tau \to \Phi_{\text{floor}} > 0$, enforcing strict quantum unitarity down to the Planck scale ($\Phi_{\text{floor}} = (1 + \pi)^{-1} \approx 0.2414$ at $L = \ell_P$) while reproducing classical decoherence ($\Phi_{\text{floor}} \sim 10^{-70}$) at macroscopic scales ($L = 1\text{ m}$).

### 3.3 Gravity-to-Thermal Crossover Ratio ($\mathcal{R}_{\text{DP}}$)
Constructing the dimensionless Buckingham-$\Pi$ ratio between gravitational self-energy collapse and thermal scattering cancels time units completely:
$$\mathcal{R}_{\text{DP}} \equiv \frac{\Gamma_{\text{grav}}}{\Gamma_{\text{th}}} = \left(\frac{M_{\text{eff}}}{M_P}\right)^2 \left(\frac{\lambda_{\text{th}}}{L}\right)^3$$
* **Thermal Dominance ($\mathcal{R}_{\text{DP}} < 1$):** Environmental heat destroys phase coherence prior to gravitational self-energy collapse.
* **Exact Mesoscopic Crossover ($\mathcal{R}_{\text{DP}} = 1$):** Occurs at $M_{\text{eff}} / M_P = (L / \lambda_{\text{th}})^{3/2}$, isolating the critical mass-temperature boundary targeted by cryogenic levitated-nanoparticle experiments.
* **Curvature Dominance ($\mathcal{R}_{\text{DP}} > 1$):** Gravitational self-energy enforces classical spatial localization even in ultracold vacuum traps.

### 3.4 Surviving Coherent Cycles ($\mathcal{N}_{\text{eff}}$) and Semiclassical Guard ($\Xi_{\text{QG}}$)
Weighting total proper wave oscillations $\mathcal{N}_\phi = f_{\text{local}}\,t_{\text{pre}}$ by $\Phi_\tau$ yields $\mathcal{N}_{\text{eff}} = \mathcal{N}_\phi \cdot \Phi_\tau$, quantifying the exact number of usable interference cycles prior to classicalization. Simultaneously, the $L_\infty$ semiclassical monitor $\Xi_{\text{QG}}$ tracks $\ell_P / L$ and $T_{\text{eff}} / T_P$ to ensure localization scales and bath temperatures remain strictly within semiclassical bounds.

---

## Acknowledgments
The human author gratefully acknowledges Google's Gemini AI assistant for collaborative mathematical formulation, dimensional verification, and LaTeX typesetting support.

## References
1. Gorini, V., Kossakowski, A., & Sudarshan, E. C. G. (1976). Completely positive dynamical semigroups of $N$-level systems. *Journal of Mathematical Physics*, 17(5), 821–825. https://doi.org/10.1063/1.522979
2. Lindblad, G. (1976). On the generators of quantum dynamical semigroups. *Communications in Mathematical Physics*, 48(2), 119–130. https://doi.org/10.1007/BF01608499
3. Caldeira, A. O., & Leggett, A. J. (1983). Path integral approach to quantum Brownian motion. *Physica A: Statistical Mechanics and its Applications*, 121(3), 587–616. https://doi.org/10.1016/0378-4371(83)90013-4
4. Joos, E., & Zeh, H. D. (1985). The emergence of classical properties through interaction with the environment. *Zeitschrift für Physik B Condensed Matter*, 59(2), 223–243. https://doi.org/10.1007/BF01725541
5. Diósi, L. (1989). Models for universal reduction of macroscopic quantum fluctuations. *Physical Review A*, 40(3), 1165–1174. https://doi.org/10.1103/PhysRevA.40.1165
6. Penrose, R. (1996). On gravity's role in quantum state reduction. *General Relativity and Gravitation*, 28(5), 581–600. https://doi.org/10.1007/BF02105068
7. Zurek, W. H. (2003). Decoherence, einselection, and the quantum origins of the classical. *Reviews of Modern Physics*, 75(3), 715–775. https://doi.org/10.1103/RevModPhys.75.715
8. Margolus, N., & Levitin, L. B. (1998). The maximum speed of dynamical evolution. *Physica D: Nonlinear Phenomena*, 120(1–2), 188–195. https://doi.org/10.1016/S0167-2789(98)00054-2
9. Lloyd, S. (2000). Ultimate physical limits to computation. *Nature*, 406(6799), 1047–1054. https://doi.org/10.1038/35023282
