# Goodreads Reading Analysis

## Overview

This project analyses my Goodreads reading history using Python, Pandas, and Matplotlib. The dataset was exported directly from Goodreads and includes information such as book titles, authors, ratings, page counts, and reading dates.

The goal of this project was to perform exploratory data analysis and identify trends in my reading habits between 2024 and 2026.

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Dataset

Source: Goodreads Library Export
For privacy reasons, personal notes and review text were removed from the dataset before analysis.

Key fields used:
- Title
- Author
- My Rating
- Number of Pages
- Date Read
- Exclusive Shelf

## Data Preparation

The dataset was cleaned and prepared by:

- Filtering books marked as "read"
- Checking for duplicate titles
- Validating missing values
- Converting dates to datetime format
- Creating Year Read and Month Read features
- Excluding unrated books from rating analysis

## Analysis Performed

- General reading statistics
- Books read per year
- Pages read per year
- Books read per month
- Rating distribution
- Reading behaviour summary

## Key Findings

- Reading volume remained stable between 2024 and 2025 (28 and 27 books respectively).
- Total pages read decreased from 7,466 in 2024 to 6,508 in 2025.
- Average book rating exceeded 4 stars.
- Most books read were under 300 pages.
- Reading activity was concentrated in specific months rather than evenly distributed throughout the year.

## Future Improvements

Possible extensions to this project include:

- Enriching the dataset with genre information from external book metadata sources.
- Integrating the Google Books API to automate metadata collection.