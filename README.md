# Analysis and Cleaning of the Product Dataset

## Note

The notebook contains extensive outputs generated during data exploration and analysis. Due to its size, GitHub may occasionally fail to render the notebook preview. If this happens, please download the notebook and open it Jupyter Notebook to view the complete contents.

## Overview

This project focuses on basic data exploration, cleaning, and preprocessing using Python and Pandas. The aim was to understand the dataset, handle missing values, perform simple data operations, create a new feature, and generate a cleaned dataset for further analysis.

## 1. Loading the Dataset

* Loaded the CSV dataset into a Pandas DataFrame and verified that it was imported correctly.

## 2. Exploring the Dataset

* Used functions such as `head()`, `tail()`, `shape`, `columns`, `dtypes`, and `info()` to understand the structure, dimensions, features, and data types of the dataset.

## 3. Handling Missing Values

* Identified columns containing missing values.
* Removed the `videos` column because a large percentage of its values were missing.
* Filled missing values in numerical columns using the median.
* Replaced missing values in categorical and text columns with `"Unknown"`.

## 4. Performing Basic Data Operations

* Selected important columns such as product title, rating, final price, and category.
* Applied filters to identify products with ratings greater than 4 and products with higher prices.
* Analyzed specific subsets of the dataset to gain useful insights.

## 5. Checking for Duplicate Records

* Reviewed the dataset and found no duplicate records.
* No duplicate removal was required.

## 6. Creating a New Feature

* Created a new column called `rating_score`.
* Calculated `rating_score` by multiplying the product rating by the number of ratings received.
* This metric combines both product quality and popularity into a single score.

## 7. Exporting the Cleaned Dataset

* Saved the cleaned dataset as a new CSV file for future analysis and use.

## Files Included

1. `Assignment_1.ipynb` – Complete notebook containing all data exploration and cleaning steps.
2. `cleaned_dataset.csv` – Cleaned version of the dataset.
3. `README.md` – Project documentation.
