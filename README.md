# Analysing-the-Google-Play-Store-Ratings-Dataset
Google Play Store Ratings Data Visualization using Matplotlib and Seaborn

** Business Understanding**

The team at Google Play Store wants to develop a feature that would enable them to boost visibility for the most promising apps. Now, this analysis would require a preliminary understanding of the features that define a well-performing app. For which, I can ask questions like:

* Does a higher size or price of an app necessarily mean that it would perform better than the other apps? 
* Does a higher number of installs give a clear picture of which app would have a better rating than others?

**Approach**

So here Rating column is our target variable. I analysed the way the rating varies across different categories of other variables to determine the most important indicators for the high-performing apps.

** Insights after visualing the data using Matplotlib and Seaborn after Cleaning the data **:

* First, I did data handling and cleaning - cleaning junk records, adding missing values, changing data types, remove outliers, etc.
* When I analysed the ratings using the histogram, I saw that they are skewed towards higher ratings.
* Using a bar chart, I saw that most of the apps belong to the Everyone category.
* I also observed a weak trend between the ratings and the size of the app, using a scatter-plot and reg plots to understand its nuances
* Using a pair-plot, I wasable to see multiple scatter plots and draw several inferences, for example, price and rating having very weak trend, reviews and price being inversely related and so on.
* After that, I utilised estimator functions along with bar plots as well as box plots to observe the spread of ratings across the different Content Rating Categories, So  my main observation was that Everyone category has a lot of apps having very low ratings.
* Finally, I created a heat map comparing the ratings across different Reviews and Content Rating buckets.
