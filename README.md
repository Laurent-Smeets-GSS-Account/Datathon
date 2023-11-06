# Code Documentation UN Datathon 


## Introduction

This repository hold all the data, code and scripts our team used to create the analyses, maps, visualizations and tools shown on this story map: https://storymaps.arcgis.com/stories/d42e912c2bf448238423fd6708a578fc. The goal of this project is to show that:
  1) To show that there is simply not enough data available at the local level, especially within African Countries
  2) To show that data science, big data and non-traditional data sources can be used (when combined the 2020-round of Census data), can be used as proxy for the estimation  SDG goals and to measure our novel Access to Information Index
  3) show that the people who need the data most are also least likely to have access to it.


## How to Use
  - All R and bin/bash scripts sit in the quarto file `documentation.qmd` and is type-setted in `documentation.html`.
  - The folder `data/` holds the raw input data (unless file sizes were too big to be included in github)
  - The folder `output_files/` holds the output files we use in the analyses (unless file sizes were too big to be included in github)
  - The folder `osrm_files/` holds all the files needed to start an OSRM server in Docker (https://hub.docker.com/r/osrm/osrm-backend/)
  -  The folder `Geo FIles/` holds the Ghana Shapefiles we used (downloadable from https://statsbank.statsghana.gov.gh/)
  -  The folder `Shiny_AII_app/` holds the code for the Shiny App we used to let user weight their personal AII. 
  
## Ghana Statistical Service Data Science Team
  - Laurent Smeets: Data Science Lead
  - Femke van den Bos: Econometrician and Data Scientist
  - Ahmed Salim Adam: Programmer (Software Engineer) 
  - Simon Tichutab Onilimor: Data Scientist 
  - Peter Yeltulme Mwinlaaru: Data Scientist

## 🛠 Tools
R, AWS, Excel, Shiny, Docker, OSRM, Google Big Query, Midjourney 


## 🔗 Data

2021 Population and Housing Census, OpenStreetMap, nightlight satellite data, high-resolution population data



## License

[MIT](https://choosealicense.com/licenses/mit/)

