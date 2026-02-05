# Modeling the Success of Kabaddi in New Countries

This repository contains my submission for **Problem 4: Why Does Kabaddi Succeed in Some Countries and Not Others?**, part of the Trosmic Sports analytical modeling assessment.

The objective of this work is to develop a principled, probabilistic framework for evaluating whether Kabaddi is likely to achieve sustained adoption in a new country and how that likelihood evolves after market entry.

---

## Problem Context

Kabaddi has demonstrated strong institutional success in certain regions while failing to gain long-term traction in others. These differences arise from a combination of cultural compatibility, economic capacity, infrastructure readiness, and post-entry engagement dynamics.

The challenge is to model this uncertainty in a way that supports strategic decision-making under limited and noisy data.

---

## Modeling Approach

The proposed framework treats Kabaddi adoption as a **latent process** rather than a directly observable outcome.

Key characteristics of the model:

- **Latent adoption strength** inferred from observable engagement signals
- **Hierarchical Bayesian structure** to capture cross-country heterogeneity
- **Dynamic evolution** of adoption after entry
- **Explicit uncertainty modeling** suitable for early-stage decisions
- **Interpretability**, enabling strategic insights rather than black-box predictions

The model is intentionally designed to be data-efficient and extensible as richer longitudinal data becomes available.

---

## Repository Structure

- `paper/`  
  Contains the compiled PDF of the analytical write-up.

- `latex/`  
  LaTeX source files used to generate the paper.

- `notes/`  
  Conceptual extensions and future research directions.

- `assets/`  
  (Optional) Figures or diagrams used in the paper.

---

## Key Assumptions

- Success is defined as **sustained adoption** rather than short-term popularity.
- Early-stage data is sparse and noisy, requiring probabilistic reasoning.
- Countries share structural similarities but remain heterogeneous.

---

## Extensions and Future Work

Possible extensions of the framework include:
- Non-linear state-space models for adoption dynamics
- Gaussian process trajectories for long-term uncertainty modeling
- Regime-switching models to capture adoption phases
- Causal inference for evaluating intervention strategies

These extensions are outlined conceptually in the `notes/` directory.

---

## Author

**Niraj Mhatre**

This work is intended as a research-oriented modeling exercise and is designed to serve as a foundation for deeper empirical analysis.

