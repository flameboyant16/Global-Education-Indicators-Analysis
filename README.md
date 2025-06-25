# Global-Education-Indicators-Analysis
Scenario:
You work as a Junior Data Analyst for UNESCO, tasked with analyzing global education indicators for 2023. Your goal is to present a clear dashboard to the policy team using Excel to show gaps, trends, and regional comparisons.
 DATA
________________________________________
Tasks & Questions
Part 1: Cleaning Instructions for Students (Part 1):
On a sheet called Cleaned_Data:
●	Remove the total row

●	Clean all percentage fields (remove %)

●	Convert GDP and population to numbers (remove "$", "USD", etc.)

●	Standardize capitalization for countries and regions

●	Replace “n/a” with blank or appropriate value

●	Fix spelling/formatting of “avg yrs of schooling”

●	Convert "two hundred fifteen" and "240M" into proper numeric values

●	Trim whitespaces from column names and fix their casing (e.g., Literacy Rate % → Literacy Rate (%))

Part 2: Answer These Questions 
Use formulas or PivotTables:
1.	What is the average literacy rate per region?

2.	Which country has the highest and lowest Internet Access?

3.	What is the total population of countries with literacy rate below 80%?

4.	Which region has the highest average GDP per Capita?

________________________________________
Part 3: Visualizations
Create at least 4 charts:
1.	Bar Chart – Literacy Rate by Country

2.	Pie Chart – Population by Region

3.	Line Chart – Compare Literacy Rate vs Internet Access (you may simulate years by duplicating this dataset with 2–3 years of dummy data)

4.	Filled Map (optional) – if using Excel 2019+: Show literacy rate by country

________________________________________
Part 4: Build Your Excel Dashboard
In a new sheet titled Dashboard:
●	Add:

○	KPIs (Average Literacy Rate, Global Internet Access Avg, Total Population)

○	Interactive filters (Slicers on Region or Country if using PivotTables)

○	Your 3–4 charts arranged neatly

○	Title and color-coded sections

________________________________________
Part 5: Key Insights
Write 2–3 insights in a text box:
●	What can you conclude from your dashboard?

●	Where are the biggest gaps in education access?

________________________________________

ADD IT TO GITHUB


1. Create a GitHub Account
If you don’t have one yet, sign up at github.com.
________________________________________
2. Create a New Repository
●	Log in to GitHub.

●	Click the + icon (top right) → New repository.

●	Name your repo (e.g., GlobalEduDashboard).

●	Add a short description (optional).

●	Choose Public or Private as per instructions.

●	Do NOT initialize with a README (we’ll add it ourselves).

●	Click Create repository.

________________________________________
3. Prepare Your Project Folder Locally
●	On your computer, create a folder named GlobalEduDashboard.

●	Place all your assignment files inside, for example:

○	Cleaned_Data.xlsx

○	YourName_GlobalEduDashboard.xlsx (your dashboard file)

○	Any notes, screenshots, or related files

________________________________________
4. Add a README.md File
In the same folder, create a new file called README.md (a simple text file with markdown formatting).
 Use the sample README content provided below or write your own to describe your project.
________________________________________
5. Upload Your Files to GitHub
Option A: Using GitHub Web Interface (Easiest)
●	Open your GitHub repo page.

●	Click Add file → Upload files.

●	Drag and drop all your assignment files including README.md.

●	Scroll down, write a commit message like:
 Initial upload: cleaned data, dashboard file, and README

●	Click Commit changes.

________________________________________
Option B: Using Git Command Line (If familiar)
 Open your terminal or command prompt:

cd path/to/GlobalEduDashboard
git init
git add .
git commit -m "Initial upload: cleaned data, dashboard, and README"
git branch -M main
git remote add origin https://github.com/yourusername/GlobalEduDashboard.git
git push -u origin main

________________________________________
6. Share Your GitHub Repository Link
Copy your repo URL (e.g., https://github.com/yourusername/GlobalEduDashboard) and submit it as per your instructor’s request.
________________________________________

Sample README.md Content

# Global Education Metrics Dashboard

## Overview
This project contains an Excel dashboard analyzing global education data for 2023. The dashboard provides insights on literacy rates, internet access, average years of schooling, GDP per capita, and population across various countries and regions.

## Data Cleaning
- Standardized country and region names.
- Removed special characters from numeric fields (%,$, USD).
- Converted text numbers to numeric values.
- Handled missing data and removed summary rows.

## Analysis & Visualizations
- Created summary tables and PivotTables to answer key questions:
  - Average literacy rate per region.
  - Countries with highest and lowest internet access.
  - Population totals for countries below 80% literacy.
  - Region with highest average GDP per capita.
- Visualized data with bar charts, pie charts, line charts, and map charts.
- Built an interactive Excel dashboard with slicers for region and country filtering.

## How to Use
Open the file `YourName_GlobalEduDashboard.xlsx` and use the `Dashboard` sheet to interact with the data. Use the slicers to filter by region or country and explore various metrics.

## Author
Your Name  
Your email or contact (optional)

## Date
June 2025



























Optional

 You can do this entire process—data cleaning, analysis, and dashboard building—in IBM Cognos Analytics, though the approach will differ a bit since Cognos is a BI/reporting platform rather than a spreadsheet tool.
________________________________________
How to adapt this Excel dashboard assignment for IBM Cognos Analytics:
1. Data Import & Cleaning in Cognos:
●	Upload your messy dataset (CSV or Excel) into Cognos.

●	Use Data Modules or Data Preparation feature to:

○	Clean data (e.g., remove extra characters like %, $, text in numeric columns)

○	Fix capitalization (you can create calculated fields using functions like UPPER(), LOWER(), INITCAP())

○	Replace missing values or nulls

○	Convert data types (text → number, string → date, etc.)

○	Filter out summary rows (like “Total”)

○	Rename columns for clarity

2. Analysis:
●	Create data visualizations and reports in Cognos:

○	Use Data Visualization feature for bar charts, line charts, pie charts

○	Use Geo Maps for filled maps (choropleth) based on country/region

●	Use calculations in the report to answer questions like averages, totals, min/max, etc.

3. Dashboard Creation:
●	Use Cognos Dashboard tool to drag and drop visualizations

●	Add filters or prompt controls for interactive filtering (region, country, year)

●	Configure interactivity between visuals (e.g., selecting a region filters other charts)

4. Sharing & Presentation:
●	Cognos dashboards are web-based and easily shared within your organization

●	Add narrative text boxes to summarize insights



