# Skilharvest-Data-Documentation

**Documentation outline**
- [Project Overview](#project-overview).
- [Data Sources](#data-sources).
- [Tools Used](#tools-used).
- [Data cleaning and Preparation](#data-cleaning-and-preparation).
- [Data Analysis](#data-analysis).
- [Findings](#findings).
- [Images from findings](#images-from-findings).


## Project Overview
---
This project seeks to analyse stationary supplies with the aim of generating insights from the data for better decision making.

## Data Sources
The primary source of the Data used is a Microsoft Excel csv file, which was provided by the learning provider.

## Tools Used
- Ms Excel for Data Cleaning [Download here] (https://www.microsoft.com/en/microsoft-365/microsoft-office?rtc=1)

## Data cleaning and Preparation

This EDA involves exploring the Data to provide answers to these questions:
  - Sales of binder items and pencil in 2015.
  - Sales in Central and East region in 2014.
  - Sales in August and September 2014.
  - Sales of items that start with pen, including their region, sales rep and year.
  - Sales of items that end with ‘sk’, include their region, sales rep and year.

## Data Analysis
This includes some basic queries that was used for this analysis.

````
GOOGLE SHEETS

QUERY(A:H,"SELECT C,H,F WHERE (C = 'Binder' OR C = 'Pencil') and F=2015",1)

````
QUERY (A:H, "SELECT A,H,F WHERE(A='Central' or A='East') and F=2014",1)

````
QUERY(A:H, "SELECT E,F,H WHERE(E ='Aug' or E='Sep') and F=2014",1)

````
=QUERY(A:H, "SELECT A, B, C, F, H WHERE C LIKE 'Pen%'",1)

````
=QUERY(A:H, "SELECT A, B, C, F, H WHERE C LIKE '%sk%'",1)

````


## Findings
Various insights were gotten from the analysis:
  1. Sales of binders were more than pencils in 2015
  2. Central region had more sales than East region in 2014
  3. August had an increased sales than September in 2014
  4. Items with 'Pen' include Pencil, Pen, and Pen sets and the total sales is 8350.23
  5. Desk is the item that has 'sk' with 1700 in sales value

*See here to refer to the table*:

![https://docs.google.com/spreadsheets/d/1w172xjC1XJ_TAVcsP1IZAl7ZGx2ns73EHxxBTKo6jVE/edit#gid=39021757]

|Region|Sales Rep|Item||Order Date||Month||Year||GDS Order Date||Sales|
|---------|---------|---------||---------|---------|---------||---------|
|Data 1|Data 2|Data 3|

## Images from findings

![Screenshot (70)](https://github.com/IbukunAjakaiye/Skilharvest-Data-Documentation/assets/81586815/bc4bdcdf-626b-437e-801d-900197d06fe8)

![Screenshot (75)](https://github.com/IbukunAjakaiye/Skilharvest-Data-Documentation/assets/81586815/ef89871c-bc52-483f-aecb-f11552d48af4)

![Screenshot (69)](https://github.com/IbukunAjakaiye/Skilharvest-Data-Documentation/assets/81586815/c4595b0b-3cea-4402-9a44-d372e2726a62)

![Screenshot (72)](https://github.com/IbukunAjakaiye/Skilharvest-Data-Documentation/assets/81586815/7044e639-01a5-4207-b748-2ac3c8bb7a77)

![Screenshot (73)](https://github.com/IbukunAjakaiye/Skilharvest-Data-Documentation/assets/81586815/f2ce2f0d-87ae-4f6e-8074-eea7b942e8c9)









