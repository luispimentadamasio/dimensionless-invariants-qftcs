# Thermodynamic Dissolution of Operational Simultaneity Across Gravitational Horizons and Galactic Timing Arrays

**Author:** Luís Pimenta Damásio  
**Affiliation:** Independent Researcher, Lisbon, Portugal  
**ORCID:** [0009-0001-7606-7557](https://orcid.org/0009-0001-7606-7557)  
**Series:** Temporal Coherence & Operational Relativistic Metrology (Paper 13 — Part II Capstone)  
**Master Compendium DOI:** [10.5281/zenodo.24163322](https://doi.org/10.5281/zenodo.24163322)  

---

## Abstract

Debates surrounding the Black Hole Information Paradox and Horizon Complementarity frequently treat the gravitational event horizon ($r = r_s$) as an abrupt geometric boundary across which classical and quantum descriptions of physics experience a sharp operational discontinuity. Concurrently, in galactic-scale metrology, Pulsar Timing Arrays (PTAs) routinely construct a cosmological "now" across kiloparsec baselines by correlating millisecond pulsar arrival times. In this paper—the capstone of Part II of the *Temporal Coherence & Operational Relativistic Metrology* series—we generalize the Operational Simultaneity Horizon ($\mathcal{L}_{\text{sim}}$) and the Spatial Locality Decay Factor ($\mathcal{D}_{\text{loc}}$) to curved Lorentzian spacetimes. We derive the **Redshift-Modulated Operational Simultaneity Horizon** $\mathcal{L}_{\text{sim}}(r)$ in a static spherically symmetric Schwarzschild background and prove that extreme gravitational redshift drives both the local coordinate signal speed and $\mathcal{L}_{\text{sim}}(r)$ smoothly toward zero well outside the classical event horizon ($r > r_s$). Consequently, operational simultaneity dissolves continuously as a thermodynamic boundary phenomenon before any geometric singularity or horizon crossing occurs, neutralizing naive cross-horizon complementarity paradoxes within a neutral four-dimensionalist ontology. Finally, we apply the far-field cosmological limit ($\Delta\ell \gg \mathcal{L}_{\text{sim}}$) to Galactic Pulsar Timing Arrays, demonstrating that astrophysical synchronization on kiloparsec scales is structurally confined to the post-selected classical correlation regime ($\mathcal{D}_{\text{loc}} \to 0$).

---

## 1. Introduction: Curved Spacetime and the Limits of Operational "Now"

In flat Minkowski spacetime, the **Coherence-Bounded Operational Locality** framework (established in Papers 9 and 10) demonstrates that real-time simultaneous phase synchronization between two spatially separated observers is strictly bounded by the Operational Simultaneity Horizon $\mathcal{L}_{\text{sim}} = (c N_{\text{eff}} \rho_\tau) / (2 \Gamma_{\text{tot}})$. While passive statistical correlations—such as post-selected Bell-CHSH coincidence records $S_{\text{CHSH}}(\Omega) = 2\sqrt{2}\Phi_\tau(\Omega)$—persist across arbitrary spacelike separations within a four-dimensionalist Block Universe, active operational agency decays exponentially according to the Spatial Locality Decay Factor $\mathcal{D}_{\text{loc}} = \exp(-\Delta\ell / \mathcal{L}_{\text{sim}})$.

When transitioning from flat Minkowski laboratories to strong gravitational fields and cosmological baselines, two extreme regimes test the foundational structure of relativistic time:
1. **Strong-Field Gravitational Horizons:** Near a compact massive object of Schwarzschild radius $r_s = 2GM/c^2$, gravitational time dilation stretches round-trip Einstein-Poincaré electromagnetic synchronization intervals ($\Delta\tau_{\text{sig}}$) toward divergence. Standard discussions of Black Hole Complementarity often frame the horizon $r = r_s$ as a sudden, paradoxical boundary separating infalling and asymptotic observers.
2. **Kiloparsec Astrophysical Networks:** At the opposite extreme of weak gravity but vast spatial separation, Pulsar Timing Arrays (PTAs) such as NANOGrav, EPTA, and PPTA monitor ensembles of millisecond pulsars separated by $\Delta\ell \sim 1\text{ to }10\text{ kpc}$ ($\sim 3 \times 10^{19}\text{ m}$) to detect nanohertz gravitational waves.

In this paper, we unify both regimes under curved-spacetime Coherence-Bounded Operational Locality. We show that gravitational horizons and galactic timing arrays represent two complementary limits in which $\mathcal{D}_{\text{loc}} \to 0$, proving that operational simultaneity is a strictly local, thermodynamically bounded construct rather than a global geometric foliation of spacetime.

---

## 2. Theoretical Framework: Redshift-Modulated Simultaneity Horizons

Consider a static, spherically symmetric Schwarzschild spacetime described in standard curvature coordinates $(t, r, \theta, \phi)$ by the line element:

$$ds^2 = -f(r) c^2 dt^2 + f(r)^{-1} dr^2 + r^2 \left(d\theta^2 + \sin^2\theta\, d\phi^2\right), \qquad f(r) = 1 - \frac{r_s}{r}$$

where $r_s = 2GM/c^2$ is the Schwarzschild radius and $r > r_s$.

### 2.1 Curved-Spacetime Round-Trip Signal Delay

Let Observer $A$ be stationed at a radial coordinate $r_A > r_s$ and Observer $B$ be stationed deeper in the gravitational well at $r_B = r_A - \Delta r$ (with $r_s < r_B < r_A$). For a radial null geodesic ($ds^2 = 0$, $d\theta = d\phi = 0$), the coordinate time interval $dt$ required for an electromagnetic synchronization pulse to propagate between $r_B$ and $r_A$ is:

$$\Delta t_{\text{one-way}} = \frac{1}{c} \int_{r_B}^{r_A} \frac{dr}{1 - r_s/r} = \frac{1}{c} \left[ (r_A - r_B) + r_s \ln\left(\frac{r_A - r_s}{r_B - r_s}\right) \right]$$

In a refractive waveguide or plasma medium of effective group index $N_{\text{eff}}$, the two-way Einstein-Poincaré round-trip proper signal delay $\Delta\tau_{\text{sig}}(r_A, r_B)$ measured by Observer $A$'s local proper clock ($d\tau_A = \sqrt{f(r_A)}\, dt$) is:

$$\Delta\tau_{\text{sig}}(r_A, r_B) = \frac{2 N_{\text{eff}} \sqrt{f(r_A)}}{c} \left[ (r_A - r_B) + r_s \ln\left(\frac{r_A - r_s}{r_B - r_s}\right) \right]$$

For a local radial proper baseline $\Delta\ell_{\text{prop}} = \int_{r_B}^{r_A} f(r)^{-1/2}\, dr \ll r_A - r_s$, expanding to first order yields the local redshift-scaled round-trip signal delay:

$$\Delta\tau_{\text{sig}}(r) \approx \frac{2 N_{\text{eff}} \Delta\ell_{\text{prop}}}{c \sqrt{1 - r_s/r}}$$

### 2.2 The Redshift-Modulated Operational Simultaneity Horizon $\mathcal{L}_{\text{sim}}(r)$

During the round-trip synchronization exchange $\Delta\tau_{\text{sig}}(r)$, local optical or atomic oscillators experience total phase decoherence at proper rate $\Gamma_{\text{tot}}$ (including thermal, technical, and local Unruh-Hawking environmental fluctuations). Setting $\Delta\tau_{\text{sig}}(r)$ equal to the coherence window $\tau_{\text{coh}} = \rho_\tau / \Gamma_{\text{tot}}$ defines the **Redshift-Modulated Operational Simultaneity Horizon** $\mathcal{L}_{\text{sim}}(r)$:

$$\mathcal{L}_{\text{sim}}(r) = \mathcal{L}_{\text{sim},\infty} \sqrt{1 - \frac{r_s}{r}} = \frac{c N_{\text{eff}} \rho_\tau}{2 \Gamma_{\text{tot}}} \sqrt{1 - \frac{r_s}{r}}$$

where $\mathcal{L}_{\text{sim},\infty} = (c N_{\text{eff}} \rho_\tau) / (2 \Gamma_{\text{tot}})$ is the asymptotic flat-spacetime horizon at $r \to \infty$.

### 2.3 Curved-Spacetime Spatial Locality Decay Factor

Over a finite radial proper separation $\Delta\ell_{\text{prop}}$ between $r_B$ and $r_A$, the generalized **Curved-Spacetime Spatial Locality Decay Factor** is governed by the integrated optical-decoherence depth:

$$\mathcal{D}_{\text{loc}}(r_A, r_B) = \exp\left( - \frac{\Delta\tau_{\text{sig}}(r_A, r_B)}{\tau_{\text{coh}}} \right) = \exp\left( - \frac{\Gamma_{\text{tot}} \Delta\tau_{\text{sig}}(r_A, r_B)}{\rho_\tau} \right)$$

In the local differential limit ($\Delta\ell_{\text{prop}} \ll r - r_s$), this reduces directly to:

$$\mathcal{D}_{\text{loc}}(r, \Delta\ell_{\text{prop}}) = \exp\left( - \frac{\Delta\ell_{\text{prop}}}{\mathcal{L}_{\text{sim}}(r)} \right) = \exp\left( - \frac{2 \Gamma_{\text{tot}} \Delta\ell_{\text{prop}}}{c N_{\text{eff}} \rho_\tau \sqrt{1 - r_s/r}} \right)$$

---

## 3. Thermodynamic Dissolution of Operational Simultaneity Across Horizons

The behavior of $\mathcal{L}_{\text{sim}}(r)$ and $\mathcal{D}_{\text{loc}}(r_A, r_B)$ as $r_B \to r_s^+$ reveals a fundamental physical principle governing black hole horizons.

### 3.1 Smooth Pre-Horizon Dissolution

Because $\lim_{r \to r_s^+} \sqrt{1 - r_s/r} = 0$ and the logarithmic Shapiro-like delay $\ln[(r_A - r_s)/(r_B - r_s)] \to +\infty$ as $r_B \to r_s^+$, we obtain two exact limits for any finite decoherence rate $\Gamma_{\text{tot}} > 0$:

$$\lim_{r \to r_s^+} \mathcal{L}_{\text{sim}}(r) = 0, \qquad \lim_{r_B \to r_s^+} \mathcal{D}_{\text{loc}}(r_A, r_B) = 0$$

Unlike the geometric event horizon $r = r_s$—which is a global teleological surface defined by the causal future of null infinity—the collapse of operational simultaneity is **continuous, local, and thermodynamic**. Specifically, for any non-zero physical separation $\Delta\ell_{\text{prop}} > 0$, the condition $\mathcal{D}_{\text{loc}} < e^{-1}$ (breakdown of operational phase locking) occurs at a critical radial coordinate $r_{\text{diss}} > r_s$ strictly outside the event horizon:

$$r_{\text{diss}} = \frac{r_s}{1 - \left(\Delta\ell_{\text{prop}} / \mathcal{L}_{\text{sim},\infty}\right)^2} > r_s$$

### 3.2 Resolution of Naive Horizon Complementarity Paradoxes

Standard formulations of Black Hole Complementarity and firewall arguments frequently assume that a distant observer $A$ and an infalling observer $B$ can meaningfully compare simultaneous quantum states across $r = r_s$, generating apparent violations of quantum no-cloning or monogamy of entanglement.

Under **Coherence-Bounded Operational Locality**, no such operational comparison exists:
* **Continuous Operational Decoupling:** As Observer $B$ approaches $r_{\text{diss}} > r_s$, $\mathcal{D}_{\text{loc}} \to 0$ smoothly erases the shared real-time simultaneity frame between $A$ and $B$.
* **Preservation of Four-Dimensionalist Consistency:** Within a neutral four-dimensionalist Block Universe ontology, the spacetime manifold and its global quantum state remain completely smooth across $r = r_s$ (consistent with the equivalence principle). What vanishes at $r_{\text{diss}}$ is not spacetime geometry or unitarity, but the *operational capacity* of two finite-decoherence observers to synchronize local clocks in real time.

---

## 4. Galactic Limit: Pulsar Timing Arrays in the $\mathcal{D}_{\text{loc}} \to 0$ Regime

At the opposite pole of astrophysical metrology—weak gravitational fields separated by galactic distances—**Pulsar Timing Arrays (PTAs)** provide an exact empirical realization of the far-field decoupled regime ($\Delta\ell \gg \mathcal{L}_{\text{sim}}$).

### 4.1 Quantitative Scaling on Kiloparsec Baselines

Consider a millisecond pulsar at distance $\Delta\ell = 1.0\text{ kpc} \approx 3.086 \times 10^{19}\text{ m}$ monitored from Earth ($N_{\text{eff}} \approx 1$ in the ionized interstellar medium at high radio frequencies). Even for an idealized atomic clock reference with ultra-low effective phase decoherence $\Gamma_{\text{tot}} = 10^{-3}\text{ s}^{-1}$ and $\rho_\tau = 0.5$:

$$\mathcal{L}_{\text{sim},\infty} = \frac{(2.9979 \times 10^8\text{ m/s})(1.0)(0.5)}{2(10^{-3}\text{ s}^{-1})} \approx 7.49 \times 10^{10}\text{ m} \approx 0.50\text{ AU}$$

Comparing the galactic baseline $\Delta\ell \approx 3.086 \times 10^{19}\text{ m}$ to the operational horizon $\mathcal{L}_{\text{sim},\infty} \approx 7.49 \times 10^{10}\text{ m}$ yields a dimensionless ratio:

$$\frac{\Delta\ell}{\mathcal{L}_{\text{sim},\infty}} \approx 4.12 \times 10^8 \implies \mathcal{D}_{\text{loc}} = \exp\left(-4.12 \times 10^8\right) \equiv 0$$

### 4.2 Metrological Classification Across Spacetime Regimes

| Physical Regime | Metric / Baseline | $\mathcal{L}_{\text{sim}}$ Behavior | $\mathcal{D}_{\text{loc}}$ Value | Operational Metrology Status |
| :--- | :--- | :--- | :--- | :--- |
| **Tabletop / Lab Core** | Minkowski, $\Delta\ell \sim 10\text{ m}$ | $\mathcal{L}_{\text{sim}} \sim 20\text{ km}$ | $\mathcal{D}_{\text{loc}} \approx 0.9995$ | Real-time active phase-locked simultaneity valid. |
| **Long-Baseline Fiber** | Minkowski, $\Delta\ell \sim 50\text{ km}$ | $\mathcal{L}_{\text{sim}} \sim 22\text{ km}$ | $\mathcal{D}_{\text{loc}} \approx 0.103$ | Operational sync degrades; post-selected Bell correlations ($S_{\text{CHSH}} > 2$) persist. |
| **Near-Horizon Strong Field** | Schwarzschild, $r \to r_s^+$ | $\mathcal{L}_{\text{sim}}(r) \to 0$ | $\mathcal{D}_{\text{loc}} \to 0$ | Smooth pre-horizon dissolution of simultaneity at $r_{\text{diss}} > r_s$; no cross-horizon operational paradox. |
| **Pulsar Timing Array** | Weak-field, $\Delta\ell \sim 1\text{ kpc}$ | $\mathcal{L}_{\text{sim}} \sim 0.5\text{ AU}$ | $\mathcal{D}_{\text{loc}} \to 0$ | Strictly post-selected classical coincidence analysis (Hellings-Downs spatial correlation). |

This proves that a cosmological or galactic "present moment" reconstructed via Pulsar Timing Arrays (such as the Hellings-Downs quadrupolar correlation curve) is fundamentally a **post-selected classical correlation** analogous to $S_{\text{CHSH}}$, never an active real-time operational simultaneity frame.

---

## 5. Conclusion

By extending Coherence-Bounded Operational Locality into curved spacetime and galactic-scale baselines, we establish a unified operational boundary across all regimes of relativistic physics. Near gravitational horizons, the Redshift-Modulated Operational Simultaneity Horizon $\mathcal{L}_{\text{sim}}(r) = \mathcal{L}_{\text{sim},\infty}\sqrt{1 - r_s/r}$ vanishes continuously outside $r_s$, dissolving operational simultaneity smoothly before any geometric horizon crossing occurs. Across galactic Pulsar Timing Arrays, $\Delta\ell \gg \mathcal{L}_{\text{sim}}$ enforces $\mathcal{D}_{\text{loc}} \to 0$, confirming that astronomical simultaneity is always a post-processed statistical reconstruction within a consistent four-dimensional spacetime manifold.

---

## AI Collaboration & Authorship Transparency Statement

This work is the result of human-AI scholarly collaboration. The core philosophical framework, conceptual architecture, operational definitions, and theoretical direction were conceived and authored by **Luís Pimenta Damásio** (ORCID: 0009-0001-7606-7557). Mathematical formalization, general relativistic derivations, and structural drafting support were provided by **Gemini** (Google AI) under the direct supervision, review, and editorial authority of the human author.
