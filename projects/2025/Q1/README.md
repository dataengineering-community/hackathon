# Scalable Data Pipeline for U.S. University Information Aggregation

## Background

One of the biggest challenges for university aspirants in the United States is finding accurate, up-to-date, and relevant information about colleges and universities. With thousands of schools nationwide, students often struggle to compare institutions based on critical factors such as tuition costs, graduation rates, admission requirements, and available programs.

To address this problem, we aim to build a scalable data pipeline that automates the extraction, transformation, and storage of university-related information from the [USA College Scorecard API](https://collegescorecard.ed.gov/data/api-documentation/). The system will retrieve data for the [top 1000 schools in the U.S](https://ambitio.club/blog/top-1000-universities-in-usa/). based on ranking and store the data in a structured format suitable for analytics.

## Project Scope & Objectives

### Data Extraction
- Retrieve school-related data (name, location, type, ranking, etc.).
- Extract admission-related details (acceptance rate, SAT/ACT scores, etc.).
- Gather cost-related information (tuition fees, financial aid, etc.).
- Capture performance metrics (graduation rates, retention rates, etc.).

### Data Processing & Transformation
- Clean and standardize data for consistency.
- Handle missing or inconsistent data gracefully.
- Normalize and structure the dataset for efficient querying and analysis.

### Data Storage & Management
- Must be based on cloud (platform to be chosen at discretion).

### Scalability & Automation
- Deploy an ETL (Extract, Transform, Load) pipeline to run on a schedule.
- Ensure the system can handle increasing API request loads efficiently.

### Data Accessibility & Visualization
- Develop a well-documented warehouse schema which showcases your data modelling prowess. Ensure it is comprehensive for a data analyst who intends to use the warehouse.
- Develop dashboards (e.g., using Streamlit, Metabase, Tableau, Power BI, etc.) with visuals containing key metrics about schools and the admissibility criteria. Feel free to explore your creativity here. 

### Error Handling & Monitoring
- Implement logging and error handling for failed API requests or transformation issues.

### Optional Score Booster
- CI/CD Integration.
- Implement Infrastructure as Code where required.

## Expected Deliverables
- A fully functional data pipeline that can fetch, process, and store university data.
- An analytics dashboard.

## Grading Metrics
- Code best practices.
- Choice of tools.
- Documentation of architectural design and tool selection.
- Ease of running the submitted code.

## Submission
Share the GitHub repository containing the solution. The submission link will be provided before the Hackathon ends.
