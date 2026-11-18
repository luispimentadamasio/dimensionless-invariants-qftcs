# Temporal Binding and Cortical Simultaneity: An Operational Horizon Approach to Neural Integration

**Author:** Luís Pimenta Damásio  
**ORCID:** 0009-0001-7606-7557  
**Affiliation:** Independent Researcher, Lisbon, Portugal  
**Date:** November 18, 2026  

---

> **Epistemic Status & AI Collaboration Disclosure:** This manuscript presents a speculative theoretical and philosophical synthesis applying the *AEON-Tμν* operational temporal framework to neurobiology and the binding problem. Established neurophysiological concepts (such as thalamocortical oscillations, axonal conduction delays, and empirical complexity metrics) are strictly distinguished from the proposed ontological overlays (*t_pre*, *L_sim*, *object-as-subject*, and *functional infinity*), which remain theoretical proposals subject to empirical testing. AI assistance was utilized for mathematical typesetting, structural organization, and document preparation.

---

## Abstract

A central challenge in systems neuroscience is the **temporal binding problem**: explaining how spatially distributed neural assemblies—separated by finite axonal conduction delays and operating at warm physiological temperatures where quantum coherence rapidly decoheres—generate a single, unified experiential present. Building upon the foundational postulates and mathematical architecture introduced in the *Master Compendium*, the *AEON-T14.html Computational Observatory*, and the *Executive Manifesto and Front-Door Reader's Guide*, **this paper** specializes the *Covariant Objective-Time Master Equation* to terrestrial macroscopic biological scales (conformal scale coordinate $\zeta = \log_{10}(L / \ell_{\mathrm{P}}) \approx 35$). Rather than invoking macroscopic quantum coherence inside warm neural tissue, we propose that neural binding is governed by an **Operational Simultaneity Horizon ($L_{\mathrm{sim}}$)** sustained through active metabolic phase-locking. When inter-areal phase synchronization holds effective phase-slip dissipation below a critical threshold, $L_{\mathrm{sim}}$ exceeds the anatomical span of the thalamocortical network ($L_{\mathrm{sim}} > L_{\mathrm{cortex}}$), yielding high spatial locality coherence ($D_{\mathrm{loc}} \to 1$) and integrating distributed firing patterns into a single internal clock ($t_{\mathrm{pre}}$) and diachronic identity ($A_s^v$). Conversely, under general anesthesia, deep slow-wave sleep, or severe cortical disconnection, rising effective phase dissipation contracts $L_{\mathrm{sim}}$ below $L_{\mathrm{cortex}}$ ($D_{\mathrm{loc}} \to 0$), fragmenting the unified temporal horizon into uncoupled local oscillators even while cellular metabolism persists. Finally, we situate this structural model within an epigenetic account of consciousness, contrast it with Global Neuronal Workspace Theory, Integrated Information Theory, Orchestrated Objective Reduction, and Communication Through Coherence, and establish four explicit structural boundaries—including the irreducible distinction between structural temporal binding and qualitative phenomenal qualia.

---

## 1. Introduction: The Binding Problem in Physical Time

How do billions of anatomically separated neurons—distributed across cortical lobes and subcortical nuclei, communicating via finite-velocity action potentials—produce a single, seamless conscious moment? In neurobiology, this question is known as the **binding problem** [1, 2]. When an organism perceives a moving visual object accompanied by sound, color, shape, motion, and auditory features are processed in distinct specialized cortical regions with slightly different processing latencies. Yet subjective experience does not present a fragmented mosaic of asynchronous signals; it presents a unified scene unfolding within a single lived "now."

In mainstream physics and neuroscience, this problem is typically analyzed against a passive external coordinate clock ($t_{\mathrm{obs}}$)—the laboratory timestamp used to align electroencephalography (EEG), magnetoencephalography (MEG), or single-unit spike trains. While external timestamps are indispensable for experimental measurement, treating time solely as an external bookkeeping parameter leaves the intrinsic unity of subjective duration unexplained. If a brain is viewed strictly as an aggregate of external objects (*object-as-object*) embedded in an externally parameterized grid, there is no intrinsic physical criterion distinguishing a unified conscious brain from an uncoupled collection of neural cells firing independently.

