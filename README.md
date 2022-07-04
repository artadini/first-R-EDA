# My first EDA in R

This repository is my first try in running a simple EDA ([Exploratory Data Analysis](https://en.wikipedia.org/wiki/Exploratory_data_analysis)) in R for the class Programming R in the [IE University](https://www.ie.edu/).

## Description

Welcome to the project of “PROGRAMMING - MBD-EN-BL2021J-1_32R377_406729” course.
In this project I will be working with a real-world dataset from the [Kaggle platform](https://www.kaggle.com/) corresponding to the [AMS 2013-2014 Solar Energy Prediction Contest](https://www.kaggle.com/c/ams-2014-solar-energy-prediction-contest/overview/).

Part of the task was also to get to know more libraries of R and get a first look into the langugae using R markdown.

To visualize the R markdown, please feel free to execute the code or press on [this page](https://htmlpreview.github.io/?https://github.com/artadini/first-R-EDA/blob/main/REDA_Nikolas_Artadi.html).

## Goal of this project

The goal in this project will be:

1. To perform an exploratory data analysis, EDA.

2. Create an R Markdown report with the EDA findings.

Each section will be split in every indivdual dataset that was looked at. I will particularily focus on the main dataset: solar_dataset.

### About this dataset

This data is about the solar energy production per stations in [Oklahoma Mesonet](http://www.mesonet.org/) sites.

This task includes 3 datasets.

- **solar_dataset**: Data about the solar energy production per station and date. Included PCA features. 
- **additional_variables**: Additional data about real Numerical Weather Prediction, NWP, values. In particular, they are the 100 original variables detected as more important to predict the first station (feature ACME) values, after feature importance analysis.
- **station_info**: Information on the station's location.

## Libraries used

- tidyverse
- corrplot
- ggplot2
- outliers
- lubridate
- ggfortify
- kableExtra
- leaflet
- dplyr
- rmarkdown

## Learnings

During this project I have learned the basics of running EDAs in R and handling some libraries. I have also gained a high level understanding of how to use R Markdown for personal projects and can confirm that I can now use leaflet to create maps.

Part of this adventure was creating plots using ggplot. This truly showed me how to boost the power of R.

R taught me to not judge a language by its looks. There is much to learn from and for this language because it is as adaptive as Python and maybe better for analysis.
