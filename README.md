# Food Delivery  Data Analysis – Hackathon

## Project Description
This repository contains my solution for a technical hackathon focused on
data integration and analysis. The task involved working with datasets
coming from different sources and formats and creating a single, clean
dataset for analysis.

## Data Sources
Three datasets were provided as part of the hackathon:
- Order-level transactional data in CSV format
- User-related information in JSON format
- Restaurant details, including cuisine and ratings, in SQL format

## Data Processing
The datasets were loaded using Python and merged using left joins based on
appropriate keys. After merging, unnecessary columns were removed and
column names were cleaned to improve readability.

## Final Dataset
The file `final_food_delivery_dataset.csv` represents the final merged
dataset. All analytical questions in the hackathon were answered using
this dataset only.

## Analysis Performed
- Order and revenue analysis
- User behavior analysis based on membership type
- City-wise and cuisine-wise performance evaluation
- Rating-based and time-based insights

## Technologies Used
- Python
- Pandas
- NumPy
- SQLite
- Jupyter Notebook

## Purpose
This project demonstrates practical data handling, cleaning, and analysis
skills as part of an online internship evaluation.
