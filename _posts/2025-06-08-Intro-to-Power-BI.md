---
title: "Introduction to Power BI"
date: 2025-06-08
categories: [data-science]
tags: [data, analytics, data-science, machine-learning, artificial-intelligence]
# description: Data science projects
---

# Hotel Booking Analytics Dashboard: Case of AtliQ Grands in India

## Problem Statement
AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality inductry for the pastrands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the manageing director of AtliQ wanted to incorporate "Business and Data Intelligence" to regain their market share  20 years. Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Gand revenue. However, they do not have an in-house data analytics team to provide them with these insights.
Their revenue management team had decided to hire a 3rd party service provider to provide them with insights from their historica data.

## Aim of the Project
You are a data analyst who has been provided with sample data and a mock-up dashboard to work on the following task. You can download all relevant documents from the download link below to:
1. Create the metrics according to the metric list.
2. Create dashboard according to the mock-up provided by stakeholders.
3. Create relevant insights that are provided in the metric list/mock-up dashboard.

[Link:] (https://codebasics.io/resources/end-to-end-data-analyst-project) 

## Tools and Techniques
**Visualization Tool**: Power BI Desktop

## Key Activities
1. **Load and Transform the various data sets** e.g. dim_date and dim_rooms  
2. **Build the Data Model**: use the star schema to build the underlying data model and the required relationships 
3. **Data Analysis Expressions**: Create new columns and measures using DAX expressions that will be useful in creating visualizations.
4. **Dashboard**: Create a compelling and interactive dashboard report from the analysis of the data set that would speak clearly to the business needs for decision making. 
5. **Publish and Share**: Share the final Power BI dashboard and ensure you capture it in your project portfolio website/blog

### Load and Transform the various data sets
The data sets consisted of five different data sets which were extracted, transformed, and loaded into Power BI Desktop. The datasets consisted of **two fact tables** and **three dimensional tables**. They include:
1. fact_aggregated_bookings
2. fact_bookings
3. dim_date
4. dim_hotels
5. dim_rooms

![Tables](../assets/images/Data.png)

### Build the Data Model
The relationship amongst the five tables were established as shown below:

![Data Model](../assets/images/Model.png)

### Data Analysis Expressions (DAX)
From the above five tables, **key_measures** table was generated using **DAX** Language. 

![Key Measures](../assets/images/Key_Measures.png)

### Dashboard
A **Dashboard** was designed to capture various outcomes obtained from the datasets as shown below:

![Home Page](../assets/images/Home.png)

![Summary Page](../assets/images/Summary.png)

![KPI](../assets/images/KPI.png)

![KPI Cont](../assets/images/KPI_Cont.png)
