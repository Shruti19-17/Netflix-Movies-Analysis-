## 📌 Project Overview
This project analyzes a dataset of 9,827 Netflix movies to uncover insights about genres, popularity, votes, and release trends. The workflow includes data cleaning, transformation, categorization, and visualization using Python libraries in Jupyter Notebook.

## ⚙️ Tech Stack
Python

Pandas – data cleaning & preprocessing

NumPy – numerical operations

Matplotlib & Seaborn – visualizations

Jupyter Notebook – interactive analysis

## 🧹 Data Cleaning Steps
Converted Release_Date column into datetime and extracted year values.

Dropped irrelevant columns: Overview, Original_Language, Poster_Url.

Categorized Vote_Average into quartile‑based labels:

not_popular, below_avg, average, popular.

Split multi‑genre strings into lists and exploded them into single rows.

## 📊 Exploratory Data Analysis
Dataset size after cleaning: 25,551 rows × 6 columns.

Most frequent genre: 🎭 Drama (appears in ~14% of movies).

Votes distribution: 25.5% of movies categorized as popular.

Highest popularity movie: Spider‑Man: No Way Home (Genres: Action, Adventure, Science Fiction).

Lowest popularity movies: The United States vs. Billie Holiday and Threads.

Year with most movies filmed: 2020.

## 📈 Visualizations
Genre distribution bar chart (Drama, Comedy, Action dominate).

Vote category distribution (popular vs average vs below_avg vs not_popular).

Popularity extremes (highest vs lowest).

Release year histogram showing production trends.

## ✅ Key Insights
Drama is the most dominant genre on Netflix.

Popular movies tend to cluster in genres like Drama, Action, and Adventure.

Spider‑Man: No Way Home stands out as the most popular movie in the dataset.

2020 saw the highest number of movie releases.

## Here is the Dataset

Casted Genre and Vote_Average into categorical types for efficient analysis.

Removed missing values to ensure a tidy dataset.
