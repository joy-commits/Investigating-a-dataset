# Investigating-a-dataset


## Table of Contents
<ul>
<li><a href="#intro">Introduction</a></li>
<li><a href="#wrangling">Data Wrangling</a></li>
<li><a href="#eda">Exploratory Data Analysis</a></li>
<li><a href="#conclusions">Conclusions</a></li>
</ul>


<a id='intro'></a>
## Introduction

### Dataset Description 

> In this project, I will be analyzing a dataset from TMDB (The Movie Database). The dataset could be downloaded [here](https://www.google.com/url?q=https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd1c4c_tmdb-movies/tmdb-movies.csv&sa=D&source=editors&ust=1653956169169040&usg=AOvVaw3NjICBc0o5HzMRr-oowG6I). 
This dataset consists of 21 columns: <br>

         1.  id
         2.  imdb_id               
         3.  popularity            
         4.  budget                  
         5.  revenue               
         6.  original_title         
         7.  cast                  
         8.  homepage              
         9.  director               
         10. tagline                
         11. keywords             
         12. overview              
         13. runtime               
         14. genres                 
         15. production_companies  
         16. release_date          
         17. vote_count             
         18. vote_average         
         19. release_year           
         20. budget_adj            
         21. revenue_adj          
 

### Question(s) for Analysis
> This analysis will be providing answers to these questions: <br>

    1. Which is the most popular movie? 
    2. What movie has the longest runtime? 
    3. What movie generated the highest revenue?
    4. Does the popularity of a movie determine the revenue generated?


<a id='conclusions'></a>
## Conclusions

Based on analysis done, it can be concluded that the most popular movie is "Jurassic World", which was directed by Colin Trevorrow. "The Story of Film: An Odyssey" had the longest runtime.
"Avatar", directed by James Cameron generated the highest revenue, totalling over 2.7 billion.
Furthermore, a positive linear relationship is observed between popularity and revenue. This indicates that as popularity increases, there is a corresponding increase in revenue generated. However, this relationship isn't a strong one.

### Limitation(s)
Variables like the revenue was not assigned any specific currency unit. It could be possible that the revenue value might assume that of the country in which the movie was produced.
