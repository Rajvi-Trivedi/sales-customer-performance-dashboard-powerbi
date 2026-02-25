# Student Academic & Behavioral Analysis Dashboard

**Business Intelligence Project | Power BI**

---

## Project Objective

Designed an interactive Power BI dashboard to analyze student academic performance, attendance patterns, and behavioral trends.

The objective was to uncover correlations between attendance, behavior, and exam performance, enabling data-driven academic decision-making.

---

## Data Sources

The dashboard integrates multiple structured datasets:

* **Students** – Student ID, Name, Class, Section, Gender
* **Scores** – Subject-wise exam scores, exam type, term, maximum score
* **Attendance** – Attendance percentage and attendance status
* **Behavior** – Categorized behavior records

All datasets are relationally connected using **StudentID**.

---

## Data Modeling

* Implemented a **star schema data model**
* Students table used as the central dimension
* Scores, Attendance, and Behavior treated as fact tables
* Established one-to-many relationships
* Performed data cleaning:

  * Data type correction
  * Handling missing values
  * Column standardization

---

## DAX Measures Implemented

Created dynamic measures to support KPI tracking and segmentation:

* Total Students
* Total Score
* Total Max Score
* Average Score
* Percentage Score
* Attendance %
* Behavior Count
* Performance Category (High / Medium / Low using SWITCH logic)

All measures dynamically update based on slicer selections.

---

## Dashboard Components

### KPI Indicators

* Total Students
* Average Score
* Percentage Score
* Attendance %
* Performance Category

### Visualizations

**Subject Performance Analysis (Bar Chart)**
Compares average scores by subject and class.

**Term-wise Performance Trend (Line Chart)**
Tracks academic progression across terms.

**Behavior Distribution (Donut Chart)**
Analyzes frequency of behavior categories.

**Student-Level Performance Table**
Includes conditional formatting to quickly identify high and low performers.

---

## Interactive Features

* Slicers for Class, Section, Subject, and Term
* Dynamic cross-filtering across all visuals
* Conditional formatting:

  * Green – High Performance
  * Red – Low Performance

---

## Key Insights Derived

* Higher attendance shows a positive correlation with academic performance
* Certain subjects consistently demonstrate lower average scores
* Medium-performing students exhibit relatively higher behavior variability
* Academic performance trends vary across different terms

---

## Deliverables

* Student_Academic_Behavior_Dashboard.pbix
* Project documentation

---

## Skills Demonstrated

* Data Modeling (Star Schema Design)
* DAX Calculations & KPI Development
* Data Cleaning & Transformation
* Interactive Dashboard Design
* Insight Extraction & Interpretation

---

## Author

Rajvi Trivedi
Data Analyst | Business Analyst

---
