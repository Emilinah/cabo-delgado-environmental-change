# Cabo Delgado environmental change

Version 0.1.0

In this project, we analyze the environmental changes due to green extractivism in Cabo Delgado province, Mozambique.


## Project organization

```
.
├── .gitignore
├── CITATION.md
├── LICENSE.md
├── README.md
├── requirements.txt
├── bin                <- Compiled and external code, ignored by git (PG)
│   └── external       <- Any external source code, ignored by git (RO)
├── config             <- Configuration files (HW)
├── data               <- All project data, ignored by git
│   ├── processed      <- The final, canonical data sets for modeling. (PG)
│   ├── raw            <- The original, immutable data dump. (RO)
│   └── temp           <- Intermediate data that has been transformed. (PG)
├── docs               <- Documentation notebook for users (HW)
│   ├── manuscript     <- Manuscript source, e.g., LaTeX, Markdown, etc. (HW)
│   └── reports        <- Other project reports and notebooks (e.g. Jupyter, .Rmd) (HW)
├── results
│   ├── figures        <- Figures for the manuscript or reports (PG)
│   └── output         <- Other output for the manuscript or reports (PG)
└── src                <- Source code for this project (HW)

```

## Project soft- and hard-ware dependencies

This is the soft- and hard-ware I used to write conduct this analysis.

### R programming language

R version 4.2.1 (2022-06-23 ucrt)
RStudio version 2021.09.1+372
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows 10 x64 (build 19042)

Matrix products: default

locale:
[1] LC_COLLATE=English_United States.1252  LC_CTYPE=English_United States.1252   
[3] LC_MONETARY=English_United States.1252 LC_NUMERIC=C                          
[5] LC_TIME=English_United States.1252    

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

loaded via a namespace (and not attached):
 [1] compiler_4.2.1   fastmap_1.1.0    rsconnect_0.8.24 htmltools_0.5.2  tools_4.2.1      yaml_2.2.1      
 [7] rmarkdown_2.14   knitr_1.39       xfun_0.31        digest_0.6.28    rlang_0.4.12     evaluate_0.15

All the packages above were either installed automatically when I downloaded R and RStudio, or were installed
when I installed packages from the CRAN and loaded them into RStudio. See here for details on how to do this:
https://support.rstudio.com/hc/en-us/articles/201057987-Quick-list-of-useful-R-packages 

### Others

ArcMap version 10.8.1

## Raw data sources

All the Landsat images were downloaded from the USGS Earth Explorer website: https://earthexplorer.usgs.gov/. 
The path and row names were: Balama (xx), Ancuabe (xx), and Palma (xx). The QA_PIXEL bands were decoded in arcgis, 
using the decode QA tool from the landsat-qa-arcgis-toolbox v.1.5.1, downloaded from earth explorer:
https://www.usgs.gov/landsat-missions/landsat-quality-assessment-arcgis-toolbox.

Users without administrative boundary data can use open access data from the 
GRID3 DATA HUB: https://data.grid3.org/

Mine areas can be constructed from the gps coordinates of the mine concession areas from the Mozambique Mining
Cadastre Map Portal: https://portals.landfolio.com/mozambique/en/

## License

This project is licensed under the terms of the [CC-BY-4.0](/LICENSE.md)

## Citation

Please [cite this project as Emilinah Namaganda(2022), Cabo Delgado environmental change - version 0.1.0. url:github.com/Emilinah/cabo-delgado-environmental-change](/CITATION.md).

## Contact

To get in touch about this project or a related topic, contact Emilinah Namaganda at e.namaganda@uu.nl