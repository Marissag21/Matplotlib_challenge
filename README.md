# Matplotlib_challenge

In this challenge I first imported the data and dependencies and merged the two dataframes into one. 
I deleted the duplicated mouse from the dataframe to use thereafter. 
I then created a summary dataframe to show the mean, median, variance, standard deviation, and standard error of the tumor volume for each drug regimen. 
Two bar charts were produced to show the number of timepoints for each drug as well as two pie charts to show the distribution between the sex of mice. 
I then created a dataframe that included the greatest timepoint for each mouse.
Next, I created a for loop that looped through each drug and located the row that corresponded to the four treatments that were being focused on. Then the final tumor volumes for each drug were added to an empty list. 
Determine outliers for each of the four drugs. 
A box plot was generated that showed the final tumor volume for all the mice in each treatment group showing any outliers. 
A line plot was created for the l509 mouse to show the tumor volume compared to timepoints. 
Then a scatter plot was generated for average tumor volume vs. mouse weight for the Capomulin regimen.
Finally, the correlation coefficient was calculated for the mouse weight and average tumor volume for the Capomulin regimen and the linear regression line was plotted to show the positive correlation. 