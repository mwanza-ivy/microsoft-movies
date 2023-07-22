# Exploratory Data Analysis on Film Industry: Genres, Popularity and Profitability
            ![istockphoto-453554783-612x612](https://github.com/mwanza00/microsoft_movies/assets/137791910/e4a87b06-47f1-4018-9348-86a06d39713d)


## Big question: What factors should Microsoft take into account for success in its new streaming service venture?
How are box office revenue and ratings influenced by genre, budget and release date?
Hypotheses:
Positive correlation between budget and revenue

## Data understanding
In this lab, I have worked with two versions of comprehensive Movies Datasets. I have modified the structure and contents of the datasets somewhat for the purposes of this lab. 

The data is contained in two separate CSV files
movie_budgets.csv:  each record represents a movie, then has release date, production budget and revenue representing features of the movies.
tmdb_movies.csv: each record represents a movie genre_id, with attributes of that genre_id (e.g. popularity).

## Process & Tools Used
1. Researched what factors might go into movie success, possible variables, etc
2. Queried data and created visuals using Matplotlib to gain insight into any interesting relationships.

## How a movie's success is measured
A film's success is dependent on multiple factors:
1. Popularity
2. User reviews
3. Returns relative to the budget

## Findings
## Does release date affect revenue?

From the analysis, I have observed that the release month of a movie affects revenue. Movies released in May tend to generate the most revenue while movies released in September tend ti generate the least revenue. Microsoft should take note of this and consider producing movies during the most favorable months or seasons for releasing films in order to maximize revenue production. Films released in May tend to have higher box office success and therefore perform better financially. These are the months of the year that Microsoft's new movie studio should consider producing new movies.

![download](https://github.com/mwanza00/microsoft_movies/assets/137791910/2b377b64-1346-480e-a8bf-6867d9b88a2c)


## Are budget and revenue correlated?

The correlation coefficient between budget and worldwide gross is 0.748, indicating a moderate to strong positive correlation between production budget and revenue. This means that as the budget of a movie increases, there is a tendency for its revenue to increase as well. In other words, higher-budget movies tend to generate higher revenue on average. However, it's important to note that correlation does not imply causation, and there may still be significant variability in revenue that is not accounted for by the budget alone. While there is a positive relationship between budget and revenue, other factors may also influence revenue generation, such as marketing, genre, star power, and release timing. There are too many confounding variables to say with any confidence that an increased budget will lead to an increase in revenue. We recommend sticking with the range indicated in the dataset.

![download](https://github.com/mwanza00/microsoft_movies/assets/137791910/5442fd2f-0033-4ebb-863e-1b97ef4b2bd2)


## Which movie genres are crowd favorites?

The most popular movie genre is the movie genre_id [28,12,35,14]. Microssoft can create movies from the most successful genres since these genres have been consistently popular over recent years. These genres have a high potential for success therefore leading to high box office revenue.

![download](https://github.com/mwanza00/microsoft_movies/assets/137791910/1d30374b-ca71-43a4-938c-f7670a03b986)


## Does production month affect popularity of a genre?

There is a positive correlation coefficient between popularity and release month for each specific movie genre_id. Apart from audience preferences and popularity, another thing that Microsoft should take into account when producing different genres of movies is the release date. They should consider producing movies for each genre during the most favorable months or seasons for releasing films in that genre.

![download](https://github.com/mwanza00/microsoft_movies/assets/137791910/4312f928-86c6-4a0b-aa53-19e573e8625e)


## Does popularity affect vote average?

The positive correlation between a film's popularity, as measured by user votes indicates that there is a tendency for the popularity and vote_average to increase together. Films with higher popularity or better ratings tend to have higher box office success and therefore perform better financially. These are the type of films that the Microsoft's new movie studio should consider producing in order to maximize revenue production.

![download](https://github.com/mwanza00/microsoft_movies/assets/137791910/b7ce7a7f-089c-435a-8244-9764b7b8661a)

## Recommendations and Suggestions

Based on the visualized data, the recommended route for a brand new movie studio is to focus on producing films with high popularity or better ratings since they tend to have a high potential for success and perform better financially. They are the most successful genres in terms of box office revenue. Microsoft's new movie studio should produce movies during the most favorable months or seasons for releasing films, taking into account competition and audience preferences. The studio should also produce movies within higher budget ranges since they have shown the highest returns on investment.
