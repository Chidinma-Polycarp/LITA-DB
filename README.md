# CHIDINMA POLYCARP - DATA ANALYST TRAINEE
Hello, my name is Chidinma and I am a data analyst trainee. I have a Bsc in Human Physiology and I am passionate about the health sector in Nigeria.

I want to see a change in the Nigerian health sector and nothing drives change like well presented and visualized facts drawn from a data set. I hope to become profiecient enough to bring about notable changes in our health sector and I can achieve this my combining my health background with the skill set I would get from data analysis.

This repository is geared towards tracking my learning journey and also sharing projects that I have worked on during this time.

### CONTENT
[PROJECT OVERVIEW](#project-overview)

[DATA SOURCES](#data-sources)

[TOOLS USED](tools-used)

[PORTFOLIO PROJECTS](#portfolio-projects)

[DATA ANALYSIS](#data-analysis)

[DATA VISUALIZATION](#data-visualization)

### PROJECT OVERVIEW
---
  I used different data sets gotten from the Incubator Hub and Kaggle to create different dashboards on excel and also imported the data to SQL where I ran some querries in other to fully understand the data. 
  
### DATA SOURCES
---
- Incubator Hub [Visit](https://theincubatorng.org/)
- Kaggle [Visit](https://www.kaggle.com/)
  

### TOOLS USED
---
- Microsoft Excel [Download Here](https://www.microsoft.com/en-us/microsoft-365/excel)
    1. For data cleaning
    2. Analysis
    3. Visualization
    
- SQL - Structured Querry Language for querrying data [Download Here](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
  
- GITHUB for portfolio building [Download Here](https://github.com)
  

### PORTFOLIO PROJECTS
---

#### ANALYZING A HEALTHCARE DATA SET SAMPLE
**Code:**[Healthcare Dataset arranged.csv](https://github.com/user-attachments/files/17266003/Healthcare.Dataset.arranged.csv)

**Goal:** To investigate the pattern of drug prescription by doctors.

**Description:** This project focused on analyzing a health data set gotten from kaggle. It is important to note that due to the sensitivity of Health sector data, this data set was generated using the Python's Faker library to generate a dataset that mirrors the structure and attributes commonly found in healthcare records. This can therefore be used for only learning purposes.

Data cleanin, transformation and visualization  was done by utilizing excel, after which the data set was imported to the SQL Server where it was further querried and manipulated.

**Skills:** Data cleaning, Data analysis, Data manipulation, Data Visualization, DQL, 

**Technology:** Microsoft Excel and SQL Server

### DATA ANALYSIS
---
I showed a snippet of some of the codes I used in querrying the dataset in SQL and some excel functions used.

```SQL
select * from [dbo].[Healthcare Dataset]

select COUNT(Name) as [total number of patients] from [dbo].[Healthcare Dataset]

select COUNT(Name) from [dbo].[Healthcare Dataset]
where Medical_Condition = 'Asthma'

select count(name) as [Diseases Prevalence], Medical_Condition from [dbo].[Healthcare Dataset]
group by Medical_Condition

select count(name) as [Blood group Prevalence], Blood_type from [dbo].[Healthcare Dataset]
group by blood_type

select * from [dbo].[Healthcare Dataset]
```
### DATA VISUALIZATION
---
This shows a brief summary of the dashboard created from the dataset gotten from Incubator Hub.
<img width="658" alt="dashboard" src="https://github.com/user-attachments/assets/b79b60ce-13d8-475a-b5d6-fe1643fa624e">

This dashboard shows the trends in the health sector
<img width="925" alt="healthcare dashboard" src="https://github.com/user-attachments/assets/eb15ec94-6f1b-4551-8e9d-462eaf327af9">



