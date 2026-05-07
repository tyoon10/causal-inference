# Causal Inference Study Guide

Interactive study module for the Causal Inference course at Columbia Engineering, covering both the mid-term (L1–L6) and final exam (L7–L11).

## [Open the Study Guide](https://tyoon10.github.io/causal-inference/)

## [View the Chat Session](https://tyoon10.github.io/causal-inference/chat.html)

## What's Inside

A self-contained HTML application with interactive visualizations covering:

**Mid-term (L1–L6):**
- **Potential Outcomes Framework** — counterfactuals, ATE/ATT/ATC, naive estimator bias
- **Causal Graphs** — chains, forks, colliders, d-separation, back-door criterion
- **Matching Methods** — exact, nearest-neighbor (Mahalanobis), propensity score matching
- **Inverse Propensity Weighting** — surprising units intuition, algebraic equivalence to BDA
- **Regression & BDA** — OLS for causal inference, predict-and-average, extrapolation danger
- **Double ML** — residualization, cross-fitting, R-learner for heterogeneous effects
- **Sensitivity Analysis** — breakdown point, robustness to unmeasured confounders

**Final exam (L7–L11):**
- **Instrumental Variables** — Wald/2SLS, exclusion restriction (graphical + contaminated), weak instruments, LATE on compliers
- **Front-Door Criterion** — three graph conditions, FDC adjustment formula, per-mechanism shortcut
- **Regression Discontinuity** — sharp & fuzzy designs, local linear regression, density check
- **Difference-in-Differences** — parallel trends, ATT, time-varying controls
- **Interrupted Time Series** — counterfactual extrapolation, robustness checks
- **Panel Designs & MC-NNM** — matrix completion via nuclear-norm minimization, staggered adoption
- **Selection Bias Adjustment** — post-stratification, IPSW, time-series s-bias
- **Estimand Selection** — statistical vs causal, three red flags, 2×2 adjustment grid
- **Situational Drills** — seven worked business cases mapping decisions to identification strategies

## Features

- Interactive canvas visualizations (propensity score overlap, PS sufficiency, IPW vs BDA, breakdown point, IV path decomposition, A/B time-varying effects, RD bandwidth, DID violations, matrix completion, regime shift)
- KaTeX-rendered math formulas
- Expandable concept cards with tags (strengths, weaknesses, assumptions)
- Practice problems with reveal/hide answers
- Fully self-contained — no build step, no dependencies, just open the HTML file

## Usage

Open `index.html` in any modern browser, or visit the [GitHub Pages deployment](https://tyoon10.github.io/causal-inference/).

## License

MIT
