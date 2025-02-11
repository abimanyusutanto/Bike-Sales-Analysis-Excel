# **Bike Sales Analysis**

## **Project Overview**

This project focuses on analyzing bike sales data to uncover key trends and insights using only Microsoft Excel. The dataset includes various demographic and economic factors that influence purchasing behavior. The primary objectives are to clean and preprocess the data to ensure accuracy and consistency, then create meaningful visualizations that provide actionable insights into customer preferences and sales performance. More details about the dataset can be found [here](https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx)

## **Objectives**

-  Ensure data accuracy and consistency by handling missing values, correcting inconsistencies, and standardizing formats.
-  Identify key trends and insights by summarizing sales performance, customer behavior, and product demand using Pivot Tables.
-  Develop a visual dashboard to effectively present findings and facilitate data-driven decision-making.

## **Data Cleaning Process**

1. Eliminated duplicate records to ensure data integrity and prevent skewed analysis.
2. Replaced abbreviations in Marital Status (M → Married, S → Single) and Gender (F → Female, M → Male) to improve readability and avoid ambiguity in data interpretation.
3. Changed the Income column from currency format to numeric. This ensures compatibility with calculations, statistical analysis, and visualizations, preventing errors in aggregations such as sum, average, or filtering.
4. Replaced 10+ miles with More than 10 miles to improve sorting accuracy and ensure consistency in filtering and analysis.
5. Added a new age_Bracket column to classify age into three categories: Young, Middle Age, and Old, making demographic analysis more insightful and easier to interpret.
   
## **Data Visualzation**

1. Distribution of Bike Sales by Age Group

   ![image](https://github.com/user-attachments/assets/71f11f02-a723-476e-9f0b-7f87ad5670c3)
   
   Objectives : To identify which age group is the most likely to purchase a bike.
   
   Insights :
   
     - The Middle Age group has the highest number of bike purchases, with more buyers (Yes) than non-buyers (No).
     - The Old and Young age groups have significantly lower purchase numbers, with more people not buying bikes.
     - This indicates that middle-aged individuals are more likely to purchase bikes compared to other age groups.
   
   Conclusion : Middle-aged individuals are the main target market for bike sales.

2. **Average Income and Bike Sales by Gender**

   ![image](https://github.com/user-attachments/assets/e36bb61c-e08b-4e4a-9df0-f40a078425a1)
   
   Objectives : To analyze the relationship between gender, income, and bike purchases.
   
   Insights :
   
     - Males have a higher number of bike purchases compared to females.
     - The average income of males is also higher than that of females.
     - This suggests that economic factors and gender preferences may influence bike purchasing decisions.
   
   Conclusion : Males with higher income are more likely to buy bikes compared to females.

3. **Distribution of Bike Sales by Commute Distance**

   ![image](https://github.com/user-attachments/assets/b083b4a6-7468-4289-ad82-4b0c7e56a3cb)
   
   Objectives : To examine how commute distance influences bike purchasing behavior.
   
   Insights :
   
     - People with a commute distance of 0-1 miles have the highest number of bike purchases, but non-buyers are also high in this category.
     - At 1-2 miles, both buyers and non-buyers drop significantly.
     - At 5-10 miles, non-buyers slightly increase compared to buyers.
     - At More than 10 miles, bike purchases are very low.
     - This suggests that individuals with shorter commutes are more inclined to buy bikes, while those with longer commutes are less likely to do so.
   
   Conclusion : People with shorter commutes (0-1 miles) are more likely to buy bikes, while those with longer commutes prefer other transportation methods.
   
4. **Bike Sales Distribution by Income Bracket**

   ![image](https://github.com/user-attachments/assets/7d4adae1-6c2e-4fe8-bf1d-a7a1ed529e64)
   
   Objectives : To determine the correlation between income levels and bike purchases.
   
   Insights :
   
     - The 50k-100k income group has the highest bike purchase numbers.
     - The <50k group has fewer purchases compared to the 50k-100k group but still more than the >100k group.
     - The >100k group has the lowest number of bike purchases.
     - This suggests that middle-income individuals are more likely to purchase bikes compared to those in lower or higher income brackets.
   
   Conclusion : Middle-income earners (50k-100k) are the primary market for bike sales, whereas higher-income individuals (>100k) are less likely to buy bikes.

5. **Interactive Filters (Slicers) for In-Depth Analysis**

   ![image](https://github.com/user-attachments/assets/1bb93513-43bb-4d6d-94f5-2b9781bd605b)
   
   Objectives :  To provide an interactive way to analyze bike sales based on different demographic factors.
   
   On the left side of the dashboard, slicers allow users to filter data by:
   
     - Marital Status (Single, Married)
     - Education Level (Bachelors, Graduate Degree, High School, Partial College, Partial High School)
     - Number of Cars Owned (0,1,2,3,4)
     - Region (Europe, North America, Pacific)
   
   These filters allow for deeper analysis of how marital status, education, car ownership, and location influence bike purchasing decisions.

## **Conclusion**

This project aimed to analyze bike sales data to identify key trends and insights using only Microsoft Excel. The analysis involved data cleaning, pivot table exploration, and dashboard visualization to uncover patterns in customer purchasing behavior.

The analysis highlights the primary target market for bike sales: middle-aged men with middle incomes who commute short distances. These insights can help businesses tailor their marketing strategies, adjust pricing, and optimize sales approaches to attract potential buyers effectively. This project demonstrates how data cleaning, pivot tables, and dashboard visualization can transform raw data into meaningful business insights, improving decision-making in sales and marketing strategies.






