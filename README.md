# Exploratory Data Analysis on Film Industry: Genres and Profitability
![image](https://github.com/mwanza00/microsoft_movies/assets/137791910/a8cec26f-9d46-404c-8e3c-baac968c9210)

## Big question: What movies should Microsoft invest in producing as part of its new streaming service venture?
How are box office revenue and ratings influenced by genre, budget and release date?
Hypotheses:
Positive correlation between budget and revenue

## Data understanding
In this lab, I have worked with a version of the comprehensive Movies Dataset Superheroes Dataset. I have modified the structure and contents of the dataset somewhat for the purposes of this lab. 

The data is contained in two separate CSV files
movie_budgets.csv:  each record represents a movie, then has release date, production budget and revenue representing features of the movies.
tmdb_movies.csv: each record represents a movie genre_id, with attributes of that genre_id (e.g. popularity).

## Process & Tools Used
1. Researched what factors might go into movie success, possible variables, etc
2. Queried data and created visuals using Matplotlib to gain insight into any interesting relationships.

## How a movie's success is measured
A film's success is dependent on multiple factors:
Popularity
User reviews
Returns relative to the budget

## Findings
## Does release date affect revenue?
![download](https://github.com/mwanza00/microsoft_movies/assets/137791910/097e6ea3-0c66-463e-841a-a941c83f38fd)


## Are budget and revenue correlated?

The relationship seemed somewhat positively correlated, with a correlation coefficient of 0.62, but there are too many confounding variables to say with any confidence that an increased budget will lead to an increase in revenue. We recommend sticking with the range indicated above

![download](https://github.com/mwanza00/microsoft_movies/assets/137791910/5442fd2f-0033-4ebb-863e-1b97ef4b2bd2)


## Which movie genres are crowd favorites?
![download](https://github.com/mwanza00/microsoft_movies/assets/137791910/1d30374b-ca71-43a4-938c-f7670a03b986)


## Does production month affect popularity of a genre?
![download](https://github.com/mwanza00/microsoft_movies/assets/137791910/4312f928-86c6-4a0b-aa53-19e573e8625e)


## Does popularity affect vote average?
The positive correlation between a film's popularity, as measured by user votes indicates that there is a tendency for the popularity and vote_average to increase together. Films with higher popularity or better ratings tend to have higher box office success and therefore perform better financially. These are the type of films that the Microsoft's new movie studio should consider producing

![download](https://github.com/mwanza00/microsoft_movies/assets/137791910/b7ce7a7f-089c-435a-8244-9764b7b8661a)

## Recommendations and Suggestions
### Does release date affect revenue?

##Specific questions I can explore using the dataset:
Genre Analysis: Determine the most successful genres in terms of box office revenue. Identify which genres have been consistently popular over recent years and have a high potential for success.

Budget vs. Revenue: Analyze the relationship between the budget allocated to a film and its box office revenue. Identify the budget ranges that have shown the highest return on investment.

Release Date Analysis: Study the impact of release dates on a film's box office performance. Identify the most favorable months or seasons for releasing films, taking into account competition and audience preferences.

Production Companies: Analyze the involvement of successful production companies in top-performing films. Identify which production companies have consistently produced successful movies and consider potential collaborations or partnerships.

Popularity and Vote Average: Explore the correlation between a film's popularity, as measured by user votes or ratings, and its box office success. Determine whether films with higher popularity or better ratings tend to perform better financially.

By analyzing these aspects of the dataset, we can provide actionable insights to the head of Microsoft's new movie studio, guiding their decision-making process in terms of film genres, budget allocation, release timing, and potential partnerships. These insights can help them develop a strategic plan to create successful movies and compete effectively in the film industry.

Doe
