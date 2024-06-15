## Simultaneous quantification of polyphenols, glycoalkaloids and saponins in African nightshade leaves using ultra-high performance liquid chromatography tandem mass spectrometry with acid assisted hydrolysis and multivariate analysis

## Abstract
In this study (see [original publication](https://www.sciencedirect.com/science/article/abs/pii/S0308814619321752?via%3Dihub)), we developed comprehensive quantification methods for major nutritive and antinutritive phytochemical aglycones in edible African nightshade leaves, an underutilized food resource in the sub-Saharan area. A simultaneous hydrolysis and extraction method was developed using methanol with 2 M sulfuric acid with incubation at 65°C for 60 min. UHPLC–QqQ–MS/MS methods were developed and validated for hydrolysis optimization and for quantification of eight major aglycones of polyphenols, alkaloids, and sapogenins in 20 differently sourced nightshade leaves, comprising two African species Solanum scabrum and S. nigrum, and from two distinct cultivation sites, one in New Jersey, US, and the other in Kenya Eldoret. Variation in species, accessions, and cultivation environment played an important role in affecting the phytochemical profile. Total antinutritive alkaloids and sapogenins in all nightshade leaves were evaluated and found to be safe for consumption. This work provides evidence that the consumption of African nightshade leaves as a nutrient-rich leafy green vegetable is safe and can contribute to food security and nutritional improvement in the sub-Saharan area.

## Script Reference
This repository documents the original R script used for data analysis and visualization in this work ([see code and output](https://yuanbofaith.github.io/NSleaf_PhytochemQqQ/)). The R code was developed with reference to [R for Data Science (2e)](https://r4ds.hadley.nz/), and the official documentation of [tidyverse](https://www.tidyverse.org/), and [**DataBrewer.co**](https://www.databrewer.co/). See breakdown of modules below:

- Data visualization with ggplot2 ([tutorial](https://www.databrewer.co/R/visualization/introduction) of the fundamentals; and [data viz. gallery](https://www.databrewer.co/R/gallery)).

- [Data wrangling](https://www.databrewer.co/R/data-wrangling) with the following packages:
  - [tidyr](https://www.databrewer.co/R/data-wrangling/tidyr/introduction): transform (e.g., pivoting) the dataset into tidy structure.
  - [dplyr](https://www.databrewer.co/R/data-wrangling/dplyr/0-introduction): a basic tool to work with data frames.     
  - [stringr](https://www.databrewer.co/R/data-wrangling/stringr/0-introduction): work with strings. 
  - [regular expression](https://www.databrewer.co/R/data-wrangling/regular-expression/0-introduction): search and match a string pattern.
  - [purrr](https://www.databrewer.co/R/data-wrangling/purrr/introduction): functional programming (e.g., iterating functions across elements of columns).
  - [tibble](https://www.databrewer.co/R/data-wrangling/tibble/introduction): work with data frames in the modern tibble structure.
  
