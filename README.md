# Steven Gerardini - Data Analyst Portfolio

## About
This repository showcases various projects I've worked on, highlighting my skills in data collection(including web scraping), data wrangling, data exploration, statistical analysis, and data visualization. Each project is completed using a combination of Python, SQL, Excel, and PowerBi.


## Table of Contents
- [Portfolio Projects](#portfolio-projects)
  
  - Python
      - [GPU Performance Analysis](#gpu-performance-analysis)
      - [Steam Sales Analysis](#steam-sales-analysis)
   
  - IBM Data Analyst Capstone Projects
      - [Collecting Data Using APIs](#collecting-data-using-apis-and-webscraping)
      - [Survey Data Exploration](#survey-dataset-exploration)
   
        
- [Data Sources](Data_Sources.md) 


## Portfolio Projects



### GPU Performance Analysis 


**Description:** This project analyzes and compares the performance of over 20 different GPUs across several video games.
Using benchmark data collected from multiple sources, we explore how different GPUs perform in terms of **frame rate** and **1% lows** 
at different resolutions (1080p, 1440p, and 4K), and different graphic settings including **Upscaling**, **Raytracing** and **Frame Generation**.

**Excel:** [Spreadsheet](https://github.com/StevenGerardini/Data-Analyst-Portfolio/blob/a72868a69e6843f4b45a62a90b8978a3c49f7b67/GPU%20Benchmarks%202024%20Games.xlsx)

**Code:** [Investigating the Impact of Hardware and Settings on Gaming Performance](https://nbviewer.org/github/StevenGerardini/Data-Analyst-Portfolio/blob/main/GPU%20Performance%20Analysis.ipynb)

**Data Source**: The dataset used for this project was manually curated using an Excel spreadsheet, combining benchmark data from three reputable sources:       
- **TechSpot**: Provides comprehensive GPU reviews and benchmark data across various games and settings. For detailed performance metrics, visit [TechSpot PC Gaming Benchmarks](https://www.techspot.com/features/gaming-benchmarks/).
  
- **Hardware Unboxed**: Offers detailed performance analysis and comparisons of GPUs, including frame rates and performance metrics at different resolutions. Access their reviews and benchmarks on Youtube at [Hardware Unboxed](https://www.youtube.com/@Hardwareunboxed/featured).

- **Tom's Hardware**: Presents detailed rankings of both current and previous-generation graphic cards by performance. Find their comprehensive performance charts at [Tom's Hardware](https://www.tomshardware.com/reviews/gpu-hierarchy,4388.html).
  
- **PCPartPicker**: Used to gather pricing data for each GPU model, ensuring accurate cost-per-performance analysis. Visit [PCPartPicker](https://pcpartpicker.com/products/video-card/) for up-to-date pricing information on GPUs and other PC components.


---------------------------------------------
### Steam Sales Analysis

**Description:** 

**Code:**

**Data Sources:**




---------------------------------------------
# IBM Data Analyst Capstone Projects

## Collecting Data Using APIs and WebScraping
  - **Description:** In order to keep pace with changing technologies and remain competitive, an organization regularly analyzes data to help identify future skill requirements. As a Data Analyst, I will be assisting with this initiative and have been tasked with collecting data from various sources and identifying trends for this year's report on emerging skills. My first task was to collect the top programming skills that are most in demand from various sources including:
      - Job postings
      - Surveys
        
    Once this is completed, I will make that data ready for analysis using data wrangling techniques. 
 
      
  - **Code**: 
    - [Collecting Jobs Data Using GitHub Jobs API](https://nbviewer.org/github/StevenGerardini/Data-Analyst-Portfolio/blob/main/Collecting%20Job%20Data%20Using%20APIs.ipynb)
    - [Web Scraping Surveys](Web_Scraping_IBM.ipynb)
    - [Data Wrangling](Data_Wrangling_IBM.ipynb)


## Survey Dataset Exploration

  - **Description:** Stack Overflow, a popular website for developers, conducted an online survey of software professionals across the world. The survey data was later open sourced by Stack Overflow. The actual data set has around 90,000 responses. I will explore, analyze, and visualize this dataset and present my analysis.

  - **Code**: [Exploratory_Data_Analysis_IBM](Exploratory_Data_Analysis_IBM.ipynb)

    
## Data Visualization and Dashboard


  - **Code:** [Data Visualization](Data_Visualization_IBM.ipynb)
  - **Dashboard:** [Dashboard](Kaggle_Survey_2023_Dashboard.pdf)
      - A. Current Technology Usage Tab
          - Top 10 Languages
          - Top 10 Databases
          - Platforms
          - Top 10 Web Frameworks
      - B. Future Technology Trends Tab
          - Top 10 Lnaguages Desired for the Next Year
          - Top 10 Databases Desired for the Next Year
          - Desired Platforms for the Next Year
          - Top 10 Web Frameworks Desired for the Next Year
      - C. Demographics Tab
          - Respondent Classified by Work Experience
          - Respondent Count for Countries
          - Respondent Count by Age
          - Respondent Count by Gender and Classified by Education Level







