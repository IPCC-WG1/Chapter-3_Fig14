DETECTION AND ATTRIBUTION ANALYIS OF TROPICAL PRECIPITATION
===========================================================
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6778068.svg)](https://doi.org/10.5281/zenodo.6778068)

Figure number: Figure 3.14
From the IPCC Working Group I Contribution to the Sixth Assessment Report: Chapter 3

![Figure 3.14](ar6_wg1_chap3_figure3_14_precip_wetdry.png?raw=true)


Description:
------------
Wet (a) and dry (b) region tropical mean (30°S-30°N) annual precipitation 
anomalies. Observed data are shown with black lines (GPCP), ERA5 reanalysis in 
grey, single model simulations results are shown with light blue/red lines 
(CMIP6), and multi-model-mean results are shown with dark blue/red lines 
(CMIP6). Wet and dry region annual anomalies are calculated as the running mean 
over 12 months relative to a 1988-2020 based period. The regions are defined as 
the wettest third and driest third of the surface area, calculated for the 
observations and for each model separately for each season (following Polson and 
Hegerl, 2017). Scaling factors (panels c,d) are calculated for the combination 
of the wet and dry region mean, where the observations, reanalysis and all the 
model simulations are first standardised using the mean standard deviation of 
the pre-industrial control simulations. Two total least squares regression 
methods are used: noise in variables (following Polson and Hegerl, 2017) which 
estimates a best estimate and a 5-95% confidence interval using the 
pre-industrial controls (circle and thick green line) and the pre-industrial 
controls with double the variance (thin green line); and a bootstrap method 
(DelSole et al., 2019) (5-95% confidence interval shown with a purple line and 
best estimate with a purple circle). Panel (c) shows results for GPCP and panel 
(d) for ERA5. Figure is adapted from Schurer et al. (2020).


Author list:
------------
- Schurer, A.: University of Edinburgh, UK; A.Schurer@ed.ac.uk
- Kazeroni, R.: DLR, Germany


Publication sources:
--------------------
Schurer, A. P., Hegerl, G. C., Ballinger, A., and Friedman, A. R. (2020). Human 
influence strengthens the contrast between tropical wet and dry regions. 
Environ. Res. Lett. 15. doi:https://doi.org10.1088/1748-9326/ab83ab.


ESMValTool Branch:
------------------
- ESMValTool-AR6-OriginalCode-FinalFigures: [ar6_chapter_3](https://github.com/ipcc-wgi/ESMValTool-AR6-OriginalCode-FinalFigures/tree/ar6_chapter_3)


ESMValCore Branch:
------------------
- ESMValCore-AR6-OriginalCode-FinalFigures: [fix_cmip6_models_newcore](https://github.com/ipcc-wgi/ESMValCore-AR6-OriginalCode-FinalFigures/tree/fix_cmip6_models_newcore)


Recipe & diagnostics:
---------------------
Recipe used: [recipes/ipccwg1ar6ch3/recipe_ipccwg1ar6ch3_wetdry_schurer2020.yml](https://github.com/ipcc-wgi/ESMValTool-AR6-OriginalCode-FinalFigures/blob/ar6_chapter_3/esmvaltool/recipes/ipccwg1ar6ch3/recipe_ipccwg1ar6ch3_wetdry_schurer2020.yml)

Diagnostic used: [diag_scripts/aschurer/WetDry_timeseries_smooth_scaling1.py](https://github.com/ipcc-wgi/ESMValTool-AR6-OriginalCode-FinalFigures/blob/ar6_chapter_3/esmvaltool/diag_scripts/aschurer/WetDry_timeseries_smooth_scaling1.py)


Expected image path:
--------------------
This is the path of the image relative to the automatically generated ESMValTool output location:
- recipe_wetdry_newextendedv2_YYYYMMDD_HHMMSS/plots/schurer20_figs/script1/WetDry_timeseries_scalefactors.png


Software description:
---------------------
- ESMValTool environment file: [IPCC_environments/ar6_newcore_remi_conda_environment.yml](https://github.com/ipcc-wgi/ESMValTool-AR6-OriginalCode-FinalFigures/blob/main/IPCC_environments/ar6_newcore_remi_conda_environment.yml)
- pip file: [IPCC_environments/ar6_newcore_remi_pip_environment.txt](https://github.com/ipcc-wgi/ESMValTool-AR6-OriginalCode-FinalFigures/blob/main/IPCC_environments/ar6_newcore_remi_pip_environment.txt)


Hardware description:
---------------------
Machine used: Mistral
