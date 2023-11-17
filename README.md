# ACN-applicant-and-learner-analysis

## Introduction
Overview and Objective
This Jupyter Notebook aims to analyze the applicant data for the SAP Educate to Employ (E2E) programme, facilitated by the African Coding Network (ACN). The primary focus countries for this analysis are Nigeria, Kenya, and South Africa. The data has been gathered through recruitment campaigns conducted by Yoma in partnership with UNICEF country offices, leveraging platforms like uReport and existing local partnerships.

## Target Audience
The intended audience for this notebook includes stakeholders from ACN, SAP, Yoma, and UNICEF, as well as any other parties interested in understanding the demographics and characteristics of the applicants.

## Key Questions
What is the gender distribution among the applicants?
What is the age range of the applicants?
What are the nationalities of the applicants?
How are applicants distributed across focus countries?

## Data Preparation
Data Import: Utilizes pandas for data manipulation and google.colab for file I/O. Data Cleaning: Employs Python's standard libraries along with pandas to clean and prepare the data. Special attention is paid to standardizing unique entries, especially in geographical information.

## Data Analysis
Demographic Analysis: Explores key demographic features like gender, age, and nationality using pandas' aggregation methods. Geographical Analysis: Utilizes fuzzywuzzy for string matching to standardize metropolitan area names. The geographical data is then further refined using geopy for geocoding.

## Visualization
Matplotlib: Used extensively for generating bar and pie charts for a detailed breakdown of demographic and geographical attributes. Folium: Employed to create heat maps for geographical distribution visualization.

## Optimization & Efficiency
Python-Levenshtein: Installed to speed up the fuzzy string matching computations. Caching: Implemented for geocoding operations to minimize API calls and enhance efficiency.
