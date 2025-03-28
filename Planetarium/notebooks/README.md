# Core

This is the **core simulation** of the MC–SGCV framework. It models the time evolution of the coherence field ψₛ★ and its energetic decay across a 2D spacetime lattice.

## Highlights

- Tracks the modulus of ψₛ★ as entropy grows
- Simulates directional coherence loss:

  $\partial_t C_{\mu\nu}(x,t) < 0$

- Introduces entropy spikes and curvature feedback
- Outputs ghost coherence, vacuum noise, and geometric curvature gain

## Purpose

This notebook forms the backbone of the MC–SGCV project, illustrating how coherence fades yet transforms across space and time. It directly supports the visual outputs and mathematical structure in the 2025 paper.

## Outputs

- MP4 animations of ψₛ★ decay
- PNG snapshots of key field states

# Phase1 DLSFH Lattice MC

**Phase 1**: Initializes a structured lattice using principles from the Dodecahedral Linear String Field Hypothesis (DLSFH). This lattice seeds the initial geometry for ψₛ★ coherence evolution.

## Highlights

- Uses dodecahedral-inspired symmetry
- Sets up curvature ($R{\mu\nu}$) and coherence ($C_{\mu\nu}$) fields
- Serves as the geometric substrate for all downstream simulations

## Purpose

Builds a metaphysical and topological starting point that reflects symmetry considerations in the MC–SGCV–DLSFH hybrid framework.

## Outputs

- Initial 2D lattice field arrays
- Static curvature map $R_{field}$

# Phase2 MC Tensor Evolution

**Phase 2** simulates the evolution of the coherence tensor ($C_{\mu\nu}(x,t)$) under directional entropy growth ($\S(x,t)$), in alignment with the MC model.

## Highlights

- Evolves Cμν over time using:

  $\partial_t C_{\mu\nu}(x,t) = -\alpha \cdot S(x,t) \cdot C_{\mu\nu}(x,t)$

- Dynamically updates the entropy field with nonlinear feedback
- Tracks coherence collapse and its spatial signature

## Purpose

Establishes time evolution equations and prepares Cμν snapshots for later integration with energy transformation models.

## Outputs

- Tensor field slices of $C_{\mu\nu}$
- Entropy-coherence coupling diagnostics

