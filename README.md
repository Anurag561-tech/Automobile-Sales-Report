# Automobile-Sales-Report

## Project Overview
This project analyzes the impact of recession periods on automobile sales for XYZAutomotives. The objective is to provide insights to the company's directors on how sales were affected during times of recession. The project is divided into three parts:

- **Part 1:** Create visualizations using Matplotlib, Seaborn, and Folium.
- **Part 2:** Build an interactive dashboard using Plotly and Dash.

## Dataset Description
The dataset used in this project contains historical automobile sales data, including variables such as:

- **Date:** The date of the observation.
- **Recession:** A binary variable indicating recession periods (`1` for recession, `0` for normal).
- **Automobile_Sales:** The number of vehicles sold during the period.
- **GDP:** The per capita GDP value in USD.
- **Unemployment_Rate:** The monthly unemployment rate.
- **Consumer_Confidence:** An index representing consumer confidence.
- **Seasonality_Weight:** The weight representing the seasonality effect on sales.
- **Price:** The average vehicle price during the period.
- **Advertising_Expenditure:** The company's advertising expenditure.
- **Vehicle_Type:** The type of vehicles sold (e.g., Superminicar, Smallfamilycar).
- **Competition:** The measure of competition in the market.
- **Month:** The month of the observation.
- **Year:** The year of the observation.



## Part 1: Visualizations

### Task 1.1: Yearly Sales Fluctuation
- Created a line chart using Pandas to show how automobile sales fluctuate from year to year.

### Task 1.2: Vehicle Type Sales Trends
- Plotted different lines for categories of vehicle type to analyze sales trends during recession periods.

### Task 1.3: Recession vs. Non-Recession Sales Comparison
- Used Seaborn to visualize and compare the sales trend per vehicle type for recession and non-recession periods.

### Task 1.4: GDP Comparison During Recession and Non-Recession Periods
- Developed line plots to compare GDP variations using subplots.

### Task 1.5: Seasonality Impact on Sales
- Created a bubble plot to display the impact of seasonality on automobile sales.

### Task 1.6: Price vs. Sales Volume Correlation
- Used Matplotlib to develop a scatter plot to identify the correlation between average vehicle price and sales volume during recessions.

### Task 1.7: Advertising Expenditure During Recession vs. Non-Recession
- Created a pie chart to display the portion of advertising expenditure during recession and non-recession periods.

### Task 1.8: Advertisement Expenditure by Vehicle Type During Recession
- Developed a pie chart to display the total advertisement expenditure for each vehicle type during the recession period.

### Task 1.9: Unemployment Rate and Sales Analysis
- Created a line plot to analyze the effect of the unemployment rate on vehicle type and sales during the recession period.

## Part 2: Dashboard Creation

### Task 2.1: Create Dash Application
- Initialized a Dash application and provided a meaningful title.

### Task 2.2: Add Drop-Down Menus
- Added drop-down menus for selecting different report types and time periods.

### Task 2.3: Add Output Display Division
- Created a division for output display with appropriate `id` and `classname` properties.

### Task 2.4: Define Callbacks
- Created callback functions to update the dashboard based on user selections.

### Task 2.5: Display Recession Report Statistics
- Created and displayed graphs to visualize statistics during recession periods.

### Task 2.6: Display Yearly Report Statistics
- Created and displayed graphs to visualize statistics for specific years.

# Conclusion: 

The analysis of automobile sales during recession periods reveals several key insights. Notably, there was no sale of Executive cars during recessions, likely due to their high cost, while sales of Sports vehicles also declined for the same reason. In contrast, more affordable vehicles like superminicars and smallfamily cars saw an increase in sales. Overall, automobile sales declined during recessions, with Sports cars being the most affected. The data suggests that the GDP was lower during these periods, which might have negatively impacted sales. Interestingly, seasonality did not significantly affect overall sales, although there was a sharp increase in sales in April. The analysis also shows that ABCAutomotives invested more in advertising during non-recession periods, while focusing on promoting lower-priced vehicles during recessions, a strategy that appears to have been effective. Additionally, a shift in buying patterns was observed, with consumers favoring more affordable vehicles like superminicars, smallfamily cars, and mediumminicars during economic downturns. Finally, New York recorded the highest sales during recession periods, indicating regional variations in consumer behavior.

