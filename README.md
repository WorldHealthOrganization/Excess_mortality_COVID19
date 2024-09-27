# R scripts for estimating WHO excess mortality associated with the COVID-19 pandemic

This repository contains R scripts designed to estimate excess mortality associated with the COVID-19 pandemic over 2020-2022. Specifically, it includes scripts that:
* predict expected mortality estimates, e.g. the estimated all-cause mortality that would have been expected if the COVID-19 pandemic had not occurred;
* predict observed mortality estimates, e.g. the estimated all-cause mortality that have occured during the COVID-19 pandemic.
* calculate and refine excess mortality estimates, taking into account mortality from other shocks unrelated to the COVID-19 pandemic for certain countries.

For more details, please refer to the WHO Methods Document available at: https://www.who.int/data/sets/global-excess-deaths-associated-with-covid-19-modelled-estimates *(2)*.

## Dependencies 
R version 3.6.3 and the following R packages: "tidyverse", "posterior", "INLA", "zoo", "readxl", "cmdstanr", "gridExtra", "mgcv", "matrixStats". 

IMPORTANT: The INLA package should be installed as the testing (not stable) branch version 22.05.03, with instructions available at: https://www.r-inla.org/download-install.

## Directories 
* **Expected/** contains R scripts for predicting expected mortality estimates for each year and age/sex categories over 2020-2022, on the basis of pre-pandemic 2000-2019 estimated death counts from *WHO Global Health Estimates*. Please refer to the Section 4 of the Methods document for more details.
* **Observed/** contains R scripts for predicting observed mortality estimates for countries with and without reported data for each year and age/sex categories over 2020-2022. Please refer to the Section 5 of the Methods document for more details.
* **Excess/** contains R scripts for calculating the final excess mortality estimates. Please refer to the Section 2 of the Methods document for more details.

## Workflow 

### Expected
* xx
* xx
### Observed
* Xx
* xx
### Excess
* Xx
* xx
    
## Contact
For any enquiries, please contact : healthstat@who.int

## Main contributors
Victoria Knutson (University of Washington) and Nelly Biondi (WHO) under the guidance of Jonathan Wakefield (University of Washington) and Haidong Wang (WHO), with valuable input from Ariel Karlinsky (Hebrew University of Jerusalem), Enrique Acosta and Jonas Schöley (Max Planck Institute for Demographic Research), William Msemburi (Bill and Melinda Gates Foundation), Serge Aleshin-Guendel (U.S. Census Bureau), Bochen Cao and Doris Ma Fat (WHO), Patrick Gerland (UN DESA) and Lucia Hug (UNICEF).

## References
* *(1)*	WHO Global excess mortality estimates : https://www.who.int/data/sets/global-excess-deaths-associated-with-covid-19-modelled-estimates
* *(2)*	WHO Global Health Estimates : https://www.who.int/data/global-health-estimates
