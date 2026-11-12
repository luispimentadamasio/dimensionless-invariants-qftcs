# Geometric Purity and Multi-Scale Diagnostic Ratios

**Author:** Luís Pimenta Damásio  
**Affiliation:** Independent Researcher, Lisbon, Portugal  
**ORCID:** [0009-0001-7606-7557](https://orcid.org/0009-0001-7606-7557)  

## Abstract
To analyze physical systems spanning over one hundred orders of magnitude without losing structural clarity in raw dimensional units, we construct four dimensionless diagnostic invariants: **Weyl Conformal Purity** ($\chi$), the **Gravity-to-Thermal Decoherence Crossover Ratio** ($\mathcal{R}_{\text{DP}}$), **Penrose–Zel'dovich Rotational Extraction Gain** ($\mathcal{E}_{\text{Penrose}}$), and the **Semiclassical Breakdown Index** ($\Xi_{\text{QG}}$). Derived from the Seeley–DeWitt $a_4$ trace anomaly, Buckingham-$\Pi$ dimensional analysis, Novikov–Thorne binding energies, and the $L_\infty$ Chebyshev supremum norm, these metrics separate geometric vacuum polarization from environmental noise while establishing strict epistemic boundaries for semiclassical gravity.

**Keywords:** Weyl trace anomaly, Penrose–Diósi collapse, Buckingham-$\Pi$ theorem, Novikov–Thorne efficiency, Semiclassical breakdown, Dimensionless invariants

---

> **AI Collaboration & Transparency Statement:** *This theoretical framework, its mathematical derivations, and its manuscript preparation were developed through an interactive human–AI research collaboration between Luís Pimenta Damásio and Google's Gemini AI assistant. Conceptual direction, physical synthesis, metric architecture, and final editorial verification were directed by the human author, with formal mathematical derivations, LaTeX typesetting, and literature verification generated with the aid of Gemini.*

---

## 1. First-Principles Mathematical Derivations

### 1.1 Weyl Conformal Purity ($\chi$) via Seeley–DeWitt Trace Anomaly
In classical massless field theory, the stress-energy tensor is traceless ($T^\mu_{\;\mu} = 0$) due to invariance under local Weyl rescalings ($g_{\mu\nu} \to \Omega^2(x) g_{\mu\nu}$). In curved spacetime, quantum vacuum fluctuations break this symmetry, generating the **Weyl Conformal Trace Anomaly** ($\langle \hat{T}^\mu_{\;\mu} \rangle_{\text{ren}}$) governed by the one-loop Seeley–DeWitt $a_4$ heat-kernel coefficient:

$$\mathcal{A}_W \equiv \frac{\langle \hat{T}^\mu_{\;\mu} \rangle_{\text{ren}}}{\rho_{\text{vac,ref}}} = \frac{\mathcal{C}_{\text{clamped}}^2}{60\pi^2}$$

where $\mathcal{C}_{\text{clamped}} = \min(\mathcal{C}_{\text{hor}}, \mathcal{C}_{\text{eff}})$ bounds the dimensionless compactness at the Kerr–Newman horizon $\mathcal{C}_{\text{hor}} = 2 / (1 + \sqrt{1 - a_*^2 - Q_*^2})$. Normalizing $\mathcal{A}_W \ge 0$ by the characteristic one-loop phase-space factor ($60$) yields the bounded **Weyl Conformal Purity**:

$$\chi \equiv \frac{1}{1 + 60\,\mathcal{A}_W} = \frac{1}{1 + \mathcal{C}_{\text{clamped}}^2 / \pi^2} \in (0, 1]$$

* **Minkowski Limit ($\mathcal{C}_{\text{clamped}} = 0$):** $\mathcal{A}_W = 0 \implies \chi = 1.0000$.
* **Schwarzschild Horizon ($\mathcal{C}_{\text{clamped}} = 1$):** $\chi = \pi^2 / (\pi^2 + 1) \approx 0.9080$.
* **Extremal Kerr–Newman Horizon ($\mathcal{C}_{\text{clamped}} \to 2$):** $\chi = \pi^2 / (\pi^2 + 4) \approx 0.7116$.

### 1.2 Gravity-to-Thermal Crossover Ratio ($\mathcal{R}_{\text{DP}}$) via Buckingham-$\Pi$ Scaling
Comparing the Penrose–Diósi gravitational self-energy collapse rate $\Gamma_{\text{grav}} = (M_{\text{eff}} / M_P)^2 (c / L)$ against the Caldeira–Leggett thermal photon scattering rate $\Gamma_{\text{th}} = L^2 (k_B T_{\text{eff}})^3 / (\hbar^3 c^2)$ eliminates time units completely, forming a dimensionless Buckingham-$\Pi$ group:

$$\mathcal{R}_{\text{DP}} \equiv \frac{\Gamma_{\text{grav}}}{\Gamma_{\text{th}}} = \left(\frac{M_{\text{eff}}}{M_P}\right)^2 \frac{\hbar^2 c^3}{L^3 (k_B T_{\text{eff}})^3} = \left(\frac{M_{\text{eff}}}{M_P}\right)^2 \left(\frac{\text{\itshape\textcrlambda}_{\text{th}}}{L}\right)^3$$

where $\text{\itshape\textcrlambda}_{\text{th}} = \hbar c / (k_B T_{\text{eff}})$ is the reduced thermal wavelength. The critical crossover $\mathcal{R}_{\text{DP}} = 1$ occurs along the mesoscopic mass-temperature boundary $M_{\text{eff}} / M_P = (L / \text{\itshape\textcrlambda}_{\text{th}})^{3/2}$.

### 1.3 Penrose–Zel'dovich Rotational Extraction Gain ($\mathcal{E}_{\text{Penrose}}$)
To quantify rotational energy extraction from a spinning Kerr–Newman ergosphere at polar angle $\theta$, we combine three dimensionless physical factors:
1. **Zel'dovich–Starobinsky Superradiant Wave Gain:** $\mathcal{G}_{\text{SR}} = \max(0, 1 - f_{\text{local}} / f_H)$, where $f_H = c a_* / (4\pi r_+)$ is the horizon angular frequency.
2. **Polar Ergosphere Coupling:** $\sin^2\theta$, reflecting the vanishing of ergosphere thickness along the rotation axis ($\theta = 0^\circ$) and peak frame-dragging at the equator ($\theta = 90^\circ$).
3. **Novikov–Thorne Radiative Binding Efficiency:** $\eta_{\text{NT}}(r_{\text{ISCO}}) = 1 - \sqrt{1 - 2r_g / (3 r_{\text{ISCO}})}$, ranging from $5.72\%$ (Schwarzschild) to $42.26\%$ (extremal Kerr).

Taking their product defines the **Penrose–Zel'dovich Extraction Gain**:

$$\mathcal{E}_{\text{Penrose}}(\theta) \equiv \max\left(0,\; 1 - \frac{f_{\text{local}}}{f_H}\right) \cdot \sin^2\theta \cdot \eta_{\text{NT}}(r_{\text{ISCO}})$$

### 1.4 Semiclassical Breakdown Index ($\Xi_{\text{QG}}$) via $L_\infty$ Supremum Norm
Semiclassical Einstein gravity ($G_{\mu\nu} = \frac{8\pi G}{c^4} \langle \hat{T}_{\mu\nu} \rangle_{\text{ren}}$) holds only while four independent dimensionless ratios remain strictly below unity:
* **Minimal Planck Length Cutoff:** $\Pi_1 = \ell_P / L$
* **Stretched-Horizon Membrane Cutoff:** $\Pi_2 = 10^{-6} / N^2(\theta)$
* **Sub-Extremal Cosmic Censorship Cutoff:** $\Pi_3 = (a_*^2 + Q_*^2) / 0.9998$
* **Planck Thermal Foam Ceiling:** $\Pi_4 = T_{\text{eff}} / T_P$

Taking the $L_\infty$ (Chebyshev) supremum norm defines the **Semiclassical Breakdown Index**:

$$\Xi_{\text{QG}} \equiv \big\|(\Pi_1, \Pi_2, \Pi_3, \Pi_4)\big\|_\infty = \max\left(\frac{\ell_P}{L},\; \frac{10^{-6}}{N^2(\theta)},\; \frac{a_*^2 + Q_*^2}{0.9998},\; \frac{T_{\text{eff}}}{T_P}\right)$$

---

## 2. Plain-Language Physical & Operational Guide

* **Weyl Conformal Purity ($\chi$):** Measures how severely spacetime curvature warps the quantum vacuum even at absolute zero and zero elapsed time. It equals $1.0000$ in flat space and drops toward $0.908$ at a Schwarzschild horizon or $0.712$ at an extremal Kerr–Newman horizon.
* **Gravity-to-Thermal Crossover ($\mathcal{R}_{\text{DP}}$):** Acts as a dimensionless tug-of-war gauge between environmental thermal decoherence ($\mathcal{R}_{\text{DP}} < 1$) and Penrose–Diósi gravitational self-energy collapse ($\mathcal{R}_{\text{DP}} > 1$), with $\mathcal{R}_{\text{DP}} = 1$ marking the exact quantum-to-classical mesoscopic threshold.
* **Penrose–Zel'dovich Extraction Gain ($\mathcal{E}_{\text{Penrose}}$):** Expresses the net fractional energy extractable from a rotating ergosphere at latitude $\theta$, vanishing identically along the spin axis ($\theta = 0^\circ$) and above the superradiant frequency cutoff ($f_{\text{local}} \ge f_H$).
* **Semiclassical Breakdown Index ($\Xi_{\text{QG}}$):** Serves as a continuous epistemic boundary monitor. Because it uses the supremum ($\max$) norm, $\Xi_{\text{QG}} \to 1.0000$ the instant *any single* semiclassical assumption reaches its physical breakdown wall.

---

## Acknowledgments
The author gratefully acknowledges Google's Gemini AI assistant for collaborative support in symbolic derivation checks, dimensional consistency auditing, LaTeX typesetting, and literature verification.

## References
1. **DeWitt, B. S.** (1965). *Dynamical Theory of Groups and Fields*. Gordon and Breach.
2. **Novikov, I. D., & Thorne, K. S.** (1973). Astrophysics of Black Holes. In *Black Holes (Les Astres Occlus)*, eds. C. DeWitt & B. S. DeWitt, Gordon and Breach, pp. 343–450.
3. **Zel'dovich, Ya. B.** (1971). Generation of Waves by a Rotating Body. *JETP Letters*, 14, 180–181.
4. **Diósi, L.** (1989). Models for universal reduction of macroscopic quantum fluctuations. *Physical Review A*, 40(3), 1165–1174. DOI: `10.1103/PhysRevA.40.1165`
5. **Penrose, R.** (1996). On Gravity's Role in Quantum State Reduction. *General Relativity and Gravitation*, 28(5), 581–600. DOI: `10.1007/BF02105068`
6. **Thorne, K. S., Price, R. H., & MacDonald, D. A.** (1986). *Black Holes: The Membrane Paradigm*. Yale University Press.
