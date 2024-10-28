# Retail Industry Data Cleaning

<p align="center">
<img src="https://imgur.com/7guRyZQ.jpg" style="height: 75%; width:75%;"/></center></p>


In this proyect I used various cleaning data tools in a [**Jupyter Notebook**](https://github.com/Renawol/Retail-Industy-Cleaning/blob/main/retail_project.ipynb) with Python. 
The data was taken of [this Kaggle dataset](https://www.kaggle.com/datasets/dgluesen/sales-and-workload-data-from-retail-industry)

## Used Libraries

- pandas
- numpy
- matplotlib
- seaborn
- scikit learn
- scipy

## Data context

This is a very plausible raw data of an international retail industry. We will be working with two different DataFrames called **'sales'** and **'openings'**.

**sales** information is grouped by month, store and department of the retailer and it specifies the turnover, units sold and hours opened of each one between October 2016 and June 2017. 
Furthermore, extra information such as the sales area or the opening hours scheme is provided.
In the other hand, **openings** contains the total opening hours of all the stores.

Our goal will be to **export** one or more **datasets** resulting from the **merging of the previous two**, where the **information is clean and organized**.

## Table of contents:
- Importing and reading files
- Format correction
- Hours
- Sales and turnover
- Area
- Openings cleaning
- Filling zeros

## Achievements
After data cleaning we exported the following files:
- retail_cleaned.csv: Information about the sales, turnover and hours per month, store and department
- month_id.csv: Numerical ID associated with each date
- depts.csv: Numerical ID associated with each department
- workers' hours: Total number of own and external employees.

Now we could use this data for an analysis, answering questions such as:
- How have the industry's profits evolved over time?
- Which department generates the most profit?
- Is there any difference between the months when external personnel is hired and those when it is not? 