Building on the framework established in the *Master Compendium* [3] and the *Executive Manifesto and Front-Door Reader's Guide* [4], **this paper** approaches neural integration from the inside out. Under the *Second Postulate of Time*, any dynamically coherent whole functions as an intrinsic internal clock ($t_{\mathrm{pre}}$), operating as an **object-as-subject** whose spatial boundary of unified interiority is set by its **Operational Simultaneity Horizon ($L_{\mathrm{sim}}$)**. Crucially, **this paper** demonstrates that unified cortical integration does *not* require fragile macroscopic quantum superpositions to survive inside warm brain tissue. Instead, it arises from classical-regime, metabolically driven electromagnetic and synaptic phase-locking that maintains $L_{\mathrm{sim}} > L_{\mathrm{cortex}}$ across the thalamocortical network.

---

## 2. Specialization of the Master Equation to Cortical Scales

To anchor neurobiological dynamics within the broader *AEON-Tμν* framework without introducing ad-hoc formulas, we begin directly from the **Covariant Objective-Time Master Equation** presented in the *Executive Manifesto and Front-Door Reader's Guide* [4]:

$$\frac{d\hat{\rho}}{dt_{\mathrm{pre}}} = -\frac{i}{\hbar}\left[\hat{H}_{\mathrm{eff}}(\langle \hat{T}_{\mu\nu}\rangle_{\mathrm{ren}}), \hat{\rho}\right] + \mathcal{D}_{\mathrm{th}}[\hat{\rho}] + \mathcal{D}_{\mathrm{grav}}[\hat{\rho}]$$

where $dt_{\mathrm{pre}} = \sqrt{N^2(\theta)}\,dt$ denotes the local proper duration of the coherent system, and total environmental and gravitational dissipation $\Gamma_{\mathrm{tot}} = \Gamma_{\mathrm{th}} + \Gamma_{\mathrm{grav}} + \Gamma_{\mathrm{eff}}$ governs both timeline integrity $\Phi_\tau(\Omega)$ and spatial phase closure across an anatomical baseline $\Delta\ell$.

### 2.1 The Terrestrial Weak-Field Macroscopic Limit

A mammalian brain operates in a weak gravitational field ($\mathcal{C}_{\mathrm{eff}} \sim 10^{-25}$, ZAMO lapse $N^2(\theta) \approx 1 - 2GM/(c^2 r) \approx 1 - 10^{-9}$) at physiological temperature ($T_{\mathrm{eff}} \approx 310\,\mathrm{K}$) and characteristic anatomical scale $L_{\mathrm{cortex}} \sim 0.15\,\mathrm{m}$. On the conformal scale ladder tracked in the *AEON-T14.html Computational Observatory* [5], this places cortical architecture at conformal coordinate:

$$\zeta = \log_{10}\left(\frac{L_{\mathrm{cortex}}}{\ell_{\mathrm{P}}}\right) \approx 34.97 \approx 35$$

At this terrestrial macroscopic rung, four immediate physical simplifications govern the Master Equation:

