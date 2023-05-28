# Unleashing the Power of Data: Analyzing Box Offices Success to Shape Microsoft's New Movie Studio strategy

## Overview

This project aims to explore the types of films that are currently performing well at the box office and provide actionable insights for Microsoft's new movie studio. The goal is to help Microsoft make informed decisions about the types of films they should create in order to succeed in the competitive movie industry.
Business Understanding

Stakeholder: Head of Microsoft's new movie studio
Key Business Questions:

    What types of films are currently performing the best at the box office?
    How can Microsoft leverage this information to make strategic decisions about film production?
    What recommendations can be made to help Microsoft's movie studio thrive?

## Data Understanding and Analysis

The data being used is from `im.db` database. The database has 8 tables:

>>- movie_basics
>>- directors
>>- known_for
>>- movie_akas
>>- movie_ratings
>>- persons
>>- principals
>>- writers

The `movie_ratings` and `movie_basics` tables will be used in the analysis. `movie_ratings` provides information on movie ratings while `movie_basics` table provides information on various movie attributes such as start_year, runtime and genre.

Visualizations:

    Bar Chart: A bar chart of counts of movie genres
        This visualization shows the popular film genres ranked by their count. It helps identify the most lucrative genres in terms of revenue generation.

    Box Plot: 
        provides a summary of the distribution of a genre's ratings. It displays key measures of the data's central tendency, spread, and potential outliers.

    Pie Chart: Top 10 Film Genres by Production Budget
        This visualization displays the proportions of movie genres in the whole dataset. 

## Conclusion

    Action, Comedy and Documentary genres tend to perform exceptionally well at the box office, generating the highest average revenue. Microsoft's movie studio should consider producing films in these genres to maximize their chances of success.

    The average box office gross has shown an upward trend over the years, indicating a growing market. Microsoft should capitalize on this trend by investing in high-quality productions that align with audience preferences.

    While high production budgets can result in higher box office gross, it is important to strike a balance between investment and potential returns. Microsoft should carefully evaluate the production budgets of different genres and consider cost-effective strategies without compromising the overall quality of the films.
