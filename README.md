# Netflix Data Cleaning, Analysis, and Visualization using Python

## Overview
This project focuses on cleaning, analyzing, and visualizing a Netflix dataset to explore patterns and gain insights into the content library. By performing data cleaning and using statistical analysis, we aim to uncover trends in content distribution across genres, countries, and ratings. The project also explores relationships between various attributes such as release year, content type (Movie/TV Show), and more through visualizations.

The analysis helps in understanding the variety of content available on Netflix and can be used for further trend analysis or content recommendation systems.

## Dataset
The dataset used in this project is available in a CSV file: [Netflix Dataset](https://github.com/aishwarya0404/Netflix-Data-Analysis-using-Python/blob/main/netflix_dataset.csv). It contains attributes such as:
- Show ID
- Type (Movie/TV Show)
- Title
- Director
- Cast
- Country
- Date Added
- Release Year
- Rating
- Duration
- Listed In (Genres)
- Description

## Installation
Ensure you have Python installed (preferably 3.7 or later).

Install the required packages using pip:

```bash
pip install pandas seaborn matplotlib plotly textblob
```

## Usage
1. Download the dataset and place it in the project folder.
2. Open and run the Jupyter Notebook `Netflix_Dataset_Analysis.ipynb`.
3. The notebook will perform data cleaning, analysis, and visualization tasks.

## Data Cleaning
Data cleaning steps include:
- Handling missing values in columns such as `director`, `cast`, `country`, etc.
- Dropping or imputing NaN values where necessary.
- Converting data types for specific columns (e.g., `date_added`) for further analysis.

## Data Analysis
The following analyses are performed:
- Understanding the distribution of content types (Movies vs TV Shows).
- Identifying the top genres and countries with the most content.
- Examining the release trends of content across different years.
- Understanding rating distribution and its impact on content type.

## Data Visualization
Various visualizations are created to enhance the analysis, including:
- **Count plots** to show the distribution of Movies and TV Shows.
- **Bar charts** for top genres, countries, and ratings.
- **Histograms** for numeric variables like release year and duration.
- **Scatter plots** to visualize relationships such as age of content vs. its duration.

## Sentiment Analysis 
A basic sentiment analysis on the content descriptions is performed using `TextBlob` to understand the sentiment polarity of the descriptions.

## Results
The analysis provides the following insights:
- The majority of content on Netflix is movies, with a smaller proportion of TV shows.
- The US dominates the content library, but other countries like India and the UK also contribute significantly.
- Recent content (released after 2015) is more prevalent.
- The most common genres include documentaries, stand-up comedies, and drama.

## Acknowledgments
- The dataset is sourced from [Kaggle Netflix Shows Dataset](https://www.kaggle.com/shivamb/netflix-shows).

---

