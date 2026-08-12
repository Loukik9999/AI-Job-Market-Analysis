# AI Job Market Analysis

<p align="left">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white" alt="Python 3.x"/>
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white" alt="Jupyter Notebook"/>
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/Microsoft%20Excel-Data%20Processing-217346?logo=microsoftexcel&logoColor=white" alt="Microsoft Excel"/>
  <img src="https://img.shields.io/badge/Git-Version%20Control-F05032?logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub-Repository-181717?logo=github&logoColor=white" alt="GitHub"/>
</p>

---

## 📌 Project Overview

The **AI Job Market Analysis** project explores the Artificial Intelligence job market by analyzing job postings across different companies, locations, experience levels, salary ranges, work arrangements, required skills, posting dates, and job sources.

The project uses **Python, Pandas, NumPy, Excel, and Power BI** to transform raw job-market data into meaningful insights and interactive visualizations.

The main goal is to understand the current demand for AI-related roles and identify patterns in **job opportunities, salaries, required skills, experience levels, locations, and remote-work arrangements**.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Analyze the distribution of AI-related job opportunities.
* Identify commonly available AI job titles.
* Analyze AI job opportunities across countries and cities.
* Examine minimum and maximum salary ranges.
* Analyze job opportunities by experience level.
* Identify frequently required skills.
* Analyze remote, hybrid, and on-site work opportunities.
* Explore job-posting trends.
* Identify patterns in the AI employment market.
* Create interactive Power BI dashboards.
* Present data-driven insights in an easy-to-understand format.

---

## 🗂️ Dataset

The dataset contains information about AI-related job postings.

### Dataset Attributes

| Column             | Description                                         |
| ------------------ | --------------------------------------------------- |
| `job_title`        | Title of the job                                    |
| `company`          | Company offering the position                       |
| `country`          | Country of the job                                  |
| `city`             | City associated with the job                        |
| `salary_min`       | Minimum reported salary                             |
| `salary_max`       | Maximum reported salary                             |
| `currency`         | Currency used for the salary                        |
| `remote_type`      | Work arrangement such as remote, hybrid, or on-site |
| `experience_level` | Required experience level                           |
| `required_skills`  | Skills required for the position                    |
| `posted_date`      | Date when the job was posted                        |
| `source`           | Source of the job posting                           |

---

## 🔄 Project Workflow

The project follows an end-to-end data analysis workflow:

```text
Raw AI Job Data
       ↓
Data Exploration
       ↓
Data Cleaning
       ↓
Data Preparation
       ↓
Exploratory Data Analysis
       ↓
Insight Generation
       ↓
Power BI Visualization
       ↓
Dashboard Development
       ↓
Project Presentation
```

---

## 🧹 Data Cleaning & Preparation

The raw AI job dataset was analyzed and prepared using **Python and Pandas**.

The data preparation process includes:

* Loading the raw Excel dataset.
* Exploring the structure of the dataset.
* Checking column names and data types.
* Checking for missing values.
* Validating the dataset.
* Preparing the data for further analysis.
* Exporting the cleaned dataset to Excel.

The cleaned dataset is available in:

```text
data/Clean_AI_Jobs.xlsx
```

---

## 🐍 Python Data Analysis

Python was used for data exploration, cleaning, and analysis.

### Libraries Used

* **Pandas** — Data manipulation and analysis
* **NumPy** — Numerical operations
* **Jupyter Notebook** — Interactive data analysis

### Analysis Areas

The notebook analyzes several aspects of the AI job market, including:

* Job titles
* Companies
* Countries
* Cities
* Salary ranges
* Currencies
* Experience levels
* Remote work types
* Required skills
* Posting dates
* Job sources

The complete Python analysis is available in:

```text
notebooks/AI_Job_Analysis.ipynb
```

---

## 📊 Power BI Dashboard

**Microsoft Power BI** was used to create an interactive dashboard for exploring the AI job market.

The dashboard provides visual analysis of:

* AI job distribution
* Job titles
* Geographic distribution
* Salary ranges
* Experience levels
* Remote work opportunities
* Required skills
* Job-market patterns

The Power BI file is available at:

```text
powerbi/AI_Job_Market_Analysis.pbix
```

---

## 📈 Key Analysis Areas

### 1. Job Market Distribution

The project analyzes the distribution of AI-related job opportunities across different job categories, companies, countries, and cities.

### 2. Salary Analysis

Salary information is analyzed using minimum and maximum salary values to understand compensation ranges across AI-related positions.

### 3. Experience Level Analysis

The project examines job opportunities according to the experience level required by employers.

This helps identify the distribution of opportunities across different career stages.

### 4. Remote Work Analysis

