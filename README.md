# Microsoft Movie Studio Analysis
![microsoft](https://github.com/learn-co-curriculum/dsc-phase-1-project/assets/134168984/1e03f246-f498-40db-a1aa-555db711168d)

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.


## Project Overview

Microsoft wants to venture into the film industry and would like to create a new movie studio but before they get started, they tasked me to evaluate the film industry and give them recommendations before making their final decision. My recommendations are based on the profitability of the different movie genres both in the local(USA) and global markets, the popularity of the different genres, the runtime of the different major movies, and lastly the ROI in short films.

## Business Problem

The main problem for Microsoft is determining if venturing into the film industry is a viable business idea. They need to identify what kind of films they need to create, how to make profits, and generally how to set themselves apart in order to be the market leaders in this industry.

### The Data

In the folder `zippedData` are movie datasets from:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)

For this project, we will be analyzing data from three movie websites:

* IMDB(Internet Movie Database)
* The MovieDB
* The Numbers

## Comprehension Check

This project involves responding to three distinct inquiries:
* What kind of movie genres should Microsoft venture into?
* How profitable are the recommended movie genres?
* What films have a good Return on Investment(ROI)?


### Analysis Overview

* **Selecting and analyzing the datasets.** 
* **Cleaning the Datasets.**

* **Generating Descriptive Statistics.** 

* **Merging DataFrames to work with.**

* **Visualization**

* **Conclusion**

* **Recommendation**
  
## Getting Started

Upon carefully choosing, analyzing, cleansing, and generating descriptive statistics, I have developed several visualizations that encapsulate my recommendations. These visual representations stem from the merging of datasets and offer valuable insights for the project.

## What kind of movie genres should Microsoft venture into?

<img width="990" alt="Screenshot 2023-07-22 130056" src="https://github.com/learn-co-curriculum/dsc-phase-1-project/assets/134168984/74fa88fc-a5cc-45f9-9af5-1ef99dbe8cb8">

From the above bar plot, we can see that the most popular genre in terms of the number of times movies have been created in that genre, is Drama followed by comedy. From the previous analysis, we saw that horrors and adventures make the most profits but drama and comedy are created the most. This might be attributed to a number of things, eg. online streaming shows might be airing this kind of movie because of the demand, The cost of making drama and comedy shows might be lower hence easier to produce more.

## How profitable are the recommended movie genres?

<img width="990" alt="Screenshot 2023-07-22 175208" src="https://github.com/learn-co-curriculum/dsc-phase-1-project/assets/134168984/72764164-1949-4009-ac5c-fadde6dfd4e0">
From the bar plot above we can see that Horror movies make the most profits followed by adventure movies. We can also see that there are certain movies that fall under more than one category and are making profits, especially if it also falls under action and drama movies.

## What films have a good Return on Investment(ROI)?

<img width="990" alt="Screenshot 2023-07-22 180254" src="https://github.com/learn-co-curriculum/dsc-phase-1-project/assets/134168984/420671ba-e559-445e-9955-92ee52701972">

From the barplot above, we can clearly see that Short films in Documentaries and Biography have the highest rate of ROI.

## More Visualizations supporting the above recommendations will be found in my ipynb file

##  Conclusion
Below are the findings from the analysis conducted above:

* The budget allocated for the production of the film will play a huge role in the profitability of the film alongside other factors like the cast, producers, marketing, language of the film, etc. Also, note that it's not guaranteed that the budget allocated will automatically result in the success of the film.
* Popularity of a film doesn't guarantee the profitability of the film. From our analysis, there are some genres that were very popular in terms of vote counts but the profitability was slightly lower.
* Films that fall under more than one category are popular and profitable too.
* There's a good ROI in short films specifically Documentaries and Biographies.

## Recommendations
* Consider having a good budget for the film production, since we have observed there's a positive correlation between the budget and the income. But it should be noted that there needs to have a very good marketing strategy for the film while factoring in the producers and cast to work with.
* Short Documentary films have a high ROI, therefore it is a good genre to focus on too. Diversifying the genres and the kind of films they create is very important as they'll appeal to a wider scope of viewers.
* There are certain external factors that affect the success of a film, therefore understanding the market and the current social-demographic issues such as - 'Black lives matter', 'Gender Inclusion', 'race' etc.- is very important. It would be good to help push the agenda the company resonates with so as to appeal to its target market.
* The runtime minutes for films average between 90 - 150 minutes, therefore if there's a probability of having a longer film, it's best to create a limited series.

