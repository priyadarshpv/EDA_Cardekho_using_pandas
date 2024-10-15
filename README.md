# EDA_Cardekho_using_pandas
CarDekho Description: CarDekho is one of India’s leading automotive portals, providing users with comprehensive information about cars, including reviews, comparisons, specifications, and prices. It helps customers make informed decisions when buying new or used vehicles. In addition to its online presence, CarDekho offers a platform for buying and selling used cars, featuring detailed listings with various filters to suit customer preferences. The platform is known for its user-friendly interface and provides a seamless experience for car buyers and sellers alike, offering features like insurance, finance, and servicing as well.

Analysis Description: This project involves an Exploratory Data Analysis (EDA) on the Cardekho dataset, containing 8148 rows and 13 columns related to used cars. The primary objective is to clean, transform, and analyze the dataset to gain insights into the distribution and relationships between various features.

Key Steps:
Data Cleaning:

Removed null and duplicate values to ensure data quality.
Converted columns like mileage, torque, engine, and max power from object to float for accurate analysis.
Feature Engineering:

Created new features, such as vehicle age and mileage condition, to further enhance the analysis.
Univariate Analysis:

Explored the distribution of categorical columns such as vehicle name, fuel type, seller type, transmission, owner type, and company using frequency counts.
Investigated the condition of vehicles (e.g., mileage condition) and categorized them into high, normal, and low mileage.
Visualization:

Used Bar plots to compare categorical data like fuel type and company distribution.
Implemented Box plots to identify outliers in numerical data such as mileage and engine size.
Line plots were used to track continuous variables and reveal trends over time.
Pie charts provided an easy-to-understand breakdown of categorical variables like fuel type and transmission type.
Groupby Analysis:

Utilized the groupby function for deeper insights into how numerical values behave across different categories, such as seller type or owner type.
Tools Used:
Python: Primary language for analysis
Pandas: For data manipulation and cleaning
Matplotlib: For visualizations
Key Insights:
The dataset primarily consists of vehicles with Diesel and Petrol engines.
Maruti dominates the market with the highest number of vehicles.
Most vehicles are sold by individual sellers and are manual transmission.
The majority of vehicles are first-owner and within the normal mileage range.
This analysis provides actionable insights into the used car market, helping in understanding vehicle trends, market dynamics, and buyer preferences.
