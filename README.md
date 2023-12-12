# Spotify_tracks_EDA
Spotify track EDA

# Introduction

The "Spotify Tracks Analysis" project involves the exploration and visualization of a dataset containing information about various Spotify tracks. The primary goal is to gain insights into the characteristics of the songs, identify patterns, and understand how certain features correlate with each other. The analysis is conducted using Python programming language and popular data analysis libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

# Data Loading and Cleaning

The project begins with loading the dataset using the Pandas library. The dataset, stored in a CSV file, includes information about each track, such as its ID, name, popularity, duration, artists, release date, and various musical features. To ensure data quality, initial checks are performed to identify missing values using the pd.isnull() and info() functions.

# Exploratory Data Analysis

## 1. 10 Least Popular Songs

The analysis starts by identifying and displaying the 10 least popular songs in the dataset. Songs are sorted based on their popularity in ascending order, and the relevant information is presented.


## 2. 10 Popular Songs with Popularity > 90
Another exploration focuses on showcasing the 10 most popular songs with a popularity score greater than 90. This information is filtered and sorted accordingly.

# Data Transformation
To facilitate further analysis, the project includes data transformation steps. The duration of the songs, initially provided in milliseconds, is converted to seconds for better interpretation. The "duration_ms" column is dropped, and a new "duration" column is created.

# Visualization
## Correlation Heatmap
A correlation heatmap is generated to visualize the relationships between numerical variables in the dataset. The heatmap provides insights into how different features correlate with each other. Certain columns, such as "key," "mode," and "explicit," are dropped before calculating the correlation. 
![download](https://github.com/DharshanR31/Spotify_tracks_EDA/assets/109989995/2b1b83cb-632d-46bf-bf0c-804034d6f144)

## Regression Plots
Two regression plots are created to explore relationships between specific pairs of variables. The first plot examines the correlation between loudness and energy, while the second analyzes the relationship between popularity and acousticness. These visualizations help in understanding the trends and patterns within the data.
![download](https://github.com/DharshanR31/Spotify_tracks_EDA/assets/109989995/9d7354d6-84bb-4450-8837-1146427e9471)
![download](https://github.com/DharshanR31/Spotify_tracks_EDA/assets/109989995/ca1ab50b-7c63-423e-b232-c55575cbd23a)


# Conclusion
The "Spotify Tracks Analysis" project offers a comprehensive exploration of the dataset, uncovering patterns, correlations, and trends in Spotify tracks. Through descriptive statistics and visualizations, the project provides valuable insights into the characteristics of songs, allowing for a better understanding of the musical landscape captured in the dataset.
