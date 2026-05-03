# NYC Airbnb Price Analysis

This project explores Airbnb pricing trends in New York City using Python. The analysis focuses on understanding how factors such as location, room type, and availability influence listing prices.

---

## Objective

To analyse key drivers of Airbnb pricing in NYC and identify patterns in listing distribution and availability.

---

## Dataset

This project uses the New York City Airbnb Open Data dataset from Kaggle.

Source:
https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data 

---

## Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Excel (for additional pivot table analysis)

---

## Data Cleaning

The dataset was preprocessed before analysis:

- Missing values in `reviews_per_month` were filled with 0
- The `last_review` column was removed due to a high number of missing values and limited relevance

These steps ensured the dataset was suitable for exploratory data analysis.

---

## Analysis Performed

- Distribution of Airbnb prices (with visual filtering to improve readability)
- Average price by neighbourhood group
- Average price by room type
- Number of listings by neighbourhood group
- Availability of listings throughout the year

---

## Key Insights

- Manhattan has the highest average Airbnb prices, indicating strong demand and premium location value
- Entire homes/apartments are significantly more expensive than private and shared rooms
- The majority of listings are concentrated in Manhattan and Brooklyn
- Airbnb prices are right-skewed, with most listings priced between $50 and $150
- Many listings have low availability, suggesting high demand or frequent bookings

---

## Repository Contents

- `airbnb_analysis_final.ipynb` – main analysis notebook
- `airbnb_analysis_pivot_tables.xlsx` – additional analysis using Excel pivot tables

- ---

- ## Excel Analysis

The Excel pivot tables and charts are included in the file:

`airbnb_analysis_pivot_tables.xlsx`

Note: GitHub may not preview this file due to its size. Please download it to view the full analysis.


## Notes

The cleaned dataset is generated within the notebook and is not stored separately in this repository.
