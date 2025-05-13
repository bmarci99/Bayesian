# Bayesian_Project

A full-stack Bayesian modeling project focused on predicting weekly ozone concentration levels across multiple geographic stations in Italy. The pipeline includes:

- 🧼 **Exploratory Data Analysis (EDA)**: Preprocessing and correlation analysis of meteorological features with ozone levels.
- 🌍 **Spatio-temporal modeling**: Hierarchical model with geospatial priors and temporal dependencies implemented in STAN.
- 📦 **Stan Integration**: Custom `cmdstanpy` pipeline for fitting, saving, and summarizing posterior samples.
- 📊 **Diagnostics & Visualization**: ArviZ summaries, geospatial maps, posterior predictive checks.

### 📁 Main Files
- `EDA.ipynb` – initial data exploration and visual analysis
- `Modeling.ipynb` – Bayesian model specification and CmdStan execution
- `OpenStan_Fit_summary_Files.ipynb` – posterior analysis and model evaluation
- `stan/spt_lm.stan` – full model definition in STAN
- `helper_functions.py` – modular helpers for transformation and metric computation

### 📦 Tools & Libraries
`Python`, `pandas`, `matplotlib`, `seaborn`, `CmdStanPy`, `ArviZ`, `PyStan`, `Cartopy`, `Stan`, `GeoPandas`

---

📍 *Note: Raw data was sourced from public meteorological APIs and is accessed via GitHub-hosted CSVs (proprietary data).*
