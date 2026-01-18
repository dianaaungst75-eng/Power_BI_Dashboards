# Data Jobs Dashboard — Documentation

Purpose
- Provide a single, easy-to-use interface for exploring 2024 data science job market trends and compensation.
- Solve fragmentation of job market information for Job Seekers, Job Transitioners, and Job Swappers.

Key Features
- Interactive Power BI dashboard visualizing job postings by title, salary, and location.
- Trend analysis (time, location, and role-level).
- Compensation distributions and comparisons across geographies and roles.
- Filtering and drill-through for targeted exploration.

Dataset
- Real-world dataset of 2024 data science job postings including: job title, salary (where available), location, posting date, and related metadata.
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