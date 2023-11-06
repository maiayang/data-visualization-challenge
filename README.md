# data-visualization-challenge

In this activity, we analyzed mouse data for a pharmaceutical company that is testing the effectiveness of the drug Capumolin at treating squamous cell carcinoma (SCC) compared to other drug regimens.

We started with data from 249 mice, however one mouse contained duplicate values so we dropped it from the dataset. We then filtered the data to isolate the ending (last) tumor volume for each mouse. From there we selected mice treated with Capumolin and three other drugs to compare ending tumor volumes using boxplots.

We also randomly selected one mouse treated with Capumolin and plotted its tumor volume against time to see if Capumolin was effective at reducing tumor volume.

Lastly, we plotted mouse weight against average tumor volume for all mice treated with Capumolin to see if there were any observeable trends. We calculcated the correlation coefficient and a linear regression model was applied.
 
Help for this code was obtained from Stack Overflow and Pandas documentation (https://pandas.pydata.org/docs).