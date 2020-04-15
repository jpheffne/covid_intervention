# covid_intervention
Behavioral data and analysis script for "Emotional responses to prosocial messages increase willingness to self-isolate during the COVID-19 pandemic" ([preprint](https://psyarxiv.com/qkxvb))

# Setup
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
# Contact me
If you have any questions or suggestions please feel free to open an issue on this repo or email me directly at joseph_heffner@brown.edu. 
