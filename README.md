Car Info Analysis SQL Queries
This repository contains a collection of SQL queries for analyzing a dataset of car information, specifically focusing on various attributes such as selling price, mileage, fuel type, transmission, and more. These queries provide insights into car data, helping identify trends and patterns in the automotive market.

Table of Contents
Overview
Queries
How to Use
License
Overview
The dataset car_info includes the following fields:

Name: Car model name
transmission: Type of transmission (e.g., Manual, Automatic)
owner: Number of previous owners
fuel: Type of fuel (e.g., Petrol, Diesel, CNG)
seats: Number of seats in the car
selling_price: Price at which the car was sold
mileage: Car mileage (km per liter)
km_driven: Total kilometers driven by the car
year: Manufacturing year of the car
The SQL queries in this repository aim to analyze the dataset to identify trends, outliers, and patterns related to car prices, mileage, and more.

Queries
Average Selling Price by Fuel Type:

Calculates the average selling price of cars with a manual transmission and owned by the first owner, grouped by fuel type.
Top 3 Car Models by Average Mileage:

Finds the top 3 car models with the highest average mileage, considering only cars with more than 5 seats.
Difference in Selling Price:

Identifies car models where the difference between the maximum and minimum selling prices is greater than $10,000.
Cars Above Average Price and Below Average Mileage:

Retrieves car models with a selling price above the overall average and a mileage below the overall average.
Cumulative Sum of Selling Prices:

Calculates the cumulative sum of the selling prices over the years for each car model.
Cars Within 10% of Average Selling Price:

Identifies car models whose selling price is within 10% of the overall average selling price.
Exponential Moving Average (EMA) of Selling Prices:

Calculates the Exponential Moving Average (EMA) of selling prices for each car model, with a smoothing factor of 0.2.
Decrease in Selling Price from Previous Year:

Identifies car models that have experienced a decrease in selling price compared to the previous year.
Highest Total Mileage per Transmission Type:

Retrieves car models with the highest total mileage for each transmission type.
Average Selling Price per Year for Top Car Models:

Calculates the average selling price per year for the top 3 car models with the highest overall selling prices.
