# Introduction to Tableau: Video Game Sales Analysis

## Table of Contents
1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Project Structure](#project-structure)
4. [Key Insights](#key-insights)
5. [How to Explore](#how-to-explore)
6. [Next Steps](#next-steps)

---

## Overview
This project analyzes video game sales data to identify trends and insights across platforms, genres, and publishers. The focus is on presenting data in a clear and interactive way to support informed conclusions.

---

## Dataset
The dataset used is publicly available and contains information on:

- Game title
- Platform
- Year of release
- Genre
- Publisher
- Global sales

> **Note:** The dataset was downloaded from [source link] for educational purposes.

---

## Project Structure


- `data/` → raw dataset  
- `tableau_workbooks/` → interactive workbook files  
- `screenshots/` → static images of dashboards for preview  
- `README.md` → project description and context  

---

## Key Insights
Some example insights highlighted in the analysis:

1. Top-selling games and the platforms that dominate sales.  
2. Genre trends over time and how they impact revenue.  
3. Publisher performance across regions.  
4. Regional sales patterns and comparisons.  

---

## How to Explore
1. Open the Tableau workbook (`.twbx`) in Tableau Desktop or Tableau Public.  
2. Interact with dashboards, filters, and charts to explore the data.  
3. View screenshots in the `screenshots/` folder for a quick overview.

---

## Next Steps
- Expand the analysis with additional datasets, such as user reviews or ratings.  
- Add calculated fields and more advanced visualizations.  
- Incorporate further interactivity into dashboards for enhanced insights.  






<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/0ddfc35b-abef-4cc6-b9ef-cc1c5a67341d" />



<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/abe7fda5-e643-4ed2-8a0a-c40887e076df" />

<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/35f6399c-8eee-4edc-9a81-34de70e5f2df" />

<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/8c4a8e86-d87d-4182-910c-7ba289ddce17" />

<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/391a1d7a-87d4-4b07-a828-dc8d407efba1" />


<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/4c24c3b7-296b-4850-bdca-c2522f6db5d7" />


<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/1ce8ebbb-b5bc-4080-94ee-0187d5d98bb0" />


<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/e05dacb1-4f87-4743-9326-094071a98999" />

<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/7f3d15d9-7815-484c-b2b3-7fa8b0ead0cf" />

<br>
<br>
<br>


# Airbnb Revenue Optimization with Tableau
In this project, I explore how to identify the best times and locations for maximizing Airbnb rental income. The objective is to provide actionable insights for hosts seeking to increase profitability.

**Beginning:** the client has raw Airbnb listing and booking data but no clear understanding of seasonal patterns, geographic trends, or pricing opportunities.

**Completion:** an interactive Tableau dashboard highlights key metrics such as revenue by neighborhood, seasonal demand fluctuations, and average nightly rates, giving the client a data-driven view of when and where to maximize earnings.

## 📊 Tools Utilized

`Tableau Public:` _data visualization and interactive dashboarding_

`Public Airbnb Dataset:` _sample dataset available_ HERE

<Br>
<br>

## Step 1) Preparing the Data
The analysis starts with an inner join of the Listings dataset and the Calendar dataset to combine property details with availability and pricing information.
<Br>
<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/ab6c8ac4-eda3-4ea7-ae75-ecbfb39886a8" />

<br>

## Step 2: Neighborhood Pricing Trends
Starting with the first worksheet, I pair Zip Code (columns) with Price (rows), adjusting the aggregation to average price instead of total sum. After changing the bar chart to be color coded, this highlights the neighborhoods where potential hosts can expect the highest returns.
<br>
<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/62740ea8-3b2b-4422-8dd7-855b0be737e9" />

<br>

## Step 3: Geographic Revenue Visualization
Using the generated latitude and longitude data, I build a filled map to provide a geographic view of average earnings. This visualization allows potential hosts to quickly identify which areas are most profitable at a glance.
<br>

<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/15b847ba-455d-4db2-a3bd-11742215cba5" />

<br>

## Step 4: Seasonal Pricing Trends
On the next worksheet, I graph average price by week to uncover seasonal patterns in rental demand. This view highlights the best times of year for hosts to list their properties at higher rates. As expected, profitability peaks during popular travel periods such as summer and the holidays—this visualization provides clear evidence of those trends.

<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/3eaf9e72-9a42-4d2c-a823-0e9dccaf87d7" />

## Step 5: Average Price per Bedroom
The final worksheet presents a bar chart of average price segmented by number of bedrooms. As expected, listings with more bedrooms command higher prices. To ensure accuracy, entries with null or zero bedrooms are excluded from the analysis.<Br>
<br>

<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/6dc539ca-cceb-44a7-bdd8-dba72e1862e9" />

<br>

## Step 6: Dashboard Assembly
All five worksheets are combined into a single interactive dashboard for streamlined analysis and quick insights. This consolidated view equips hosts with actionable data to make informed decisions. It is expected that clients may have follow-up questions or requests for additional information, which can be addressed as part of ongoing support.
<Br>
<br>
<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/56ca0372-3098-494e-aaec-c105a8682ea5" />

<br> 

## Final Project:
https://public.tableau.com/app/profile/justin.soflin/viz/AirbnbFinalProject_17587402051360/Dashboard1?publish=yes
