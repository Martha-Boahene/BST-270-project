# Project Reproduction: How Americans Like Their Steak
## Overview
This repository contains a class project which aims at reproducing tables/figures from FiveThirtyEight's How  Americans Like their Steak [How Americans Like Their Steak](https://fivethirtyeight.com/features/how-americans-like-their-steak/). The project successfully achieves the goal of reproducing both a table and a figure from the original content. This README provides a detailed guide on the project's objective, packages used, data loading, and the process of reproducing the table and figure.

## Packages
The project relies on several R packages to facilitate different tasks:

readr: Used for efficient loading and reading of data, ensuring successful importation of the required dataset.
kableExtra: Crucial for constructing and formatting tables, providing enhanced capabilities for table customization.
ggplot2: An influential package utilized for creating plots, contributing to the visualization aspect of the project.
dplyr: Essential for data manipulation and transformation, providing functionalities to streamline data processing tasks.
By incorporating these packages, the project establishes a solid foundation for effective data handling, table construction, and plot generation.


## Data Loading
The dataset for this project is available on the FiveThirtyEight GitHub repository at steak-risk-survey.csv. The data is loaded into the R environment using the read_csv function from the readr package. The provided code includes specifying the dataset URL and using skip = 1 to skip the first row during the import process.

## Reproducing the Table
The first goal of the project is to reproduce the table summarizing people's risk perceptions and their steak preferences. The survey included a hypothetical scenario involving Lotteries A and B, and respondents' choices were recorded in the "Response_2" column. The dataset also captures participants' steak preferences in the "Response_10" column, categorizing them into five distinct levels. The reproduction of the table involves utilizing the kableExtra package for efficient table construction and customization.

## Reproducing the Figure
Following the table reproduction, a horizontal bar plot is created to visually represent how people prefer their steak cooked. The results are compared with the original findings from FiveThirtyEight. The plot accurately reflects the original author's discovery, showing a significant preference for medium-level steak. Notably, the plot reveals interesting insights, such as a higher preference for medium-rare compared to medium-well. This similarity in results confirms the accuracy of the reproduction in capturing the original findings.

Feel free to explore the provided code and reproduce the results in your R environment. If you encounter any issues or have questions, please refer to the issues section of this repository for assistance. Happy reproducing!

