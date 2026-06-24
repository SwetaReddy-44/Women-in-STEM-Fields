# 📊 Women in STEM Fields - Tableau Dashboard Analysis

An interactive data visualization project built in Tableau to examine the gender representation, graduation trends, educational alignment, and salary disparities for women in Science, Technology, Engineering, and Mathematics (STEM) fields.

---

## 📌 Table of Contents
* [🎨 Dashboard Overview](#-dashboard-overview)
* [📈 Key Visualizations & Insights](#-key-visualizations--insights)
  * [1. Occupation Representation & Total Employment](#1-occupation-representation--total-employment)
  * [2. Graduation Trends in CS & Engineering (2000-2015)](#2-graduation-trends-in-cs--engineering-2000-2015)
  * [3. Education vs. Field of Work](#3-education-vs-field-of-work)
  * [4. Career Pathway Alignment by Gender](#4-career-pathway-alignment-by-gender)
  * [5. Salary Disparities by Gender & Ethnicity](#5-salary-disparities-by-gender--ethnicity)
* [🗃️ Data Sources & Structure](#%EF%B8%8F-data-sources--structure)
* [🛠️ Technical Implementation](#%EF%B8%8F-technical-implementation)
* [🚀 How to View the Dashboard](#-how-to-view-the-dashboard)

---

## 🎨 Dashboard Overview

This Tableau dashboard is designed to highlight the systemic gender gap in STEM fields. By analyzing dataset trends across graduation rates, employment shares, educational levels, and annual earnings, the dashboard visually presents the major friction points preventing women's equal representation in high-paying technical fields.

> [!TIP]
> **View the Interactive Dashboard:** 
> 🔗 **[Click here to view the live dashboard on Tableau Public](YOUR_TABLEAU_PUBLIC_LINK_HERE)** *(Replace this placeholder with your actual Tableau Public URL)*

---

## 📈 Key Visualizations & Insights

The dashboard is structured vertically to guide the viewer through a narrative of representation, education, alignment, and finally compensation. Below are the key components and their corresponding data insights:

### 1. Occupation Representation & Total Employment
* **Worksheets:** 
  * `Percentage of Women in Different Occupations`
  * `Women % of Total Employeed` (KPI metric)
* **Visual Representation:** Bar charts showing the breakdown of women in specific STEM careers alongside overall employment share indicators.
* **Key Insight:** 
  > **"The main reason for the gender gap is STEM Jobs is the lower percentage of women in computer and engineering occupations. Because out of 100%, only 41.7% of women opt for STEM fields for their graduation. Out of this 41.7%, only 38.1% of women graduate in both fields—a very low percentage. While many factors contribute to the gender gap, this low participation rate in core majors is a primary driver. Society should encourage women to opt for these fields."**

---

### 2. Graduation Trends in CS & Engineering (2000-2015)
* **Worksheet:** `Trend of percent women graduating in computer science and engineering from 2000-2015`
* **Visual Representation:** A line graph tracking the graduation rates over a 15-year period.
* **Key Insight:** 
  > **"According to the trend, only 20% of women graduated in the field of Engineering and only 18% of women graduated in the field of Computer Science in 2015."**

---

### 3. Education vs. Field of Work
* **Worksheet:** `Percent of Women by education in Different fields`
* **Visual Representation:** A segmented analysis of women's career choices based on their level of education (e.g., Master's degree, Professional Doctorate).
* **Key Insight:** 
  > **"According to the graph, 80% of women who completed their master's degree and 45% of women who completed their professional doctor degree are working in health-related jobs."**

---

### 4. Career Pathway Alignment by Gender
* **Worksheet:** `percentage of Men and Women working in the related field of their Education`
* **Visual Representation:** A comparative flow or side-by-side bar chart evaluating how many graduates actually enter their field of study.
* **Key Insight:** 
  > **"According to this graph: 1. Only 38% of women working in Computers majored in Computer Science. 2. Only 24% of women working in Engineering majored in Engineering."**

---

### 5. Salary Disparities by Gender & Ethnicity
* **Worksheet:** `Comparison graph of All/Men/Women by Salaries Ethnicity`
* **Visual Representation:** A multi-layered bar chart showing median annual earnings compared by gender and ethnic background.
* **Key Insight:** 
  > **"The median salary of an Asian man is greater than the salary of an Asian woman, with a significant pay gap of $15,300."**

---

## 🗃️ Data Sources & Structure

The workbook utilizes 5 specialized datasets (Project 1 data) to feed the visualizations:

1. **Employed Persons:** Details demographics of the workforce.
   * *Key Fields:* `Occupation`, `Total employed`, `Women (% of total)`, `White (%)`, `Black or African American (%)`, `Asian (%)`, `Hispanic or Latino (%)`.
2. **Women Graduated:** Longitudinal graduation data (2000–2015).
   * *Key Fields:* `Year`, `Engineering`, `Computer sciences`, `Physical sciences`, `Social sciences`, `Psychology`, `Biological and agricultural sciences`, `Mathematics and statistics`.
3. **Stem jobs by Education:** Level of education by job type.
   * *Key Fields:* `High school or less`, `Some college`, `Bachelor's degree`, `Master's degree`, `Professional Doctoral degree`.
4. **Professional working in same major:** Tracks career alignment.
   * *Key Fields:* `Profession`, `Men (%)`, `Women (%)`.
5. **Median Annual Earnings:** Salary comparison.
   * *Key Fields:* `Ethnicity`, `All (Dollars)`, `Men (Dollars)`, `Women (Dollars)`.

---

## 🛠️ Technical Implementation

* **Platform:** Tableau Desktop / Tableau Public
* **Workbook Format:** `.twbx` (Tableau Packaged Workbook including data extracts)
* **Interactions & Design:**
  * Custom pastel-colored canvas panels (`#e9f3f2`, `#f3faf9`, `#faf5f0`, `#f6eee3`, `#f9eee8`) to separate findings visually.
  * Solid structural borders (`border-width: 2px`) for a clean, report-style aesthetic.
  * Interactive legends and dynamic tooltips to reveal exact percentages on hover.

---

## 🚀 How to View the Dashboard

### Option 1: Live Web View (Recommended)
Simply click the Tableau Public link above to interact with the visualizations directly in your web browser.

### Option 2: Local Tableau Software
1. Clone this repository or download the workbook file: `Women in STEM fields.twbx`.
2. Open the file using **Tableau Desktop** (v2020.1 or newer) or **Tableau Public** (Free version).
3. If prompted, the packaged file already contains all necessary data extracts (no database configuration required).

---

*Analysis and Dashboard created by **[Your Name]**.*

