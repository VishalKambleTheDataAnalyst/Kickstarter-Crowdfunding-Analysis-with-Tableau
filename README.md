# Kickstarter Crowdfunding Analysis & Insights Dashboard in Tableau. 📊
Welcome to the **Kickstarter Crowdfunding Analysis with Tableau** repository! 🚀

This repository contains a project demonstrating an Overview of the Kickstarter Crowdfunding Platform using Tableau. Developed as part of my data analytics portfolio, it highlights my ability to transform raw data into meaningful insights and visually compelling stories using Tableau.

You can see the Dashboard here - https://public.tableau.com/views/Kickstarter_Project_Tableau_VishalOnlyCharts/SuccessInsights?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link


## 📖Table of Contents
- [Introduction](#introduction)
- [Tools & Datasets Used](#tools-&-datasets-used)
- [Methodology](#methodology)
- [Documentation](#documentation)

## ⭐Introduction
Kickstarter is a crowdfunding platform where creators launch independent projects and seek financial support from the public. Funding is all-or-nothing; backers are only charged if a project meets its goal by the deadline. This project aims to uncover trends behind successfully funded Kickstarter campaigns and explore how project creation patterns evolve throughout the year.

## 🛠️Tools & Datasets Used
**Excel:** Power Query for Data Cleaning and Manipulation.

**Tableau:**  Dashboard Building.

**🗒️[Datasets](https://drive.google.com/uc?export=download&id=1libz82_4g2suswoXgAM-UVbkxsqeNnB1):**  Access to project datasets(csv files)
This is a cleaned Dataset.

## 🗂️Methodology
The project followed a structured data analysis and visualization workflow:

**1. Understanding the Objective**
   
   The key goal was to analyze Kickstarter project trends, success rates, and funding behaviors across time and categories.

**2. Data Preparation (Excel + Power Query)**

   - Imported raw Kickstarter data into Excel.
   - Cleaned and transformed the dataset using Power Query (e.g., removed duplicates, standardized column formats, filtered irrelevant records).
   - Created new time-based fields like Year, Quarter, and Month for time series analysis.

**3. Exploratory Data Analysis (EDA)**

   - Explored patterns in project categories, launch dates, and funding outcomes.
   - Identified success trends based on goal amount, category, and time.

**4. Dashboard Development (Tableau)**

   - Built dynamic KPI cards for metrics such as total raised amount, success rate, and project counts.
   - Created interactive charts:
           - Line charts to visualize trends over time
           - Tree Map charts to show category performance
           - A donut chart for the success percentage
   - Implemented parameter-based filtering for Year, Quarter, and Month for dynamic exploration.
     
**5. Insight Generation**

   - Analyzed dashboards to draw meaningful conclusions on what makes a campaign successful.
   - Observed seasonality, popular categories, and goal amount ranges that impact success.

## Documentation

   - The dashboard layout was designed to present insights in a clean, intuitive, and user-friendly format.
   - Included mockup files to showcase the initial design concepts and support decision-making throughout the dashboard development process.
   - Compared the mockup with the final Tableau dashboard to highlight improvements and design choices made during implementation.
   - All visualizations and filters are labeled clearly to ensure interpretability for stakeholders.

## 🔍Insights Findings
From the Dashboard, we were able to find the following answers:

### 🎯Success Factors

- **Goal Amount:**
  
     1. Projects with goals under $10,000 have the highest success rates(42% out of total successful projects).
     2. Among backers who contributed between $1,000 and $10,000, 84% of the funding went to projects in the "Residencies" category, indicating strong support for that category within this funding range.
 
- **Category:**
  
     1. The "Chiptune" (76%) and "Residencies" (74%) categories have the highest success rates, closely followed by "Anthologies" (70%), indicating the strongest success-to-campaign ratios among all categories.

- **Time-Based Trends:**

   - Success rates peak in Q2, particularly in April.
   - On average, successful projects run 31 days from launch to deadline.


### 💸 Funding Patterns

- **Top-Earning Categories:** Product Design(21.40%) and Tabletop Games(14.29%) lead in total funds raised.
- **Average Pledged Amounts:** Successfully funded projects tend to exceed their goals by 20–30%.

### 📅 Seasonal Trends

- More projects are launched in the year's first half, but not all perform equally.
- Late Q4 campaigns show lower engagement and funding.
   
   

## 📂Repository Structure
```
Kickstarter-Crowdfunding-Analysis/
├── 📁 Dashboard/
│   └── Kickstarter_Project_Tableau_Vishal(Charts+Dashboard).twbx
├── 📁 resources/
│   ├── kickstarter logo.png
│   └── 📁 Mockups/
│       ├── Container mockup for Kickstarter Dashboard.drawio
│       ├── Project Trends.png
│       └── Success Insights.png
├── LICENSE
└── README.md
