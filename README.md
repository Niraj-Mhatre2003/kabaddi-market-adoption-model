# Modeling the Likelihood of Kabaddi Adoption Across Countries

This repository presents a structured probabilistic framework to model the likelihood
that Kabaddi will successfully adopt in a new country.

The approach treats adoption as a **latent variable** and combines:
- Pre-entry country-level indicators
- Hierarchical Bayesian modeling
- Post-entry time-series and stochastic dynamics
- Sequential Bayesian updating

The framework is designed for **strategic decision-making**, **risk management**,
and **phased investment planning** in sports market expansion.

---

## Problem Motivation

Kabaddi has achieved strong popularity in some countries while failing to gain traction
in others. Investors, league operators, and sports federations require a systematic,
data-driven method to:

- Estimate adoption potential before market entry
- Adapt strategies after launch
- Monitor adoption strength over time
- Reduce uncertainty in early-stage investments

---

## Methodology Overview

### 1. Pre-Entry Modeling
- Country-level features:
  - Cultural compatibility
  - Economic capacity
  - Media and digital readiness
  - Institutional support
  - Demographic and social indicators
- Logistic regression with Bayesian priors
- Regional random effects

### 2. Hierarchical Bayesian Structure
- Country-specific feature sensitivities
- Partial pooling across similar markets
- Reduced overfitting and improved uncertainty estimates

### 3. Post-Entry Adaptive Learning
- Latent adoption dynamics modeled as a stochastic process
- State-space models (Kalman / particle filtering)
- Noisy observation modeling from real adoption signals

### 4. Bayesian Updating
- Continuous belief updates as new data arrives
- Dynamic estimation of sustained adoption probability

---

## Repository Structure
kabaddi-adoption-model/
├── README.md
├── LICENSE
├── paper/
│   ├── kabaddi-adoption-model.tex
│   └── kabaddi-adoption-model.pdf

---

## Author

**Niraj Mhatre**

---


