# Geospatial Data Analysis

## Project Overview

This project analyzes location-based regional data to identify high-demand geographic clusters and potential underserved markets.

The project uses Python, Pandas, and Folium to clean regional data, calculate revenue and user metrics, and create an interactive geographical visualization.

## Objective

The main objectives of this project are:

- Clean regional data using State, City, and Postal Code.
- Analyze revenue by geographic region.
- Analyze user density by region.
- Identify high-demand geographic clusters.
- Detect potentially underserved regions.
- Identify the top 3 potential expansion areas.
- Create an interactive geographical map.

## Technologies Used

- Python
- Pandas
- Folium
- Jupyter Notebook
- HTML
- CSV
- ReportLab

## Dataset

The demonstration dataset contains regional information including:

- State
- City
- Postal Code
- Revenue
- Users
- Latitude
- Longitude

**Note:** This repository currently uses a synthetic demonstration dataset because an original business dataset was not provided.

## Analysis Process

1. Load the regional dataset.
2. Remove duplicate records.
3. Handle missing values.
4. Validate numerical data.
5. Aggregate revenue and users by region.
6. Calculate revenue per user.
7. Calculate a demand indicator.
8. Calculate an underserved-market screening score.
9. Generate an interactive Folium map.
10. Identify the top 3 potential expansion regions.

## Interactive Map

Open:

`Geospatial_Data_Analysis_Map.html`

The map provides:

- Geographic markers
- Revenue information
- User information
- User-density visualization
- Potential underserved regions
- Interactive popups

## Top 3 Demonstration Regions

Based on the demonstration dataset and screening score:

1. Patna, Bihar
2. Lucknow, Uttar Pradesh
3. Bhubaneswar, Odisha

These are demonstration results and should be recalculated when actual regional business data is available.

## Project Files

| File | Description |
|---|---|
| `Geospatial_Data_Analysis_Report.pdf` | Complete project report |
| `Geospatial_Data_Analysis.ipynb` | Python analysis notebook |
| `Geospatial_Data_Analysis_Map.html` | Interactive geographical map |
| `regional_sales_dataset.csv` | Demonstration dataset |

## Conclusion

Geospatial analysis helps organizations understand where customers are concentrated, compare regional performance, and identify locations that may offer expansion opportunities.

The interactive map makes regional patterns easier to understand, while the analytical scoring method provides a simple way to shortlist potential underserved markets.

## Author

Vanshika Kotiya
