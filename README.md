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
### Software requirements

R version 4.2.1
RStudio version 2021.09.1+372
ArcMap version 10.8.1

### Raw data sources

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