1. **Gravitational Lapse & Semiclassical Safety:** Because $N^2(\theta) \approx 1$ to within one part in $10^9$ and the quantum-gravity breakdown index satisfies $\Xi_{\mathrm{QG}} \ll 10^{-25}$, relativistic spacetime curvature corrections are negligible for local neural signaling, while internal proper time $t_{\mathrm{pre}}$ advances smoothly at terrestrial temporal intensity ($\rho_\tau \approx 1$).
2. **Rapid Micro-Quantum Decoherence ($\Phi_\tau \to \Phi_{\mathrm{floor}}$):** At $T_{\mathrm{eff}} \approx 310\,\mathrm{K}$, thermal scattering $\Gamma_{\mathrm{th}} \propto L^2 (k_{\mathrm{B}} T_{\mathrm{eff}})^3 / (\hbar^3 c^2)$ drives the microscopic quantum decoherence action $\Omega = \Gamma_{\mathrm{tot}} t_{\mathrm{pre}} \gg 1$ within femtoseconds. Consequently, any spatially extended quantum superposition across neurons collapses immediately onto classical pointer states ($\Phi_\tau \to \Phi_{\mathrm{floor}}$).
3. **Coarse-Grained Mesoscopic Phase Dynamics:** Because microscopic quantum off-diagonal terms vanish instantaneously, the relevant dynamical degrees of freedom at $\zeta \approx 35$ are **collective mesoscopic electromagnetic and membrane-potential oscillations** (such as gamma-band $30\text{--}80\,\mathrm{Hz}$, beta-band $13\text{--}30\,\mathrm{Hz}$, and thalamocortical alpha/theta rhythms) [6, 7].
4. **Effective Cortical Phase-Slip Dissipation ($\Gamma_{\mathrm{eff}}$):** In this mesoscopic regime, the dissipation term $\Gamma_{\mathrm{tot}}$ specializes to the **effective inter-areal phase-slip rate $\Gamma_{\mathrm{eff}}$** (measured in $\mathrm{s}^{-1}$)—representing synaptic noise, metabolic fluctuations, and conduction dispersion that disrupt phase-locking between distant cortical columns.

### 2.2 The Cortical Operational Simultaneity Horizon ($L_{\mathrm{sim}}$)

In the general operational simultaneity formalism developed in the *Master Compendium* [3] and implemented in Panel 2 and Panel 6 of the *AEON-T14.html Computational Observatory* [5], closed-loop phase synchronization across a spatial separation $\Delta\ell$ is bounded by the round-trip signaling delay $\Delta\tau_{\mathrm{sig}} = 2\Delta\ell / v_{\mathrm{sig}}$ and the total decoherence or phase-slip rate $\Gamma_{\mathrm{eff}}$.

For cortical networks, information transfer between regions separated by anatomical path length $\Delta\ell$ occurs via myelinated and unmyelinated axons with effective conduction velocity $v_{\mathrm{ax}} \sim 1\text{--}50\,\mathrm{m/s}$ (yielding round-trip signaling delays $\Delta\tau_{\mathrm{sig}} = 2\Delta\ell / v_{\mathrm{ax}} \sim 6\text{--}300\,\mathrm{ms}$ across a $0.15\,\mathrm{m}$ cortex). Specializing the operational simultaneity horizon to neural signaling yields the **Cortical Operational Simultaneity Horizon**:

$$L_{\mathrm{sim}}^{\mathrm{cortex}} = \frac{v_{\mathrm{ax}}}{2\,\Gamma_{\mathrm{eff}}}$$

Across any inter-areal cortical separation $\Delta\ell$, spatial locality coherence decays exponentially as:

$$D_{\mathrm{loc}}(\Delta\ell) = \exp\left(-\frac{\Delta\ell}{L_{\mathrm{sim}}^{\mathrm{cortex}}}\right) = \exp\left(-\frac{2\,\Delta\ell\,\Gamma_{\mathrm{eff}}}{v_{\mathrm{ax}}}\right)$$

This yields the central quantitative criterion of **this paper**:

