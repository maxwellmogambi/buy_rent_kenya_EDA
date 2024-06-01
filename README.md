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
  - [11. Clustering Analysis](#11-clustering-analysis)
  - [12. Visualization Techniques](#12-visualization-techniques)
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

```bash
jupyter notebook Buy_Rent_Kenya_Analysis.ipynb
```
