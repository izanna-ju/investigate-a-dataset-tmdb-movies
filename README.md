# Project: Investigate a Dataset - TMDb Movie Data

## Table of Contents
<ul>
<li><a href="#intro">Introduction</a></li>
<li><a href="#wrangling">Data Wrangling</a></li>
<li><a href="#conclusions">Conclusions</a></li>
</ul>

<a id='intro'></a>
## Introduction

### Dataset Description 

> 
The TMDb Dataset contains information about 10000 plus movies collected from "The Movie Database". This is a csv dataset that contains 21 columns and 10866 rows

This TMDb dataset contains the following columns:
1. id - A unique identifier for each movie.
2. imdb_id - A unique identifier for each movie on the TMDb dataset.
3. popularity - A numeric representation of the movie popularity.
4. budget - The budget in which the movie was made.
5. revenue - The revenue generated per movie.
6. original_title - The title of the movie before released.
7. cast - The name of lead and supporting actors.
8. homepage - A link to the homepage of the movie.
9. director - the director(s) of the movie
10. tagline - Each movies tagline.
11. keywords - The keywords or tags associated to the movie.
12. overview - A brief description of the movie.
13. runtime - The runtime of the movie in minutes.
14. genres - The genre of the movie, Adventure, Drama, etc.
15. production_companies - The production house of the movie.
16. release_date - The date on which it was released.
17. vote_count - The number of votes per movie
18. vote_average - average ratings the movie recieved.
19. released_year - The year each movies was released
20. budget_adj - shows the full budget per movie in dollars.
21. revenue_adj - shows the full revenue per movie in dollars.



### Question(s) for Analysis

1. Are high budget movies more popular?
2. Which company produced the highest movies?

<a id='conclusions'></a>
## Conclusions

From my analysis:
Q1: There's a weak positive correlation between movies budget and popularity. This means most times the budget of a movie does not influence its popularity.

Q2: The companies from the known list of producers that produced the most movies is "Universal Pictures"



## Limitations

During my analysis of the production companies, I discovered that majority of the production companies data was not entered, hence did not really give an accurate results of the company that produced the most movies.