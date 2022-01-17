<h1 align="center">
  <br>
    SASC:  A Simple Approach to Synthetic Cohort Generation
    <br>
   <a href="https://github.com/Fraunhofer-ITMP/SASC/actions/workflows/repo2docker.yml">
    <img src="https://github.com/Fraunhofer-ITMP/SASC/workflows/repo2docker/badge.svg"
         alt="GitHub Actions">
  </a>
  <a href="https://mybinder.org/v2/gh/Fraunhofer-ITMP/SASC/main?urlpath=shiny/">
    <img src="https://mybinder.org/badge_logo.svg" alt="SASC Shiny App">
  </a>
  <br>
</h1>

<p align="center">
<a href="https://github.com/HAIRLAB/Pre_Surv_COVID_19/tree/master/data"> Public COVID-19 reference data </a> have been used for the following Shiny App to generate synthetic data via the SASC algorithm. Here, a comparison through the Kaplan-Meier plots is provided so that the parameters chosen for the virtual cohort can be checked against the real-world data.
</p>


## Details about the App
- **Data** - *PreSurv* data can be found [here](https://github.com/HAIRLAB/Pre_Surv_COVID_19/tree/master/data)
- **Shiny App** - Click the binder icon on the top to run the current SASC version application.
- **Packages used** - 
    1. *shiny* version 1.6.0
    2. [*tidyverse*](https://doi.org/10.21105/joss.01686)
    3. [*survival*](https://github.com/therneau/survival)
    4. [*survminer*](https://github.com/kassambara/survminer/)
    5. [*corrr*](https://github.com/tidymodels/corrr)
    6. [*reshape2*](https://github.com/hadley/reshape)
    7. [*ggforce*](https://github.com/thomasp85/ggforce)
    8. [*gridExtra*](https://cran.r-project.org/web/packages/gridExtra/index.html)
    9. [*lubridate*](https://github.com/tidyverse/lubridate) 

<b>TO NOTE: The app is heavy on server side, and it can be slow - be patient.</b> 

## What do you see in the app?
In the app, one can compare the Kaplan-Meier plots for each parameter (found in the cohort) for the virtual cohort and real-world data


## Issues
If you have difficulties using the app, please open an issue at our bug-tracker on [GitHub](https://github.com/Fraunhofer-ITMP/SASC/issues).


## Disclaimer
SASC is a scientific application that has been developed in an academic capacity and thus comes with no warranty or guarantee of maintenance, support, or back-up of data.
