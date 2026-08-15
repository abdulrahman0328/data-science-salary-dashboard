# Data Science Salary Dashboard

An interactive Excel dashboard for exploring data science job-market salaries, job counts, countries, employment types, and job platforms.

## Dashboard Preview

[[photot1.png]]

## Project Overview

This project analyzes a dataset of **32,672 job postings** and turns the data into an interactive Excel dashboard.

The dashboard is designed to answer practical questions about salary levels, job demand, employment types, and job-posting platforms.

## Business Questions

| Question                                                                                            | Dashboard Approach                      |
| --------------------------------------------------------------------------------------------------- | --------------------------------------- |
| **What is the median salary for a selected job title?**                                             | Median Salary KPI                       |
| **How does salary vary across countries?**                                                          | Country map                             |
| **How does salary differ by employment type?**                                                      | Employment Type chart                   |
| **Which job platforms have the highest number of postings?**                                        | Top Job Platform KPI                    |
| **How do salary and job demand vary across different job titles, countries, and employment types?** | Interactive filters + dashboard visuals |

## Tools & Techniques

- Microsoft Excel
- Excel Tables
- XLOOKUP
- COUNTIFS
- MEDIAN
- FILTER
- SORT
- UNIQUE
- SEARCH
- Dynamic Array Formulas
- Data Validation
- Interactive Charts
- Dashboard Design

## Dataset

The dataset contains **32,672 job-posting records** with fields covering:

- Job title
- Job location
- Job platform
- Employment type
- Work-from-home indicator
- Search location
- Posting date
- Country
- Salary information
- Company
- Job skills

The workbook contains 7 sheets:

1. `datasets` — source dataset
2. `basic calculations` — supporting calculations and lookup lists
3. `jobs` — job-title salary analysis
4. `Dashboard` — interactive dashboard
5. `Country` — country-level salary analysis
6. `type` — employment-type analysis
7. `platform` — job-platform analysis

## Dashboard

The dashboard provides interactive filters for:

- Job Title
- Country
- Employment Type

The selected filters update the main salary, job-count, country, employment-type, and platform views.

[Data Science Salary Dashboard](https://github.com/abdulrahman0328/data-science-salary-dashboard/blob/main/images/Screenshot%202026-08-15%20035618.png)

## Example Dashboard View

The default dashboard view shown in the project uses:

- Job Title: Data Analyst
- Country: United States
- Employment Type: Full-time
- Median Salary: $90,000
- Top Job Platform: Indeed
- Job Count: 6,480

These values describe the displayed filter selection and should not be interpreted as overall dataset statistics.

## Key Project Takeaways

- Built an interactive dashboard from a large job-posting dataset.
- Used Excel formulas and dynamic arrays to create supporting analysis.
- Used lookup and conditional-counting logic to connect dashboard selections with the underlying data.
- Compared salaries across job titles, countries, and employment types.
- Designed the final output as an interactive dashboard rather than a static report.

## Project Structure

```text
data-science-salary-dashboard/
├── README.md
├── excel/
│   └── data-science-salary-dashboard.xlsx
├── images/
│   ├── dashboard.png
│   └── dashboard-full.png
└── documentation/
    └── project-documentation.md
```

## Project Demo

🎥 **Loom walkthrough:**  
[Watch the Project Demo](https://www.loom.com/share/f08c0cd74d6b4ea3bc650c63086ad085)

## Author

**Abdulrahman Muhammad**

Data Analytics | SQL | Power BI | Excel
