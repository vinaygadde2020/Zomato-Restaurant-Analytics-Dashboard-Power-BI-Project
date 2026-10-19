🍽️ Zomato Restaurant Analytics Dashboard

An interactive Power BI dashboard built to analyze Zomato restaurant data and generate business insights using data analytics and visualization techniques.

---


---

📌 Project Overview

This project analyzes restaurant data to explore ratings, cuisines, locations, customer votes, approximate cost for two people, online ordering, and table-booking availability.

The Power BI dashboard presents key performance indicators (KPIs), charts, and filters to make restaurant data easier to explore and understand.

---

🎯 Problem Statement

Restaurant datasets contain multiple attributes that can be difficult to compare manually. This project uses data cleaning, exploratory data analysis (EDA), data modeling, and visualization to identify patterns in restaurant performance and customer engagement.

---

🚀 Project Objectives

- Clean and prepare restaurant data for analysis.
- Analyze ratings, cuisines, locations, votes, and costs.
- Build meaningful visualizations and KPI cards.
- Create an interactive Power BI dashboard.
- Identify data-supported business insights.
- Provide practical recommendations based on the findings.
- Document and maintain the project using Git and GitHub.

---

🛠️ Tools & Technologies Used

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel
- Data Modeling
- Exploratory Data Analysis (EDA)
- Git
- GitHub

---

📂 Dataset Details

The cleaned dataset is available in "zomato_cleaned.xlsx".

Dataset Summary

- Cleaned Records: 6,801 rows
- Columns in the cleaned workbook: 11
- Distinct Restaurant Names: 1,658
- Distinct Locations: 80
- Total Votes: 3,661,283
- Average Rating: 3.90
- Average Cost for Two: 629.09 (currency not specified in the source data)

Dataset Attributes

- Restaurant Names
- Locations
- Ratings
- Votes
- Cuisines
- Online Order Availability
- Table Booking Availability
- Approximate Cost for Two

The original raw CSV was not available for this report, so raw-data row counts and raw missing-value counts are not included.

---

🧹 Data Cleaning & Preparation

The documented Power Query process includes:

- Promoting headers and setting data types.
- Removing errors and blank rows.
- Removing duplicate URLs.
- Removing unnecessary columns.
- Filtering incomplete records.
- Preparing fields for analysis and visualization.

Data Quality Notes

- The Week 5 report identified 2,258 exact duplicate rows across eight retained columns.
- All 6,801 cleaned rows have "online_order = Yes".
- The original raw CSV was not available for this report.

The duplicate rows require further investigation to determine whether they represent repeated records or separate restaurant outlets.

Because every cleaned row has "online_order = Yes", this dataset cannot support a meaningful online-versus-offline ordering comparison.

---

🏗️ Data Modeling

The project report documents a model containing a fact table and dimension tables.

Fact Table

- "Zomato_Fact"

Dimension Tables

- "Location_Table"
- "Cuisine_Table"
- "Rating_Table"
- "BookTable_Table"
- "OnlineOrder_Table"

The relationship between the numeric rating and rating category was flagged for verification in the Week 5 report. The model relationships and related measures should be tested in Power BI Desktop before final submission.

---

📈 Dashboard Features

⭐ KPI Cards

- Average Rating
- Total Restaurants (distinct restaurant names)
- Total Locations
- Average Cost for Two

📊 Visualizations

- Top 10 Restaurants by Votes
- Rating Category Distribution
- Cuisine Distribution Treemap
- Location vs Rating Matrix
- Table Booking Availability

🎛️ Interactive Filters

- Location
- Rating Category
- Cuisine

The slicers are designed to filter the dashboard. Their interactions should be tested in Power BI Desktop before claiming that all filters work correctly.

---

🔍 Exploratory Data Analysis (EDA)

The analysis explores rating distributions, cuisine patterns, location-based listing counts, customer votes, average ratings, costs, and table-booking availability.

Key Observations

