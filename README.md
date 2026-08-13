Netflix Movies Data Analysis 🎬
Description

An exploratory data analysis (EDA) project on a movies dataset (mymoviedb.csv), performed using Python, Pandas, and Seaborn. The project covers data cleaning, feature engineering, and visualization to answer key questions about movie genres, popularity, and vote trends.

What I did
Data Cleaning: Checked for missing values and duplicates (dataset was already clean — 9,827 rows × 9 columns, no NaNs or duplicates).
Feature Engineering:
Converted Release_Date to datetime and extracted the release year.
Dropped irrelevant columns (Overview, Original_Language, Poster_Url) not useful for analysis.
Categorized Vote_Average into quartile-based bins (not_popular, below_avg, average, popular) using a custom function.
Split and exploded the Genre column (originally comma-separated) so each row represents a single movie-genre pair.
Data Visualization: Used Seaborn count plots and histograms to explore genre distribution, vote distribution, and release year trends.
Key Insights
Drama is the most frequent genre, appearing in over 14% of entries across 19 genres.
Drama also dominates in popularity, accounting for over 18.5% of movies with a "popular" vote rating.
Spider-Man: No Way Home has the highest popularity score (genres: Action, Adventure, Science Fiction).
2020 was the year with the highest number of films released in the dataset.
Tech Stack

Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook
