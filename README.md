🚗 Used Car Sales Analysis Dashboard
📌 Project Overview

This project analyzes a Used Car Sales Dataset to uncover insights about car brands, fuel types, transmission, ownership, accident history, and pricing trends.
The project is completed in 4 phases:

Data Cleaning & Preprocessing (Python / Pandas)

Exploratory Data Analysis (EDA)

Insights & Comparisons

Interactive Power BI Dashboard

The final output is a multi-page Power BI dashboard that provides deep insights into the used car market.

📂 Dataset

Source: Provided CSV dataset (Used Car Sales).

Rows: ~140k

Columns: Brand, Model, Variant, Car Type, Transmission, Fuel Type, Year, Kilometers, Owner, State, Accidental, Price.

⚙️ Phase 1: Data Cleaning

Checked for null values → No missing data.

Detected & handled outliers (Price had 1820 outliers).

Cleaned data for consistency (e.g., Fuel Type, Transmission categories).

🔎 Phase 2: Exploratory Data Analysis (EDA)

Top Car Brand → Maruti Suzuki (54,030 cars).

Most Common Car Type → Hatchback (55,890 cars).

Fuel Type Majority → Petrol (79,187 cars).

Most Common Transmission → Manual (119,793 cars).

Kilometer Stats: Avg ~95,000 km.

Outliers detected mainly in Price, not in Kilometers.

📊 Phase 3: Insights & Comparisons

Automatic cars are ~9.8% more expensive than Manual (for Petrol cars).

Hybrid & Electric cars have highest average prices.

First-owner cars have higher resale value compared to multiple-owner cars.

Accidental cars are fewer and tend to have lower prices.

📈 Phase 4: Power BI Dashboard

The dashboard has 5 pages:

📄 Page 1: Brand & Car Type Analysis

Top 5 Car Brands by sales.

Distribution of Car Types (Hatchback, Sedan, SUV, etc.).

📄 Page 2: Transmission & Fuel Insights

Transmission split (Manual vs Automatic).

Fuel type distribution.

Avg Price by Fuel & Transmission.

📄 Page 3: Price Distribution

Avg Price by Car Type.

Top 10 Most Expensive Brands.

Outlier price analysis.

📄 Page 4: Ownership & Accident Analysis

Cars by Owner type (First, Second, Third owner).

Avg Price by Ownership.

Accidental vs Non-Accidental distribution.

📄 Page 5: Year & Kilometers Analysis

Cars sold by Year.

Avg Kilometers driven by Car Type.

Price depreciation trends by Age of car.

🛠️ Tools & Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn) → Data cleaning & EDA.

Power BI → Dashboard creation & visualization.

GitHub → Version control & project showcase.


📢 Key Learnings

Handling large datasets (~140k rows).

Performing EDA with outlier detection.

Building interactive dashboards in Power BI.

Writing data-driven business insights.
