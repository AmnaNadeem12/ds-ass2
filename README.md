# Data Science Assignment 2 – Cleaned Datasets




## Files
- 23L_0791_A2_netflix_cleaned.csv
- 23L_0791_A2_supermarket_cleaned.csv

## Netflix (8,807 rows, 27 columns)
Source: Netflix Movies and TV Shows, Kaggle (https://www.kaggle.com/datasets/shivamb/netflix-shows). All credit to the original author.

What I changed:
- Removed extra spaces from text columns.
- Moved 3 durations that were wrongly stored in the rating column back to duration.
- Filled missing director, cast, country and rating with "Unknown".
- Changed date_added to a date type (10 missing dates left empty).
- Split duration into duration_min (movies) and n_seasons (TV shows).
- Added columns: year_added, month_added, year_gap, gap_negative, n_countries, n_directors, n_cast, n_genres, primary_country, primary_genre, release_decade, rating_group, movie_duration_outlier.
- No duplicates found. Outliers were kept and only flagged.

## Supermarket Sales (1,000 rows, 21 columns)
Source: supermarket_Sales.csv provided by the course instructor.

What I changed:
- Changed Date to a date type and kept Time as text.
- Added columns: Month, Weekday, Hour, Is_weekend.
- No missing values, duplicates or wrong values were found, so nothing was removed.
- Large Total outliers (9 rows) were kept.
- Branch/City and the money columns (Tax 5%, Cost of goods sold, Total, Gross income) are kept but are redundant.

## Version history
- v1.0 (19 October 2026): first version used for Assignment 2.
