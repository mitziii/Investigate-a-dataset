# Investigate-a-dataset

Using Python libraries such as Pandas, NumPy and Matplotlib to investigate (wrangle, explore, draw conclusions and communicate) a dataset

## Overview

In this project, I have analysed a dataset and then communicate the findings about it. 

## Python libraries

* pandas
* NumPy
* Matplotlib

## Project tasks

 * A typical data analysis process: posing questions that can be answered and answering those questions
 * Investigate problems and wrangle the data into a format, and communicate the results 
 * Be able to use vectorized operations in NumPy and pandas, use pandas' Series and DataFrame objects
 * Use Matplotlib to produce plots 
 
##  Dataset

**tmdb-movies.csv**
* This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.
* Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|)characters.
* There are some odd characters in the ‘cast’ column. 
* The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of 2010 dollars,accounting for inflation over time.

## Questions 

* Which genres are most popular from year to year?
* What properties are correlated with movies having high revenues/profits?
* Who are the most frequent cast in the profitable movies? 
* Who are the most frequent director in the profitable movies?

## Findings

* Looking at the total movies made throughout the years, drama, comedy and thriller are the top three genres which have the most films. However, relying on the popularity score, it can be concluded that science fiction, adventure, fantasy and animation are the most popular genre with the highest average popularity.

* Regarding the most profitable directors and actors, it is apparent that Harrison Ford, Tom Cruise, Tom Hanks, Carrie Fisher and Emma Watson are the five casts who have highest total profit movies. The directors Steven Spielberg, James Cameron, George Lucas and Peter Jackson are the top most profitable directors, as their total profits and total revenues rank the highest.

* The relationship between the budget, genre, voting score and popularity with the profitability of a movie is not strong. This can be due to the lack of data and the existence of many outliers. In further research, if these limitations can be tackled, the results may be more precise and accurate. Another limitation of this research if that there are too many missing values as well as a lot of zero values in budget and revenue variables, which made me delete a lot of rows while doing the cleaning data. Thus, only more than 3,000 entries are examined, which may also be a reason leading to the bias results.

