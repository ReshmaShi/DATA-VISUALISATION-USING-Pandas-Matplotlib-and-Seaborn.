# Seaborn Taxis Dataset – Data Visualization

## 1. Project Overview

This project focuses on analyzing and visualizing the Taxis dataset using Python and data visualization libraries.

The main objective is to understand taxi trip data, identify patterns and relationships, and represent the findings using different types of charts.

## 2. Tools and Technologies Used

* Python
* Pandas
* Seaborn
* Matplotlib
* Jupyter Notebook

## 3. Dataset

The Taxis dataset is a built-in dataset available through Seaborn.

It contains information about taxi trips, including:

* Pickup and drop-off times
* Number of passengers
* Distance
* Fare
* Tip
* Tolls
* Total amount
* Payment method
* Pickup zone
* Drop-off zone
* Pickup borough
* Drop-off borough

## 4. Data Cleaning

The dataset was checked for missing values.

Missing values were identified in categorical columns such as payment method, pickup zone, drop-off zone, pickup borough, and drop-off borough.

The missing categorical values were handled using the mode of the respective columns.

## 5. Data Visualizations

### 5.1 Line Chart – Fare Over Time

A line chart was created to visualize how taxi fares change over pickup time.

**Analysis:**
This chart helps identify variations and trends in fare amounts over different pickup times.

### 5.2 Bar Chart – Total Fare by Pickup Borough

A bar chart was created to compare the total fare generated from different pickup boroughs.

**Analysis:**
This helps identify which pickup boroughs generated higher or lower total fare amounts.

### 5.3 Pie Chart – Trips by Payment Method

A pie chart was created to show the distribution of trips based on payment method.

**Analysis:**
Each slice represents the number of trips made using a particular payment method, allowing the proportion of different payment methods to be compared.

### 5.4 Histogram – Distribution of Trip Distance

A histogram was created to visualize the distribution of taxi trip distances.

**Analysis:**
The histogram shows how frequently different ranges of trip distances occur and helps understand the overall distribution of distances.

### 5.5 Box Plot – Tip Distribution by Pickup Borough

A box plot was created to visualize the distribution of tip amounts for each pickup borough.

**Analysis:**
The box plot helps compare the median, spread, and possible outliers in tip amounts across different pickup boroughs.

### 5.6 Count Plot – Number of Trips by Pickup Borough

A count plot was created to visualize the number of trips from each pickup borough.

**Analysis:**
It shows how many taxi trips started in each borough and makes it easy to compare trip counts between boroughs.

### 5.7 Scatter Plot – Distance vs Fare

A scatter plot was created to show the relationship between distance and fare.

The points were colored according to the pickup borough.

**Analysis:**
This visualization helps determine whether longer trips generally have higher fares. Different colors allow trips from different pickup boroughs to be differentiated.

### 5.8 Heatmap – Correlation Between Numerical Variables

A heatmap was created using a correlation matrix for distance, fare, tip, tolls, and total.

**Analysis:**
The heatmap helps identify the strength and direction of relationships between the numerical variables.

### 5.9 Pair Plot – Pairwise Relationships

A pair plot was created to visualize the pairwise relationships between distance, fare, tip, and total.

The data points were colored according to pickup zone.

**Analysis:**
The pair plot allows multiple numerical variables to be compared simultaneously and helps identify relationships and patterns between different variables across pickup zones.

### 5.10 Violin Plot – Fare Distribution by Payment Method

A violin plot was created to show the distribution of fare for each payment method.

**Analysis:**
The violin plot helps compare the distribution, spread, and concentration of fare amounts across different payment methods.

## 6. Key Learning Outcomes

Through this project, the following concepts were practiced:

* Loading and exploring a dataset
* Identifying and handling missing values
* Working with categorical and numerical variables
* Understanding correlation
* Creating statistical visualizations
* Comparing categories
* Analyzing distributions
* Identifying relationships between numerical variables
* Using Seaborn for data visualization
* Using Matplotlib for chart titles and axis labels

## 7. Conclusion

This project demonstrates how data visualization can be used to explore and understand taxi trip data.

Different charts provide different types of insights. Relationship charts such as scatter plots and pair plots help analyze numerical variables, while heatmaps show correlations. Histograms and violin plots help understand distributions, and bar, count, and pie charts help compare categorical data.
