## Bayesian Mixed Media Modeling (MMM)

This project demonstrates the use of a Bayesian mixed-media modeling approach to estimate and interpret the delayed impact of multi-channel marketing spend on weekly revenue. The analysis is performed using the latest [PyMC](https://www.pymc.io/) probabilistic programming framework.

### Objective

Model the relationship between advertising spend across seven paid marketing channels and weekly revenue using a Bayesian framework. Capture delayed marketing effects via adstock modeling, and incorporate uncertainty, trend, and optional seasonality in a principled probabilistic way.

### Data

The dataset contains:
- Weekly revenue data
- Weekly spend on seven marketing channels
- Time index (start of week)

### Key Modeling Features

- **Adstock transformation** to model carry-over effects of media spend
- **Bayesian linear regression** using PyMC
- Optional inclusion of **trend and seasonality components**
- ROI (Return on Investment) estimates with uncertainty
- Prior and posterior predictive checks
- Model fit evaluation via posterior predictive checks and WAIC

### Tools & Libraries

- Python
- PyMC
- Arviz
- pandas, numpy, matplotlib, seaborn

### Outputs

- Channel effectiveness estimates
- ROI per channel
- Posterior credible intervals for marketing impact
- Adstock-adjusted spend curves

---

*This project is designed as a practical demonstration of applying Bayesian inference to a real-world MMM setting. It emphasizes interpretability, uncertainty quantification, and temporal structure common in marketing data.*
