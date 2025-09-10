# 🏠 Real Estate Dashboard in Tableau – Excel Data
This project outlines the creation of a Tableau dashboard visualizing real estate data sourced from an Excel file. The dashboard provides insights into average prices per bedroom, listing distributions by bedroom count, price variations by zip code, and yearly revenue trends.

## 📁 Data Structure

**Original Source**: Excel file containing raw real estate data.

**Visualized Output**: Tableau dashboard with multiple views.


## ✅ Dashboard Components
### 1. Average Price Per Bedroom

Description: Bar chart showing the average price per bedroom (1 to 6).

Key Data:
- 1 bedroom: $102.4
- 2 bedrooms: $200.7
- 3 bedrooms: $291.5
- 4 bedrooms: $334.8
- 5 bedrooms: $562.7
- 6 bedrooms: $661.4


Purpose: Highlights pricing trends based on bedroom count.

### 2. District Count of Bedroom Listings

Description: Bar chart displaying the total number of listings by bedroom count.

Key Data:

- 1 bedroom: 1,811 listings
- 2 bedrooms: 483 listings
- 3 bedrooms: 206 listings
- 4 bedrooms: 55 listings


Purpose: Provides an overview of listing distribution, excluding null values.

### 3. Price Per Zipcode

Description: Map view illustrating average prices across different zip codes.

Purpose: Enables spatial analysis of pricing trends.

### 4. Price by Zipcode

Description: Bar chart detailing average prices for various zip codes (e.g., 98134, 98119, etc.).
Purpose: Facilitates detailed price comparison by location.

### 5. Revenue for Year

Description: Line graph tracking revenue trends throughout 2016.

Purpose: Monitors revenue growth over time.

## 📊 Data Preparation

Source: Excel file with fields including bedroom count, price, zip code, and revenue.

Cleaning: Ensured data consistency by removing duplicates, handling null values, and standardizing formats (e.g., dates, zip codes).

Notes: Data reflects 2016 conditions and excludes listings with null bedroom values.

## 🚀 Usage

Explore pricing and listing trends using the bar charts and map.
Analyze revenue progression with the line graph.
Use filters in Tableau to customize views as needed.

## 📅 Date Context

Data is based on the year 2016, current as of the dashboard's creation.
