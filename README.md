# SQL-data_warehouse-project-AP
Project description
This repository contains my implementation of a Data Warehouse project using Microsoft SQL server. 
The project is based on the educative content from "Data with Baraa" which help us to put into practice concepts related to storage, integration, cleaning and data transformation.
This repository represents my implementation of the project as part of my learning and development process about my skills on data analysis.
Through the construction of stored data we are looking to integrate information from different source systems (CRM & ERP), transform it in structured information and prepare it to a future analyse. 

Project objectives
1. Comprehend the fundaments and structure of a Data Warehouse.
2. Integrate information from different data sources.
3. Apply ETL processes via SQL server.
4. Make cleaning processes, transformation and data standarization.
5. Build an organized data structure which expedite query and analysis.

Data Architecture
The project uses the architecture "Medallion" which organizes the processing of data in 3 layers:
1. Bronze Layer: Where the original data is saved and comes from the source systems, keeping the original structure.
2. Silver Layer: Cleaning, Standarization and Transformation processes are made to make quality, consitency and reliability about data even better.
3. Gold Layer: Tha Data is organized and structured to ease the consultation, analysis and repository about reporting.

Tools and technologies
-Microsoft SQL server
-SQL server managment studio
-Git & Github
-Draw.io (Diagrams and data modeling)
-Notion (create, plan and arrange projects)

Data sources
The project uses information from 2 simultaneous source systems:
1. CRM (contains related information which customers, products and sales transactions)
2. ERP (provides complementary information related to customers, locations and products category)

Repository structure
The repository is organized in different folders to keep a clear structure and ease the consultation of the project files:
-Data sets (contains the files of original data)
-Docs (stores the documentation, diagrams and data modeling)
-Scripts (contains organized SQL scripts based on the different stages of processing)
-Test (Includes proof and validation of data quality)

Credits to:
Baraa Khatib Salkini (Data with Baraa) 
