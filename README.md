# SURE-2024-EDA-Project-1
EDA Project - Hospital Ratings Group 1

Summer Research EDA Project - 1

Overview

This project involves exploratory data analysis (EDA) on hospital cost and quality data. The aim is to analyze the relationship between hospital costs and the quality of care provided, with a focus on heart failure procedures. This research is conducted as part of the summer research program at Carnegie Mellon University.

Project Files

Cost_Quality(Q3).Rmd: Analysis of heart failure cost and quality data.

HospitalCounts.Rmd: Analysis and visualization of hospital counts.

Kmeans.Rmd: K-means clustering analysis on hospital data.

question1.Rmd: Analysis Hospitals type and Mortality Rate

Prerequisites

Make sure you have R and RStudio installed on your machine. You will also need to install the following R packages:

install.packages(c("tidyverse", "scales", "RColorBrewer", "cluster", "factoextra", "virids", "statebins", "datasets", "maps"))

Loading Libraries

In each R Markdown file, the following libraries are loaded. Ensure these libraries are installed and loaded in your R session.

library(tidyverse)
library(scales)
library(RColorBrewer)
library(cluster)
library(factoextra)
library(viridis)
library(statebins)
library(datasets)
library(maps)

Data:

  The data used in this project is sourced from the CORGIS Dataset Project. Ensure you have the    dataset properly loaded and accessible in your working directory.

Running the Analysis:

  To run the analysis, open each R Markdown file in RStudio and click on the "Knit" button to      generate the HTML output. The analysis will include visualizations and statistical tests to      explore the relationship between hospital costs and quality.

Files Description: 

1. Cost_Quality(Q3).Rmd

Data Preparation: Loaded and cleaned hospital data, renamed columns, and filtered out unknown values.

Outlier Handling: Replaced outliers in heart failure cost data with the mean for each quality category.

Visualization: Created violin and box plots to visualize heart failure costs by quality ratings.

Statistical Analysis: Performed pairwise t-tests to compare costs between different quality ratings ("Worse", "Average", "Better").

2. HospitalCounts.Rmd

Data Preparation: Loaded and cleaned hospital data, mapped state abbreviations to state names.

State Aggregation: Grouped data by state to count the number of hospitals.

Data Merging: Merged hospital counts with U.S. state map data.

Visualization: Created a chloropleth map to visualize hospital counts by state using ggplot2 and viridis.

3. Kmeans.Rmd

Data Preparation: Cleaned and scaled hospital cost data for clustering.

Hierarchical Clustering: Used to determine the optimal number of clusters.

K-means Clustering: Applied with 5 clusters, visualized results.

Silhouette Analysis: Evaluated cluster quality and cohesion.

4. question1.Rmd

Data Preparation: Loaded and cleaned hospital data, filtered out unknown and "None" mortality ratings.

Proportion Calculation: Calculated proportions of mortality ratings for each hospital type.

Visualization: Created a stacked bar graph to visualize the proportions of mortality ratings by hospital type.

Summary Analysis: Generated a bar graph to show the count of hospitals by type and their corresponding mortality ratings.

This README provides an overview of the EDA project and instructions on how to set up and run the analysis. Each R Markdown file contains detailed steps and code for the analysis, ensuring reproducibility and clarity.

Contact
For any questions or further information, please contact (your name and email)

