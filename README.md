# matplotlib_pymaceuticals

# DESCRIPTION:
Use pandas and matplotlib to analyze fake drug experiments on 249 mice (ahem, 248 mice after data cleaning). The instructions are as follows:

    1. Before beginning the analysis, check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.

    2. Use the cleaned data for the remaining steps.

    a) Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

    b) Generate a bar plot using both Pandas’s DataFrame.plot() and Matplotlib’s pyplot that shows the total number of measurements taken for each treatment regimen throughout the course of the study.

      NOTE: These plots should look identical.

    c) Generate a pie plot using both Pandas’s DataFrame.plot() and Matplotlib’s pyplot that shows the distribution of female or male mice in the study.

      NOTE: These plots should look identical.

    d) Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

    e) Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

      Hint: All four box plots should be within the same figure. Use this Matplotlib documentation page for help with changing the style of the outliers.

    f) Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

    g) Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

    h) Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

I provided three observations or inferences from the data. These observations are noted at the top of jupyter notebook.

# REFLECTIONS:
This project was a challenge! I may have spent more than 5 hours trying to think and work out the boxplot problem. Learning about these plots and the various ways they can be used/presented was a invaluable way for me to learn. Tough but rewarding when I completed it through. I also learned that I knew what I wanted at the end, but needed to refine the knowledge of how to get the end results. Asking the right question to search through Google seems like at an art and not a science. Two of many positive outcomes from this challenge was knowing there are so many ways to approach a problem and seeing the Python community supported with so many resources.
