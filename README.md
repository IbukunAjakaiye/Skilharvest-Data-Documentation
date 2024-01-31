# Skillharvest-Data-Documentation

## Project Overview
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

~~~~
GOOGLE SHEETS

QUERY(A:H,"SELECT C,H,F WHERE (C = 'Binder' OR C = 'Pencil') and F=2015",1)

~~~~
QUERY (A:H, "SELECT A,H,F WHERE(A='Central' or A='East') and F=2014",1)

~~~~
QUERY(A:H, "SELECT E,F,H WHERE(E ='Aug' or E='Sep') and F=2014",1)

~~~~
=QUERY(A:H, "SELECT A, B, C, F, H WHERE C LIKE 'Pen%'",1)

~~~~
=QUERY(A:H, "SELECT A, B, C, F, H WHERE C LIKE '%sk%'",1)

## Result/Findings
Various insights were gotten from the analysis:
  1. Sales of binders were more than pencils in 2015
  2. Central region had more sales than East region in 2014
  3. August had an increased sales than September in 2014
  4. Items with 'Pen' include Pencil, Pen, and Pen sets and the total sales is 8350.23
  5. Desk is the item that has 'sk' with 1700 in sales value

See here for to refer to the table
![https://docs.google.com/spreadsheets/d/1w172xjC1XJ_TAVcsP1IZAl7ZGx2ns73EHxxBTKo6jVE/edit#gid=39021757]