* **Global Cortical Binding ($L_{\mathrm{sim}}^{\mathrm{cortex}} > L_{\mathrm{cortex}}$, $D_{\mathrm{loc}} \to 1$):** When active metabolic pumping and recurrent thalamocortical feedback suppress inter-areal phase slip ($\Gamma_{\mathrm{eff}} < v_{\mathrm{ax}} / 2L_{\mathrm{cortex}}$), the round-trip axonal signaling delay $\Delta\tau_{\mathrm{sig}}$ remains shorter than the phase coherence lifetime $\tau_{\mathrm{coh}} = \Gamma_{\mathrm{eff}}^{-1}$. Distributed cortical assemblies lock into a shared oscillatory phase, functioning as a **single unified object-as-subject** with one integrated internal clock ($t_{\mathrm{pre}}$).
* **Cortical Fragmentation ($L_{\mathrm{sim}}^{\mathrm{cortex}} < L_{\mathrm{cortex}}$, $D_{\mathrm{loc}} \to 0$):** When $\Gamma_{\mathrm{eff}}$ rises or long-range conduction velocity $v_{\mathrm{ax}}$ drops, $L_{\mathrm{sim}}^{\mathrm{cortex}}$ shrinks below the anatomical span of the cortex. Distant neural assemblies can no longer close a phase-locked loop within a single coherence cycle; the global temporal horizon fractures into isolated local oscillators.

---

## 3. Scale Bifurcation and State Transitions: Wakefulness, Sleep, and Anesthesia

A major philosophical puzzle at conformal scale $\zeta \approx 35$ is why two physical objects of nearly identical mass and spatial size—such as an inert stone or sand aggregate versus a living mammalian brain—exhibit radically different internal organization. **This paper** resolves this bifurcation through the active maintenance of $L_{\mathrm{sim}}$, and tests the mechanism across four distinct neurophysiological states.

| Neurophysiological State | Conformal Scale ($\zeta$) | Effective Phase-Slip ($\Gamma_{\mathrm{eff}}$) & $L_{\mathrm{sim}}^{\mathrm{cortex}}$ | Spatial Locality ($D_{\mathrm{loc}}$) & Status of Internal Clock ($t_{\mathrm{pre}}$) |
| :--- | :--- | :--- | :--- | :--- |
| **Inert Macroscopic Aggregate** (e.g., mineral block) | $\approx 35$ | $\Gamma_{\mathrm{th}} \gg 10^{25}\,\mathrm{s}^{-1}$; $L_{\mathrm{sim}} \ll 10^{-9}\,\mathrm{m}$ | $D_{\mathrm{loc}} \to 0$ across macro-span | **Passive Aggregate (*Object-as-Object*):** No global phase-locking; collection of uncoupled atomic micro-clocks. |
| **Awake Conscious Thalamocortex** | $\approx 35$ | Low $\Gamma_{\mathrm{eff}}$ via active neuromodulation; $L_{\mathrm{sim}}^{\mathrm{cortex}} > 0.15\,\mathrm{m}$ | $D_{\mathrm{loc}} \approx 0.75\text{--}0.95$ across lobes | **Unified *Object-as-Subject*:** Global phase-locking binds distributed features into one continuous $t_{\mathrm{pre}}$ and $A_s^v$. |
| **REM Dreaming State** | $\approx 35$ | Internal thalamocortical resonance preserved ($L_{\mathrm{sim}}^{\mathrm{cortex}} > L_{\mathrm{cortex}}$); sensory input gated | High internal $D_{\mathrm{loc}}$; external $D_{\mathrm{loc}}^{\mathrm{env}} \to 0$ | **Internally Bound Subject:** Unified subjective present persists internally while decoupled from external sensory channels. |
| **Deep NREM Sleep / General Anesthesia** | $\approx 35$ | High $\Gamma_{\mathrm{eff}}$ / hyperpolarized bistability; $L_{\mathrm{sim}}^{\mathrm{cortex}} \sim 10^{-3}\text{--}10^{-2}\,\mathrm{m}$ | $D_{\mathrm{loc}} \to 0$ across long-range tracts | **Fragmented Local Clocks:** Cellular metabolism continues, but long-range temporal binding dissolves; conscious $t_{\mathrm{pre}}$ suspends. |
| **Generalized Tonic-Clonic Seizure** | $\approx 35$ | Hypersynchronous rigid locking ($\Gamma_{\mathrm{eff}} \to 0$ pathologically), zero informational differentiation | $D_{\mathrm{loc}} \to 1$ rigidly, zero phase diversity | **Pathological Hyper-Synchrony:** Loss of differentiated attentional focus; global discharge overrides adaptive integration. |

