# Semester 1 Capstone Project - Data Explorers

![data explorer](https://media.giphy.com/media/xT9C25UNTwfZuk85WP/giphy-downsized-large.gif)

## Authors
 * Dylan Orndorf-Ronk
 * Alex Bonczkiewicz
 * Alberto Torres
 * Travis McCloughan
 * Jaemin Lee


## Overview
 * Business Problem
      * For this project Data Explorers used data analysis and statistical methods to generate metrics where Computer Vision should invest their funds in
        to be able to create a new movie studio and have a positive flow in profits coming in. 
       
 * Business Solution
      * We recommend Computer Vision to produce movies of the Musical, Animation, Sci-Fi or Adventure genres. 
      * Target top 7 languages for max region reach.
      * Invest in popular directors.

## Business Understanding
  * Computing Vision (a made-up company for the purposes of this project) sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t have much background in creating movies. You are charged with exploring what types of films are currently doing the best at the box office using different samples of available data. You then will translate those findings into actionable insights that the head of Computing Vision's new movie studio can use to help decide what type of films to create.
    
 
## Data Understanding and Analysis
   * Source of data
     * [Box Office Mojo](https://www.boxofficemojo.com/)
     * [IMDB](https://www.imdb.com/)
     * [Rotten Tomatoes](https://www.rottentomatoes.com/)
     * [TheMovieDB](https://www.themoviedb.org/)
     * [The Numbers](https://www.the-numbers.com/)
   * Description of data & Features used
     * IMDB Data - SQL Database
       * Movie Genres
       * Language
       * Director Names
       * Average Rating
       * Number of Votes
     * The Numbers Data - csv file
       * Production Budget
       * Domestic Gross & Worldwide Gross
     
     
   *(Figure 1)* Demonstration of ROI by language to target the most regions with the most popular released movies
   
   ![image](https://user-images.githubusercontent.com/110133652/185657004-775cbff4-1820-4849-908a-d8e036cd4cae.png)
 
   *(Figure 2)* Visualizing the distribution of movie ratings and where the mean and median lie.
   
   ![image](https://user-images.githubusercontent.com/110133652/185686264-4ab89ffd-463d-4d55-be47-a1defe8f4f11.png)
   
   *(Figure 3)* Visualizing that there is a statistical significance that higher rated movies make more money.
   
   ![image](https://user-images.githubusercontent.com/110133652/185686381-4c44b3ac-a942-40e1-a4a4-724e60cbab21.png)

   *(Figure 4)* Most profitable movie genres.

   ![image](https://user-images.githubusercontent.com/110133652/185657214-b57a3ced-3cf9-43f7-8d17-0388e65ed4c9.png)



       
## Statistical Communication
   * Q: Do movies with a rating of at least 6.5 lead to a higher revenue?
   * A: There is a statistical significance that higher rated movies make more money.
   * Q: Which genres perform the best, given a high rating and high total profit?
   * A: Musical, Animation, Sci-Fi, and Adventure
       
## Conclusion

Recommendations:
   * Invest in top genres
   * Release in areas with top languages.
   * Research pricing for directors.
   * Continue researching trends.
   
Positives:
   * Avoid common pitfalls through intelligent investment
   * Greatly imporved return on investment potential
   * Reduce losses

## Next Steps

Limitations:
   * Lack pricing for directors.
   * Return on investment is easily skewed.
   * Limited data for some countries.

## For More Information

See the full analysis in the [Jupyter Notebook](./student.ipynb) or review this [presentation](./pdf).

**provide the link to our respository when we finalize everything**
