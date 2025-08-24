---
title: "Global Methane Emissions - Year 2019, 0.1 degree resolution"
collection: code_and_data
date: 8 Aug 2025
---

**Dataset**    
Data: a_summary_emission_ensemble_201805_201910.nc
Contact: Xueying Yu (xyu2@albany.edu); Dylan Millet (dbm@umn.edu)

**Description**
This dataset provides global methane emission estimates derived from TROPOMI satellite-based methane observations using a Bayesian 4D-Var inversion in the GEOS-Chem adjoint model.
Spatial resolution: 0.1° × 0.1°
Temporal resolution: monthly
Time period: May 2018 – October 2019

Variables
prior: Prior emission estimates
opt_sf: Emission scaling factors from SF inversion
opt_bg: Emission scaling factors from BG inversion
opt_ig: Emission scaling factors from IG inversion
opt_eh: Emission scaling factors from EH inversion
num_obs: Number of observations used in the inversions

Recommendation
For analysis, we recommend using the optimized emission ensemble mean: prior * (opt_sf + opt_bg + opt_ig + opt_eh)/4

**[Download](https://github.com/yu-xue-ying/data/tree/main/1_methane_emissions)**

**Citation**
Yu, X., Millet, D. B., Henze, D. K., Turner, A. J., Delgado, A. L., Bloom, A. A., and Sheng, J.: A high-resolution satellite-based map of global methane emissions reveals missing wetland, fossil fuel, and monsoon sources, Atmos. Chem. Phys., 23, 3325–3346, https://doi.org/10.5194/acp-23-3325-2023, 2023.
https://acp.copernicus.org/articles/23/3325/2023
