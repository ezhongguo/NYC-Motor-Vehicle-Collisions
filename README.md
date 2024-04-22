## SQL Data Processing for NYC Vehicle Collisions Analysis
**Description:**
This project focuses on analyzing New York City Motor Vehicle Collisions (MVC) data from 2016 to 2022. We aim to provide actionable insights to stakeholders like car insurance companies, NYPD Traffic Enforcement, and the New York Department of Motor Vehicles (DMV) by exploring trends, patterns, and contributing factors related to MVCs.

**Code:** [LINK](https://github.com/ezhongguo/NYC-Motor-Vehicle-Collisions/blob/main/NYC%20Motor%20Vehicle%20Collisions.ipynb)

**Skills:**
* **Shell Commands:** Used for data acquisition by downloading datasets, file management through renaming and basic navigation, and initial data preprocessing.
* **SQL in AWS:** SQL for data manipulation, querying, and analysis including creating tables and schemas, importing data, querying datasets, and joining tables for complex analyses. Utilized within AWS for setting up and managing the database environment, executing SQL queries, and storing results.


**Roles:**
Responsible for Data Cleaning and Exploration, Star-schema Design and Implementation and SQL Table Creation and Query Writing for Analysis.

**Team Size:** 7

**Project Workflow:**
* Data Acquisition
  * Download the dataset using the wget command.
  * ename and preprocess the dataset.
* Data Wrangling & Cleaning 
  * Create a fact table named "Crashes" and import all data.
  * Select and clean columns to streamline the dataset.
  * Handle null values in crucial columns.
  * Design a star schema with a fact table and four dimensional tables: Geography, Contributing factor, Vehicle type, and Crash time.
* Data Exploration & Analysis
  ** Analysis 1 (Car Insurance)
    *** Identify top 10 vehicle types with the most crashes.
    *** Determine boroughs with the highest number of crashes.
  ** Analysis 2 (NYPD Traffic Enforcement)
    *** Find top 10 zip code areas with the highest number of persons injured.
    *** Analyze combinations of day, hour, and zip code with top 30 highest injured counts.
  ** Analysis 3 (NY DMV)
    *** Determine top 10 contributing factors to the highest number of fatalities.
* SQL Implementation
  ** Create SQL tables based on the star schema design.  
  ** Write SQL queries to link and query the fact and dimensional tables for analysis.
