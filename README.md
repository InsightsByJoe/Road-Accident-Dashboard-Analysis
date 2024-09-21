# Road-Accident-Dashboard-Analysis(Interactive Dashboard creation using MS Excel)
I developed a comprehensive project in Excel, creating multiple dashboards and tables to analyze the data. This process involved several stages, including data processing, data cleaning and data visualization
[Download the Excel file from Google Drive](https://docs.google.com/spreadsheets/d/1LndDpHtaXU51DVV6XdJLQxnGa8idUa-i/edit?usp=sharing&ouid=118220627709812641957&rtpof=true&sd=true)
# Road Accident Dashboard Analysis
![Road Accident Dashboard](https://github.com/InsightsByJoe/Road-Accident-Dashboard-Analysis/blob/main/Screenshot%202024-09-21%20141911.png)

## Project Overview

### Project Title: Road Accident Dashboard Analysis

### Objective:
The **Road Accident Dashboard Analysis** project aims to provide comprehensive insights into road accidents, focusing on casualty types, vehicle involvement, road conditions, surface type, and time factors. By leveraging data visualization techniques, this project helps identify accident trends, high-risk areas, and factors contributing to road accidents. The ultimate goal is to provide actionable recommendations to reduce road accidents and casualties.

---

### Data Source:
The dataset used in this project was sourced from a publicly available **Road Accident Dataset**, which contains detailed information about road accidents, casualties, vehicle types, road conditions, light conditions, and surface conditions.

---

### Tools Used:
- **Microsoft Excel**[Download here(https://microsoft.com): This project was built entirely using Excel for data loading, cleaning, and visualization.
  - **Excel Functions**: Used for data wrangling, inspection, and cleaning.
  - **Pivot Tables**: Used for summarizing and grouping data.
  - **Charts and Graphs**: Used to create visualizations like bar charts, pie charts, and line graphs for analyzing trends and patterns.
  - **Slicers**: Used to create interactive filters to allow dynamic data exploration within the dashboard.

---

### Process:

#### 1. Data Loading and Inspection:
The road accident data was loaded into **Excel** for further analysis. Initial steps included inspecting the dataset to understand its structure and check for any inconsistencies or missing values.
   - **Tools Used**: Excel’s **data import** and **filter** features.
   - **Inspection**: Assessed the number of rows and columns, checked for null values, incorrect entries, and ensured the format of the data (dates, numbers) was correct.

#### 2. Data Cleaning:
Data cleaning involved removing any unwanted or erroneous data and ensuring that the dataset was in a usable format for analysis.
   - **Removing Duplicates**: Duplicate rows were identified and removed to ensure that the data was accurate and there was no over-representation of specific records.
     - Used **Excel’s Remove Duplicates** feature.
   - **Handling Missing Values**: Any missing data points were either filled using median values (where applicable) or removed if they were non-essential.
     - Performed conditional filtering in Excel to check for **blanks** and remove irrelevant rows.
   - **Data Formatting**: Ensured consistency in formatting, including text normalization (e.g., vehicle names), converting date formats, and ensuring numerical columns had proper data types.
     - Used **Excel's Text-to-Columns**, **Find and Replace**, and data type conversion features.

#### 3. Data Analysis:
The cleaned data was then analyzed using Excel’s built-in tools:
   - **Pivot Tables**: Used to group and summarize data by key attributes like casualty type, road type, vehicle type, and time (year/month).
   - **Descriptive Statistics**: Calculated various metrics like total casualties, fatal vs. non-fatal, and accident distribution across vehicle types.
   - **Trend Analysis**: Examined year-over-year and month-over-month trends in road accidents, as well as the distribution of accidents by vehicle type and road conditions.

#### 4. Data Visualization:
The analysis results were visualized using dynamic charts, graphs, and slicers in Excel:
   - **Line Charts**: Used for visualizing monthly accident trends.
   - **Bar Charts**: Highlighted the distribution of casualties by road type, vehicle type, and lighting conditions.
   - **Pie Charts**: Used to illustrate the proportion of accidents based on surface type and light conditions.
   - **Interactive Dashboard**: Slicers were added to create an interactive experience where users can filter data by year, area type (urban/rural), and accident date.
   - **Charts Featured**: The final dashboard contains key metrics such as total casualties, fatalities, serious injuries, and vehicle types, providing a high-level overview for users.

---

### Key Features of the Dashboard:
1. **Interactive Filters**: Allows users to filter data by year, urban/rural areas, and accident date, providing a dynamic experience.
2. **Comprehensive Visualizations**: Displays key accident insights through line graphs, pie charts, bar charts, and tables.
3. **User-Friendly Interface**: Built entirely using Excel, ensuring ease of use and accessibility for users familiar with spreadsheet tools.
4. **Dynamic Data Exploration**: With pivot tables and slicers, the dashboard can be adjusted in real-time for different types of analysis.

---

### Conclusion:
The **Road Accident Dashboard** offers a powerful tool for traffic analysts, policymakers, and road safety professionals to explore key trends and factors contributing to road accidents. By focusing on data visualization, this project offers actionable insights and supports data-driven decision-making to improve road safety.



## Findings

### 1. Total Casualties
- The total number of casualties recorded is **41,788**. 
- **Serious casualties** account for **14.2%** of the total, while **slight casualties** dominate at **84.1%**.
- **Fatal casualties** represent only **1.7%** of the total, indicating that while accidents are frequent, most are non-fatal.

### 2. Vehicle Type Involvement
- **Cars** are involved in the majority of accidents, accounting for **79.8%** of total casualties (333,484 out of 417,88).
- **Motorcycles** and **bicycles** contribute **8.2%** and **2.4%**, respectively, indicating that while these vehicles are less common, they still play a significant role in accidents.
- **Buses** are responsible for **12,798 casualties** (3%), which is relatively low compared to cars and motorcycles.

### 3. Road Type and Casualties
- The majority of accidents occur on **single carriageways**, resulting in **390.7k casualties**.
- **Dual carriageways** account for **67.4k casualties**, and **roundabouts** see much fewer accidents with **26.8k casualties**.
- Casualties on **one-way streets** and **slip roads** are minimal, making up a very small portion of the overall accidents.

### 4. Surface Condition and Accidents
- Most accidents occur on **dry surfaces**, contributing to **96.5%** of total casualties, indicating that dry conditions do not necessarily imply safer driving.
- **Wet surface** accidents contribute to **3.2%**, and accidents on **snow-covered surfaces** are minimal at **0.3%**.

### 5. Lighting Condition
- The majority of accidents take place during **daylight** hours, accounting for **306.0k casualties** (67.2%).
- **Dark, no street lighting** conditions lead to **69.8k casualties**, while **dark with street lighting** accounts for **112.9k casualties**, suggesting that poor lighting conditions still pose a significant risk.

---

## Analysis Results

### Vehicle Types
- **Cars** lead the list of vehicles involved in accidents, suggesting that efforts to improve road safety should focus heavily on this category.
- **Motorcycles** have a high rate of accidents compared to their lower usage, indicating a potential need for stricter regulations or awareness campaigns for motorcycle safety.

### Accident Conditions
- The predominance of accidents on **dry surfaces** and during **daylight** indicates that factors beyond weather, such as human error or vehicle malfunction, are key contributors to road accidents.
- **Single carriageways** are responsible for the highest number of casualties, suggesting infrastructure improvements, such as road widening or safety barriers, may be needed to reduce accidents on these roads.

### Light Conditions
- Even though **daylight** hours see the majority of accidents, the occurrence of casualties in **dark conditions** without street lighting suggests that improving street lighting could play a crucial role in reducing night-time accidents.

---

## Recommendations

1. **Focus on Car-Related Accidents**:
   - Since **cars** are involved in **nearly 80%** of total accidents, safety measures, stricter vehicle regulations, and public awareness campaigns should target car drivers.
   - Encourage the adoption of **advanced driver assistance systems (ADAS)** in cars, including automated emergency braking and lane departure warning systems.

2. **Infrastructure Improvements**:
   - **Single carriageways** contribute to the most casualties. Government and road planners should consider widening these roads or introducing safety barriers to reduce accident rates.
   - **Improved lighting** should be prioritized on dark roads without street lights. Enhancing street lighting on high-risk roads could reduce accidents during **night-time driving**.

3. **Motorcycle Safety Programs**:
   - Despite lower usage, **motorcycles** have a high accident rate, suggesting the need for targeted **motorcycle safety campaigns**, stricter **helmet laws**, and improved **driver awareness** of motorcycle riders.

4. **Wet Weather Preparedness**:
   - Although wet surfaces account for a small percentage of accidents, awareness campaigns can focus on the dangers of driving in wet conditions, particularly by highlighting the risks of hydroplaning.

---

## Limitations

1. **Data Scope**:
   - The dashboard provides an overview of accidents based on general vehicle types, road types, and surface conditions. More specific breakdowns (e.g., types of cars, make and model) could provide deeper insights.
   - The data does not include **real-time factors** such as **driver behavior** (e.g., distracted driving, speeding), which may also contribute significantly to accident rates.

2. **External Influences**:
   - The dashboard does not account for external factors like **weather conditions**, **traffic volume**, or **time of day** beyond daylight/dark, which could help in providing a more comprehensive understanding of accidents.

3. **Geographic Limitations**:
   - The analysis is generalized and does not consider **geographic variances** such as regional differences in road conditions, weather patterns, or driving culture.

4. **Historical Data**:
   - The dashboard compares **2021** and **2022** data but does not include historical data from previous years, which could offer better insight into long-term trends.

5. **Data Granularity**:
   - While the dashboard provides a high-level overview, the lack of granular data (e.g., specific causes of accidents) limits deeper analysis and more specific recommendations for prevention.
