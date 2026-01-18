# Data Jobs Dashboard — Documentation
![Dashboard Page 1](/Project1_Page1.png)
## Introduction
- Provide a single, easy-to-use interface for exploring 2024 data science job market trends and compensation.
- Solve fragmentation of **job market information for Job Seekers, Job Transitioners, and Job Swappers**.

Key Features
- Interactive Power BI dashboard visualizing job postings by title, salary, and location.
- Trend analysis (time, location, and role-level).
- Compensation distributions and comparisons across geographies and roles.
- Filtering and drill-through for targeted exploration.

Dataset
- *Real-world dataset of 2024 data science job postings including: job title, salary (where available), location, posting date, and related metadata*.
- Preprocessing steps: cleaning of missing values, salary normalization, and location standardization.

Getting Started
- Open the Power BI Desktop file (.pbix) in Power BI Desktop (recommended latest stable version).
- If provided separately, place the dataset file(s) in the expected data directory or update data source connections in Power Query.
- Refresh data and verify credentials for any linked sources.

Usage Notes
- Salary fields may require normalization (annual vs. hourly, currency conversions) — see Power Query steps.
- Geographic visualizations rely on standardized location names; update mappings in the data model when needed.
- Privacy: remove or anonymize any personally identifiable information before sharing.

Extending & Contributing
- Add new visualizations in Power BI or extend data model with additional job attributes (seniority, remote/hybrid flags).
- For custom analyses, export underlying tables and use external tools (Python/R) as needed.

Credits & License
- Data sources should be cited in the project repository.
- Include an appropriate open-source license file in the repo (e.g., MIT) if sharing code or transformations.

Contact
- For questions about the dashboard structure or data transformations, consult the repository maintainer or the project README.
# Data Jobs Dashboard w/ Power Bi


## Skills Showcased

- **Data Transformation (ETL) with Power Query:**
Cleaned, shaped, and prepared the raw data for analysis by handling blanks, changing data types, and creating new columns.

- **Implicit Measures:** Formulated measures to derive key insights and KPIs like "Median Yearly Salary" and "Job Count".

- **Cpre Charts:** Utilized **Column, Bar, Line,** and **Areas Charts:** to compare job counts and track trends over time.
- **Geospatial Analysis:** Leveraged **Map Charts** to visualize the global distribution of jobs.
- **KPI Indicators & Tables:** Used **Cards** to display key metrics and **Tables** to provide granular, sortable data.
- **Dashboard Design:** Designed an intuitive and visually appealing layout, exploring both common and uncommon chart types to best tell the data story.
- **Interactive Reporting:**
- **Slicers:** To dynamically filter the report by Job Title.
- **Buttons & Bookmarks:** To create a seamless navigation experience.
- **Drill-Through:** To navigate from high-level summary to a contextual, detailed view.

## Dashboard Overview

### Page 1: High-Level Market View
![Dashboard Page 1](/Project1_Page2.png)
This is your mission control for the data job market. It showcases key KPIs like total job count, median salaries, and top job titles to give you a quick understanding of what's happening in the job market at a glance.

### Page 2: Job Title Drill Through
![Dashboard Page 1](/Project1_Page1.png)

This is the deep-dive page. From the main dashboard, you can drill through to this view to get specific details for a single job title, including salary ranges, work-from home stats, top hiring platforms, and a global map of job locations.

## Conclussion

This dashboard showcases how Power BI can transform raw job posting data into a powerful tool for career analysis. It allows user to slice, filter, and drill through data to make informed decisions about their career path.
