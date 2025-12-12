# Life-Expectancy-Analytics-Dashboard
This project analyzes global life expectancy, BMI, mortality, expenditure, and health indicators across countries and years.

Project Overview

The Life Expectancy Dashboard provides insights into:

Global life expectancy trends

Health expenditures

Mortality rates (adult, infant, under-five)

BMI and thinness levels

Country-level health comparisons

Developed vs. developing country variations

The dashboard is filter-enabled (by year, country, and status) and presents KPIs and multiple charts for deeper analysis.

🛠️ Data Cleaning & Preprocessing

To prepare the dataset, the following steps were performed:

✔ 1) Removed Missing (Null) Values

Filled or removed missing values in columns such as BMI, thinness, life expectancy, etc.

✔ 2) Handled Inconsistent Spellings & Formats

Standardized categories like Developed and Developing, corrected country names.

✔ 3) Treated Outliers

Extreme values (like 0 life expectancy or 0 BMI) were inspected and flagged for visualization only.

✔ 4) Removed Duplicate Rows

Ensured accurate aggregation and KPI values.

✔ 5) Converted Columns to Correct Data Types

Year → Integer

Life expectancy → Float

Country → Category

Status → Category

🎯 Dashboard Features & Insights
🔹 1. Key KPIs (Top Section)

Maximum Life Expectancy

Minimum Life Expectancy

Average Life Expectancy

Maximum BMI

Minimum BMI

Average Thinness (1–19 years)

Count of Countries

🔹 2. Developed vs Developing Analysis

Pie/Donut charts show:

Total health expenditure

% of GDP spent on health

These make it easy to compare how economic status impacts health outcomes.

🔹 3. Country-Based Mortality Statistics

Donut charts for:

Adult mortality

Infant deaths

Under-five deaths

Countries shown include India, Pakistan, Nigeria, China, Democratic Republic of Congo, Zimbabwe, etc.

🔹 4. Thinness & BMI Trends

KPIs highlight:

Max thinness

Average thinness

Min thinness

BMI variations

These factors help understand nutritional status worldwide.

🔹 5. Year-Based Filtering

Users can select a year (2000–2015) to see how health metrics changed over time.

📊 Dashboard Visuals Included
✓ KPI Cards
✓ Donut Charts
✓ Pie Charts
✓ Year-based slicer
✓ Categorized insights (Developed vs Developing)
🧰 Tools & Technologies Used

Power BI Desktop

Data Cleaning

Data Transformation

DAX Measures

Interactive Visualization
