# Airbnb-Datasets-EDA-Project
![361236125-28234df7-a935-4fa5-bcbf-a8555152b5c7](https://github.com/user-attachments/assets/dae84a10-9cac-4651-9f84-3840d55bd002)
## Project Type
Exploratory Data Analysis
Contribution: Individual
## Airbnb Project Details
### Project Summary
The Airbnb project involves analyzing a dataset from Airbnb listings to derive insights that can help the business optimize its operations and improve customer satisfaction. The analysis focuses on understanding the factors that influence the pricing of listings, identifying trends in guest preferences, and uncovering key patterns in booking behavior. The project uses data science techniques such as exploratory data analysis (EDA), data visualization, and statistical modeling to achieve these objectives.

### Business Objective
The primary business objective of this project is to identify the key factors that affect the pricing of Airbnb listings and to understand guest preferences based on various listing attributes. By doing so, Airbnb can help hosts optimize their pricing strategies and improve the overall guest experience, leading to higher occupancy rates, better reviews, and increased revenue for both hosts and the platform.

### All About the Dataset
The dataset used for this project contains information about Airbnb listings in a specific location, such as New York City. It includes various attributes related to each listing, such as:

- **Listing ID:** Unique identifier for each listing.
- **Host ID:** Unique identifier for the host of the listing.
- **Neighborhood:** The neighborhood where the listing is located.
- **Room Type:** Type of accommodation (e.g., entire home/apt, private room, shared room).
- **Price:** The nightly price of the listing.
- **Minimum Nights:** The minimum number of nights required for booking.
- **Number of Reviews:** The total number of reviews received by the listing.
- **Last Review:** The date of the most recent review.
- **Reviews per Month:** Average number of reviews received per month.
- **Availability 365:** Number of days the listing is available for booking in a year.
- **Latitude and Longitude:** Geographical coordinates of the listing.
The dataset is rich with both numerical and categorical variables, making it suitable for various types of analyses.

### Understanding Variables
- **Categorical Variables:** Neighborhood, Room Type.
- **Numerical Variables:** Price, Minimum Nights, Number of Reviews, Reviews per Month, Availability 365.
- **Date Variables:** Last Review.
These variables allow us to explore various aspects of the listings, such as how location and room type affect pricing, or how the number of reviews correlates with availability and guest satisfaction.

### Manipulations and Wrangling Performed
Data manipulation and wrangling were essential steps in preparing the dataset for analysis. The following steps were performed:

- **Handling Missing Values:** Missing values were identified and appropriately handled. For example, missing values in the Last Review and Reviews per Month columns were filled with suitable imputed values.
- **Data Type Conversion:** Variables like Last Review were converted from string to date format for better analysis.
- **Outlier Detection and Removal:** Outliers in the Price and Minimum Nights columns were detected and removed to avoid skewing the analysis.
- **Feature Engineering:** New features, such as the number of days since the last review, were created to enhance the analysis.
- **Normalization:** Continuous variables were normalized to bring them to a common scale, making them more suitable for modeling.
### Solution to the Business Objective
To address the business objective, a series of analyses were conducted:

 - **Correlation Analysis:** A correlation heatmap was created to identify relationships between numerical variables, such as how availability affects pricing.
- **Pair Plots:** Pair plots were used to explore relationships between variables like price, number of reviews, and minimum nights, segmented by neighborhood.
- **Price Prediction Model:** A regression model was developed to predict the price of a listing based on its attributes. Important factors such as neighborhood, room type, and availability were found to have significant impacts on pricing.
- **Guest Preferences:** Analysis of reviews and availability provided insights into what guests value most, such as proximity to popular neighborhoods and the type of accommodation.
- 
### Conclusion
The analysis provided valuable insights into the factors that influence Airbnb pricing and guest preferences. By understanding these factors, hosts can better optimize their listings, set competitive prices, and enhance guest satisfaction. The project also demonstrated the importance of data cleaning and feature engineering in obtaining reliable results. The model developed can serve as a tool for hosts to predict optimal pricing strategies based on listing attributes.

## Thank You
