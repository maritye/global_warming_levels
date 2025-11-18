# global_warming_levels
Identify 20 year climate periods when 2GWL and 3GWL are reached in CMIP5 and CMIP6 models used for NA-CORDEX

## Background
The American Society of Civil Engineers (ASCE) Structural Engineering Institute (SEI) has decided to consider a future global warming level (GWL) of 3°C for structures whose design life will end in 2080-2100, referred to as 3GWL. GWL is considered to be the increase in global mean surface air temperature above the pre-industrial (1850-1900) mean.

This repository accompanies an NSF NCAR Technical Note "Evaluating the time of occurrence of selected global warming levels for CMIP5 and CMIP6 models" (2025) by Mari R. Tye, Rachel R. McCrary, Jacob Stuivenvolt-Allen, Ahmed Abdelaal and Abbie Liel. The technical note documents the methodology used to estimate changes in global mean temperature to enable others to reproduce these results for other models. It also presents the estimates of when specific thresholds will be crossed by different models/ensemble members/emissions scenarios in the North American Coordinated Downscaling Experiment (NA-CORDEX) for reference by ASCE design code developers.

## Contents
This repository contains:
* .csv of the start/end of the climatological periods for 2GWL and 3GWL for each model, ensemble member and emissions scenario
* Jupyter notebooks to reproduce figures in the technical notes
* NCL scripts to produce global mean temperature time series for each model, ensemble member and emissions scenario
* Individual global mean temperature time series for NA-CORDEX-CMIP5 models and all CMIP6 models available in the NSF NCAR archives
