# ENVS-193DS_spring-2025_final

Final Exam for ENVS154, Spring 2025 Sanjana Sujeet

# Rendered output

You can find my rendered final at this [link](https://sanjanasujeet.github.io/ENVS-193DS_spring-2025_final/code/final_code)


# General Info

Repository is for my ENVS 193DS Final taken in Spring Quarter 2025 at UCSB with Prof. An Bui. The final covers analyzing and suggesting statistical elements, visualizing sea surface temperature, analyzing and re-visualizing a research paper's regression model on bird nest boxes, and finalizing thoughts on affective visualization. The data and papers' citations are: Citations for data: Kui, L. 2024. Daily sea surface temperature in Santa Barbara channel between 1982 and 2023 ver 3. Environmental Data Initiative. <https://doi.org/10.6073/pasta/e930954949b2635928b8be6824630f84>. Accessed 2025-06-08.

Stojanovic, Dejan et al. (2021). Do nest boxes breed the target species or its competitors? A case study of a critically endangered bird Dataset. Dryad. [https://doi.org/10.5061/dryad.83bk3j9sb\\](https://doi.org/10.5061/dryad.83bk3j9sb\){.uri} Accessed 2025-06-08.

The packages used are: 
```
library(tidyverse)
library(janitor)
library(dplyr)
library(here)
library(tibble)
library(lubridate)
library(MuMIn)
library(DHARMa)
library(ggplot2)
library(ggeffects)
```

# Data and File Structure
```
├── ENVS-193DS_workshop-08.Rproj
├── README.md
├── code                                     # code folder
│   └── final_code.Rmd                       # rmd with all code
└── data                                     # data folder
    └── occdist.csv                          # bird nest box data
    └── SST_update2023.csv                   # sea surface temp data
```
