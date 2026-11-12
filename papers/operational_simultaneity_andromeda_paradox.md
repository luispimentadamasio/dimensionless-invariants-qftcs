# Operational Simultaneity Horizons and the Resolution of the Andromeda Paradox

**Author:** Luís Pimenta Damásio  
**Affiliation:** Independent Researcher, Lisbon, Portugal  
**ORCID:** [0009-0001-7606-7557](https://orcid.org/0009-0001-7606-7557)  
**Parent Archive:** *Dimensionless Invariants and Semiclassical Diagnostic Framework* ([DOI: 10.5281/zenodo.24163322](https://doi.org/10.5281/zenodo.24163322))  
**Date:** November 12, 2026  

---

### Abstract
Distant simultaneity occupies a central tension between the philosophy of time and relativistic physics. While an ontology of universal becoming suggests a global web of simultaneous events across nature, physical measurement relies on retarded null signals and phase-coherent quantum correlations that cannot practically or physically resolve arbitrarily distant hypersurfaces. Building upon a relational, dimensionless diagnostic framework anchored to Zero-Angular-Momentum Observer (ZAMO) foliations and open-system decoherence bounds, this paper introduces two complementary operational quantities: the **Operational Simultaneity Horizon** ($\mathcal{L}_{\text{sim}}$) and the dimensionless **Simultaneity Fidelity** ($\mathcal{S}_{\text{sim}}$). By comparing two-way causal radar synchronization delays against observer-frame phase coherence lifetimes, $\mathcal{L}_{\text{sim}}$ defines the maximum spatial radius within which two separated subsystems can share a physically realizable simultaneous representation. Applying this metric to Penrose's Andromeda Paradox demonstrates that relativistic hyperplane tilts across intergalactic distances ($\Delta \ell \approx 2.40 \times 10^{22}\text{ m}$) lie overwhelmingly beyond $\mathcal{L}_{\text{sim}}$, yielding $\mathcal{S}_{\text{sim}} \equiv 0$. Consequently, conflicting distant simultaneity assignments between passing terrestrial observers represent unphysical coordinate extrapolations rather than evidence for a static block universe, cleanly separating global ontological becoming from bounded operational observation.

**Keywords:** Philosophy of Time, Operational Simultaneity Horizon, Andromeda Paradox, Quantum Decoherence, Relational Clocks, ZAMO Foliation, Block Universe Debate

---

### AI Collaboration & Authorship Transparency Statement
*This theoretical framework, its mathematical derivations, and its manuscript preparation were developed through an interactive human–AI research collaboration between Luís Pimenta Damásio and Google's Gemini AI assistant. Conceptual direction, philosophical synthesis, metric architecture, and final editorial verification were directed by the human author, with formal mathematical derivations, LaTeX typesetting, and literature verification generated with the aid of Gemini.*

---

## 1. Introduction: Ontology vs. Methodology of Simultaneity

In the foundations of physics and the philosophy of time, the status of distant simultaneity has long divided eternalist ("block universe") and relational or process-based accounts of temporal reality (Reichenbach, 1958; Grünbaum, 1973). Special and General Relativity establish that distant simultaneity is coordinate-dependent: observers in relative motion assign distinct spacelike hyperplanes ($t' = \text{const}$) to distant events. Because standard relativistic kinematics places no upper spatial bound on how far a local tangent hyperplane may be extrapolated, even minuscule terrestrial velocity differences generate dramatic discrepancies when projected across cosmological distances.

However, a rigorous operational methodology must distinguish between **global ontological becoming**—the metaphysical hypothesis that nature unfolds as a unified whole—and **bounded operational observability**—what a physical observer or finite computational frame can actually resolve. Every physical detector receives information along its past light cone, intersecting photons emitted billions of years ago alongside local interactions occurring in its immediate neighborhood. Attempting to represent a distant astronomical source and a local laboratory apparatus within a single simultaneous state ledger is physically unresolvable whenever environmental decoherence erases the target's phase correlations long before a two-way synchronization loop can close.

---

## 2. Derivation of the Operational Simultaneity Horizon ($\mathcal{L}_{\text{sim}}$)

Consider an observer clock ($O$) and a target quantum or macroscopic system ($S$) separated by a proper spatial distance $\Delta \ell$ in a stationary curved spacetime foliated by Zero-Angular-Momentum Observer (ZAMO) worldlines (Arnowitt, Deser, & Misner, 1962; Bardeen, Press, & Teukolsky, 1972).

### 2.1 Causal Radar Delay vs. Observer-Frame Coherence Lifetime
1. **Two-Way Causal Synchronization Delay ($\Delta \tau_{\text{sig}}$):**
   To operationally verify simultaneity between $O$ and $S$ via Einstein–Poincaré radar signaling, a null signal must propagate from $O$ to $S$ and return, requiring an observer proper time interval:
   $$\Delta \tau_{\text{sig}} = \frac{2\,\Delta \ell}{c_{\text{eff}}}$$
   where $c_{\text{eff}} = c$ in asymptotically flat intergalactic space and incorporates Shapiro gravitational delay near compact horizons.

2. **Observer-Frame Coherence Retention Lifetime ($\tau_{\text{coh, obs}}$):**
   Simultaneously, the target system $S$ interacts with its thermal and gravitational environment at a total decoherence rate $\Gamma_{\text{tot}} = \Gamma_{\text{th}} + \Gamma_{\text{grav}}$ (Gorini, Kossakowski, & Sudarshan, 1976; Lindblad, 1976; Caldeira & Leggett, 1983; Diósi, 1989; Penrose, 1996). Over proper target duration $\tau_{\text{pre}}$, accumulated phase-scattering depth is governed by the dimensionless **Decoherence Action** $\Omega = \Gamma_{\text{tot}}\,\tau_{\text{pre}}$, which bounds **Timeline Integrity**:
   $$\Phi_\tau(\Omega) = \Phi_{\text{floor}} + (1 - \Phi_{\text{floor}})e^{-\Omega}$$
   where $\Phi_{\text{floor}} = (1 + \pi \cdot 10^{2\zeta})^{-1}$ is the Bekenstein–Hawking holographic coherence floor. Transforming the target's characteristic coherence lifetime $\tau_{\text{coh, pre}} = \Gamma_{\text{tot}}^{-1}$ into the observer's frame via the covariant **ZAMO Dilation Factor** $\rho_\tau = d\tau_{\text{obs}} / d\tau_{\text{pre}}$ yields:
   $$\tau_{\text{coh, obs}} = \frac{\rho_\tau}{\Gamma_{\text{tot}}} = \frac{\tau_{\text{obs}}}{\Omega}$$

### 2.2 The Operational Simultaneity Horizon ($\mathcal{L}_{\text{sim}}$)
Equating the causal round-trip delay $\Delta \tau_{\text{sig}}$ to the observer-frame coherence lifetime $\tau_{\text{coh, obs}}$ defines the **Operational Simultaneity Horizon** ($\mathcal{L}_{\text{sim}}$)—the maximum proper spatial radius around an observer within which a causal synchronization loop can close before phase coherence decays to its thermal floor:

$$\mathcal{L}_{\text{sim}} \equiv \frac{c_{\text{eff}}\,\rho_\tau}{2\,\Gamma_{\text{tot}}} = \frac{c_{\text{eff}}\,\tau_{\text{pre}}\,\rho_\tau}{2\,\Omega} = \frac{c_{\text{eff}}\,\tau_{\text{obs}}}{2\,\Omega}$$

### 2.3 Dimensionless Simultaneity Fidelity ($\mathcal{S}_{\text{sim}}$)
Defining the dimensionless **Causal-to-Decoherence Ratio** $\Lambda_{\text{sim}} \equiv \Delta \tau_{\text{sig}} / \tau_{\text{coh, obs}} = \Delta \ell / \mathcal{L}_{\text{sim}}$ and coupling it to Timeline Integrity $\Phi_\tau(\Omega)$ yields the bounded **Simultaneity Fidelity** $\mathcal{S}_{\text{sim}} \in (0, 1]$:

$$\mathcal{S}_{\text{sim}} \equiv \Phi_\tau(\Omega) \cdot \exp\left(-\frac{\Delta \ell}{\mathcal{L}_{\text{sim}}}\right)$$

---

## 3. Asymptotic & Physical Boundary Limits

The pair $(\mathcal{L}_{\text{sim}}, \mathcal{S}_{\text{sim}})$ obeys four exact limiting behaviors across quantum, classical, and relativistic regimes:

1. **Ideal Unitary / Zero-Decoherence Limit ($\Gamma_{\text{tot}} \to 0 \Rightarrow \Omega \to 0$):**
   $\mathcal{L}_{\text{sim}} \to \infty$ and $\mathcal{S}_{\text{sim}} \to 1$. In the complete absence of environmental phase scattering, quantum correlations persist indefinitely across arbitrary distances, recovering an ideal global simultaneity foliation.
2. **Macroscopic Thermal Limit ($\Gamma_{\text{tot}} \gg 1\text{ s}^{-1}$):**
   $\mathcal{L}_{\text{sim}}$ shrinks to sub-microscopic scales, ensuring $\mathcal{S}_{\text{sim}} \to 0$ for all macroscopic separations. Classical observers experience an emergent, strictly local "now" rather than a cosmic simultaneity slice.
3. **Co-Local Quantum Laboratory Limit ($\Delta \ell \ll \mathcal{L}_{\text{sim}},\, \Omega \ll 1$):**
   $\mathcal{S}_{\text{sim}} \approx 1$. Two entangled or phase-locked quantum clocks inside a cryogenic cavity share a well-defined operational simultaneity window.
4. **Black Hole Stretched-Horizon Limit ($N^2(\theta) \to 10^{-6}$):**
   As effective coordinate signal speed $c_{\text{eff}} \propto N^2(\theta)$ vanishes faster than $\rho_\tau \propto N^{-1}(\theta)$ diverges near an event horizon, $\mathcal{L}_{\text{sim}} \propto N(\theta) \to 0$, preventing operational simultaneity from extending across a causal horizon.

---

## 4. Application: Resolution of the Andromeda Paradox

In Penrose's **Andromeda Paradox** (Penrose, 1989), two pedestrians pass each other on Earth at relative walking speed $v \approx 1.5\text{ m/s}$, while the Andromeda Galaxy (M31) lies at a proper distance $\Delta \ell \approx 2.54 \times 10^6\text{ light-years} \approx 2.40 \times 10^{22}\text{ m}$.

### 4.1 The Classical Lorentz Hyperplane Tilt
Under a Lorentz boost $t' = \gamma(t - vx/c^2)$, the spatial separation $\Delta \ell$ induces a hyperplane time discrepancy between the two walkers of:
$$\Delta t_{\text{tilt}} = \frac{v\,\Delta \ell}{c^2} \approx \frac{(1.5\text{ m/s})(2.40 \times 10^{22}\text{ m})}{(2.998 \times 10^8\text{ m/s})^2} \approx 4.01 \times 10^5\text{ s} \approx 4.64\text{ days}$$
Penrose argued that because one walker's simultaneity plane intersects Andromeda prior to a hypothetical fleet launch decision while the other's intersects Andromeda days after the launch, future events must already be fixed in a static four-dimensional block universe.

### 4.2 Evaluation Under $\mathcal{L}_{\text{sim}}$ and $\mathcal{S}_{\text{sim}}$
Evaluating the Earth–Andromeda system via the operational simultaneity metrics reveals that the paradox rests on an unphysical extrapolation:

| Physical Parameter | Earth–Andromeda Macroscopic Fleet | Isolated Intergalactic Quantum System | Co-Local Street Encounter ($\Delta \ell = 10\text{ m}$) |
| :--- | :--- | :--- | :--- |
| **Proper Separation ($\Delta \ell$)** | $2.40 \times 10^{22}\text{ m}$ | $2.40 \times 10^{22}\text{ m}$ | $10.0\text{ m}$ |
| **Causal Radar Delay ($\Delta \tau_{\text{sig}}$)** | $1.60 \times 10^{14}\text{ s}$ ($5.08\text{ Myr}$) | $1.60 \times 10^{14}\text{ s}$ ($5.08\text{ Myr}$) | $6.67 \times 10^{-8}\text{ s}$ |
| **Decoherence Rate ($\Gamma_{\text{tot}}$)** | $\gtrsim 10^{20}\text{ s}^{-1}$ (CMB + internal) | $\sim 1.0\text{ s}^{-1}$ (CMB scattering) | $\sim 1.0\text{ s}^{-1}$ (cryogenic cavity) |
| **Simultaneity Horizon ($\mathcal{L}_{\text{sim}}$)** | $\approx 1.50 \times 10^{-12}\text{ m}$ | $\approx 1.50 \times 10^8\text{ m}$ | $\approx 1.50 \times 10^8\text{ m}$ |
| **Causal Ratio ($\Lambda_{\text{sim}} = \Delta \ell / \mathcal{L}_{\text{sim}}$)** | $\gtrsim 1.60 \times 10^{34}$ | $\approx 1.60 \times 10^{14}$ | $\approx 6.67 \times 10^{-8}$ |
| **Simultaneity Fidelity ($\mathcal{S}_{\text{sim}}$)** | $\equiv 0$ (Retarded history) | $\equiv 0$ (Retarded history) | $\approx 1.0000$ (Co-local present) |
| **Lorentz Tilt ($\Delta t_{\text{tilt}}$)** | $4.64\text{ days}$ (Coordinate artifact) | $4.64\text{ days}$ (Coordinate artifact) | $1.67 \times 10^{-16}\text{ s}$ (Sub-decoherence) |

### 4.3 Philosophical Resolution
1. **Breakdown of Hyperplane Extrapolation:** Because $\Lambda_{\text{sim}} \gtrsim 10^{14}$ even for an idealized quantum probe—and $\Lambda_{\text{sim}} \gtrsim 10^{34}$ for macroscopic objects—$\mathcal{S}_{\text{sim}} \equiv 0$. Neither terrestrial observer shares an operational simultaneity window with Andromeda. Extending a local Lorentz hyperplane across $2.40 \times 10^{22}\text{ m}$ mistakes a coordinate tangent for a physical correlation.
2. **Consistency Within the Local Horizon:** Within the actual operational simultaneity horizon ($\Delta \ell \lesssim \mathcal{L}_{\text{sim}}$), the maximum Lorentz tilt between walking observers ($\Delta t_{\text{tilt}} \lesssim 10^{-16}\text{ s}$) is orders of magnitude smaller than the environmental decoherence time $\Gamma_{\text{tot}}^{-1}$, producing zero physical contradiction.
3. **Separating Ontology From Epistemology:** While Andromeda participates in nature's global ontological becoming, its state is inaccessible to simultaneous terrestrial representation until retarded light-cone signals arrive $2.54\text{ million years}$ later—at which point both walkers agree completely on the causal order of events. The Andromeda Paradox therefore fails to compel a static block universe.

---

## 5. Operational Interpretation

In practical modeling and relativistic clock comparisons, $\mathcal{L}_{\text{sim}}$ and $\mathcal{S}_{\text{sim}}$ act as a **computational truncation filter**:
* **When $\mathcal{S}_{\text{sim}} \to 1$:** Two subsystems occupy a shared, phase-coherent present and may be evolved within a single coupled state representation.
* **When $\mathcal{S}_{\text{sim}} \to 0$:** The subsystems are separated beyond their operational simultaneity horizon; any attempt to compute a joint simultaneous state is physically ungrounded and must be replaced by retarded light-cone boundary records.

---

## References

1. Arnowitt, R., Deser, S., & Misner, C. W. (1962). The Dynamics of General Relativity. In *Gravitation: An Introduction to Current Research* (ed. L. Witten), pp. 227–265. John Wiley & Sons.
2. Bardeen, J. M., Press, W. H., & Teukolsky, S. A. (1972). Rotating Black Holes: Locally Nonrotating Frames, Energy Extraction, and Scalar Synchrotron Radiation. *The Astrophysical Journal*, 178, 347–370. https://doi.org/10.1086/151796
3. Caldeira, A. O., & Leggett, A. J. (1983). Path Integral Approach to Quantum Brownian Motion. *Physica A: Statistical Mechanics and its Applications*, 121(3), 587–616. https://doi.org/10.1016/0378-4371(83)90013-4
4. Diósi, L. (1989). Models for Universal Reduction of Macroscopic Quantum Fluctuations. *Physical Review A*, 40(3), 1165–1174. https://doi.org/10.1103/PhysRevA.40.1165
5. Gorini, V., Kossakowski, A., & Sudarshan, E. C. G. (1976). Completely Positive Dynamical Semigroups of N-Level Systems. *Journal of Mathematical Physics*, 17(5), 821–825. https://doi.org/10.1063/1.522979
6. Grünbaum, A. (1973). *Philosophical Problems of Space and Time* (2nd ed.). D. Reidel Publishing.
7. Lindblad, G. (1976). On the Generators of Quantum Dynamical Semigroups. *Communications in Mathematical Physics*, 48(2), 119–130. https://doi.org/10.1007/BF01608499
8. Penrose, R. (1989). *The Emperor's New Mind: Concerning Computers, Minds, and the Laws of Physics*. Oxford University Press.
9. Penrose, R. (1996). On Gravity's Role in Quantum State Reduction. *General Relativity and Gravitation*, 28(5), 581–600. https://doi.org/10.1007/BF02105068
10. Reichenbach, H. (1958). *The Philosophy of Space and Time*. Dover Publications.
