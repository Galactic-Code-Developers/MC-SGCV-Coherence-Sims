# MC–SGCV Coherence Simulation Suite

Welcome to the central simulation repository for the **Multifaceted Coherence (MC)** and **Superluminal Graviton Condensate Vacuum (SGCV)** research initiative. This repository hosts all interactive notebooks, field simulations, exportable figures, and energy transformation visualizations developed as part of the 2025 MC–SGCV publication suite.

---

## 🧭 Project Goals

- Simulate coherence decay in observable quantum fields (ψₛ★)
- Track entropy growth and curvature evolution over time
- Visualize how energy redistributes into ghost coherence, vacuum noise, and geometric structure
- Validate hypotheses around directional irreversibility and partial recondensation

---

## 📁 Repository Structure

- `/notebooks/`: Contains 18 modular simulation notebooks, each with its own subdirectory and `README.md`
- `/figures/`: Output images and visualizations (modulus, phase, ghost, etc.)
- `/exports/`: MP4 animations and time series snapshots
- `/data/`: Saved NumPy or symbolic tensor arrays (optional)
- `/latex/`: LaTeX source for the paper with auto-included figures and citations

---

## 🔬 Notebooks by Phase

| Phase | Notebook | Purpose |
|-------|----------|---------|
| Core | `MC_SGCV_Coherence_Simulation.ipynb` | Central coherence decay and field evolution model |
| Phase 1 | `Phase1_DLSFH_Lattice_MC.ipynb` | Lattice initialization (dodecahedral/dynamic) |
| Phase 2 | `Phase2_MC_Tensor_Evolution.ipynb` | Tensor evolution: $\partial_t C_{\mu\nu}(x,t) = -\alpha \cdot S(x,t) \cdot C_{\mu\nu}(x,t) $ |
| Phase 3 | `Phase3_Physical_Scenarios_MC.ipynb` | Collapse scenarios: BH analogues, decoherence spikes |
| Phase 4 | `Phase4_HPC_MC_Sweeps.ipynb` | HPC-ready parameter sweeps |

Extended models include animated phase wrapping, SGCV-PsiStar conversion layers, and α-based entropy comparisons.

---

## 📖 Related Work

- Valamontes, A. (2025). *Converted ψₛ★ Energy and its Persistence in MC–SGCV Thermodynamic Models*.
- Markoulakis, E. (2024). *Superluminal Graviton Condensate Vacuum*.
- Planck Collaboration (2020), Penrose (2021), Einstein (1935)

---

## 📦 Installation

All notebooks are Google Colab compatible. To run locally:
```bash
pip install numpy matplotlib sympy
```

---

## 🔗 Contact

Developed by the Galactic Code Developers. For contributions or simulation extensions, contact: [galactic@coherence.dev](mailto:galactic@coherence.dev)
