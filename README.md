# PGPR_mortality

# Reproducible Analysis of In-vitro Mortality Assay Data on the Impact of Plant Growth Promoting Rhizobacteria (PGPR) strains on Meloidogyne incognita Second Stage Juveniles (J2s) Mortality

## Data Source and Description of PGPR
The dataset for this project comes from an in vitro mortality assay, which evaluates the effect of PGPR strains on the mortality of *Meloidogyne incognita* second stage juvenile(J2) and has Untreated control(tap water),and positive control(Fluopyram)).  The data were collected in a controlled laboratory experiment at Auburn University. Each strain was tested in four replicates to assess its nematicidal activity at 48 hours.

## Data Analysis Plan
- All data processing and analysis are conducted in R using a reproducible pipeline. The analysis includes:

- Data cleaning and visualization using the tidyverse (e.g., dplyr, ggplot2)

- Exploratory Data Analysis (EDA) including summary statistics and mortality trend visualizations

- Statistical modeling using Generalized Linear Mixed Models (GLMM) with the lme4 package to evaluate the effect of bacterial strain on nematode mortality

- Post hoc mean separation with emmeans to identify significantly different strain effects

*All figures are generated to be manuscript-ready using ggplot2.*


## Reproducible Workflow
- Version control using Git and GitHub to track all code and file changes

- R Markdown used to document code, analysis, and interpretation in an executable format

- Relative paths used throughout to ensure consistent file referencing

- Scripted data pipeline to automate data cleaning, analysis, and figure generation

- README documentation and final scripts made public in this repository for reproducibility and reuse


## File tree


├── data
│   └── Mortality.csv
├── DT_PGPR__GB.html
├── Dummy.Rproj
├── FinalProject_PGPR.html
├── FinalProject_PGPR.pdf
├── FinalProject_PGPR.Rmd
├── FinalProject_PGPR_files
│   ├── figure-html
│   └── figure-latex
├── README_dummy.md
└── Renv_dummy.R

## Folder Structure

- `data/Mortality.csv`: Raw mortality data
- invitr0_mortality.Rmd`: Reproducible R Markdown script
- `figs/mortality_barplot.png`: Manuscript-quality figure
- `PGPR_Mortality.Rproj`: R project file

##  Software Requirements

- R version ≥ 4.3
- RStudio
- Required libraries: `tidyverse`, `lme4`, `lmerTest`, `emmeans`, `multcomp`, `multcompView`, `ggplot2`,`fs`






