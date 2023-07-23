# Project Title: Movie Data Exploration and Analysis.

![image](https://github.com/fwanalwenge/dsc-phase-1-project/assets/134020486/cbf2ef36-0527-433e-a451-ff2ae3b59ef4)


## Project Overview

This project uses data from IMDB, and The Numbers and analyazes it to come up with three suggestions for helping the head microsoft's new movie studio department. It will aim to answer the following: 

1. What is the best time of the year to release movies?
2. What is the most popular genre?
3. What is the relationship between rating vs profit/loss and rating vs release year?
4. What is the average movie runtime?

### Business Problem

Microsoft wants to create a new movie studio, but they don't know anything about creating movies. So the project will cover exploring and analyzing movie data to find what types of films are currently doing the best at the box office and come up with recommendations for business.

### The Data

In the folder `zippedData` are movie datasets from:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)



### What is the best time of the year to release movies


![Profit by Month](https://github.com/fwanalwenge/dsc-phase-1-project/assets/134020486/4228326f-7bc9-4839-a607-bee2a3ebe587)

Conclusion: The top 3 months to release the movie are December,June and May for better profits.

### What is the most popular genre?
i. Distribution of genres in different categories?
![Movies per Genre](https://github.com/fwanalwenge/dsc-phase-1-project/assets/134020486/7f2fd2a3-1211-4d13-bbd5-ee80b740cb36)

The most common genre is Drama

ii. Analysis of ratings

![Average Ratings](https://github.com/fwanalwenge/dsc-phase-1-project/assets/134020486/5ddf85ba-cecc-4b12-9f2e-1e58f9a980c7)

The graph above confirms that average rating of most movies is between 6-7

![Ratings per Genre](https://github.com/fwanalwenge/dsc-phase-1-project/assets/134020486/b97b14c7-e4c2-4f73-8951-e9297bca2ccb)

Conclusion:The Genre Comedy,Documentary,Fantasy is rated highest by average rating. 

### What is the relationship between rating vs profit/loss and rating vs release year?
![Correlation](https://github.com/fwanalwenge/dsc-phase-1-project/assets/134020486/fc7825b9-8e81-43ae-92cd-c0bb849b740f)

Conclusions:

i. Averagerating Vs profit/loss have 0.16 correlation between them. This means there is a low possibility that movies with higher average ratings have higher profits.

ii. Production_budget Vs profit both have 0.65 correlation between them. This means there is a good possibility that movies with higher investments result in better revenue.

iii. Start_year Vs num votes have a negative(-0.088) correlation. This means that movie rating (num votes) do not depend on the release year.


### What is the Average movie runtime?
Displaying of the boxplot before remiving outliers from  the dataframe

![Outliers](https://github.com/fwanalwenge/dsc-phase-1-project/assets/134020486/a8032e63-e232-40b7-bade-0d7705e9fef2)


Displaying of the boxplot after removing the outliers

![Runtime Boxplot](https://github.com/fwanalwenge/dsc-phase-1-project/assets/134020486/f813229c-89db-4051-ae38-baad86dc7aba)


Distribution of movie runtimes

![Runtime Distribution](https://github.com/fwanalwenge/dsc-phase-1-project/assets/134020486/d2e165ae-f337-43d7-b1c6-7312f8c3811a)



Conclusion: The average movie run_time after eliminating outliers is 91 minutes


## Recommendations

1. Plan the production schedule for a release in December
2. Higher production budgets are likely to have a higher profit owing to the correlation of 0.65
3. Comedy, Documentary, Fantasy films are highest rated while Drama is the most common
4. The average length of films is 91 minutes hence this can serve as a benchmark for production length of films

