# Unit 5 Homework: MatPlotLib

Compared the effects on tumor size in mice for 9 drug regimen and a Placebo through a few different methodologies in Pandas using MatPlotLib.


## Setup

* Created a new repository for this project called `matplotlib-challenge` with a ReadMe and a folder "Pymaceuticals".  
* In the folder is the pandas file (Pymaceuticals.ipynb) and a folder with the data sources.

### Pymaceuticals.ipynb

* Imported dependencies and data sources
* Combined data sources into one dataframe "mouse_study_data"
* Created cleaned up data (mouse_study_df) by looking at the mouse count, looking for duplicates and removing them

### Summary Statistics
* Generated Summary Statistics table for the different drug regimen using three different methods

### Bar and Pie Charts
* Created bar charts for drug regimen vs mouse count using two different methods
* Created pie charts showing gender distribution using two different methods

### Quartiles, Outliers and Boxplots
* Created a dataframe of the tumor data (final_data) corresponding with the final timepoint check
* Created a dataframe from that for 4 drugs; Capomulin, Ramicane, Infubinol, and Ceftamin with the final tumor volume for each mouse id
* Used a loop to cycle through the drugs and calculated the quartiles and upper/lower bounds based on those 
* Used another loop to go through the rows to discover potential outliers by comparing to the bounds, and print that info out
* Generated a box plot to reflect the calculated information

### Line and Scatter Plots
* Chose a mouse id at random to plot the effect of the Capomulin treatment over time on the Tumor Volume
* Created scatter plot and then a trend line for that scatter plot reflecting the average final tumor volume for mice on the Capomulin drug regimen
* Calculated and printed the correlation.

## Drew Conclusions

* From the box plot and the calculations leading up to it we can see that of the 4 drugs examined, only Infubinol had a noticeable outlier requiring further examination.

* From the tumor sizes over time it seems the two most effective drugs were Capomulin and Ramicane.

* The final scatterplots for mouse weight to tumor size under the Capomulin regimen shows a very strong linear relationship given the Pearson correlation of .84, indicating a conclusion can be drawn that the higher the mouse weight, the larger the average tumor seen.