# Electric Vehicle 

> "Electric Vehicles aren't just cars; they're the key to a greener planet."

## INTRODUCTION

As a data analyst exploring the electric vehicle dataset, our goal is to uncover patterns and trends that define the evolving landscape of EV adoption. With a comprehensive view of over 191,000 EVs and 147 unique models, we aim to analyze adoption trends, regional distribution, and model preferences. By examining metrics like electric range, vehicle type, and geographic insights, we will identify key drivers behind EV growth and provide valuable recommendations to stakeholders. This journey through the data will help us understand the factors shaping the transition to sustainable transportation.

- [Dataset Here](https://github.com/NishaChandila/Electric-Vehicle-EDA-/blob/main/Electric_Vehicle_Population_Data.csv)

- [Power BI Dashboard](https://github.com/NishaChandila/Electric-Vehicle-EDA-/blob/main/Electric-Vehicle-Dashboard.pdf)

- [Data Cleaning & EDA](https://github.com/NishaChandila/Electric-Vehicle-EDA-/blob/main/electric-vehicle-eda.ipynb)

## DATA STRUCTURE

The dataset consists of 191,400 rows and multiple columns that capture detailed information about electric vehicles (EVs), including their make, model, type, range, and geographical distribution. Below is a detailed description of each column:

![Dataset](https://github.com/NishaChandila/project-assets/blob/main/electric-dataset.PNG)

- **Make**: The manufacturer of the vehicle (e.g., Tesla, Nissan, Chevrolet).
- **Model**: The specific model of the vehicle (e.g., Model 3, Leaf, Bolt EV).
- **Model Year**: The year the EV model was released, indicating its generation.
- **Electric Range**: The maximum distance the EV can travel on a single charge, measured in miles.
- **Electric Vehicle Type (EVT)**: Categorizes vehicles as either fully electric (BEV) or plug-in hybrid (PHEV).
- **CAFV Eligibility**: Whether the vehicle qualifies for Clean Alternative Fuel Vehicle (CAFV) incentives (Yes, No, Unknown).
- **County**: The county of registration, providing insights into regional EV adoption.
- **City**: The city where the vehicle is registered, showing urban-level trends.
- **Location**: Geographic coordinates (latitude and longitude) for mapping EV distributions.

This dataset offers a detailed overview of EV adoption, performance, and geographic patterns.

- [Dataset Here](https://github.com/NishaChandila/Electric-Vehicle-EDA-/blob/main/Electric_Vehicle_Population_Data.csv)

## EXECUTIVE SUMMARY

![Home](https://github.com/NishaChandila/project-assets/blob/main/electric1.PNG)

This dashboard provides an analysis of electric vehicle (EV) adoption trends and insights into EV models and their performance. It explores data from over 191,000 EVs and 147 unique models to uncover regional adoption patterns, vehicle type preferences, and advancements in technology. The **EV Adoption Trends** page examines the distribution of EVs by region, type, and CAFV eligibility, while the **EV Model Insights** page focuses on model performance, popularity, and the evolution of EV capabilities over time. Together, these pages offer a clear view of the EV landscape to inform data-driven decisions.

### Page 1: EV Adoption Trends

![EV Adoption](https://github.com/NishaChandila/project-assets/blob/main/electric2.PNG)

- **Total EVs and Models**: 191.4K EVs and 147 unique models, reflecting the growing adoption of electric vehicles.
- **Regional Distribution**: King County leads with 99K EVs, followed by Snohomish (23K) and Pierce (15K).
- **EV Type Insights**: BEVs dominate the market with 149.69K units, far surpassing PHEVs (41.72K).
- **CAFV Eligibility**: CAFV eligibility data shows varied adoption patterns by region, influenced by policy and infrastructure.

### Page 2: EV Model Insights

![EV Model](https://github.com/NishaChandila/project-assets/blob/main/electric3.PNG)

- **Top Manufacturer**: Tesla stands out as the leader, with Model 3 (31K) and Model Y (40K) being the most popular.
- **Average Range**: EVs demonstrate an average electric range of 55.7 miles, indicating technological progress.
- **Range by EV Type**: BEVs achieve 9M miles, while PHEVs deliver 1M miles, showcasing their relative capabilities.
- **Model Year Trends**: CAFV eligibility trends by model year reflect alignment with changing incentives and policies.

This streamlined view ensures clarity and relevance for stakeholders while emphasizing key data points.

- [Power BI Dashboard](https://github.com/NishaChandila/Electric-Vehicle-EDA-/blob/main/Electric-Vehicle-Dashboard.pdf)

## DATA CLEANING

We have cleaned the dataset to ensure accuracy and readiness for analysis. Below are the steps we followed:

- **Checked for Missing Values**: Identified and handled null values in the dataset.
- **Dropped Irrelevant Columns**: Removed unnecessary columns such as 'VIN (1-10)', 'Postal Code', 'Base MSRP', 'Legislative District', 'DOL Vehicle ID', 'Electric Utility', and '2020 Census Tract' to streamline the dataset.
- **Reviewed Vehicle Models**: Checked for inconsistencies and outliers within the vehicle models to ensure accurate data.
- **Ensured Data Consistency**: Ensured the dataset was clean, with no discrepancies, for reliable analysis.

- [Data Cleaning & EDA](https://github.com/NishaChandila/Electric-Vehicle-EDA-/blob/main/electric-vehicle-eda.ipynb)

## RECOMMENDATION

The Power BI dashboard should be designed to provide a clear, interactive, and insightful view of the EV data. To ensure a smooth user experience and meaningful analysis, the following recommendations are suggested:

- **Design**: Use a dark gray background (#2C2C2C) with steel silver borders (#C0C0C0) for a modern and polished look.
- **KPIs**: For KPIs like Total EVs and Unique Models, incorporate intuitive icons (e.g., vehicle icons for EVs, battery icons for electric range).
- **Slicers**: Use slicers for filtering by Make, Model Year, County, and EV Type to allow users to explore data based on their preferences.
- **Charts**: Use distinct chart types:
  - **Bar Charts**: For EV make and model distribution.
  - **Donut Charts**: For EV Type Distribution (BEVs vs. PHEVs).
  - **Line Charts**: For Electric Range Trends.
- **Tooltips**: Include interactive tooltips to display additional details on hover, allowing users to explore the data without cluttering the dashboard.
- **Color Scheme**: Apply a soothing and elegant color scheme with shades of blue, green, and soft white to ensure clarity and professionalism while maintaining a balanced aesthetic.

By following these recommendations, the Power BI dashboard will be an effective tool for analyzing and visualizing EV data, providing valuable insights into EV adoption trends and model performance.

- [Dataset Here](https://github.com/NishaChandila/Electric-Vehicle-EDA-/blob/main/Electric_Vehicle_Population_Data.csv)

- [Power BI Dashboard](https://github.com/NishaChandila/Electric-Vehicle-EDA-/blob/main/Electric-Vehicle-Dashboard.pdf)

- [Data Cleaning & EDA](https://github.com/NishaChandila/Electric-Vehicle-EDA-/blob/main/electric-vehicle-eda.ipynb)
