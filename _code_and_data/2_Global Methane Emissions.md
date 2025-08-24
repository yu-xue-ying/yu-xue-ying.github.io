---
title: "Global Methane Emissions - Year 2019, 0.1 degree resolution"
collection: code_and_data
date: 8 Aug 2025
---

**Dataset**<br>
Data: a_summary_emission_ensemble_201805_201910.nc<br>
Contact: Xueying Yu (xyu2@albany.edu); Dylan Millet (dbm@umn.edu)<br>

**Description**<br>
This dataset provides global methane emission estimates derived from TROPOMI satellite-based methane observations using a Bayesian 4D-Var inversion in the GEOS-Chem adjoint model.<br>
Spatial resolution: 0.1° × 0.1°<br>
Temporal resolution: monthly<br>
Time period: May 2018 – October 2019<br>

Variables<br>
prior: Prior emission estimates<br>
opt_sf: Emission scaling factors from SF inversion<br>
opt_bg: Emission scaling factors from BG inversion<br>
opt_ig: Emission scaling factors from IG inversion<br>
opt_eh: Emission scaling factors from EH inversion<br>
num_obs: Number of observations used in the inversions<br>

Recommendation<br>
For analysis, we recommend using the optimized emission ensemble mean: prior * (opt_sf + opt_bg + opt_ig + opt_eh)/4<br>

**[Download](https://github.com/yu-xue-ying/data/tree/main/1_methane_emissions)**

**Citation**<br>
Yu, X., Millet, D. B., Henze, D. K., Turner, A. J., Delgado, A. L., Bloom, A. A., and Sheng, J.: A high-resolution satellite-based map of global methane emissions reveals missing wetland, fossil fuel, and monsoon sources, Atmos. Chem. Phys., 23, 3325–3346, https://doi.org/10.5194/acp-23-3325-2023, 2023.<br>
[Available Here](https://acp.copernicus.org/articles/23/3325/2023)
