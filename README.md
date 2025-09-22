# Canadian Job Market Analysis – Tableau Project

This project analyzes the **Canadian Job Market** using the **Job Bank Dataset (July 2025)**.  
The goal is to uncover actionable insights for job seekers, employers, and policymakers through interactive Tableau dashboards.

---

## Project Overview

The purpose of this project is to explore the Canadian job market to answer questions such as:

- Highest-paying job roles across Canada  
- Vacancy trends by province and job title  
- Salary vs. demand (experience level analysis)  
- Deliver an interactive tool to support career decision-making  

---

## The Dataset

The project uses the **Canadian Job Bank Dataset (July 2025)**, obtained from the official [Government of Canada Job Bank](https://www.jobbank.gc.ca/) website.  
The dataset contains job postings with details such as:

- Job titles  
- Number of vacancies  
- Province  
- Salary ranges  

Data cleaning was performed in **Excel** before creating Tableau visualizations.

---

## Methodology

### 1. Data Cleaning
Performed in Excel to ensure accuracy and consistency for visualization:

1. Removed unnecessary columns (retaining Job Title, Province, Vacancies, Salaries, Experience Level)  
2. Standardized job titles (cleaned duplicates, fixed spellings, merged similar roles)  
3. Corrected and formatted the `Date` column  
4. Handled duplicates and removed records with missing job titles  
5. Replaced `NA` values with *Not Specified* in salary fields  
6. Created a calculated **Average Salary** column from Min and Max values  
7. Adjusted unrealistic or zero salaries (< $15/hour)  
8. Derived a clean **Annual Salary** column using formulas and SWITCH logic  
9. Standardized the Experience Level column into consistent ranges (e.g., "1–3 years")  

### 2. Visualization in Tableau
Developed a suite of dashboards to answer real-world questions about the Canadian job market. Each chart addresses specific problems faced by job seekers, employers, and policymakers.  

**Key Dashboards & Charts:**

- **“Where Should I Work” Tool:**  
  Allows users to select province, experience level, and ranking preference (**Salary** vs **Vacancy**) and see KPIs like:

  - Highest Salary Job Title and Highest Salary (if ranked by Salary)  
  - Top In-Demand Job and Total Vacancies (if ranked by Vacancy)  

- **Vacancies by Province & Job Roles:**  
  Highlights roles with the highest vacancies in each province to help job seekers identify real opportunities.

- **Pay vs Demand (Dual-Axis):**  
  Plots experience levels against vacancy counts and average salaries, showing the trade-off between salary and demand.

- **Job Market Heatmap:**  
  Displays the top 5 in-demand jobs per province. Square size = vacancies, color intensity = salary.

- **Top 10 Salaries by Province:**  
  Ranks the top 10 jobs by average annual salary with a province filter for comparison.

---

## Key Insights & Findings

- **Salary vs Demand Trade-Off:**  
  Entry-level roles have higher vacancies but lower salaries; senior roles have better pay but fewer openings.  

- **Provincial Job Market Gaps:**  
  Ontario and British Columbia have high demand; other provinces offer competitive pay but fewer opportunities.  

- **Top-Paying Roles Identified:**  
  Specialized technical and healthcare positions consistently rank among the highest-paying jobs.  

- **In-Demand Occupations:**  
  Retail, customer service, and IT support roles dominate vacancy counts for early-career professionals.  

- **Decision-Support Tool:**  
  The *“Where Should I Work”* dashboard empowers users to filter by province, experience level, and ranking preference, making raw data actionable.

---

## Business Impact

This project provides actionable insights for multiple stakeholders:

- **Job Seekers:** Identify high-paying roles, understand provincial demand, and make informed career choices.  
- **Employers:** Benchmark salaries, locate competitive provinces for hiring, and anticipate workforce supply-demand gaps.  
- **Policymakers:** Gain visibility into labor market gaps for targeted education, training, and immigration policies.

By transforming raw labor market data into interactive dashboards, this project acts as a decision-support system, turning complex datasets into practical guidance for workforce planning.

---

## Tools & Skills

- **Tools:** Excel (Data Cleaning), Tableau (Visualization)  
- **Skills:** Calculated Fields · Parameters · Dual-Axis Charts · Dashboard Actions · Interactive Filters · Data Cleaning in Excel  

---