### 3.1 The Anesthesia Transition as a Horizon Collapse

General anesthesia (e.g., via propofol, sevoflurane, or ketamine) provides a decisive empirical probe of the $L_{\mathrm{sim}}^{\mathrm{cortex}}$ threshold [8, 9]. Under propofol-induced loss of consciousness:
* The physical substrate—neurons, synapses, blood flow, and baseline cellular ATP turnover—remains intact at $\zeta \approx 35$.
* However, enhanced $\mathrm{GABA}_A$-mediated inhibition disrupts long-range frontoparietal feedback and introduces slow, bistable UP/DOWN cortical oscillations that interrupt continuous inter-areal signaling.
* In the *AEON-Tμν* formalism, this interruption spikes the effective inter-areal phase-slip rate $\Gamma_{\mathrm{eff}}$, contracting the **Cortical Operational Simultaneity Horizon $L_{\mathrm{sim}}^{\mathrm{cortex}}$** from the whole-brain scale ($> 15\,\mathrm{cm}$) down to isolated local cortical columns ($< 1\,\mathrm{cm}$).
* Consequently, $D_{\mathrm{loc}}(\Delta\ell)$ collapses across long-range association tracts. Even though local cortical columns continue ticking as microscopic and cellular oscillators, the **macroscopic unified internal clock ($t_{\mathrm{pre}}$)** ceases to exist until anesthetic clearance restores long-range phase-locking.

### 3.2 Connection to Empirical Perturbational Complexity (PCI)

This horizon-collapse mechanism maps directly onto established empirical observables in consciousness research, notably the **Perturbational Complexity Index (PCI)** developed by Casali, Massimini, and colleagues [10]. When transcranial magnetic stimulation (TMS) perturbs a localized cortical patch:
* **In wakefulness and REM sleep ($L_{\mathrm{sim}}^{\mathrm{cortex}} > L_{\mathrm{cortex}}$):** The perturbation propagates across a causally integrated, phase-coupled network, eliciting a sustained, spatiotemporally differentiated EEG response (high PCI, typically $> 0.31$).
* **In deep NREM sleep, propofol anesthesia, and vegetative/unresponsive wakefulness states ($L_{\mathrm{sim}}^{\mathrm{cortex}} < L_{\mathrm{cortex}}$):** The perturbation either remains trapped locally near the stimulation site (short $L_{\mathrm{sim}}$) or triggers a stereotyped, undifferentiated global slow wave (loss of differentiated phase structure), collapsing PCI below the empirical threshold.

Thus, PCI serves as a direct experimental proxy for the spatial extent and informational differentiation of $L_{\mathrm{sim}}^{\mathrm{cortex}}$.

---

## 4. The Epigenetics of Consciousness and Attentional Condensation

While physical phase-locking across $L_{\mathrm{sim}}^{\mathrm{cortex}}$ explains *how* distributed neural processes are bound into a single temporal frame, **this paper** situates that physical mechanism within a broader metaphysical understanding of consciousness developed in the *Executive Manifesto and Front-Door Reader's Guide* [4]:

