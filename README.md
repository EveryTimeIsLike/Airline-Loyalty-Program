# Airline-Loyalty-Program
Power BI project analyzing airline loyalty program performance – enrollments, cancellations, and campaign ROI.

✈️ Airline Loyalty Program – Power BI Project
Project Overview:
This project analyzes customer loyalty data from Northern Lights Air (NLA), a fictitious Canadian airline.
The company launched a promotional campaign (Feb–Apr 2018) to boost loyalty enrollments and flight activity.
As a Senior Business Analyst, I developed a full analytical solution in Power BI to measure campaign performance, retention, and customer engagement trends.

🎯 Business Objectives:
Measure the impact of the campaign on loyalty program enrollments (gross and net).
Identify which customer segments and enrollment types responded best.
Evaluate the campaign’s influence on flight activity by loyalty members.
Provide actionable recommendations to improve customer retention and campaign ROI.

🧩 Data & Preparation:
Dataset: Maven Analytics (public domain)
Data Volume: ~412K records, 28 fields

Sources:
Customer Loyalty History (enrollments, cancellations)
Customer Flight Activity (bookings by month)
Calendar (date intelligence)

Data Preparation Steps:
Profiled data quality and standardized field types.
Created monthly “Start of Month” fields for alignment across tables.
Added binary cancellation flag for churn analysis.
Joined tables using surrogate keys in a star schema structure.

⚙️ Data Model & DAX Logic
Key measures created:
Total Enrollments
Total Cancellations
Net Loyalty Members = Enrollments – Cancellations
Running Total of Net Members
Flights Booked (Current Year)
Flights Booked (Previous Year)

The model follows Kimball best practices, enabling accurate trend analysis and YoY comparisons.

📊 Visualizations & Dashboard Highlights
Enrollment vs Cancellation Trends: Monthly patterns with seasonality context.
Net Membership Growth: Running totals highlighting campaign retention.
Flights Booked Analysis: Comparison between loyalty and non-loyalty flights.
Enrollment Type Breakdown: Stacked columns with slicers for filtering.

You can view an interactive version here:
👉 View the Power BI Report
 (replace with your Power BI Service public link)

📈 Key Insights
Campaign generated a +37% increase in enrollments during Feb–Apr 2018.
Cancellations rose 12% post-promotion, suggesting short-term engagement gains.
Net loyalty growth remained positive, with a strong Q2–Q3 retention effect.
Members who joined via credit-card or premium plans had higher flight activity.

💼 Business Impact
This project helped demonstrate how data-driven campaign evaluation can guide better marketing investments:
Identified high-value acquisition channels for future promotions.
Enabled forecasting of loyalty-driven flight activity.
Supported ROI analysis for retention strategies and customer lifetime value.

🛠️ Tools & Skills Used
Category	Tools / Skills
BI Tools	Power BI Desktop, Power BI Service
Data Modeling	Star Schema, Relationships, Calendar Table
Data Transformation	Power Query
DAX	Calculated Columns, Measures, Time Intelligence
Visualization	Line Charts, Stacked Columns, KPI Cards, Slicers
Analytics Skills	Campaign Performance, Retention, Trend Analysis, Data Storytelling
