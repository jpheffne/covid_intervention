# covid_intervention
Behavioral data and analysis script for "Emotional responses to prosocial messages increase willingness to self-isolate during the COVID-19 pandemic"

The preprint can be found on PsyArxiv: [https://psyarxiv.com/qkxvb](https://psyarxiv.com/qkxvb)

# Setup
Clone repository or simply download in a zip file. 

The R Markdown file in the Analysis folder contains all the analysis code for the paper as well as a html version. In order to run the code you'll need the following packages up-to-date: 

```
library(here)        # relative paths
library(tidyverse)   # tidy functions
library(knitr)       # knit functions
library(kableExtra)  # extra markdown functions
library(lsr)         # cohenD()
library(broom.mixed) # tidy() 
library(AICcmodavg)  # predictSE()
library(cowplot)     # plot_grid()
library(ggrepel)     # geom_text_repel
```

# Folders
This repo contains the following folders: Analysis, Data, and Graphs. 

1. **Analysis**

   Main analysis script can be found here alongside an html Markdown file showing all results and code. 

2. **Data**

   Cleaned data can be found here. See Analysis script for a description of all variables. 

3. **Graphs**

   Graphs produced for the preprint manuscript from R. Note that some style changes have been added to the final graphs in the manuscript using Illustrator, but in general I try to keep the graph output from R as close as possible to the final graph. 

# Contact
If you have any questions or suggestions please feel free to open an issue on this repo or email me directly at joseph_heffner@brown.edu. 