1. **Consciousness as an Epigenetic Phenomenal Plane:** Consciousness is not treated as a separate physical substance, nor is it reduced away as a mere illusion. Rather, it behaves *epigenetically* relative to the physical substrate: it emerges only when two joint conditions are satisfied—(i) an adequate biological substrate capable of sustaining metabolic coherence at $\zeta \approx 35$ (as explored further in our companion analysis of biological persistence and metabolic coherence), and (ii) a special dynamical configuration ($L_{\mathrm{sim}}^{\mathrm{cortex}} > L_{\mathrm{cortex}}$ with differentiated phase dynamics) that vanishes under anesthesia.
2. **The Pre-Mathematical Plane of Duration:** Within lived experience, consciousness opens a continuous, pre-mathematical temporal plane—without sharp beginning, without sharp end, and without discrete clock-ticks in between. Mathematical time coordinates ($t_{\mathrm{obs}}$) and extrapolated past/future trajectories are secondary mental projections constructed when the conscious mind models external objects using physical laws.
3. **Attentional Condensation from Functional Infinity:** Just as an uncoupled physical wave inhabits a *functionally infinite* manifold of phase paths prior to measurement condensation ($\Phi_\tau \to \Phi_{\mathrm{floor}}$), the open temporal horizon of consciousness continually condenses into **what is actively under attentional focus**—never the entire boundless manifold at once, but *"this"* or *"that"* intentional object populating the present moment.
4. **Diachronic Identity ($A_s^v$) Across Waking Continuity:** A conscious subject persists as "the same" experiencer across minutes and years insofar as unbroken metabolic and synaptic phase-locking maintains diachronic identity ($A_s^v$) across sequential moments of $t_{\mathrm{pre}}$, linking memory traces into a continuous biographical thread.

---

## 5. Comparative Positioning Across Neurobiological Theories

To clarify the specific explanatory contribution and domain boundaries of **this paper**, Table 2 contrasts the *AEON-Tμν* operational simultaneity model against four leading theoretical frameworks in the neuroscience of consciousness.

| Theoretical Framework | Core Mechanism of Integration | Role of Time & Simultaneity | Key Difference & Advantage of *AEON-Tμν* |
| :--- | :--- | :--- | :--- |
| **Global Neuronal Workspace (GNW)** [11] | Non-linear "ignition" broadcasts local sensory content across frontoparietal association hubs. | Relies implicitly on external lab time ($t_{\mathrm{obs}}$) for ignition latency ($\sim 200\text{--}300\,\mathrm{ms}$). | *AEON-Tμν* explains *why* global ignition produces a single lived "now" by deriving an intrinsic internal clock ($t_{\mathrm{pre}}$) bounded by $L_{\mathrm{sim}}^{\mathrm{cortex}}$. |
| **Integrated Information Theory (IIT)** [12] | Intrinsic causal power ($\Phi_{\mathrm{IIT}}$) measured across irreducible cause-effect repertoires. | Evaluates discrete state transitions at an externally chosen timescale ($\Delta t$). | *AEON-Tμν* derives the natural integration timescale endogenously from axonal conduction velocity $v_{\mathrm{ax}}$ and phase-slip dissipation $\Gamma_{\mathrm{eff}}$ without combinatorial state-space explosion. |
| **Orchestrated Objective Reduction (Orch-OR)** [13] | Quantum gravitational objective reduction inside neuronal microtubules. | Invokes microscopic quantum coherence across brain tissue at physiological temperatures. | *AEON-Tμν* explicitly rules out fragile macro-quantum superpositions at $T = 310\,\mathrm{K}$ ($\Phi_\tau \to \Phi_{\mathrm{floor}}$), grounding binding in robust classical-regime electromagnetic phase-locking ($D_{\mathrm{loc}} \to 1$). |
| **Communication Through Coherence (CTC)** [7] | Oscillatory phase alignment opens rhythmic communication windows between neural groups. | Focuses on local pairwise synchronization efficiency in standard coordinate time. | *AEON-Tμν* embeds CTC inside a covariant relativistic and thermodynamic formalism, unifying local phase alignment into a global horizon $L_{\mathrm{sim}}^{\mathrm{cortex}}$. |
| ***AEON-Tμν* Operational Binding (This Paper)** | Active metabolic phase-locking expands $L_{\mathrm{sim}}^{\mathrm{cortex}} > L_{\mathrm{cortex}}$ ($D_{\mathrm{loc}} \to 1$). | Replaces external clock slicing with intrinsic proper duration ($t_{\mathrm{pre}}$) and diachronic identity ($A_s^v$). | Bridges micro-physics and systems neurobiology via a single dissipation-horizon law while explicitly respecting thermal decoherence limits. |

