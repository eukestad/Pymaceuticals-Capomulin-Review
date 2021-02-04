# Review of Capomulin Treatment Regimen for Pymaceuticals

## Summary
This project reviews the Capomulin treatment regimen for squamous cell carcinoma (SCC) as compared to other treatment regimens for Pymaceuticals. 

Some observations and insights that are outlined in the report are:

* The study reviewed the progress of 249 mice with about an even split between male (50.2%) and female (49.8%) mice.

* Capomulin was one of two treatment regimens that had the most measurements (230) taken over the course of the study. The treatment with the next highest measurement count was Ramicane at 228.

* Of the four regimens depicted, Capomulin and Ramicane have the lowest final tumor volumes in mice. Capomulin had a median final tumor volume of 38 and Ramicane had a median of 36.5. 

* While Capomulin is effective at reducing tumor volume, it may not reduce the spread of SCC. Mouse l509 saw an increase in metastatic sites as their tumor volume decreased throughout the treatment regimen. 

* There is a strong positive correlation (r=0.95) between average tumor volume and mouse weight. It may be beneficial to look at other factors that affect weight that could help treat and reduce tumor volume in patients with SCC.

## Files in the Repository
The repository contains a folder for the analysis called Pymaceuticals. This main folder contains the following: 

* a folder to store the data provided for analysis
* the Capomulin Analysis Report as a Jupyter Notebook

## Using the Jupyter Notebook
Open in Jupyter and set the Kernel to Python 3.6. Run all to see output. 

## Output
The notebook generates: 

* A summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Bar plots using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the total number of measurements taken for each treatment regimen throughout the course of the study.

* Pie plots using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.

* The final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Including the quartiles and IQR to quantitatively determine if there are any potential outliers across all four treatment regimens.

* A Matplotlib box and whisker plot of the final tumor volume for all four treatment regimens. Potential outliers are highlighted with a red diamond.

* A line plot comparing tumor volume and time point for mouse l509 that was treated with Capomulin.

* A scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* The correlation coefficient and linear regression model for mouse weight and average tumor volume for the Capomulin treatment. 

* A summary of observations or inferences included at the top of notebook.

## Features
The analysis makes use of plots from both PyPlot and Matplotlib. 

## Status
_finished_

## Inspiration 
This project was assigned as part of the UTSA Data BootCamp.