- Very Good is the largest rating category at 46.36%.
- Good accounts for 45.48% of rows.
- North Indian cuisine appears in 40.19% of rows when cuisine combinations are split for analysis.
- Chinese cuisine appears in 31.36% of rows when cuisine combinations are split.
- Table booking is available in 1,327 of 6,801 rows, approximately 19.51%.

These percentages describe the analyzed rows and should not automatically be interpreted as percentages of distinct restaurant businesses.

---

💡 Key Business Insights

- Rating Distribution: Very Good is the largest category, followed by Good. Very Good does not represent a majority.
- Cuisine Trends: North Indian and Chinese cuisine have substantial representation in the analyzed data.
- Cuisine Ratings: Desserts + Beverages averages 4.15 across 110 rows, while North Indian + Chinese averages 3.59 across 179 rows.
- Customer Engagement: The top 10 restaurant names account for approximately 17.0% of total votes.
- Table Booking: Approximately 19.51% of rows indicate table-booking availability.
- Location Trends: The five largest areas by row count account for approximately 33.1% of rows.

These findings describe patterns in the available data. They do not establish cause and effect.

---

🎯 Recommendations

- Improve Table Booking Adoption: Pilot table-booking services with suitable restaurants in locations where availability is low, then measure the results.
- Explore Cuisine Opportunities: Investigate highly rated cuisine combinations and identify opportunities for restaurant differentiation.
- Improve Data Quality: Review exact duplicate rows and use a stable restaurant or outlet identifier wherever possible.
- Improve Reporting Accuracy: Distinguish row counts from distinct restaurant counts in KPI cards and visualizations.
- Verify the Dashboard: Check data relationships, DAX measures, slicers, and cross-filter behavior before publishing final results.

These recommendations should be treated as opportunities for further investigation, not guaranteed business outcomes.

---

🐙 Git & GitHub

This project is maintained on GitHub for version control, documentation, and portfolio presentation.

Repository

https://github.com/vinaygadde2020/Zomato-Restaurant-Analytics-Dashboard-Power-BI-Project

The repository includes the project files, dashboard, documentation, Week 6 report, and presentation.

The repository history has shown multiple commits documenting project setup, file uploads, and documentation changes.

Git Workflow Requirements

The Week 6 assignment requires practice with:

- "git clone" — copy a repository locally.
- "git add" — stage changes.
- "git commit" — record meaningful changes.
- "git push" — upload local commits to GitHub.
- "git pull" — retrieve remote updates.

The repository's commit count alone does not confirm that every workflow operation has been practised.

---

📁 Project Files

- "README.md" — Project documentation
- "zomato_cleaned.xlsx" — Cleaned dataset
- "zomato.pbix" — Power BI dashboard
- "Dashboard Screenshot.png" — Dashboard preview
- "InternNova_Week6_Final_Project_Report.pdf" — Week 6 project report
- "InternNova_Week6_Zomato_Project_Presentation_DRAFT.pptx" — Week 6 presentation draft

Check the exact filenames displayed in GitHub and update this list if they differ.

---

⚠️ Limitations & Verification

- The original raw CSV was not available for this report.
- Exact duplicate rows require further investigation.
- The currency of the cost field is not specified.
- The rating relationship and highest-rated restaurant measure require verification.
- Dashboard slicer and cross-filter interactions require testing.
- Online-versus-offline ordering comparisons are not possible because every cleaned row has "online_order = Yes".
- The relationship between table booking, ratings, and votes is observational; causation cannot be concluded from these data alone.

---

🏁 Conclusion

This project uses data preparation, exploratory analysis, data modeling, and Power BI visualizations to explore restaurant ratings, cuisine trends, customer engagement, location patterns, costs, and table-booking availability.

The dashboard provides an interactive way to investigate restaurant data and identify opportunities for further analysis and business improvement. Data-quality checks and verification of the Power BI model remain important before relying on every reported result.

---

🔗 GitHub Repository

"View the Zomato Restaurant Analytics Dashboard project on GitHub" (https://github.com/vinaygadde2020/Zomato-Restaurant-Analytics-Dashboard-Power-BI-Project)

---
