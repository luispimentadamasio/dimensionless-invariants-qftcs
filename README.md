# dimensionless-invariants-qftcs
A collection of works that result from applying concepts of Philosophy of Time directly to Theoretical Physics
[master_glossary.md](https://github.com/user-attachments/files/34762210/master_glossary.md)
# Master Glossary of Symbols & Operational Metrics (v2.0)

**Author:** Luís Pimenta Damásio (`Luís {Pimenta Damásio}` in BibTeX)  
**Affiliation:** Independent Researcher, Lisbon, Portugal  
**ORCID:** [0009-0001-7606-7557](https://orcid.org/0009-0001-7606-7557)  
**Series:** Temporal Coherence & Operational Relativistic Metrology (Papers 1–13)  
**Master Compendium DOI:** [10.5281/zenodo.24163322](https://doi.org/10.5281/zenodo.24163322)  

---

## Overview

This document establishes the unified mathematical nomenclature and operational definitions across the *Temporal Coherence & Operational Relativistic Metrology* research series (Part I: Papers 1–10; Part II: Papers 11–13) and the `aeon-t.html` simulation suite. All definitions maintain strict compatibility with a neutral four-dimensionalist (Block Universe) ontology while formalizing the operational boundaries imposed by finite relativistic signaling and environmental decoherence.

---

## 1. Channel & Synchronization Primitives

| Symbol | Name | Units / Domain | Operational Definition & Formula |
| :--- | :--- | :--- | :--- |
| $\Delta\ell$ | **Proper Spatial Baseline** | $\text{m}$ ($\Delta\ell \ge 0$) | Physical waveguide or free-space separation between two local clock nodes $A$ and $B$. |
| $N_{\text{eff}}$ | **Effective Group Refractive Index** | Dimensionless ($N_{\text{eff}} \ge 1$) | Group refractive index governing electromagnetic wavepacket transit speed in the transmission medium ($N_{\text{eff}} = 1$ in vacuum; $N_{\text{eff}} \approx 1.468$ in standard telecom optical fiber). |
| $\Delta\tau_{\text{sig}}$ | **Round-Trip Signal Delay** | $\text{s}$ | Minimum two-way Einstein-Poincaré electromagnetic synchronization time across baseline $\Delta\ell$: $$\Delta\tau_{\text{sig}} = \frac{2 \Delta\ell}{c N_{\text{eff}}}$$ |
| $\Gamma_{\text{tot}}$ | **Total Phase Decoherence Rate** | $\text{s}^{-1}$ ($\Gamma_{\text{tot}} > 0$) | Combined environmental, thermal, acoustic, and quantum projection phase-diffusion rate acting on the clock network. |
| $\rho_\tau$ | **Phase-Locking Threshold Parameter** | Dimensionless ($\rho_\tau \in (0, 1]$) | Minimum fractional phase coherence required to sustain an operationally valid real-time simultaneity frame. |

---

## 2. Operational Simultaneity & Locality Metrics (Papers 9–10)

| Symbol | Name | Units / Domain | Operational Definition & Formula |
| :--- | :--- | :--- | :--- |
| $\mathcal{L}_{\text{sim}}$ | **Operational Simultaneity Horizon** | $\text{m}$ | Maximum physical baseline over which closed-loop real-time phase synchronization can converge before decoherence erases the shared reference frame: $$\mathcal{L}_{\text{sim}} = \frac{c N_{\text{eff}} \rho_\tau}{2 \Gamma_{\text{tot}}}$$ |
| $\Phi_\tau(\Omega)$ | **Intrinsic Local Temporal Coherence** | Dimensionless ($\Phi_\tau \in [0, 1]$) | Local quantum phase purity of the clock ensemble under coupling/drive parameter $\Omega$ prior to spatial channel transit. |
| $\mathcal{S}_{\text{sim}}(\Omega, \Delta\ell)$ | **Operational Simultaneity Fidelity** | Dimensionless ($\mathcal{S}_{\text{sim}} \in [0, 1]$) | Actionable real-time phase synchronization fidelity across baseline $\Delta\ell$ without post-selection: $$\mathcal{S}_{\text{sim}}(\Omega, \Delta\ell) = \Phi_\tau(\Omega) \cdot \exp\left(-\frac{\Delta\ell}{\mathcal{L}_{\text{sim}}}\right)$$ |
| $S_{\text{CHSH}}(\Omega)$ | **Post-Selected CHSH Bell Correlation** | Dimensionless ($S_{\text{CHSH}} \in [0, 2\sqrt{2}]$) | Statistical Bell-inequality correlation obtained via post-selected classical coincidence records, independent of baseline $\Delta\ell$: $$S_{\text{CHSH}}(\Omega) = 2\sqrt{2} \cdot \Phi_\tau(\Omega)$$ |
| $\mathcal{D}_{\text{loc}}$ | **Spatial Locality Decay Factor** | Dimensionless ($\mathcal{D}_{\text{loc}} \in (0, 1]$) | Normalized ratio isolating the pure relativistic signaling-decoherence decay from local quantum purity: $$\mathcal{D}_{\text{loc}} = \frac{2\sqrt{2} \cdot \mathcal{S}_{\text{sim}}(\Omega, \Delta\ell)}{S_{\text{CHSH}}(\Omega)} = \exp\left(-\frac{\Delta\ell}{\mathcal{L}_{\text{sim}}}\right)$$ |

### Core Foundational Principle: Coherence-Bounded Operational Locality
* **Definition:** The physical principle replacing idealized *naive classical point-locality* ($\mathcal{D}_{\text{loc}} \equiv 1$). It states that Bell's theorem (1964) is completely vindicated regarding non-factorizable joint quantum correlations ($S_{\text{CHSH}} > 2$ across spacelike intervals within a four-dimensionalist manifold), whereas active real-time operational synchronization ($\mathcal{S}_{\text{sim}}$) is strictly bounded by the exponential decay factor $\mathcal{D}_{\text{loc}}$.
* **Regime Boundaries:**
  * **Near-Field Coherent Regime ($\Delta\ell \ll \mathcal{L}_{\text{sim}}$, $\mathcal{D}_{\text{loc}} \to 1$):** Naive classical point-locality holds as an accurate engineering approximation.
  * **Horizon Transition Regime ($\Delta\ell \approx \mathcal{L}_{\text{sim}}$, $\mathcal{D}_{\text{loc}} = e^{-1} \approx 0.368$):** Operational simultaneity degrades rapidly while post-selected Bell violations remain maximal.
  * **Far-Field Decoupled Regime ($\Delta\ell \gg \mathcal{L}_{\text{sim}}$, $\mathcal{D}_{\text{loc}} \to 0$):** Real-time phase synchronization fails; entanglement persists exclusively as a non-signaling, post-selected correlation.

---

## 3. Part II Extension Metrics (Papers 11–13 & `aeon-t.html`)

| Symbol | Name | Context / Paper | Operational Definition & Formula |
| :--- | :--- | :--- | :--- |
| $\Lambda_{A \to B}$ | **Coherence-Bounded QRF Channel** | Paper 11 | Non-unitary completely positive trace-preserving (CPTP) map governing transformations between spatially separated Quantum Reference Frames, weighted by $\mathcal{D}_{\text{loc}}$: $$\Lambda_{A \to B}(\rho_A) = \mathcal{D}_{\text{loc}} \left(\hat{U}_{A \to B} \rho_A \hat{U}_{A \to B}^\dagger\right) + (1 - \mathcal{D}_{\text{loc}}) \frac{\mathbb{I}}{d}$$ |
| $\mathcal{F}_{\text{QRF}}(\Delta\ell, \Gamma_{\text{tot}})$ | **QRF Transformation Fidelity Bound** | Paper 11 | Maximum achievable state fidelity when shifting a $d$-dimensional quantum clock description across baseline $\Delta\ell$: $$\mathcal{F}_{\text{QRF}}(\Delta\ell, \Gamma_{\text{tot}}) = \frac{1}{d} + \left(1 - \frac{1}{d}\right) \exp\left(-\frac{2 \Gamma_{\text{tot}} \Delta\ell}{c N_{\text{eff}} \rho_\tau}\right)$$ |
| $\Xi_{\text{QG}}$ | **Two-Tier Quantum Gravity Anomaly Monitor** | Paper 12 & `aeon-t.html` (Panel 6) | Differential phase-drift observable isolating genuine spacetime/gravitational decoherence anomalies from the deterministic baseline relativistic synchronization lag ($\mathcal{D}_{\text{loc}}$). |
| $\mathcal{L}_{\text{sim}}(r)$ | **Redshift-Modulated Simultaneity Horizon** | Paper 13 | Local proper-distance operational simultaneity horizon in curved spacetime (e.g., Schwarzschild metric), vanishing smoothly ($\mathcal{L}_{\text{sim}}(r) \to 0$) as the radial coordinate $r$ approaches the event horizon $r_s$. |

---

## AI Collaboration & Authorship Transparency Statement

This work is the result of human-AI scholarly collaboration. The core philosophical framework, conceptual architecture, operational definitions, and theoretical direction were conceived and authored by **Luís Pimenta Damásio** (ORCID: 0009-0001-7606-7557). Mathematical formalization, analytical verification, and structural drafting support were provided by **Gemini** (Google AI) under the direct supervision, review, and editorial authority of the human author.
