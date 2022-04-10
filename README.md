# Pymaceuticals Inc. Matplotlib Exercise

## Background

This exercise involves working with data from a fictional animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.
The goal is to generate tables and figures needed for a technical report of the study. I have also created a top-level summary of the study results.

## Process

The following was completed as part of this exercise:

* The data was cleaned of any mouse IDs with duplicate time points.

* A summary statistics table was generated consisting of the mean, median, variance, standard deviation, and SEM of tumor volumes for each drug regimen.

* Bar plots were created using both Pandas and Matplotlib that show the number of total mice for each treatment regimen throughout the course of the study.

* Pie plots were created using both Pandas and Matplotlib that shows the distribution of female and male mice in the study.

* The final tumor volume was calculated for each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. The quartiles and IQR were calculated to quantitatively determine any potential outliers across all four treatment regimens.

* A box and whisker plot was generated using Matplotlib to described the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot.

* A mouse that was treated with Capomulin was selected, and a line plot of tumor volume vs. time point for that mouse was generated.

* Generated a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plotted the linear regression model on top of the previous scatter plot.

* Proper labeling of plots to include properties such as: plot titles, axis labels, legend labels, _x_-axis and _y_-axis limits, etc.

### Copyright

Trilogy Education Services © 2020. All Rights Reserved.
