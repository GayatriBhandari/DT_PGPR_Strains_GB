
##links yo analysis
#Output of 

list.files("data")
read.csv("data/datapbu.csv")

#DOI Link: https://doi.org/10.5281/zenodo.18692014

#File tree
library(fs)


df <- read.csv("data/datapbu.csv")
head(df)

list.files(recursive = TRUE)
dir_tree(".")

fs: :dir_tree("")

.
├── data
│   └── datapbu.csv
├── Dummy.Rproj
├── README_dummy.html
└── README_dummy.md


dir.create("data/raw", recursive = TRUE)
dir.create("data/processed", recursive = TRUE)

file.rename("data/datapbu.csv", "data/raw/datapbu.csv")

