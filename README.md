🚗 Electric Vehicle Registration Analytics Dashboard
1. Project Title / Headline

🚗 Electric Vehicle Registration Analytics Dashboard
A comprehensive and interactive Power BI dashboard designed to analyze Electric Vehicle (EV) registrations across counties, cities, manufacturers, and model years. The dashboard provides valuable insights into EV adoption trends, geographical distribution, manufacturer performance, and vehicle eligibility, enabling stakeholders to make data-driven decisions in the rapidly growing electric mobility sector.

2. Short Description / Purpose
The Electric Vehicle Registration Analytics Dashboard provides a detailed overview of EV registrations by exploring geographical distribution, manufacturer performance, model trends, CAFV eligibility, and year-over-year growth. It is designed to help policymakers, automobile manufacturers, researchers, and business analysts understand EV adoption patterns and identify emerging opportunities in the electric vehicle market.

3. Tech Stack
The dashboard was built using the following tools and technologies:
📊 Power BI Desktop – Used for designing interactive reports and dashboards.
📂 Power Query – Used for data cleaning, transformation, and preprocessing.
🧠 DAX (Data Analysis Expressions) – Used for KPI calculations, dynamic measures, and analytical metrics.
🔗 Data Modeling – Relationships created among vehicle registration, manufacturer, location, and eligibility datasets for efficient filtering and analysis.
📈 Interactive Visualizations – KPI Cards, Maps, Bar Charts, Donut Charts, Treemaps, Line Charts, Waterfall Charts, Funnel Charts, and Slicers.
📁 File Format – .pbix for development and .png for dashboard previews.
4. Data Source

Source: Washington State Electric Vehicle Population Dataset (Public EV Registration Data) - Kaggle
The dataset contains approximately 18,000 electric vehicle registration records and includes detailed information about:
Vehicle Identification Number (VIN)
Model Year
Electric Vehicle Type (BEV & PHEV)
Manufacturer
Vehicle Model
Electric Range
County
City
CAFV Eligibility
Utility Provider
Geographic Coordinates

The data was cleaned and transformed using Power Query before building the dashboard.

5. Features / Highlights
• Business Problem
As electric vehicle adoption continues to grow, governments, manufacturers, and infrastructure planners require a centralized platform to monitor registration trends and market penetration. However, raw registration data makes it difficult to answer questions such as:

Which manufacturers dominate the EV market?
Which counties have the highest EV adoption?
How has EV registration changed over time?
What proportion of vehicles are Battery Electric Vehicles (BEVs) versus Plug-in Hybrid Electric Vehicles (PHEVs)?
Which cities are experiencing the fastest EV growth?
How many vehicles qualify for Clean Alternative Fuel Vehicle (CAFV) incentives?

Without interactive analytics, identifying these trends becomes time-consuming and inefficient.

• Goal of the Dashboard
The dashboard was developed to:
Monitor overall EV registration trends.
Analyze geographical distribution of electric vehicles.
Compare manufacturer performance.
Evaluate EV adoption across model years.
Understand CAFV eligibility distribution.
Track year-over-year registration growth.
Support strategic planning for EV infrastructure, policy, and market expansion.
• Walkthrough of Key Visuals

Dashboard 1 – EV Overview
Executive KPI Cards

Provides a high-level overview of the EV market:
Average Electric Range
Total EV Registrations (18K)
Number of Manufacturers (48)
Number of Vehicle Models (196)

These KPIs summarize the overall scale and diversity of the EV ecosystem.
Vehicle Type Distribution (Donut Chart)

Shows the proportion of:
Battery Electric Vehicles (BEV)
Plug-in Hybrid Electric Vehicles (PHEV)

This visualization highlights the market share of each EV technology.
Top 10 EV Manufacturers (Horizontal Bar Chart)
Ranks manufacturers based on total EV registrations.

Helps identify:
Leading manufacturers
Market competition
Brand popularity
Top Cities Having EV (Column Chart)

Displays cities with the highest EV registrations.

Useful for identifying urban adoption hotspots.

EV Registrations by Model Year (Line Chart)

Illustrates registration trends across different model years, helping users understand the evolution of EV adoption over time.

