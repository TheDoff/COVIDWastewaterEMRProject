# COVID-19 Wastewater Excess Mortality Project

A statistics capstone project using R to understand the relationship between the viral activity of COVID-19 in wastewater and change in excess mortality

## Description

This R Markdown file details the data importation, cleaning, and subsequent analysis that took place over the Spring 2024 semester in STAT 460 (Statistical Practicum). The data collected were various time series (COVID-19 viral wastewater activity, hospital admissions, deaths, and excess mortality) at both the national and state (just MN) level, save for excess mortality which was calculated for just national data. After normalizing graphing some of the time series side by side (searching for a visual correlation), ARIMA and VAR models were produced to predict excess mortality using previous excess mortality data and previous data from other time series, respectively. Forecast plots were then produced from the VAR models to visualize the models' predictive power.

## Getting Started

### Dependencies

* This program should run on any software that supports R Markdown, RStudio was used for this analysis.
* This program will also require the openxlsx, vars, forecast, and ggplot2 packages to be installed.
* The supplimentary xlsx file in the repository provides the data used in the analysis.

### Installing

* To download the program, download and pull the entire repository into your preferred R Markdown compatible software (ensure the R Markdown file and xlsx spreadsheet are in the same directory)
* Install the dependent packages in the console (as needed)

### Executing program

* Run the R markdown file to populate your environment with the various objects created and view the graphs/output generated
  
## Authors

Contributors names

* Cameron Doffing
* Braeden Kuehn
* Joey Millner


## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
