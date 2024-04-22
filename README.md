# Car-Sales
![](yard.jpg)
## Introduction 
I came across the dataset online in Kaggle and I have been trying to practice my skills in data cleaning, analysis, and visualization and thought this would be a good opportunity to put my skills to work
## Problem Statement


1. Sales Overview, Calculate 
    - YTD Total sales.
    - MTD Total sales. 
    - YOY Growth in Total Sales.
    - Difference between YTD sales and PYTD sales.

2.  Average Price Analysis
    - YTD Average price 
    - MTD Average Price
    - YOY growth in Average
    - Difference between YTD Average price and PTYD Average Price.
  
3. Cars Sold Metrics 
    - YTD cars sold
    - MTD cars sold 
    - YOY Growth in Cars sold 
    - Difference between YTD cars sold and PYTD cars sold

## Data Sourcing and transformation
Data was efficiently cleaned and transformed with the power Query Editor. The screenshot below shows some of the steps taken during this process of.

![](Steps_applied.png)

## Data Modeling 
Since it was a time-based analysis the first step was to create a calendar table to better establish a relationship with the other table.

![](calendar_table.png)

Then I went ahead to connect the original table and the calendar table with the common column being the date and formed a one-to-many relationship.

![](Model_data_cars.png)

##  Visualization

In this visualization DAX measures where highly utilized, Buttons were also used to make the dashboard navigation user friendly.
![](folio_pic.png)
![](folio_details.png)

## Analysis and Conclusion
According to the analysis, the best-selling companies are Chevrolet and Ford,
The most bought color is pale white for all the cars, especially the SUVs 
Scottsdale, Austin, And Janesville are the top 3 best-selling regions.
The cars with automatic transmissions sell more than the ones with manual transmissions which makes sense since people today prefer automatic over manual ones.