Manufacturers by Model Year (Treemap)

Shows how manufacturers are distributed across different model-year categories, allowing comparison of manufacturer presence in newer and older vehicle segments.

Dashboard 2 – Geographical Analysis
Geographic KPI Cards

Displays:

Total Counties (47)
Total Cities (301)
Average Electric Range
Number of Vehicle Models

Provides a quick geographical summary of the dataset.
Interactive Map – EV Locations
Plots EV registrations across counties and cities using Bing Maps.
Allows users to explore regional EV distribution and identify areas with higher vehicle concentration.
EV Registrations by County (Treemap)
Ranks counties according to total EV registrations.
Quickly highlights the counties with the largest EV populations.
EV Registrations by County and Vehicle Type (Filled Map)
Visualizes the distribution of Battery Electric Vehicles and Plug-in Hybrid Electric Vehicles across different counties.
Supports regional comparisons of EV adoption.
Electric Vehicle Distribution by County (Pie Chart)
Shows the percentage share of EV registrations across selected counties, making it easy to compare regional market share.
Vehicle Models Used by City (Donut Chart)
Displays the distribution of vehicle models across major cities, helping identify areas with greater model diversity.

Dashboard 3 – Advanced EV Analytics
EV Registrations Over Time by Type (Area Chart)

Compares yearly registration trends for:

Battery Electric Vehicles (BEVs)
Plug-in Hybrid Electric Vehicles (PHEVs)

This visualization highlights adoption growth across vehicle technologies.
Top Manufacturer Ranking by Model Year (Ribbon Chart)
Illustrates changes in manufacturer rankings over different model-year groups, helping identify shifts in market leadership.
CAFV Eligibility Breakdown (Funnel Chart)
Displays the number of vehicles that are:

CAFV Eligible
Not Eligible
Unknown Eligibility

Useful for understanding eligibility for clean-energy incentive programs.
Year-over-Year EV Registration Growth (Waterfall Chart)
Shows how EV registrations have increased across model-year categories and illustrates cumulative growth over time.
This chart helps stakeholders measure the pace of EV adoption.
Interactive Filters
Users can filter the dashboard by:

County
City
Manufacturer
Model Year
Vehicle Type
CAFV Eligibility

All visuals update dynamically, enabling detailed exploration from multiple perspectives.

• Business Impact & Insights
Market Intelligence
Manufacturers can analyze market share, identify high-performing regions, and benchmark their performance against competitors.
Infrastructure Planning
Government agencies can identify counties with high EV adoption to prioritize charging station deployment and grid expansion.
Policy Evaluation
CAFV eligibility analysis helps policymakers evaluate the effectiveness of clean-energy incentive programs.

Regional Planning
Geographical insights enable better allocation of transportation resources and support sustainable urban planning.
Consumer Trend Analysis
Businesses can understand consumer preferences for specific manufacturers, models, and vehicle types across different cities and counties.
Strategic Decision Making

The dashboard consolidates EV registration data into an interactive analytical platform, enabling stakeholders to make informed decisions regarding market expansion, infrastructure investment, and future mobility planning.

6. Screenshots / Demo
Dashboard Pages
📊 Dashboard 1 – EV Overview -https://github.com/chentsa/Electric-Vehicle-Registration-Analytics-Dashboard/blob/main/Electric%20Vehicle%20Overview.png
Displays key KPIs, manufacturer analysis, vehicle type distribution, city-wise registrations, model-year trends, and manufacturer segmentation.

🌍 Dashboard 2 – Geographical Analysis - https://github.com/chentsa/Electric-Vehicle-Registration-Analytics-Dashboard/blob/main/Electric%20Vehicle%20Ogeogrpahical analysis.png 
Provides interactive maps, county-wise registration analysis, geographical distribution of EVs, and regional adoption insights.

📈 Dashboard 3 – EV Trends & Advanced Analytics - https://github.com/chentsa/Electric-Vehicle-Registration-Analytics-Dashboard/blob/main/Electric%20Vehicle%20Otrend.png 
Includes EV registration growth over time, manufacturer ranking analysis, CAFV eligibility breakdown, and year-over-year registration trends.
