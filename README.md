# Data Science Assignment 2- Cleaned Datasets
**Version:** v1.0  
**Date:** October 16, 2026

## Netflix Movies and TV Shows
**Source:** [Netflix Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
**Original dataset:** 8,807 rows and 12 columns  
**Cleaned dataset:** 8,807 rows and 17 columns

### Cleaning Performed
- Replaced missing director, cast, country and rating values with Unknown.
- Corrected three movie durations incorrectly stored in the rating column.
- Converted dates into datetime format.
- Created year_added, movie_minutes, tv_seasons, num_countries and num_genres.
- Retained valid outliers and missing dates.

## Supermarket Sales

**Source:** Instructor-provided supermarket_Sales.csv

**Original dataset:** 1,000 rows and 17 columns  
**Cleaned dataset:** 1,000 rows and 20 columns

### Cleaning Performed
- Converted Date and Time into appropriate formats.
- Created hour, weekday and month columns.
- Verified that no missing values or duplicate records were present.
- Retained nine valid high-value transactions identified as outliers.
- Kept the original financial columns.

## Version History

**v1.0 — October 16, 2026**

These datasets will also be used in Assignment 3.

