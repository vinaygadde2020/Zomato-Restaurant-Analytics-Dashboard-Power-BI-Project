🍽️ Zomato Restaurant Analytics Dashboard

An interactive Power BI dashboard built to analyze Zomato restaurant data and generate business insights using data visualization techniques.

---

📊 Dashboard Preview

"Dashboard Preview" (Dashboard%20Screenshot.png)

---

📌 Project Overview

This project focuses on analyzing restaurant trends, ratings, cuisines, customer votes, online ordering, and table booking availability using Power BI.

The dashboard helps in understanding customer preferences and restaurant performance through interactive visualizations and KPIs.

---

🚀 Tools & Technologies Used

- Power BI
- SQL
- Excel
- DAX
- Power Query
- Data Modeling
- Git
- GitHub

---

📂 Dataset Details

The cleaned dataset is available in "zomato_cleaned.xlsx".

The dataset contains information related to:

- Restaurant Names
- Locations
- Ratings
- Votes
- Cuisines
- Online Orders
- Table Booking
- Approximate Cost for Two

Dataset Summary

- Cleaned Records: 6,801 rows
- Columns in cleaned workbook: 11
- Distinct Restaurant Names: 1,658
- Total Locations: 80
- Total Votes: 3,661,283
- Average Rating: 3.90
- Average Cost for Two: 629.09 (currency not specified)

---

🧹 Data Cleaning & Preparation

The documented Power Query process includes:

- Promoting headers and setting data types
- Removing errors and blank rows
- Removing duplicate URLs
- Removing unnecessary columns
- Filtering incomplete records
- Preparing data for visualization and analysis

Data Quality Notes

- 2,258 exact duplicate rows were identified across eight retained columns.
- All 6,801 cleaned rows have "online_order = Yes".
- The original raw CSV was not available for this report.

Duplicate rows require further investigation to determine whether they represent repeated records or separate restaurant outlets.

---

🏗️ Data Modeling

This project follows a Star Schema Model.

Fact Table

- "Zomato_Fact"

Dimension Tables

- "Location_Table"
- "Cuisine_Table"
- "Rating_Table"
- "BookTable_Table"
- "OnlineOrder_Table"

The rating relationship and related measures should be verified in Power BI before final submission.

---

📈 Dashboard Features

⭐ KPI Cards

- Average Rating
- Total Restaurants (distinct restaurant names)
- Total Locations
- Average Cost for Two

📊 Interactive Visualizations

- Top Restaurants by Votes
- Rating Category Distribution
- Cuisine Distribution
- Location vs Rating Matrix
- Table Booking Availability

🎛️ Interactive Filters

- Locations
- Rating Category
- Cuisines

Slicer interactions should be tested in Power BI Desktop.

---

🔍 Exploratory Data Analysis (EDA)

The analysis explores rating distributions, cuisine patterns, location-based restaurant counts, customer votes, and table-booking availability.

Key observations:

- Very Good is the largest rating category at 46.36%.
- Good accounts for 45.48% of rows.
- North Indian cuisine appears in 40.19% of rows when cuisine combinations are split.
- Chinese cuisine appears in 31.36% of rows when cuisine combinations are split.
- Table booking is available in 1,327 of 6,801 rows (approximately 19.51%).

---

💡 Key Business Insights

- Rating Distribution: Very Good is the largest category, followed by Good. Very Good does not represent a majority.
- Cuisine Trends: North Indian and Chinese cuisine have substantial representation in the dataset.
- Cuisine Ratings: Desserts + Beverages averages 4.15 across 110 rows, while North Indian + Chinese averages 3.59 across 179 rows.
- Customer Engagement: The top 10 restaurant names account for approximately 17.0% of total votes.
- Table Booking: Only approximately 19.51% of rows indicate table-booking availability.
- Location Trends: The five largest areas by row count account for approximately 33.1% of the rows.

These findings describe patterns in the available data and do not establish cause and effect.

---

🎯 Recommendations

- Encourage suitable restaurants to pilot table-booking services and measure the results.
- Investigate highly rated cuisine combinations and opportunities for differentiation.
- Review duplicate records and distinguish total rows from distinct restaurant counts.
- Verify Power BI relationships, measures, and slicer interactions before publishing final results.

---

🐙 Git & GitHub

This project is maintained in GitHub for version control and documentation.

Repository link:

https://github.com/vinaygadde2020/Zomato-Restaurant-Analytics-Dashboard-Power-BI-Project

The repository currently contains three commits:

- Initial commit
- Add files via upload
- Update README.md

The Week 6 workflow practice for "clone", "add", "commit", "push", and "pull" must be verified separately.

---

📁 Project Files

- "README.md" — Project documentation
- "zomato_cleaned.xlsx" — Cleaned dataset
- "zomato.pbix" — Power BI dashboard
- "Dashboard Screenshot.png" — Dashboard preview

The Week 6 report PDF and presentation should be added after they are finalized.

---

⚠️ Limitations

- The original raw CSV was not available for this report.
- Exact duplicate rows require further investigation.
- The currency for the cost field is not specified.
- The rating relationship and highest-rated restaurant measure require verification.
- Dashboard slicer and cross-filter interactions require testing.
- Online-order comparisons are not possible because every cleaned row has "online_order = Yes".

---

🏁 Conclusion

This project uses data preparation, exploratory analysis, data modeling, and Power BI visualizations to understand restaurant ratings, cuisine trends, customer engagement, location patterns, and table-booking availability.

The dashboard provides an interactive way to explore restaurant data and identify opportunities for further analysis and business improvement.

---
