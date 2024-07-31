#  Statistics & Plotting Challenge

![Laboratories](Images/preclinical.jpg)

# # Pymaceuticals Inc.
---

## Dependencies and Setup:

* Import necessary libraries such as:
* pandas
* matplotlib.pyplot
* scipy.stats

## Load Data:

* Load both data from CSV files into Pandas DataFrames.

## Combine Data:

* Merge the mouse and study data into a single DataFrame for comprehensive analysis.

## Clean Data:

* Calculate number of animals, check if there is any duplicates, unique ID of the mice make a clean data fram .

## Statistical Summary:

* Group the data by Drug Regimen calculate mean, median, variance, standard deviation and Standard Error of the Mean.
* Format the summary data for display as data frame.



![Laboratories](Images/preclinicallab.jpg)

# Plotting Charts:

## Bar Chart
* Sort number of Observed Mouse Timepoints to have a sorted plot both with:
* Pandas &
* pyplot

## Pie Chart
* Show the percentage of the Male and Female number of mice both with:
* Pandas &
* pyplot

## Boxplot 
* Calculate Quartiles which are statistical measures that divide a dataset into four equal parts, each containing 25% of the data.
* And calculating Interquartile Range (IQR)
* And calculating upper & lower bounds to show the Final Tumor Volume across four Regimens

## Line ans Scatter plots 
* Calculate the Tumor Volume over days for specific Mouse under Campomulin treatment
* Calculate the Average Tumor Volume over weight for Mice under Campomulin Regimen


# Correlation
* Calculate the Correlation between the Average Tumor Volume and weight for Mice under Campomulin Regimen

### The statement "The correlation between mouse weight and the average tumor volume is 0.84" describes the strength and direction of the relationship between two variables: mouse weight and average tumor volume. we can draw a line with positive slope going through the data.

* A correlation of 0.84 suggests a strong association, which could be useful for making predictions or understanding how mouse weight might influence tumor volume.

* Correlation does not imply causation. While there is a strong relationship between mouse weight and average tumor volume, this doesn’t necessarily mean that one causes the other. Other factors could be influencing both variables.

