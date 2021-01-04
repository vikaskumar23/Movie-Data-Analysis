# Investigate Movie Dataset
The objective of this project to analyze Movie Dataset using numpy, pandas and matplotlib and then communicate the findings about it.

## Introduction
- This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

- In this project we first wrangle the data set to make it fit for analysis then we analyze data and draw some conclusions on the basis of provided data. For now we only focus on Descriptive Statistics to draw conclusions.

- We are going to use Numpy, Pandas, Matplotlib for our data analysis process.
We will analyse data and try to draw some conclusions like the impact of budget on popularity, revenue, or which genre are getting popular over the years and many more...

## Scope of the Project
In this project, we will go through the data analysis process and see how everything fits together.

## Data Required for Project
**tmdb-movies.csv :** This data set is provided by udacity
- Source of dataset : https://www.google.com/url?q=https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd1c4c_tmdb-movies/tmdb-movies.csv&sa=D&ust=1532469042115000
- This dataset contain all the information related to movies like movie_name, release_date, budget, genre and many more things.
- This dataset contains 10866 rows and 21 columns.

## Explore and Asses the data
### The movie dataset needs to be cleaned as it has many data quality issues.
**Following issues are fixed :**
- Duplicated rows are removed
- Those rows are removed in which genre field is empty as we need this column in further analysis
- Those data points are removed in which budget is less than 999$, as it seems impossible to make a movie in such low amount.
- Datatypes of release_date columns is converted from object to datetime

### Feature Engineering
Following columns are extracted using feature engineering from the given dataset to find deep insights and relations:
**weekday :** weekday is extracted from release_date
**profit :** profit is calculated from subtracting budget_adj from revenue_adj

## Exploratory Analysis
- Questions are planned based on data
- Statistical Analysis is done to find the answers
- Visualizations like line plot, bar plot, scatter plot etc. are plotted to find trends and deeps insigts and relation among variables.
- Conclusions are drawn based on findings

## References
www.udacity.com

https://www.kaggle.com/tmdb/tmdb-movie-metadata