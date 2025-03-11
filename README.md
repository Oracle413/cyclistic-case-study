# **Cyclistic Bike Share Case Study 🚲**
**Author:** Alana Ellis | **Tools Used**: R, SQL (BigQuery), Tableau
**Data analysis project using R, SQL (BigQuery), and Tableau to analyze Cyclistic's bike-share data.**

## **Project Overview**
This case study analyzes Cyclistic bike-share data to uncover insights on **casual riders vs. annual members**, with the goal of increasing membership conversions. 
**Objective:** Identify trends in casual vs. member riders and develop data-driven marketing strategies.
This project uses **R for data cleaning, SQL for analysis, and Tableau for visualization**, this project provides data-driven recommendations to optimize Cyclistic's marketing strategy. 

## **Repository Structure**
- `data/` (not included due to licensing)
- `scripts/` -> R scripts for **data cleaning & prep**
- `visuals/` -> All Tableau-generated **final visualizations**
- `notebooks/` -> **Kaggle Notebook** with SQL queries and insights
- `README.md` -> Project Overview

## **Data Cleaning & Preparation (R Studio)**
- Extracted ride duration, ride day, and month
- Filtered out invalid ride durations (negative values, zero-length rides, and rides exceeding 24 hours).
- Formatted timestamps to ensure compatibility with BigQuery
- Full R Script: `Cyclistic_Cleaning.R`

## **Exploratory Data Analysis (BigQuery)**
The dataset was analyzed using SQL queries in BigQuery. Key queries include:
- Total rides by user type
- Ride duration trends
- Peak ride times by user type
- Weather impact on ridership
- Round trip vs. one-way rides
Full analysis in the **Kaggle Notebook**: [Cyclistic Case Study on Kaggle](https://www.kaggle.com/code/alanaellis/cyclistic-bike-share-case-study)

## **Data visualization (Tableau)**
All final charts were created in Tableau and exported as PNGs for this repository.

**Key Insights & Recommendations:**
- Casual riders increase significantly in spring -> Launch seasonal discounts
- Casual riders take longer, round-trip rides -> Introduce flexible pass options
- Casual rides occur on weekdays -> Promote commuter memberships

Visuals Directory: `visuals/`

## **Next Steps**
- Set up a portfolio website to host case studies (in progress)
- Add additional case studies to strengthen portfolio
- Apply these methods to new datasets for more practice

## **References**
[Divvy Data License](https://divvybikes.com/data-license-agreement)
[National Weather Service](https://www.weather.gov/lot/ord_rfd_monthly_yearly_normals)

## **How to Use this Repository**
1. Clone the repository:
``` 
git clone https://github.com/Oracle413/cyclistic-bike-share.git
```
2. Explore the `scripts/` folder for **R cleaning scripts**
3. View the **SQL queries** in the Kaggle notebook
4. Check out **final visuals** in `visuals/`

## **Connect with Me**
📍 [LinkedIn](https://www.linkedin.com/in/alana-ellis-12840774/) | 📍 [Portfolio (Currently in Development)]()



**🔗 View Full Case Study on Kaggle:** [Cyclistic Case Study](https://www.kaggle.com/code/alanaellis/cyclistic-bike-share-case-study)


