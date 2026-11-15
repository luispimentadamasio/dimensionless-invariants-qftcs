# Covariant Kerr–Newman QFTCS, Open-System Decoherence, and Coherence-Bounded Operational Locality: Theoretical Architecture of the AEON-Tμν Observatory

**Author:** Luís Pimenta Damásio (Independent Researcher, Lisbon, Portugal)  
**ORCID:** [0009-0001-7606-7557](https://orcid.org)  
**Master Compendium DOI:** [10.5281/zenodo.24163322](https://doi.org)  
**Companion Software:** `AEON-T14.html` (Version 14.0.0)  
**Date:** November 15, 2026  

---

## Abstract

Computational modeling of quantum fields in curved spacetime (QFTCS) is frequently fragmented across isolated regimes: strong-field black hole thermodynamics, open-system quantum decoherence, and long-baseline relativistic metrology are rarely evaluated within a single coupled numerical state. **`AEON-Tμν` (`AEON-T14.html`)** bridges this divide by integrating polar Boyer–Lindquist Kerr–Newman metric geometry, Hadamard-renormalized stress-energy ($\langle T_{\mu\nu} \rangle_{\text{ren}}$), QED Schwinger vacuum screening, Hawking–Page black hole evaporation, and **Coherence-Bounded Operational Locality** across 120 orders of spatial magnitude ($1.62 \times 10^{-35}\text{ m}$ to $1.00 \times 10^{23}\text{ m}$). This companion paper documents the physical foundations, exact mathematical definitions, and causal dependency hierarchy of the observatory's core metrics, demonstrating how gravitational redshift, thermodynamic decoherence, and finite-speed signaling jointly bound real-time quantum synchronization while preserving fundamental relativistic and holographic consistency limits.

---

## 1. Introduction: Purpose and Physical Scope

Modern foundational physics faces a persistent conceptual gap between **asymptotic relativistic field theory**—which assumes idealized, infinitely precise rods, clocks, and point-local observers—and **realistic open quantum systems**, whose phase coherence degrades continuously through thermal scattering, gravitational self-energy, and technical noise.

The **`AEON-Tμν`** observatory is designed to demonstrate four central physical theses within a unified, real-time numerical laboratory:

1. **Metric–Stress-Energy Coupling Across Scale:** Gravitational compactness, polar frame-dragging, and renormalized vacuum polarization evolve continuously from the Planck regime through elementary particles, condensed matter, stars, and ultramassive Kerr–Newman black holes.
2. **Separation of Static Limits from Causal Horizons:** Polar Boyer–Lindquist evaluation explicitly resolves the geometric distinction between the oblate ergosphere boundary ($-g_{tt}(\theta) = 0$) and the latitude-independent event horizon where the Zero-Angular-Momentum Observer (ZAMO) lapse vanishes ($N^2(\theta) \to 0$).
3. **Operational Simultaneity vs. Nonlocal Correlations:** Real-time closed-loop phase synchronization across a spatial baseline $\Delta\ell$ is strictly bounded by an **Operational Simultaneity Horizon** ($\mathcal{L}_{\text{sim}}(r)$), whereas post-selected Bell-CHSH correlations ($S_{\text{CHSH}}$) depend solely on local temporal coherence ($\Phi_\tau(\Omega)$) and remain distance-invariant.
4. **Explicit Semiclassical Breakdown Monitoring:** Rather than allowing numerical approximations to diverge silently near Planckian or extremal limits, a four-channel **Quantum-Gravity Wall** ($\Xi_{\text{QG}}$) tracks proximity to ultraviolet length, stretched-horizon, extremal censorship, and Hagedorn temperature cutoffs.
## 2. The Four-Tier Causal Architecture

To maintain strict physical self-consistency across six coupled panels, `AEON-Tμν` evaluates all state variables in a deterministic four-tier dependency hierarchy:

* **Tier 1 — Spacetime Bedrock:** Polar Boyer–Lindquist Kerr–Newman metric potentials ($N^2(\theta)$, $-g_{tt}(\theta)$, $\omega_{\text{FD}}$) and radiation-coupled effective compactness ($\mathcal{C}_{\text{eff}}$).
* **Tier 2 — Quantum & Relativistic Bridges:** Covariant proper-time dilation ($\rho_\tau$), Hadamard-renormalized stress-energy ($\langle T_{\mu\nu} \rangle_{\text{ren}}$), and Lindblad/Penrose–Diósi timeline integrity ($\Phi_\tau(\Omega)$).
* **Tier 3 — Operational Locality Observables:** Round-trip signaling latency ($\Delta\tau_{\text{sig}}$), the Operational Simultaneity Horizon ($\mathcal{L}_{\text{sim}}(r)$), Spatial Locality Decay ($\mathcal{D}_{\text{loc}}$), Active Sync Fidelity ($\mathcal{S}_{\text{sim}}$), and Null Visibility ($V_{\text{null}}$).
* **Tier 4 — Cross-Panel Invariants & Breakdown Bounds:** Dimensionless consistency checks (Lloyd–Bekenstein, Tolman–Ehrenfest, Penrose–Zel'dovich, Penrose–Diósi ratio, and Maldacena–Shenker–Stanford chaos saturation) capped by the four-cutoff Quantum-Gravity Wall ($\Xi_{\text{QG}}$).

---

## 3. Tier 1: The Spacetime Bedrock

### 3.1 Effective Compactness and Semiclassical Back-Reaction ($\mathcal{C}_{\text{eff}}$)
For a physical system of characteristic radius $L \ge \ell_P$ and bare rest mass $M_0$, dimensionless bare gravitational compactness is defined as:

$$\mathcal{C}_0 = \frac{2 G M_0}{c^2 L} = \frac{2 \ell_P^2 M_0}{\hbar c L}$$

In semiclassical gravity ($G_{\mu\nu} = 8\pi G \langle T_{\mu\nu} \rangle_{\text{ren}}$), thermal radiation ($\rho_{\text{th}}$) and renormalized quantum vacuum energy ($\rho_{\text{vac}}$) carry gravitating mass-energy $M_{\text{rad}} = \frac{4}{3}\pi L^3 (\rho_{\text{th}} + \rho_{\text{vac}})$. When self-consistent back-reaction is active, the effective gravitating compactness becomes:

$$\mathcal{C}_{\text{eff}} = \min\!\left(2.0,\; \mathcal{C}_0 + \frac{2 \ell_P^2 M_{\text{rad}}}{\hbar c L}\right)$$

This coupling demonstrates **Kugelblitz radiation collapse**: a sub-horizon configuration ($\mathcal{C}_0 < \mathcal{C}_{\text{hor}}$) subjected to extreme thermal entropy or vacuum polarization crosses the horizon formation threshold solely through the gravitational weight of its radiation field.

### 3.2 Polar Boyer–Lindquist Metric and ZAMO Lapse ($N^2(\theta)$)
For dimensionless Kerr spin $a_* \in [0, 0.9998]$ and dimensionless electric charge $Q_* \in [0, 0.9998]$ constrained by the sub-extremal cosmic censorship bound $a_*^2 + Q_*^2 \le 0.9998$, the horizon compactness threshold is:

$$\mathcal{C}_{\text{hor}}(a_*, Q_*) = \frac{2}{1 + \sqrt{1 - a_*^2 - Q_*^2}}$$

Defining the normalized compactness ratio $u = \min(1, \mathcal{C}_{\text{eff}} / \mathcal{C}_{\text{hor}})$, $\tilde{a} = a_* / \mathcal{C}_{\text{hor}}$, and $\tilde{Q} = Q_* / \mathcal{C}_{\text{hor}}$ at polar latitude $\theta \in [0^\circ, 90^\circ]$, the dimensionless Boyer–Lindquist metric functions are:

$$\Delta_{\text{norm}} = 1 - 2u + (\tilde{a}^2 + \tilde{Q}^2)u^2, \qquad \Sigma_{\text{norm}} = 1 + \tilde{a}^2 \cos^2\theta\, u^2$$

$$A_{\text{BL,norm}} = (1 + \tilde{a}^2 u^2)^2 - \Delta_{\text{norm}} \tilde{a}^2 \sin^2\theta\, u^2$$

From these potentials, the observatory extracts two distinct causal indicators:

1. **ZAMO Lapse Function ($N^2(\theta)$):**
   $$N^2(\theta) = \max\!\left(10^{-6},\; \frac{\Sigma_{\text{norm}} \cdot \Delta_{\text{norm}}}{A_{\text{BL,norm}}}\right)$$
   Representing the squared lapse of a Zero-Angular-Momentum Observer co-rotating with frame-dragging angular velocity $\omega_{\text{FD}}$, $N^2(\theta)$ equals $1$ in flat Minkowski spacetime and approaches the stretched-horizon membrane floor ($10^{-6}$) uniformly across all latitudes as $u \to 1$.

2. **Static Limit Potential ($-g_{tt}(\theta)$):**
   $$-g_{tt}(\theta) = \frac{\Delta_{\text{norm}} - \tilde{a}^2 \sin^2\theta\, u^2}{\Sigma_{\text{norm}}}$$
   Unlike $N^2(\theta)$, $-g_{tt}(\theta)$ vanishes outside the horizon at the polar ergosphere boundary $r_E(\theta)$. Varying $\theta$ from the equatorial plane ($90^\circ$) to the rotation pole ($0^\circ$) demonstrates how the ergosphere swells at the equator—enabling rotational energy extraction—and pinches tangent to the outer event horizon $r_+$ at the poles.

### 3.3 QED Schwinger Vacuum Pair Screening ($E_H$)
When a compact object carries dimensionless charge $Q_* > 0$, its horizon electric field strength scales as:

$$E_H = \frac{Q_* \, c^4}{4\pi\varepsilon_0 G M_{\text{eff}} (1 + \chi_{\text{ext}})^2} \, u^2, \qquad \chi_{\text{ext}} = \sqrt{1 - a_*^2 - Q_*^2}$$

Whenever $E_H$ exceeds the Schwinger critical field $E_{\text{crit}} = \frac{m_e^2 c^3}{e\hbar} \approx 1.323 \times 10^{18}\text{ V/m}$, spontaneous electron–positron pair creation discharges the horizon, clamping $Q_*$ to the maximum stable electrostatic ceiling.
## 4. Tier 2: Quantum and Relativistic Bridges

### 4.1 Covariant Proper-Time Dilation ($\rho_\tau$)
Comparing an inspected system with Lorentz factor $\gamma_{\text{pre}}$ and ZAMO lapse $N^2(\theta)$ against a reference observer moving at velocity $\beta_{\text{obs}}$ within gravitational compactness $\mathcal{C}_{\text{obs}}$ ($-g_{00,\text{obs}} = \max(10^{-6}, 1 - \mathcal{C}_{\text{obs}})$), the covariant proper-time dilation ratio is:

$$\rho_\tau = \frac{dt_{\text{lab}}}{d\tau_{\text{pre}}} = \frac{\gamma_{\text{pre}} / \sqrt{N^2(\theta)}}{\gamma_{\text{obs}} / \sqrt{-g_{00,\text{obs}}}}$$

$\rho_\tau$ governs both macroscopic clock drift ($t_{\text{pre}} = t_{\text{obs}} / \rho_\tau$) and the spectral redshift $z = \rho_\tau - 1$ of matter-wave frequencies ($f_{\text{obs}} = f_{\text{local}} / \rho_\tau$).

### 4.2 Hadamard-Renormalized Stress-Energy ($\langle T_{\mu\nu} \rangle_{\text{ren}}$) and Weyl Anomaly ($\mathcal{A}_W$)
Subtracting flat-space zero-point divergences yields the finite stress-energy components:

$$\rho_{\text{tot}} = \rho_{\text{matter}} + \rho_{\text{th}} + \rho_{\text{vac}}$$

$$p_r = \frac{1}{3}\rho_{\text{th}} - \rho_{\text{vac}}\!\left(1 - \frac{w_{\text{vac}}}{2}\right), \qquad p_\perp = \frac{1}{3}\rho_{\text{th}} + \rho_{\text{vac}}\!\left(\frac{1}{2} + \frac{w_{\text{vac}}}{4}\kappa_{\text{KN}}\right)$$

where $w_{\text{vac}} \in [0, 2]$ \in$ interpolates continuously across **Boulware** ($w_{\text{vac}} \approx 0$), **Unruh** ($w_{\text{vac}} \approx 1$), and **Hartle–Hawking** ($w_{\text{vac}} \approx 2$) vacuum states. In vacuum-dominated curved regimes where $p_r < 0$ and $\rho_{\text{tot}} + p_r < 0$, the observatory flags a **Null Energy Condition (NEC) violation**, illustrating the negative radial vacuum tension required to sustain black hole evaporation. Conformal scale-invariance breaking is simultaneously tracked via the dimensionless Weyl trace anomaly $\mathcal{A}_W = \mathcal{C}_{\text{clamped}}^2 / (60\pi^2)$.

### 4.3 Open-System Decoherence and Timeline Integrity ($\Phi_\tau(\Omega)$)
Quantum phase coherence degrades through three independent physical channels:

1. **Caldeira–Leggett Thermal Scattering ($\Gamma_{\text{th}}$):**
   $$\Gamma_{\text{th}} = \frac{L^2 (k_B T_{\text{eff}})^3}{(\hbar c)^2 \hbar} \quad (S > 0)$$
2. **Penrose–Diósi Gravitational Self-Energy Collapse ($\Gamma_{\text{grav}}$):**
   $$\Gamma_{\text{grav}} = \left(\frac{M_{\text{eff}}}{M_P}\right)^2 \frac{c}{L} \cdot \mathcal{F}_{\text{DP}}, \qquad \mathcal{F}_{\text{DP}} = \begin{cases} 1, & \text{horizon} \\ \min(1, \mathcal{C}_{\text{eff}}/\mathcal{C}_{\text{hor}}), & \text{bound matter} \end{cases}$$
   Incorporating the compactness form factor $\mathcal{F}_{\text{DP}}$ prevents unphysical whole-body superposition artifacts in rigid condensed matter while preserving exact collapse scaling at horizons and in mesoscopic nanoparticle interferometry.
3. **Engineering / Environmental Phase Noise ($\Gamma_{\text{tech}}$):** User-adjustable optical or oscillator phase diffusion rate.

Over elapsed proper time $t_{\text{pre}}$, the cumulative dimensionless decoherence action $\Omega = (\Gamma_{\text{th}} + \Gamma_{\text{grav}} + \Gamma_{\text{tech}}) \, t_{\text{pre}}$ drives **Timeline Integrity**:

$$\Phi_\tau(\Omega) = \Phi_{\text{floor}} + (1 - \Phi_{\text{floor}}) e^{-\Omega}, \qquad \Phi_{\text{floor}} = \frac{1}{1 + \pi (L / \ell_P)^2}$$

$\Phi_\tau$ quantifies the surviving unitary phase fraction, reducing total unscattered phase oscillations $\mathcal{N}_\varphi = f_{\text{local}} t_{\text{pre}}$ to net coherent phase cycles $\mathcal{N}_{\text{eff}} = \mathcal{N}_\varphi \cdot \Phi_\tau$.

### 4.4 Hawking Evaporation and the Unitary Page Curve
For black hole configurations ($\mathcal{C}_{\text{eff}} \ge \mathcal{C}_{\text{hor}}$) evolving over cosmological timescales, mass loss obeys the Stefan–Boltzmann–Page luminosity law:

$$M(t) = \max\!\left(M_P,\; \left(M_0^3 - 3\alpha_H \left(\frac{2\chi_{\text{ext}}}{1 + \chi_{\text{ext}}}\right)^2 t_{\text{pre}}\right)^{1/3}\right), \qquad \alpha_H = \frac{\hbar c^4}{15360\pi G^2} \approx 3.8904 \times 10^{53}\text{ GeV}^3/\text{s}$$

Comparing the instantaneous Bekenstein–Hawking horizon entropy $S_{\text{BH}}(t) = k_B A_H(t) / (4\ell_P^2)$ against initial entropy $S_{\text{BH}}(0)$ yields the unitary Page radiation entanglement entropy $S_{\text{rad}}(t) = \min(S_{\text{BH}}(0) - S_{\text{BH}}(t),\, S_{\text{BH}}(t))$, capturing the Page turnover and eventual purification toward a Planck-mass relic.

---

## 5. Tier 3: Coherence-Bounded Operational Locality

A central demonstration of `AEON-Tμν` is the operational distinction between **active closed-loop synchronization** and **post-selected quantum entanglement** across a spatial baseline $\Delta\ell$.

### 5.1 Operational Simultaneity Horizon ($\mathcal{L}_{\text{sim}}(r)$)
Establishing Einstein–Poincaré clock synchronization across a link of refractive index $n_{\text{eff}}$ requires a round-trip signaling interval $\Delta\tau_{\text{sig}} = \frac{2\Delta\ell}{c \, n_{\text{eff}}}$. Because local clock phase coherence decays at rate $\Gamma_{\text{tot}}$ and suffers gravitational/kinematic time dilation $\sqrt{N^2(\theta)} / \gamma_{\text{pre}}$, real-time phase locking is bounded by a finite **Operational Simultaneity Horizon**:

$$\mathcal{L}_{\text{sim}}(r) = \frac{c \, n_{\text{eff}} \, \left(\sqrt{N^2(\theta)} / \gamma_{\text{pre}}\right)}{2 \, \Gamma_{\text{tot}}}$$

### 5.2 Spatial Locality Decay ($\mathcal{D}_{\text{loc}}$), Active Sync Fidelity ($\mathcal{S}_{\text{sim}}$), and Bell Correlations ($S_{\text{CHSH}}$)
Evaluating a spatial baseline $\Delta\ell$ relative to $\mathcal{L}_{\text{sim}}(r)$ yields three coupled observables:

1. **Spatial Locality Decay Factor:**
   $$\mathcal{D}_{\text{loc}} = \exp\!\left(-\frac{\Delta\ell}{\mathcal{L}_{\text{sim}}(r)}\right), \qquad \mathcal{F}_{\text{QRF}} = \frac{1}{2}\left(1 + \mathcal{D}_{\text{loc}}\right)$$
   where $\mathcal{F}_{\text{QRF}}$ measures the fidelity of spatial Quantum Reference Frame transformations across $\Delta\ell$.
2. **Active Synchronization Fidelity:**
   $$\mathcal{S}_{\text{sim}}(\Omega, \Delta\ell) = \Phi_\tau(\Omega) \cdot \mathcal{D}_{\text{loc}}$$
3. **Post-Selected CHSH Bell Parameter:**
   $$S_{\text{CHSH}}(\Omega) = 2\sqrt{2} \cdot \Phi_\tau(\Omega)$$

**Physical Demonstration:** When $\Delta\ell \gg \mathcal{L}_{\text{sim}}(r)$ (or near a stretched horizon where $N^2(\theta) \to 10^{-6}$ causes $\mathcal{L}_{\text{sim}}(r) \to 0$), $\mathcal{D}_{\text{loc}}$ and $\mathcal{S}_{\text{sim}}$ collapse to zero, proving that real-time operational simultaneity dissolves. Simultaneously, $S_{\text{CHSH}}$ remains independent of $\Delta\ell$ (violating the classical Bell bound $S_{\text{CHSH}} > 2$ whenever $\Phi_\tau > 1/\sqrt{2}$), demonstrating that nonlocal quantum correlations persist without enabling superluminal signaling.

### 5.3 Baseline Null Visibility ($V_{\text{null}}$)
In long-baseline quantum interferometers, $V_{\text{null}}(\Omega, \Delta\ell) = \Phi_\tau(\Omega)\cdot\mathcal{D}_{\text{loc}}$ establishes the exact fringe-contrast roll-off predicted by environmental decoherence and finite-speed signaling lag alone—providing a quantitative null-hypothesis benchmark for tabletop quantum-gravity tests.
## 6. Tier 4: Cross-Panel Invariants and the Quantum-Gravity Wall

Panel 6 synthesizes outputs across Panels 1–5 to verify fundamental physical bounds:

1. **Lloyd–Bekenstein Gate Bound ($\eta_{\text{Lloyd}}$):**
   $$\eta_{\text{Lloyd}} = \frac{\mathcal{N}_{\text{eff}}}{S_{\text{BH}} / k_B}$$
   Verifies that net coherent quantum operations never exceed the holographic information capacity of the bounding surface.
2. **Tolman–Ehrenfest Thermal Occupancy Invariant ($\Xi_{\text{thermal}}$):**
   $$\Xi_{\text{thermal}} = \frac{k_B T_{\text{obs}}}{h f_{\text{obs}}} \equiv \frac{k_B T_{\text{eff}}}{h f_{\text{local}}}$$
   Demonstrates exact frame invariance of Bose–Einstein thermal photon occupancy under arbitrary gravitational and kinematic redshift $\rho_\tau$.
3. **Penrose–Zel'dovich Extraction Efficiency ($\mathcal{E}_P$):**
   $$\mathcal{E}_P = \max\!\left(0,\; 1 - \frac{f_{\text{local}}}{f_H}\right) \sin^2\theta \cdot \eta_{\text{NT}}(r_{\text{ISCO}})$$
   Quantifies rotational energy harvesting in the superradiant regime ($f_{\text{local}} < f_H$, $f_H = \frac{c a_*}{4\pi r_+}$) weighted by equatorial frame-dragging ($\sin^2\theta$) and Novikov–Thorne ISCO binding efficiency.
4. **Penrose–Diósi Gravity/Thermal Ratio ($\mathcal{R}_{\text{DP}}$):**
   $$\mathcal{R}_{\text{DP}} = \frac{\Gamma_{\text{grav}}}{\Gamma_{\text{th}}}$$
   Maps the crossover between thermally dominated decoherence ($\mathcal{R}_{\text{DP}} < 1$) and curvature-induced collapse ($\mathcal{R}_{\text{DP}} > 1$).
5. **Maldacena–Shenker–Stanford (MSS) Chaos Ratio ($\lambda_L / \lambda_{\text{MSS}}$):**
   $$\frac{\lambda_L}{\lambda_{\text{MSS}}} = \frac{\Gamma_{\text{th}} + \Gamma_{\text{grav}}}{2\pi k_B T_{\text{eff}} / \hbar}$$
   Evaluates intrinsic quantum scrambling relative to the universal thermal chaos ceiling, saturating at $1.0000$ on black hole horizons.
6. **Four-Channel Quantum-Gravity Wall ($\Xi_{\text{QG}}$):**
   $$\Xi_{\text{QG}} = \max\!\left(\frac{\ell_P}{L},\; \frac{10^{-6}}{N^2(\theta)},\; \frac{a_*^2 + Q_*^2}{0.9998},\; \frac{T_{\text{eff}}}{T_P}\right)$$
   Monitors proximity to the four breakdown limits of semiclassical gravity: ultraviolet vacuum divergence ($\ell_P/L$), infinite horizon redshift ($10^{-6}/N^2$), naked singularity formation ($a_*^2 + Q_*^2 \to 1$), and Planckian spacetime foam ($T_{\text{eff}} \to T_P$). When $\Xi_{\text{QG}} < 0.1$, smooth semiclassical QFTCS holds reliably; as $\Xi_{\text{QG}} \to 1$, explicit regulators prevent unphysical mathematical singularities.

---

## 7. Summary of Benchmark Regimes

Across its 25 built-in presets and continuous Conformal Preset Elevator, `AEON-T14.html` spans four canonical physical regimes:

| Regime | Representative States | Characteristic Behavior in `AEON-Tμν` |
| :--- | :--- | :--- |
| **Unitary Quantum Vacuum & Particles** | Vacuum Ground State, Electron, Proton, Higgs, CMB Photon | $N^2(\theta) \approx 1$, $\Phi_\tau = 1.0000$, $\mathcal{L}_{\text{sim}} \to \infty$, $\Xi_{\text{QG}} \ll 0.1$; pure unitary phase evolution and maximal Bell violation ($S_{\text{CHSH}} = 2.8284$). |
| **Mesoscopic Quantum–Classical Frontier** | C₆₀ Fullerene, Cryogenic Nanoparticles, Virus Capsid | $\mathcal{R}_{\text{DP}} \sim 1$; direct competition between Penrose–Diósi gravitational collapse and thermal scattering. |
| **Classical Macroscopic & Stellar Bodies** | Human Being, Earth, The Sun, R136a1, El Gordo Cluster | $\Phi_\tau \to \Phi_{\text{floor}}$, $\mathcal{C}_{\text{eff}} \in [10^{-17}, 10^{-3}]$; deterministic proper-time clock drift ($\rho_\tau > 1$) alongside finite operational simultaneity horizons. |
| **Strong-Field Kerr–Newman Horizons** | Planck Black Hole, Omega Centauri IMBH, Sagittarius A\*, TON 618 | $N^2(\theta) \to 10^{-6}$, $-g_{tt}(\theta) \le 0$ in the ergosphere, superradiant amplification, Hawking–Page evaporation ($\log_{10} S_{\text{rad}}$), MSS chaos saturation, and horizon dissolution ($\mathcal{D}_{\text{loc}} \to 0$). |

---

## AI Collaboration & Authorship Transparency Statement

Conceptual architecture, physical models, operational simultaneity horizon equations, and theoretical synthesis were originated and directed by **Luís Pimenta Damásio**. Numerical verification, software structuring, and manuscript formatting support were provided by **Gemini** (Google AI) under the author's direct supervision.

Copyright © 2026 Luís Pimenta Damásio (`luipimentadamasio`). All rights reserved.