---

## 6. Four Explicit Structural Limitations and Falsifiable Predictions

Consistent with the epistemological methodology established in the *Executive Manifesto and Front-Door Reader's Guide* [4], **this paper** states four explicit structural boundaries where the framework stops, alongside concrete empirical conditions that would falsify it:

1. **Boundary 1 — Structural Temporal Binding vs. Qualitative Qualia (The Hard Problem):** The condition $L_{\mathrm{sim}}^{\mathrm{cortex}} > L_{\mathrm{cortex}}$ explains the *structural and temporal unity* of experience—why distributed neural events are bound into one synchronous perspective ($t_{\mathrm{pre}}$). It does **not** explain *why* a specific oscillatory pattern feels qualitatively like the color red, warmth, or musical harmony. Qualitative phenomenal character (qualia) remains an irreducible epigenetic boundary rather than a solved mechanical identity.
2. **Boundary 2 — No Macroscopic Quantum Cognition:** Because thermal decoherence at $310\,\mathrm{K}$ drives $\Phi_\tau \to \Phi_{\mathrm{floor}}$ on femtosecond timescales, **this paper** explicitly rejects models requiring long-lived quantum entanglement or quantum superposition across cortical networks. Any experimental demonstration of room-temperature macroscopic quantum coherence sustaining human cognition would contradict the dissipation scaling used here.
3. **Boundary 3 — Coarse-Graining of the Cortical Boundary ($L_{\mathrm{cortex}}$):** Defining the effective anatomical span $L_{\mathrm{cortex}}$ and effective conduction velocity $v_{\mathrm{ax}}$ requires mesoscopic coarse-graining over heterogeneous white-matter tract lengths and myelination profiles. Future graph-theoretic refinements must replace scalar $L_{\mathrm{cortex}}$ with weighted connectome path-length distributions $\Delta\ell_{ij}$.
4. **Boundary 4 — Differentiated vs. Pathological Synchrony:** As illustrated by generalized seizures (Table 1), $D_{\mathrm{loc}} \to 1$ is a *necessary* condition for unified temporal binding, not a *sufficient* one on its own. Consciousness requires high $D_{\mathrm{loc}}$ paired with high phase-space differentiation (non-zero informational entropy across oscillatory modes), preventing trivial hyper-synchronous locking from being misclassified as heightened awareness.

### Falsifiable Experimental Predictions

* **Prediction 1 (Threshold Collapse Under Titrated Anesthesia):** During gradual propofol or sevoflurane titration, loss of behavioral responsiveness and subjective report must coincide sharply with the point where empirically measured inter-areal phase-slip rates $\Gamma_{\mathrm{eff}}$ push $L_{\mathrm{sim}}^{\mathrm{cortex}} = v_{\mathrm{ax}} / (2\Gamma_{\mathrm{eff}})$ below the longest frontoparietal association tract lengths ($\Delta\ell \approx 0.12\text{--}0.15\,\mathrm{m}$).
* **Prediction 2 (Conduction Velocity Scaling Across Species and Development):** Across mammalian species with differing brain sizes $L_{\mathrm{cortex}}$ and myelination speeds $v_{\mathrm{ax}}$, as well as during infant myelination development, unified perceptual binding will emerge only once axonal myelination increases $v_{\mathrm{ax}}$ sufficiently for $v_{\mathrm{ax}} / (2\Gamma_{\mathrm{eff}})$ to span the thalamocortical loop.

---

## 7. Conclusion

