This repository contains code for the analyses reported in the following manuscript:

**Mindful attention to alcohol can reduce cravings in the moment and consumption in daily life**

## Compiled analysis files

The main and supplementary analyses from fMRI task are reported [here](https://cnlab.github.io/shine-mindfulness-mvpa/code/analysis_task).

The main and supplementary analyses from the EMA intervention are reported [here](https://cnlab.github.io/shine-mindfulness-mvpa/code/analysis_ema).

## Analysis reproduction

To reproduce the analyses in the manuscript, first execute the study cleaning script `clean_data.Rmd`, then the analysis scripts (`analysis_task.Rmd`, `analysis_ema.Rmd`). Given that raw data is required to run the cleaning and prep scripts, people outside the research team will only be able to reproduce the analysis scripts.

## Directory structure

* `code` = R code for cleaning and running the analyses reported in the manuscript and supplementary material
* `data` = text files containing the data

```
├── code
│   ├── analysis_ema.Rmd
│   ├── analysis_ema.html
│   ├── analysis_task.Rmd
│   ├── analysis_task.html
│   ├── clean_data.Rmd
│   ├── code.Rproj
│   ├── demographics.Rmd
│   ├── demographics.html
│   ├── mvpa.ipynb
│   ├── mvpa_holdout.Rmd
│   ├── mvpa_holdout.html
│   └── weight_map.png
└── data
    ├── classifier_data.csv
    ├── disaggregated_data.csv
    ├── ema.csv
    ├── ratings.csv
    └── task_neuro_data.csv
```
