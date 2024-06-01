# House Price Analysis in Kenya

This project aims to perform extensive Exploratory Data Analysis (EDA) on housing data in Kenya. The dataset is sourced from BuyRentKenya and includes various features such as the number of bathrooms, bedrooms, external and internal features, location, nearby amenities, and price.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [1. Overview of the Data](#1-overview-of-the-data)
  - [2. Distribution Analysis](#2-distribution-analysis)
  - [3. Geographic Analysis](#3-geographic-analysis)
  - [4. Feature Analysis](#4-feature-analysis)
  - [5. Price Influencers](#5-price-influencers)
  - [6. Temporal Analysis](#6-temporal-analysis)
  - [7. Nearby Amenities](#7-nearby-amenities)
  - [8. Text Analysis](#8-text-analysis)
  - [9. Outlier Detection](#9-outlier-detection)
  - [10. Comparative Analysis](#10-comparative-analysis)
  - [11. Visualization Techniques](#12-visualization-techniques)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The primary goal of this project is to explore and analyze housing data in Kenya to uncover trends and insights that can inform potential buyers, investors, and real estate professionals.

## Dataset

The dataset was scraped from the BuyRentKenya website and contains the following columns:
- `bathrooms`: Number of bathrooms in the property.
- `bedrooms`: Number of bedrooms in the property.
- `external_features`: List of external features (e.g., Balcony, Parking).
- `internal_features`: List of internal features (e.g., En Suite, Fibre Internet).
- `location`: General location of the property.
- `nearby`: Nearby amenities (e.g., Shopping Centre, Hospital).
- `price`: Price of the property.
- `title`: Title or description of the listing.
- `price_bin`: Price range bin.
- `suburb`: Specific suburb of the property.
- `common_external`: Most common external features.
- `common_internal`: Most common internal features.
- `common_nearby`: Most common nearby amenities.

## Installation

To use this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/house-price-analysis-kenya.git
cd house-price-analysis-kenya
pip install -r requirements.txt
```
## Usage
Run the Jupyter notebook to perform EDA and visualize the data:

# Exploratory Data Analysis (EDA) for Housing Data

## 1. Overview of the Data
- **Shape of the Dataset**: Check the number of rows and columns.
- **Data Types**: Verify the data types of each column.
- **Missing Values**: Identify any missing values in the dataset and their proportions.
- **Summary Statistics**: Calculate mean, median, standard deviation, minimum, and maximum for numerical features.

## 2. Distribution Analysis
- **Price Distribution**: Plot the distribution of house prices using histograms and box plots.
- **Price Bins**: Analyze the distribution of houses across different price bins.
- **Bathrooms and Bedrooms Distribution**: Plot histograms and box plots for the number of bathrooms and bedrooms.

## 3. Geographic Analysis
- **Top Preferred Suburbs**: Identify and visualize the most common suburbs where houses are listed.
- **Suburb vs. Price**: Analyze the average house prices per suburb using bar plots or box plots.
- **Suburb vs. Features**: Explore how different features (e.g., external and internal features) vary across suburbs.

## 4. Feature Analysis
- **External and Internal Features**: Count the occurrences of each feature and identify the most common ones.
- **Feature Combinations**: Investigate common combinations of features in houses.
- **Correlation Analysis**: Compute and visualize the correlation matrix to see relationships between numerical features.

## 5. Price Influencers
- **Price vs. Bathrooms**: Analyze the relationship between the number of bathrooms and house prices.
- **Price vs. Bedrooms**: Analyze the relationship between the number of bedrooms and house prices.
- **Price vs. External/Internal Features**: Investigate how different features influence house prices.

## 7. Nearby Amenities
- **Top Nearby Amenities**: Identify and visualize the most common nearby amenities (e.g., schools, shopping centers).
- **Impact of Nearby Amenities on Price**: Analyze how the presence of certain amenities influences house prices.

## 8. Text Analysis
- **Title Analysis**: Perform text analysis on the titles to identify common words or phrases.
- **Word Clouds**: Create word clouds for the most frequent words in the titles.

## 9. Outlier Detection
- **Price Outliers**: Identify and visualize outliers in house prices using box plots.
- **Feature Outliers**: Identify outliers in other numerical features (e.g., unusually high number of bathrooms or bedrooms).

## 10. Comparative Analysis
- **Comparison by Suburb**: Compare different suburbs based on various features (e.g., average price, common features).
- **Comparison by Feature**: Compare houses with certain features (e.g., houses with swimming pools vs. houses without swimming pools).

## 11. Visualization Techniques
- **Bar Plots**: For categorical data analysis (e.g., top preferred suburbs).
- **Box Plots**: For understanding the distribution and outliers in numerical data.
- **Histograms**: For visualizing the distribution of numerical features.
- **Heatmaps**: For correlation analysis.
- **Scatter Plots**: For analyzing relationships between two numerical features.
- **Word Clouds**: For text analysis of the titles.


```bash
jupyter notebook Buy_Rent_Kenya_Analysis.ipynb
```