Different work arrangements are analyzed, including:

* Remote
* Hybrid
* On-site

This provides an overview of flexible work opportunities in the AI job market.

### 5. Skills Analysis

The `required_skills` field is analyzed to understand the skills employers commonly request for AI-related positions.

This can help students and job seekers identify important technical skills to develop.

### 6. Geographic Analysis

Countries and cities are analyzed to identify locations where AI-related job opportunities are concentrated.

### 7. Job Posting Analysis

The `posted_date` field can be used to examine the timing and distribution of job postings and identify potential trends in AI hiring activity.

---

## 🛠️ Technologies & Tools

| Technology / Tool    | Purpose                                 |
| -------------------- | --------------------------------------- |
| **Python**           | Data analysis and preprocessing         |
| **Pandas**           | Data cleaning and manipulation          |
| **NumPy**            | Numerical operations                    |
| **Jupyter Notebook** | Interactive analysis                    |
| **Microsoft Excel**  | Raw and cleaned dataset storage         |
| **Power BI**         | Interactive dashboard and visualization |
| **PowerPoint**       | Project presentation                    |
| **Git**              | Version control                         |
| **GitHub**           | Project hosting and portfolio           |

---

## 📁 Project Structure

```text
AI-Job-Market-Analysis/
│
├── data/
│   ├── AI Jobs Data.xlsx
│   └── Clean_AI_Jobs.xlsx
│
├── notebooks/
│   └── AI_Job_Analysis.ipynb
│
├── powerbi/
│   └── AI_Job_Market_Analysis.pbix
│
├── presentation/
│   └── AI_Job_Market_Analysis.pptx
│
├── .gitignore
└── README.md
```

---

## ▶️ How to Explore the Project

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/AI-Job-Market-Analysis.git
```

### 2. Navigate to the Project

```bash
cd AI-Job-Market-Analysis
```

### 3. Explore the Dataset

The raw and cleaned datasets are available inside:

```text
data/
```

### 4. Open the Jupyter Notebook

Open:

```text
notebooks/AI_Job_Analysis.ipynb
```

using Jupyter Notebook or JupyterLab.

The notebook contains the Python-based data analysis and preprocessing work.

### 5. Open the Power BI Dashboard

Open:

```text
powerbi/AI_Job_Market_Analysis.pbix
```

using Microsoft Power BI Desktop.

### 6. View the Project Presentation

The project presentation is available in:

```text
presentation/AI_Job_Market_Analysis.pptx
```

---

## 💡 Project Insights

The project provides a data-driven view of the AI employment landscape by examining relationships between:

* Job demand
* Salary
* Experience level
* Required skills
* Location
* Remote-work arrangements
* Companies
* Job-posting activity

The analysis can help **students, job seekers, recruiters, and organizations** better understand the changing requirements of the AI job market.

---

## 🚀 Future Improvements

The project can be further enhanced by:

* Adding more recent AI job-market data.
* Automating data collection from job portals.
* Building an automated ETL pipeline.
* Performing salary normalization across currencies.
* Performing advanced skill-frequency analysis.
* Applying Natural Language Processing to job descriptions.
* Developing salary prediction models.
* Predicting future AI job-demand trends.
* Adding interactive geographic maps.
* Automating Power BI data refresh.
* Comparing AI job-market trends across different time periods.

---

## 📚 Skills Demonstrated

This project demonstrates practical knowledge of:

* Data Collection
* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Data Visualization
* Python
* Pandas
* NumPy
* Excel
* Power BI
* Dashboard Development
* Data Interpretation
* Business Insights
* Data Storytelling
* Git & GitHub

---

## 📊 Project Deliverables

The project contains the following deliverables:

### Dataset

```text
AI Jobs Data.xlsx
```

Original/raw AI job-market dataset.

### Cleaned Dataset

```text
Clean_AI_Jobs.xlsx
```

Prepared dataset used for analysis and visualization.

### Python Analysis

```text
AI_Job_Analysis.ipynb
```

Jupyter Notebook containing the data analysis workflow.

### Power BI Dashboard

```text
AI_Job_Market_Analysis.pbix
```

Interactive dashboard for exploring the AI job market.

### Project Presentation

```text
AI_Job_Market_Analysis.pptx
```

Presentation summarizing the project and analysis.

---

## 👨‍💻 Author

**Louks**

Data Science / Data Analytics Project

---

## ⭐ Project Summary

**AI Job Market Analysis** is an end-to-end data analytics project that transforms AI job-market data into meaningful insights using **Python, Pandas, NumPy, Excel, and Power BI**.

The project demonstrates the complete analytics workflow — from **raw data exploration and cleaning to analysis, visualization, dashboard development, and presentation of insights**.
