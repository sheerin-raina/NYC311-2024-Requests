# NYC311-2024-Requests

NYC 311 Project Overview:
This project analyzes New York City 311 service requests from January to March 2024 (Q1) to uncover trends in citizen complaints, weather-related conflicts, and borough-specific needs. 

Project Structure:
The project is split into two Jupyter Notebooks:

01_data_ingestion.ipynb - This notebook focused on ensuring a clean and usable dataset in Excel before conducting the analysis.

Key Steps:
1. Data Formatting
    - Delete duplicate rows using a content similarity checker and fuzzy searching
    - Filtered out rows with missing values in essential fields

2. Data Grouping
    - Grouped cases by the same borough, complaint type, and day

3. Data Type Optimization
    - Converted dates to proper datetime format
    - Converted texts with frequent phrases to the category data type for memory optimization

4. Numeric Validation
    - Verified numeric fields and converted as necessary

02_eda.ipynb - This notebook used visual and statistical techniques to extract insights and patterns from the data.

Data Profiling Factors:
1. Incident Severity Ranking System
2. Submission Method Time Analysis
3. Winter Weather Impact 
4. Daily Request Patterns
5. Missing Data Profiling
6. Top Complaint Types
7. Request Volume Fluctuation
8. Requests Per Borough and Capita

