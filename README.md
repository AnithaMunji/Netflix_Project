#  Netflix Dashboard | Power BI Project

## Project Overview

The Netflix Dashboard is an interactive Power BI project developed using the Netflix Movies and TV Shows dataset. The dashboard provides analytical insights into Netflix’s content library by exploring trends related to movies, TV shows, genres, ratings, release years, and country-wise content distribution.

The project helps users understand content growth patterns, audience ratings, and global distribution of Netflix titles through dynamic visualizations and KPI-driven reporting.

---

## Objectives

- Analyze Netflix content distribution across movies and TV shows
- Identify trends in content releases over time
- Explore genre-wise and rating-wise content patterns
- Examine country-wise contribution to Netflix’s catalog
- Build an interactive dashboard for data-driven insights

---

## Dataset Information

The project uses the Netflix Movies and TV Shows dataset containing:

- Show ID
- Title
- Type (Movie / TV Show)
- Director & Cast Information
- Country
- Release Year
- Date Added
- Rating
- Duration
- Genre Categories

Dataset Source: Kaggle / Public Dataset

---

## Data Cleaning & Transformation

Performed data preprocessing and transformation using Power Query:

- Removed empty rows and unnecessary columns
- Converted “Date Added” into proper date format
- Handled missing values and duplicate records
- Standardized text formatting
- Cleaned genre and country-related fields
- Improved overall data consistency and quality

---

## DAX Measures Used

- Total Shows = COUNTROWS('Netflix')
- Total Movies = CALCULATE(COUNTROWS('Netflix'), 'Netflix'[type] = "Movie")
- Total TV Shows = CALCULATE(COUNTROWS('Netflix'), 'Netflix'[type] = "TV Show")
- Titles Added = COUNT('Netflix'[show_id])

---

## Dashboard Features

Developed an interactive Power BI dashboard including:

- KPI Cards
- Interactive Slicers & Filters
- Donut Charts
- Bar Charts
- Column Charts
- Line Charts
- Map Visualizations
- Trend Analysis

The dashboard enables users to explore Netflix content dynamically across multiple dimensions.

---

## Key Analysis Performed

- Movies vs TV Shows distribution analysis
- Genre-wise content analysis
- Rating distribution analysis
- Country-wise Netflix content contribution
- Year-wise title addition trends
- Content growth pattern analysis
- Interactive filtering based on title type

---

## Dashboard Visuals

### KPI Cards
- Total Titles
- Total Movies
- Total TV Shows
- Total Countries

### Donut Chart
- Movies vs TV Shows distribution

### Bar Chart
- Genre-wise content count

### Column Chart
- Rating distribution across titles

### Map Visualization
- Country-wise content production analysis

### Line Chart
- Titles added by year trend analysis

### Slicers / Filters
- Movie / TV Show selection
- Country filters
- Genre filters
- Rating filters

---

## Key Insights

- Movies contributed a larger share of Netflix content compared to TV Shows
- Content additions increased significantly over recent years
- Certain genres dominated Netflix’s content library
- Some countries contributed higher volumes of titles to the platform
- Ratings analysis revealed the most common audience categories targeted by Netflix

---

## Recommendations

- Expand content production in high-performing genres to increase audience engagement
- Analyze viewer preferences across countries for localized content strategies
- Increase investment in regions with growing content demand
- Monitor yearly content growth trends to optimize release planning
- Use dashboard insights to improve content recommendation strategies
- Enhance audience targeting based on rating and genre preferences
- Develop advanced analytics for predicting future content trends

---

## Tools & Technologies Used

- Power BI
- Power Query
- DAX
- Excel / CSV Dataset
- Data Visualization Techniques

---

## Skills Demonstrated

- Data Cleaning & Transformation
- Power BI Dashboard Development
- DAX Calculations
- Data Visualization
- Exploratory Data Analysis (EDA)
- KPI Reporting
- Business Insight Generation
- Analytical Thinking

---

## Project Deliverables

- Netflix_Dashboard.pbix
- Dashboard Screenshots
- README Documentation
- Processed Dataset Files

---

## Conclusion

This project demonstrates practical experience in Power BI dashboard development, data transformation, DAX calculations, and visual analytics. The dashboard provides meaningful insights into Netflix’s content ecosystem and showcases strong business intelligence and reporting skills relevant to Data Analyst and BI roles.
