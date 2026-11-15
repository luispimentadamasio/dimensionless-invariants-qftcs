# AEON-Tμν User Guide: Quick-Start & Observatory Manual

**Software:** `AEON-T14.html` (Covariant Kerr–Newman QFTCS & Semiclassical Back-Reaction Observatory)  
**Author:** Luís Pimenta Damásio (Independent Researcher, Lisbon, Portugal)  
**ORCID:** [0009-0001-7606-7557](https://orcid.org)  
**Master Compendium DOI:** [10.5281/zenodo.24163322](https://doi.org)  

---

## 1. Welcome & 60-Second Quick Start

`AEON-Tμν` is an interactive computational physics observatory that couples **curved-spacetime quantum field theory (QFTCS)**, **polar Boyer–Lindquist Kerr–Newman black hole geometry**, **open-system quantum decoherence**, and **Coherence-Bounded Operational Locality** across 120 orders of magnitude—from the Planck length ($1.62 \times 10^{-35}\text{ m}$) to galaxy clusters ($10^{23}\text{ m}$).

If this is your first time opening `AEON-T14.html`, follow these four steps to see the entire observatory come alive:

1. **Pick a Physical System (Panel 4):** Scroll through **Panel 4: Object Presets** and click **Proton**, **The Sun**, or **Sagittarius A\***. Watch all 6 panels update simultaneously.
2. **Ride the Scale Elevator (Panel 1):** Drag the purple **Conformal Preset Elevator** slider in Panel 1 smoothly from `Floor 0` (Planck Black Hole) up to `Floor 24` (El Gordo Galaxy Cluster) to see how curvature, entropy, and quantum decoherence scale across the cosmos.
3. **Start the Covariant Clocks (Panel 2):** Click **▶ START STOPWATCH** in Panel 2. Compare how fast the **Lab Observer (`t_obs`)** clock ticks relative to the **Inspected (`t_pre`)** clock near massive or relativistic objects.
4. **Orbit the 3D Light Cone (Bottom Stage):** Click and drag inside the **3D Kerr–Newman Causal Stage** at the bottom left. Watch the cyan light cone pinch shut as compactness approaches an event horizon and twist azimuthally under frame-dragging.

---

## 2. Guided Mini-Experiments (Try These First)

### Experiment A: Coherence-Bounded Operational Simultaneity vs. Bell Nonlocality
* **Goal:** See how real-time phase synchronization fails over long distances while post-selected Bell correlations remain intact (Papers 9–10).
* **Steps:**
  1. Click **Quantum Vacuum Ground State (N²=1)** in Panel 4.
  2. In **Panel 2** under **Operational Simultaneity (`Δℓ`)**, slide the baseline $\Delta\ell$ to `10.00 km` (`4.000` on the log slider) and set **Tech Noise (`Γ_tech`)** to `1.00e+1 s⁻¹` (`4.00` on the slider).
  3. Watch **Simultaneity Horizon (`ℒ_sim(r)`)** drop to `~10.21 km` and **Active Sync Fidelity (`𝒮_sim`)** fall to `~0.375`—while **Post-Selected CHSH (`S_CHSH`)** remains pinned at `2.8284 [Bell Violation]`.

### Experiment B: Ergosphere vs. Horizon & Polar Latitude
* **Goal:** Separate the static limit ($-g_{tt}(\theta) = 0$) from the true event horizon ($N^2(\theta) \to 0$).
* **Steps:**
  1. Select **Sagittarius A\* (Kerr a\*=0.90)** in Panel 4.
  2. Notice in Panel 1 that at the equator ($\theta = 90.0^\circ$), `-g_tt(θ)` turns negative inside the ergosphere while the ZAMO lapse $N^2(\theta)$ remains positive.
  3. Slowly drag **Polar Latitude (`θ`)** from `90.0°` down to `0.0°` (the rotation pole). Watch the orange ergosphere silhouette in the 3D stage pinch inward until it meets the red event horizon at the poles.

### Experiment C: QED Schwinger Vacuum Screening
* **Goal:** Observe vacuum electron–positron pair production discharging an over-charged black hole.
* **Steps:**
  1. Select **Planck Black Hole Limit** or **Omega Centauri IMBH**, and ensure **`SCHWINGER: ON`** is active in Panel 1.
  2. Drag **Charge (`Q_*`)** upward. Whenever the horizon electric field $E_H$ exceeds the Schwinger critical limit ($1.323 \times 10^{18}\text{ V/m}$), the regulator automatically screens excess charge and flags `[SCREENED]`. Toggle **`SCHWINGER: OFF`** to inspect unscreened extremal Reissner–Nordström–Newman limits.

### Experiment D: Hawking Evaporation & The Unitary Page Curve
* **Goal:** Watch a black hole evaporate and trace its entanglement entropy across the Page time.
* **Steps:**
  1. Select **Planck Black Hole Limit (Floor 0)** and ensure **`AUTO-EVAP: ON`** is enabled in Panel 3.
  2. Set **Cosmological Time Scale** in Panel 2 to `1.000 s` (or `1 Julian Year` for larger masses) and click **▶ START STOPWATCH**.
  3. Watch **Dressed / Evaporating Mass (`M_eff(t)`)** in Panel 5 decrease while **Page Curve Entanglement (`Log₁₀ S_rad`)** in Panel 3 rises and then purifies back down after passing the half-area Page turnover.

---

## 3. Panel-by-Panel Reference Map

| Panel | Core Focus | Key Controls & Observables |
| :--- | :--- | :--- |
| **Panel 1** | **Kerr–Newman QFTCS & Metric** | Radius $\log_{10}(L)$, Lorentz boost $\gamma$ (center `0.50` = rest), spin $a_*$, charge $Q_*$, polar angle $\theta$, vacuum state $w_{\text{vac}}$, bare compactness $\mathcal{C}_0$, ZAMO lapse $N^2(\theta)$, and the **Conformal Preset Elevator**. |
| **Panel 2** | **ZAMO Chronological Flux & Simultaneity** | Proper-time dilation $\rho_\tau$, observer velocity $\beta_{\text{obs}}$ & compactness $\mathcal{C}_{\text{obs}}$, 77-order **Stopwatch**, and **Operational Simultaneity** ($\Delta\ell, n_{\text{eff}}, \Gamma_{\text{tech}}, \mathcal{L}_{\text{sim}}(r), \mathcal{S}_{\text{sim}}, S_{\text{CHSH}}$). |
| **Panel 3** | **Thermodynamics & Page Curve** | System entropy $\log_{10} S$, Bekenstein–Hawking bound $\log_{10} S_{\text{BH}}$, Page radiation entropy $\log_{10} S_{\text{rad}}$, ZAMO/observer temperatures ($T_{\text{eff}}, T_{\text{obs}}$), decoherence action $\Omega$, and **Timeline Integrity ($\Phi_\tau$)**. |
| **Panel 4** | **Object Presets & Data I/O** | 25 built-in physical regimes spanning particles, biology, stars, and black holes, plus **`+ Save`** custom states, **`CSV`** 29-column telemetry export, and **`JSON`** snapshot save/load. |
| **Panel 5** | **QFT Dispersion & Superradiance** | Relativistic dispersion ($E^2 - p^2 = m_0^2$), redshifted frequency $f_{\text{obs}}$, spectral shift $z$, Compton scale $\lambdabar$, ZAMO horizon compression $\mathcal{H}_{Q,\text{obs}}$, Zel'dovich superradiance ($f_{\text{local}} < f_H$), and coherent phase cycles $\mathcal{N}_{\text{eff}}$. |
| **Panel 6** | **Cross-Panel Invariants & Bounds** | Synthesizes **8 dimensionless invariants**: (1) Lloyd–Bekenstein $\eta_{\text{Lloyd}}$, (2) Tolman–Ehrenfest $\Xi_{\text{th}}$, (3) Penrose efficiency $\mathcal{E}_P$, (4) Gravity/Thermal ratio $\mathcal{R}_{\text{DP}}$, (5) MSS chaos ratio $\lambda_L/\lambda_{\text{MSS}}$, (6) **4-Cutoff Quantum-Gravity Wall ($\Xi_{\text{QG}}$)**, (7) **Spatial Locality Decay ($\mathcal{D}_{\text{loc}}$)**, and (8) **Null Visibility ($V_{\text{null}}$)**. |

---

## 4. Glossary of Key Symbols & Color Codes

### Visual Status Colors
* **Green (`#00ff87`):** Unitary evolution, point-local synchronization ($\mathcal{D}_{\text{loc}} > 0.707$), or exact QFTCS validity ($\Xi_{\text{QG}} < 0.1$).
* **Cyan (`#00d2ff`):** Nominal covariant baseline, flat Minkowski vacuum, or thermal-dominated decoherence.
* **Amber (`#ffb703`):** Relativistic dilation, ergosphere entry ($-g_{tt}(\theta) \le 0$), or approaching a semiclassical cutoff.
* **Red (`#ff3333`):** Event horizon trapping ($N^2(\theta) \to 10^{-6}$), Null Energy Condition (NEC) violation ($p_r < 0$), tachyonic spacelike sector ($\gamma < 1$), or Quantum-Gravity Wall saturation ($\Xi_{\text{QG}} \to 1$).

### Core Framework Symbols (Papers 9–13)
* **$N^2(\theta) = \Sigma \cdot \Delta / A_{\text{BL}}$:** Zero-Angular-Momentum Observer (ZAMO) lapse function; vanishes at the outer event horizon $r_+$.
* **$\rho_\tau$:** Covariant proper-time dilation factor between the inspected frame and lab observer.
* **$\mathcal{L}_{\text{sim}}(r)$:** Operational Simultaneity Horizon—maximum spatial baseline over which closed-loop phase synchronization can complete within one coherence time.
* **$\mathcal{D}_{\text{loc}} = \exp(-\Delta\ell / \mathcal{L}_{\text{sim}}(r))$:** Spatial Locality Decay Factor quantifying classical signaling-decoherence roll-off.
* **$\Xi_{\text{QG}}$:** Four-channel Semiclassical Breakdown Index monitoring proximity to the Planck length ($\ell_P/L$), stretched horizon ($10^{-6}/N^2$), extremal Kerr–Newman limit ($a_*^2 + Q_*^2$), and Planck temperature ($T_{\text{eff}}/T_P$).

---

## 5. AI Collaboration & Authorship Transparency Statement

Conceptual architecture, physical equations, operational simultaneity horizon models, and experimental protocols were originated and directed by **Luís Pimenta Damásio**. Software structuring, numerical verification, and documentation formatting support were provided by **Gemini** (Google AI) under the author's direct supervision.

Copyright © 2026 Luís Pimenta Damásio (`luipimentadamasio`). All rights reserved.