By specializing the *Covariant Objective-Time Master Equation* to terrestrial neurobiological scales ($\zeta \approx 35$), **this paper** demonstrates that the temporal binding problem does not require exotic quantum-gravitational effects inside warm brain tissue, nor does it force us to treat conscious unity as an illusion inside a static block universe. Instead, a waking brain achieves unified interiority by expending metabolic energy to hold inter-areal phase-slip dissipation $\Gamma_{\mathrm{eff}}$ low enough that its **Cortical Operational Simultaneity Horizon $L_{\mathrm{sim}}^{\mathrm{cortex}}$** spans the thalamocortical network. Within that horizon ($D_{\mathrm{loc}} \to 1$), distributed neural assemblies lock into a single internal clock ($t_{\mathrm{pre}}$) and preserve diachronic identity ($A_s^v$). When anesthetic or physiological disruption shrinks $L_{\mathrm{sim}}^{\mathrm{cortex}}$ below $L_{\mathrm{cortex}}$, the unified subject dissolves back into uncoupled local oscillators—revealing how physical phase coherence and lived temporal interiority meet across a measurable operational boundary.

---

## References

1. von der Malsburg, C. (1981). *The Correlation Theory of Brain Function*. Internal Report 81-2, Max-Planck-Institute for Biophysical Chemistry, Göttingen.
2. Singer, W., & Gray, C. M. (1995). Visual feature integration and the temporal correlation hypothesis. *Annual Review of Neuroscience*, 18, 555–586.
3. Pimenta Damásio, L. (2026). *AEON-Tμν & Philosophy of Time: Master Compendium — Foundations of Temporal Metrology and Operational Quantum Mechanics (v2.0)*. Zenodo. https://doi.org/10.5281/zenodo.24190229
4. Pimenta Damásio, L. (2026). *AEON-Tμν & Philosophy of Time: Executive Manifesto and Front-Door Reader's Guide*. Zenodo Preprint.
5. Pimenta Damásio, L. (2026). *AEON-T14.html: Covariant Kerr–Newman QFTCS & Semiclassical Back-Reaction Computational Observatory*. Zenodo. https://doi.org/10.5281/zenodo.24244501
6. Buzsáki, G., & Draguhn, A. (2004). Neuronal oscillations in cortical networks. *Science*, 304(5679), 1926–1929.
7. Fries, P. (2015). Rhythms for cognition: communication through coherence. *Neuron*, 88(1), 220–235.
8. Mashour, G. A., & Hudetz, A. G. (2018). Neural correlates of unconsciousness in large-scale brain networks. *Trends in Neurosciences*, 41(3), 150–160.
9. Brown, E. N., Lydic, R., & Schiff, N. D. (2010). General anesthesia, sleep, and coma. *New England Journal of Medicine*, 363(27), 2638–2650.
10. Casali, A. G., Gosseries, O., Rosanova, M., et al. (2013). A theoretically based index of consciousness independent of sensory processing and behavior. *Science Translational Medicine*, 5(198), 198ra105.
11. Dehaene, S., & Changeux, J. P. (2011). Experimental and theoretical approaches to conscious processing. *Neuron*, 70(2), 200–227.
12. Tononi, G., Boly, M., Massimini, M., & Koch, C. (2016). Integrated information theory: from consciousness to its physical substrate. *Nature Reviews Neuroscience*, 17(7), 450–461.
13. Hameroff, S., & Penrose, R. (2014). Consciousness in the universe: A review of the 'Orch OR' theory. *Physics of Life Reviews*, 11(1), 39–78.
14. Varela, F., Lachaux, J. P., Rodriguez, E., & Martinerie, J. (2001). The brainweb: phase synchronization and large-scale integration. *Nature Reviews Neuroscience*, 2(4), 229–239.
15. Tegmark, M. (2000). Importance of quantum decoherence in brain processes. *Physical Review E*, 61(4), 4194–4206.
16. Engel, A. K., Fries, P., & Singer, W. (2001). Dynamic predictions: oscillations and synchrony in top-down processing. *Nature Reviews Neuroscience*, 2(10), 704–716.
