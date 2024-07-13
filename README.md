# EDA on Google Play Store 📱

## Table of Contents
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Data Description](#data-description)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [How to Run](#how-to-run)


## Introduction
This project involves conducting an Exploratory Data Analysis (EDA) on the Google Play Store dataset. The goal is to derive insights and trends from the data related to app ratings, reviews, genres, and pricing models.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure
EDA-on-Google-Play-Store/
├── data/
│ ├── googleplaystore.csv
├── notebooks/
│ ├── EDA_Google_Play_Store.ipynb
├── images/
│ ├── visualizations/
├── README.md


## Data Description
The dataset contains information about various apps on the Google Play Store, including:
- App Name
- Category
- Rating
- Reviews
- Size
- Installs
- Type (Free/Paid)
- Price
- Content Rating
- Genres
- Last Updated
- Current Version
- Android Version

## Exploratory Data Analysis
In the EDA, the following analyses were performed:
- Data Cleaning: Handling missing values, correcting data types.
- Descriptive Statistics: Summary statistics of the data.
- Distribution Analysis: Histograms and KDE plots of numerical features.
- Correlation Analysis: Heatmaps to identify relationships between features.
- Genre Analysis: Analysis of app genres and their popularity.
- Rating Analysis: Insights into app ratings and factors affecting ratings.
- Price Analysis: Distribution and trends of app prices.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Yagnik9734/EDA-Playstore.git                                                                             2. Navigate to the project directory:
   cd EDA-on-Google-Play-Store
3. Install the required dependencies:
   pip install -r requirements.txt
4. Open the Jupyter Notebook:
   jupyter notebook notebooks/EDA_Google_Play_Store.ipynb
