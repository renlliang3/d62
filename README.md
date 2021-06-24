# Dynamic Circumstellar Debris around an SNIa Runaway

This repository contains the analysis code for Chandra et al (2021, in prep). All the code used to generate plots and simulations for the paper is contained here in Jupyter notebooks. Several data files are too large to host on GitHub or are under proprietary access. Don't hesitate to reach out to the corresponding author if you have any questions, or would like any additional data. 

The main code is stored in notebooks labelled 01-07. Auxilliary analysis is written in notebooks labelled 99. Main output plots can be found in the fig/ directory. The primary analysis is organized as follows:
```
01_sed: SED fitting of the stellar model and IR excess. 
02_cmd_hypervelocity: CMD plots and Gaia EDR3 kinematics. 
03_wise_lc_pm: WISE light curve analysis and WISE astrometry. 
04_hipercam_lc: Optical light curve from HiPERCAM, fitting extinction curves. 
05_apo_spec: Optical spectrum from Apache Point 3.5m, compared to atmospheric model spectra. 
06_rebound_dynamics: Numerical simulations of circumbinary planets. 
07_analytic_calculations: E.g., the total dust mass. 
```
All Python libraries that are used in this analysis are listed in the ``requirements.txt`` file. 
