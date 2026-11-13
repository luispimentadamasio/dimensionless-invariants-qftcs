# Dissipative Quantum Reference Frames: Non-Unitary Transformations Beyond the Operational Simultaneity Horizon

**Author:** Luís Pimenta Damásio  
**Affiliation:** Independent Researcher, Lisbon, Portugal  
**ORCID:** [0009-0001-7606-7557](https://orcid.org/0009-0001-7606-7557)  
**Series:** Temporal Coherence & Operational Relativistic Metrology — Part II: Applications, Open Quantum Systems & Gravitational Horizons (Paper 11)  
**Master Compendium DOI:** [10.5281/zenodo.24163322](https://doi.org/10.5281/zenodo.24163322)  

---

## Abstract

Recent advances in quantum foundations have generalized coordinate transformations to **Quantum Reference Frames (QRFs)**, treating physical clocks and rulers as quantum systems capable of existing in superposition or entanglement. Standard formulations of QRF covariance model frame shifts between distinct observers as idealized, noiseless unitary transformations ($\hat{U}_{A \to B}$) acting on composite Hilbert spaces. In this paper, we demonstrate that unitary QRF covariance implicitly relies on *naive classical point-locality*—assuming instantaneous, zero-noise synchronization across arbitrary spatial separations. By integrating the **Operational Simultaneity Horizon** ($\mathcal{L}_{\text{sim}}$) and the **Spatial Locality Decay Factor** ($\mathcal{D}_{\text{loc}}$) established in Papers 9 and 10, we prove that any physically realized transformation between spatially separated QRFs separated by baseline $\Delta\ell > 0$ under environmental phase decoherence $\Gamma_{\text{tot}} > 0$ is inherently an irreversible, non-unitary completely positive trace-preserving (CPTP) channel $\Lambda_{A \to B}$. We derive an explicit **QRF Transformation Fidelity Bound** ($\mathcal{F}_{\text{QRF}}$) and show that distributed quantum computing architectures naturally bifurcate at $\mathcal{L}_{\text{sim}}$ into monolithic real-time coherent cores and post-selected entanglement links. Finally, we examine the philosophical implications of dissipative QRF covariance within a neutral four-dimensionalist ontology.

---

## 1. Introduction: The Idealization of Unitary Quantum Reference Frames

In relational approaches to quantum mechanics and quantum gravity, physical observables are defined relative to material reference systems—such as optical clocks, gyroscopes, or massive particles—rather than an external, classical background manifold. The **Quantum Reference Frame (QRF)** formalism (Giacomini et al., 2019; Castro-Ruiz et al., 2020) elevates these reference systems to quantum degrees of freedom, demonstrating that properties such as superposition and entanglement are frame-dependent under quantum coordinate transformations.

However, standard QRF transformations construct the map from Frame $A$ to Frame $B$ as a global unitary operator $\hat{U}_{A \to B}$ acting instantaneously across the joint Hilbert space $\mathcal{H}_A \otimes \mathcal{H}_B \otimes \mathcal{H}_S$. While mathematically consistent in a zero-latency, closed-system idealization, this construction overlooks the operational metrological channel required to align two physically separated quantum clocks:

1. **Finite Relativistic Signaling Latency ($\Delta\tau_{\text{sig}}$):** Aligning a quantum clock at node $B$ with a quantum reference clock at node $A$ across a physical baseline $\Delta\ell$ requires an Einstein-Poincaré electromagnetic handshake of duration $\Delta\tau_{\text{sig}} = \frac{2\Delta\ell}{c N_{\text{eff}}}$.
2. **Continuous Open-System Decoherence ($\Gamma_{\text{tot}}$):** During the round-trip interval $\Delta\tau_{\text{sig}}$, both the quantum reference clocks and the optical synchronization channel undergo phase diffusion at rate $\Gamma_{\text{tot}}$.

As demonstrated in Paper 10 (*Coherence-Bounded Operational Locality*), conflating abstract algebraic correlations with active, real-time synchronization reintroduces *naive classical point-locality*. Here, we extend Coherence-Bounded Operational Locality to QRF transformations, replacing idealized unitary frame shifts with **Dissipative Quantum Reference Frame Channels**.

---

## 2. Formal Derivation: From Unitary Shifts to Coherence-Bounded CPTP Channels

### 2.1 Review of the Operational Simultaneity Horizon and Spatial Locality Decay

Consider two quantum clock laboratories $A$ and $B$ separated by a proper physical baseline $\Delta\ell$ connected via a waveguide or free-space channel of effective group refractive index $N_{\text{eff}}$. The minimum two-way synchronization delay is:

$$\Delta\tau_{\text{sig}} = \frac{2\Delta\ell}{c N_{\text{eff}}}$$

Let $\Gamma_{\text{tot}}$ denote the total phase decoherence rate (in $\text{s}^{-1}$) and $\rho_\tau \in (0, 1]$ denote the target phase-locking threshold parameter required to maintain an operationally valid simultaneity frame. As established in Papers 9 and 10, the **Operational Simultaneity Horizon** is given by:

$$\mathcal{L}_{\text{sim}} = \frac{c N_{\text{eff}} \rho_\tau}{2 \Gamma_{\text{tot}}}$$

The fraction of active, real-time phase synchronization preserved across baseline $\Delta\ell$ is quantified by the dimensionless **Spatial Locality Decay Factor**:

$$\mathcal{D}_{\text{loc}}(\Delta\ell, \Gamma_{\text{tot}}) = \exp\left(-\frac{\Delta\ell}{\mathcal{L}_{\text{sim}}}\right) = \exp\left(-\frac{2 \Gamma_{\text{tot}} \Delta\ell}{c N_{\text{eff}} \rho_\tau}\right)$$

In the idealized limit of zero spatial separation ($\Delta\ell \to 0$) or zero environmental noise ($\Gamma_{\text{tot}} \to 0$), $\mathcal{D}_{\text{loc}} \to 1$, recovering naive classical point-locality.

### 2.2 The Coherence-Bounded QRF Channel ($\Lambda_{A \to B}$)

Let $\rho_A \in \mathcal{B}(\mathcal{H}_S)$ represent the quantum state of a $d$-dimensional target system (such as a multi-level optical clock transition or distributed register) as described relative to Quantum Reference Frame $A$. Under an idealized, noiseless QRF transformation, the state relative to Frame $B$ is obtained via the unitary map:

$$\rho_B^{\text{ideal}} = \hat{U}_{A \to B} \, \rho_A \, \hat{U}_{A \to B}^\dagger$$

where $\hat{U}_{A \to B}$ encodes the quantum-controlled spatial translation or temporal phase shift between clocks $A$ and $B$.

When the frame transformation is implemented operationally across physical baseline $\Delta\ell$, the quantum phase correlation linking the control degrees of freedom of Clock $A$ and Clock $B$ decays exponentially according to $\mathcal{D}_{\text{loc}}$. In the absence of real-time phase lock (the far-field limit $\Delta\ell \gg \mathcal{L}_{\text{sim}}$, where $\mathcal{D}_{\text{loc}} \to 0$), the relative phase between Frame $A$ and Frame $B$ becomes uniformly randomized over the interval $[0, 2\pi)$, projecting the target state onto the maximally mixed state $\mathbb{I}/d$ (or, for pure dephasing channels, onto the classical diagonal ensemble in the clock eigenbasis).

Combining the coherent unitary branch weighted by $\mathcal{D}_{\text{loc}}$ with the decohered branch weighted by $(1 - \mathcal{D}_{\text{loc}})$ yields the **Coherence-Bounded QRF Channel** $\Lambda_{A \to B}$:

$$\Lambda_{A \to B}(\rho_A) = \mathcal{D}_{\text{loc}} \left(\hat{U}_{A \to B} \, \rho_A \, \hat{U}_{A \to B}^\dagger\right) + \left(1 - \mathcal{D}_{\text{loc}}\right) \frac{\mathbb{I}}{d}$$

Because $\mathcal{D}_{\text{loc}} \in (0, 1]$ for all finite $\Delta\ell \ge 0$ and $\Gamma_{\text{tot}} \ge 0$, $\Lambda_{A \to B}$ is strictly a **completely positive trace-preserving (CPTP)** map. Unitary QRF covariance is recovered *only* as an asymptotic boundary case when $\Delta\ell / \mathcal{L}_{\text{sim}} \to 0$.

### 2.3 QRF Transformation Fidelity Bound ($\mathcal{F}_{\text{QRF}}$)

To evaluate the operational accuracy of shifting descriptions between separated QRFs, we compute the Uhlmann-Jozsa state fidelity between the physically realized state $\Lambda_{A \to B}(\rho_A)$ and the idealized unitary prediction $\rho_B^{\text{ideal}}$ for a pure input state $\rho_A = |\psi\rangle\langle\psi|$:

$$\mathcal{F}_{\text{QRF}}(\Delta\ell, \Gamma_{\text{tot}}) = \operatorname{Tr}\!\left[\rho_B^{\text{ideal}} \, \Lambda_{A \to B}(\rho_A)\right] = \mathcal{D}_{\text{loc}} + \frac{1 - \mathcal{D}_{\text{loc}}}{d}$$

Rearranging terms yields the closed-form **QRF Transformation Fidelity Bound**:

$$\mathcal{F}_{\text{QRF}}(\Delta\ell, \Gamma_{\text{tot}}) = \frac{1}{d} + \left(1 - \frac{1}{d}\right) \exp\left(-\frac{2 \Gamma_{\text{tot}} \Delta\ell}{c N_{\text{eff}} \rho_\tau}\right)$$

For a qubit clock reference ($d = 2$), this simplifies to:

$$\mathcal{F}_{\text{QRF}}^{(d=2)} = \frac{1}{2} \left[1 + \exp\left(-\frac{\Delta\ell}{\mathcal{L}_{\text{sim}}}\right)\right]$$

---

## 3. Application: Architectural Bifurcation of the Quantum Internet

The dissipative QRF channel $\Lambda_{A \to B}$ imposes a fundamental physical scaling law on **distributed quantum computing** and **quantum internet** architectures. Current engineering roadmaps frequently treat multi-node quantum processors as unified, phase-coherent registers limited primarily by photon attenuation in optical fiber.

Our formalism demonstrates that even in an idealized, lossless optical waveguide, **active real-time quantum gate synchronization** across spatially separated nodes is strictly bounded by $\mathcal{L}_{\text{sim}}$.

| Architectural Tier | Baseline Condition | $\mathcal{D}_{\text{loc}}$ & $\mathcal{F}_{\text{QRF}}^{(d=2)}$ | Operational Capability |
| :--- | :--- | :--- | :--- |
| **Monolithic Coherent Core** | $\Delta\ell \ll \mathcal{L}_{\text{sim}}$ | $\mathcal{D}_{\text{loc}} \to 1$, $\mathcal{F}_{\text{QRF}} \to 1$ | Real-time phase-locked two-qubit gates; unitary QRF covariance holds to high precision. |
| **Mesoscopic Metrology Link** | $\Delta\ell \approx \mathcal{L}_{\text{sim}}$ | $\mathcal{D}_{\text{loc}} \approx 0.368$, $\mathcal{F}_{\text{QRF}} \approx 0.684$ | Severe non-unitary frame drift; requires active error mitigation and frequent re-calibration. |
| **Wide-Area Quantum Network** | $\Delta\ell \gg \mathcal{L}_{\text{sim}}$ | $\mathcal{D}_{\text{loc}} \to 0$, $\mathcal{F}_{\text{QRF}} \to 0.5$ | Real-time QRF synchronization impossible; restricted strictly to post-selected Bell/CHSH correlations ($S_{\text{CHSH}} > 2$) and heralded teleportation. |

For a cryogenic optical-clock link ($\rho_\tau = 0.5$, $N_{\text{eff}} = 1.468$, $\Gamma_{\text{tot}} = 5.0 \times 10^3\text{ s}^{-1}$), the Operational Simultaneity Horizon is $\mathcal{L}_{\text{sim}} \approx 22.0\text{ km}$. Consequently, metropolitan-scale quantum networks exceeding $\sim 20\text{ km}$ cannot operate as single unitary quantum reference frames; they must be engineered as hybrid architectures coupling local unitary cores with post-selected wide-area entanglement channels.

---

## 4. Philosophical Implications: Relational Covariance in a Four-Dimensionalist Spacetime

From the perspective of the philosophy of time and spacetime foundations, the transition from unitary QRF shifts ($\hat{U}_{A \to B}$) to dissipative CPTP channels ($\Lambda_{A \to B}$) clarifies the ontological status of relational quantum covariance.

Within a neutral four-dimensionalist or Block Universe ontology, the worldlines of quantum clocks $A$ and $B$ and the photon signals connecting them constitute a fixed, Lorentz-invariant geometric structure. Unitary QRF transformations tempt the theorist to treat "jumping" from Clock $A$'s perspective to Clock $B$'s perspective as a frictionless mathematical coordinate relabeling—akin to a passive Lorentz boost in classical special relativity.

Coherence-Bounded Operational Locality reveals why quantum coordinate transformations carry an irreducible thermodynamic cost: **a Quantum Reference Frame is not an abstract mathematical coordinate system, but an open physical system embedded in a noisy spacetime environment.** Transforming operational descriptions across a spatial interval $\Delta\ell$ requires physical signaling ($\Delta\tau_{\text{sig}}$) during which environmental entanglement ($\Gamma_{\text{tot}}$) irreversibly degrades phase coherence. Thus, exact unitary QRF covariance is a local tangent-space approximation valid only within the Operational Simultaneity Horizon ($\Delta\ell \ll \mathcal{L}_{\text{sim}}$).

---

## 5. Conclusion

By incorporating finite relativistic signaling delays and open-system phase decoherence into the Quantum Reference Frame formalism, we have shown that spatial QRF transformations are governed by the non-unitary CPTP channel $\Lambda_{A \to B}$ and bounded in fidelity by $\mathcal{F}_{\text{QRF}}$. Unitary QRF covariance is recovered strictly in the near-field limit $\mathcal{D}_{\text{loc}} \to 1$, while wide-area quantum networks naturally bifurcate into local coherent cores and post-selected entanglement links beyond $\mathcal{L}_{\text{sim}}$.

---

## References

1. Bell, J. S. (1964). On the Einstein Podolsky Rosen paradox. *Physics Physique Fizika*, 1(3), 195–200.
2. Castro-Ruiz, E., Giacomini, F., Belenchia, A., & Brukner, Č. (2020). Quantum clocks and the temporal localisability of events in the presence of gravitating quantum systems. *Nature Communications*, 11, 2672.
3. Giacomini, F., Castro-Ruiz, E., & Brukner, Č. (2019). Quantum mechanics and the covariance of physical laws in quantum reference frames. *Nature Communications*, 10, 494.
4. Pimenta Damásio, L. (2026). *Temporal Coherence & Operational Relativistic Metrology: Master Compendium (Papers 1–10)*. Zenodo. DOI: [10.5281/zenodo.24163322](https://doi.org/10.5281/zenodo.24163322).
5. Pimenta Damásio, L. (2026). *Coherence-Bounded Operational Locality: An Experimental Test of Simultaneous Phase Synchronization vs. Bell Correlations* (Paper 10). Zenodo.

---

## AI Collaboration & Authorship Transparency Statement

This work is the result of human-AI scholarly collaboration. The core philosophical framework, conceptual architecture, operational definitions, and theoretical direction were conceived and authored by **Luís Pimenta Damásio** (ORCID: 0009-0001-7606-7557). Mathematical formalization, analytical verification, and structural drafting support were provided by **Gemini** (Google AI) under the direct supervision, review, and editorial authority of the human author.
