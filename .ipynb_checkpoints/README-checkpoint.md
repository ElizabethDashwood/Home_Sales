# Home_Sales

## Module 22 Homework Home_Sales_Challenge
### Description:
This is the Module 22 Homework Home_Sales_Challenge for Big Data techniques such as PySpark with SQL, temporary views of tables, parquet and caching.

### Getting started:
This challenge has 1 project called: Home_Sales containing a starter_code ipynb files called Home_Sales_colab.ipynb. Input data is sourced from the curriculum file "home_sales_revised.csv" located at the following link: "https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.2/22-big-data/home_sales_revised.csv"

### Installations required:
These projects have been run in a Windows 11 GitBash environment, together with Google Colab to write and execute code, and Jupyter Lab as the text editor for the README file.

### Executing Homework Challenge Requirements:
Please see Home_Sales_colab.ipynb for the script which perform all code requirements of the project.
I have added a link and also a PDF version of the final code, in the event that the link is not working as expected. 

### Results: 
As can be seen from the times shown for running of the query relating to home_sales by views where the average price of the hours was $350,000 or more, the method used to run the query affects the time needed to run and output the results. 

Running with a temporary view of the data table took 1.27 seconds.
Running with a cached version of the temporary view took only 0.97 seconds.
Running with a parquet formatted view partitioned on the date_built took 1.9 seconds. 

Such differences can greatly impact the resources needed to process data, when dealing with extremely large datasets.