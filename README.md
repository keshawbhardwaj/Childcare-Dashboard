# Childcare Assistance Analytics Dashboard — Power BI
🧭 Overview

This Power BI project delivers an end-to-end analytics solution for a Childcare Assistance Program Data Warehouse.
It provides deep insights into how public childcare funds are distributed across programs, providers, and families — helping agencies make data-driven decisions that improve efficiency, equity, and service delivery.

Built with a robust star schema (Fact_Childcare_Assistance + Dim_ tables like Child, Family, Program, Provider, Eligibility, and Time), the model enables detailed drill-down analysis across multiple perspectives such as program, county, income level, and demographics.

🎯 Key Objectives

Track funding utilization and program effectiveness

Measure provider performance and attendance trends

Analyze family eligibility, income brackets, and child demographics

Enable data transparency and performance monitoring for decision-makers

💡 Data Model Highlights

Fact_Childcare_Assistance captures enrollment, attendance, and subsidy transactions

Dimension tables: Child, Parent, Family, Provider, Program, Eligibility_Status, Location, Time, and Caseworker

Designed following Kimball’s dimensional modeling principles for optimal Power BI performance

📈 Dashboard Pages
1️⃣ Program & Funding Overview

Purpose: Monitor total subsidy disbursed, program reach, and funding trends
Key KPIs:

Total Subsidy Amount: $9.02M

Total Enrollments: 10,000

Total Programs: 6

Total Providers: 200

Avg Subsidy per Child: $2.09K
Visuals:

Program-wise Subsidy Comparison

Yearly Subsidy Trend

Top Counties by Subsidy Amount

KPI Cards Summary

2️⃣ Provider Performance

Purpose: Evaluate provider-level attendance, subsidy distribution, and service load
Key KPIs:

Total Providers: 200

Avg Subsidy per Provider: $45.08K

Avg Attendance per Provider: 878.39 Days

Children per Provider: 21.55

Eligibility Rate: 97%
Visuals:

Top 10 Providers by Subsidy Amount

Attendance vs Subsidy (Scatter)

Provider Summary Table

Provider Distribution by County

3️⃣ Family & Eligibility

Purpose: Understand family composition, income profiles, and eligibility outcomes
Key KPIs:

Total Families Served: 2,000

Eligible Families: 1,940

Eligibility Rate: 97%

Average Family Size: 3.74 Members
Visuals:

Eligibility Breakdown (Approved/Pending/Rejected)

Eligibility Rate by County

Families by Income Level

4️⃣ Child Profile & Attendance

Purpose: Analyze attendance, age group distribution, and participation across programs
Key KPIs:

Total Children: 4,310

Total Attendance Days: 175,677

Average Attendance per Child: 40.76 Days

Avg Subsidy per Child: $2.09K
Visuals:

Attendance Trend by Year

Attendance by Program

Children by Age Group

Children by Race & Gender

⚙️ Tools & Technologies

Microsoft Power BI for visualization

SQL / Python / Excel for data preparation

Dimensional Data Modeling (Star Schema)

DAX for measures and KPIs

🚀 Impact

This dashboard empowers administrators and policymakers to:

Optimize subsidy allocation across programs

Identify underperforming providers

Ensure equity in access based on family and child demographics

Track participation trends to guide future funding decisions
