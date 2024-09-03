# Vehicle Analysis and Segmentation

This project focuses on analyzing car prices, performing segmentation, and visualizing various aspects of the dataset. The dataset contains various features like car name, year, selling price, mileage, engine size, fuel type, and more.

## Project Overview

The main objectives of this project include:
- **Data Cleaning:** Handling missing values, converting data types, and cleaning categorical data.
- **Exploratory Data Analysis (EDA):** Visualizing relationships between different features such as mileage, engine size, and selling price.
- **Segmentation:** Using K-Means clustering to segment cars into different groups based on features like mileage, engine size, and price.
- **Visualization:** Creating various plots to understand the distribution and relationship between the features.

## Dataset

The dataset used in this project includes the following columns:
- `name`: Car model name
- `year`: Year of manufacture
- `selling_price`: Selling price of the car
- `km_driven`: Kilometers driven
- `fuel`: Fuel type (Diesel, Petrol, LPG, CNG)
- `seller_type`: Seller type (Individual, Dealer, Trustmark Dealer)
- `transmission`: Transmission type (Manual, Automatic)
- `owner`: Number of previous owners
- `mileage`: Mileage of the car
- `engine`: Engine capacity in CC
- `max_power`: Maximum power in BHP
- `torque`: Torque of the car
- `seats`: Number of seats

## Key Steps

1. **Data Preprocessing:**
   - Cleaned and filled missing values for mileage, engine size, max power, torque, and seats.
   - Converted string data to numerical format where necessary.

2. **Exploratory Data Analysis (EDA):**
   - Visualized distributions and relationships using bar graphs, scatter plots, and pair plots.
   - Analyzed car prices over the years and relationships between engine size and mileage.

3. **Segmentation:**
   - Performed K-Means clustering to group similar cars based on selected features.
   - Evaluated cluster quality using the elbow method to choose the optimal number of clusters.

4. **Visualization:**
   - Plotted bar graphs, scatter plots, and pair plots to explore the data and clusters.
   - Visualized the car prices over the years and engine size vs. mileage.

## Visualizations

- **Car Prices Over the Years:** Displays how car prices have evolved over time using a bar graph.
- **Engine Size vs. Mileage:** A scatter plot showing the relationship between engine size and mileage.
- **Pair Plots for Clusters:** Visualizes clustering results to explore relationships among variables within clusters.

## Dependencies
 - Python 3.x
 - pandas
 - numpy
 - matplotlib
 - seaborn
 - scikit-learn

## Conclusion

This project provides insights into car prices and characteristics, helping to identify trends and patterns. The segmentation helps categorize cars into different groups, which could be valuable for pricing strategies, marketing, or customer segmentation
