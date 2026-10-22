Dataset Name

Superstore Sales Dataset

Source

https://www.mathewkanalytics.com/datasets/superstore-sales/

Description

This dataset contains approximately 10,000 retail sales records covering the years 2014–2017.

It was used to analyze overall sales, profit, profit margins, monthly sales trends, category performance, regional performance, and sub-category profitability.

Fields Used

Order Date

Category

Sub-Category

Region

State

Segment

Sales

Profit

Quantity

Data Preparation

The CSV dataset was imported into Google Sheets and connected to Google Looker Studio.

Order dates were used to create a monthly date field for time-series analysis. A calculated profit-margin metric was created using:

SUM(Profit) / SUM(Sales)

Dataset Usage

The dataset is referenced from its original source rather than redistributed in this repository.
