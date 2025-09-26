# Introduction to Tableau: 
## Video Game Sales Analysis & [Airbnb Revenue Optimization](#project-2-airbnb-revenue-optimization) Projects

In this project, I explore video game sales data to uncover trends in revenue by genre, platform, and over time. The objective is to provide actionable insights into the performance of different types of games across markets and platforms.

---

## 📑 Table of Contents
[Preparing the Data](#step-1-preparing-the-data) | [Global Sales by Genre](#step-2-global-sales-by-genre) | [Revenue Trends Over Time](#step-3-revenue-trends-over-time) | [Dashboard Assembly](#step-4-dashboard-assembly) | [Final Project](#final-project)

---

## 📊 Tools Utilized

- `Tableau Public`: _data visualization and interactive dashboarding_  
- `Video Game Sales Dataset`: _sample dataset available [HERE via kaggle](https://www.kaggle.com/datasets/gregorut/videogamesales)_  

---

## Step 1: Preparing the Data

The project starts off with loading the sample videogame sales dataset into Tableau. This provides a spreadsheet of the raw data, totaling 16,598 rows, which will serve as the foundation for aggregation and subsequent visualizations. <br>
<Br>
<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/0ddfc35b-abef-4cc6-b9ef-cc1c5a67341d" />

## Step 2: Global Sales by Genre

The analysis begins with a basic bar graph showing Global Sales across different Genres. This provides a simple yet clear overview of which types of games generate the most revenue, providing the starting point for deeper insights.

<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/e05dacb1-4f87-4743-9326-094071a98999" />


## Step 3: Revenue Trends Over Time

To start, Year and Global Sales are added to a basic visualization to map revenue trends over time. The initial chart is then enriched with additional features such as Genre, color coding, and labels, providing deeper insight into how different types of games contribute to overall sales.

The data can also be filtered and grouped by Platform, allowing for more targeted analysis of revenue trends across specific gaming systems.

<Br>

<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/abe7fda5-e643-4ed2-8a0a-c40887e076df" />

<Br>


<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/35f6399c-8eee-4edc-9a81-34de70e5f2df" />

<Br>


<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/8c4a8e86-d87d-4182-910c-7ba289ddce17" />

<Br>


<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/391a1d7a-87d4-4b07-a828-dc8d407efba1" />

<Br>



<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/4c24c3b7-296b-4850-bdca-c2522f6db5d7" />

<Br>



<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/1ce8ebbb-b5bc-4080-94ee-0187d5d98bb0" />

<Br>
<Br>

## Step 4: Dashboard Assembly

Sheets 1 and 2 are combined into a single interactive dashboard, providing quick access to both the global sales by genre and revenue trends over time. This consolidated view allows users to explore insights efficiently and make data-driven decisions at a glance.
<br>


<img width="1280" height="764" alt="image" src="https://github.com/user-attachments/assets/7f3d15d9-7815-484c-b2b3-7fa8b0ead0cf" />

---
<br>
<br>
<br>


# Project 2: Airbnb Revenue Optimization
In this project, I explore how to identify the best times and locations for maximizing Airbnb rental income. The objective is to provide actionable insights for hosts seeking to increase profitability.

**Beginning:** the client has raw Airbnb listing and booking data but no clear understanding of seasonal patterns, geographic trends, or pricing opportunities.

**Completion:** an interactive Tableau dashboard highlights key metrics such as revenue by neighborhood, seasonal demand fluctuations, and average nightly rates, giving the client a data-driven view of when and where to maximize earnings.

## 📑 Table of Contents
[Data Preparation](#step-1-data-preparation) | [Pricing Trends](#step-2-neighborhood-pricing-trends) | [Geographic Visualization](#step-3-geographic-revenue-visualization) | [Seasonal Trends](#step-4-seasonal-pricing-trends) | [Price per Bedroom](#step-5-average-price-per-bedroom) | [Dashboard Assembly](#step-6-dashboard-assembly) | [Interactive Dashboard](#final-project)


---


## 📊 Tools Utilized

`Tableau Public:` _data visualization and interactive dashboarding_

`Public Airbnb Dataset:` _sample dataset available_ [HERE via kaggle](https://www.kaggle.com/datasets/alexanderfreberg/airbnb-listings-2016-dataset)

<br>

## Step 1: Data Preparation
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
<Br>

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

## Final Project
Access the full interactive dashboard here:  
[Airbnb Revenue Optimization Dashboard](https://public.tableau.com/app/profile/justin.soflin/viz/AirbnbFinalProject_17587402051360/Dashboard1?publish=yes)
