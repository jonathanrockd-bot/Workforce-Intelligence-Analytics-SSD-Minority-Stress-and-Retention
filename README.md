# Predictive Workforce Intelligence: Minority Stress & Retention Modeling
**Target Cohort: Homosexual Males in STEM**

## Executive ROI & Strategic Impact
This repository serves as a technical proof-of-concept for bridging Industrial-Organizational (I-O) Psychology with predictive People Analytics. By focusing on the specific stressors faced by **Homosexual Males in STEM**, this analytical engine enables organizations to:

* **Forecast Attrition Risk:** Move from descriptive "historical" turnover reporting to a 12-month predictive risk forecast using Monte Carlo simulations.
* **Identify Moderating Buffers:** Quantitatively demonstrate how "Psychological Safety" and "Self-Disclosure" act as primary buffers to mitigate the negative impact of minority stress on retention.
* **Optimize Human Capital P&L:** Identify high-risk turnover zones to enable targeted interventions, preserving the high cost of replacement for specialized STEM roles.

## Technical Architecture
* **Core Language:** Python 3.10+
* **Analytical Stack:** NumPy, Pandas, Scikit-learn
* **Statistical Logic:** Multiple Linear Regression integrated with a 10,000-iteration Monte Carlo Simulation.
* **Visualization:** High-fidelity 3D Surface Plots (via Plotly) to visualize the interaction between stressors and retention.

## Methodology
The model utilizes synthetic data representative of psychometric assessments measuring:
1. **Minority Stress:** The independent variable/stressor.
2. **Psychological Safety:** The moderator.
3. **Self-Disclosure:** The secondary moderator.
4. **Retention Probability:** The dependent variable/outcome.

## How to Deploy
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Execute `analysis.py` to generate the predictive model and interactive visualizations.
