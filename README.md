# Book Recommender System

This repository contains a series of Jupyter notebooks and datasets that document the process of creating a book recommender system. The system was built using data scraped from Goodreads, covering the top 100 best books published in 2023, an extensive GoodReads dataset containing 100k books and utilizes a KMeans clustering algorithm to provide recommendations.

## Repository Structure

- `0. Data Links and Explanations`: This notebook contains links to the data sources used, along with explanations of why and how the data was gathered.

- `1. Data Import and Inspection`: The initial data import steps are detailed here, along with the first look at the raw data structures.

- `2. Data Cleaning`: A crucial step where the data is cleaned and preprocessed, including handling missing values, outliers, and standardizing text values.

- `3. Exploratory Data Analysis (EDA)`: This notebook explores the data visually and statistically to uncover patterns, trends, and relationships.

- `4. Feature Engineering and Model Preparation`: This stage refines the dataset by performing sentiment analysis on book descriptions, encoding genres, and normalizing numerical features. The process culminates in the use of K-Means clustering to group books, with the final model evaluated based on cluster homogeneity and the silhouette score, eschewing 'total_ratings' for a content-based recommendation approach.

- `5. Book Recommender`: The final notebook where the recommender system is implemented, tested, and validated.

- `Data/`: A folder containing all the CSV files of datasets used throughout the project.

## How to Use

To use the recommender system:

1. Ensure all files from the Data folder are downloaded. Make sure to run everything in the same directory.

2. Start with notebook `0. Data Links and Explanations` to understand the data sources.

3. Proceed through the notebooks in numerical order, as each notebook builds upon the work done in the previous ones.

4. To get a recommendation, run the final notebook `5. Book Recommender`. You will be prompted to enter a book title and author name. Based on this input, the system will either provide a recommendation from the existing dataset or fetch information online to generate a recommendation.

## Documentation

Each notebook is well-documented with markdown cells explaining the steps taken, the rationale behind them, and interpretations of the results. Comments in code cells provide additional context for the code being run.

## Contributing

Contributions are welcome, and any feedback or suggestions can be made by opening an issue or a pull request.

---
