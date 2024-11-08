Welcome to my Data analysis Portfolio! Here you'll find some of my data analysis project

# Sales Analysis Of a Retail Store

### Objective
----
To analyze the sales performance of a retail store by exploring the sales data to unconver insights to identify the top performing products, identify regional performance and to get insights of the performance of the store.

### Data sources
---
The primary source of this data is from my project topic.

### Tools Used
---
- Microsoft Excel[Download here](https:www.microsoft.com)
  1. Data entry and storage:
     The data was uploaded on excel and stored properly in files for analysis.
  2. Data analysis and filtering:
     The data contained duplicate data which were filtered to prevent inaccurate analysis. The data was analysed uncovering 
     insights that helped to identify the trends of sales of the 
     retail store. The analysis included top selling products, regional performance, total revenue etc.
  3. Data visualization:
     using charts and graphs, a visual representation of the data was uncovered for easy understanding of the analysis
   
- Structured Query Lamnguage[ Download here](http://www.microsoft.com)
  1. For quering Data
     
- Power Bi[ Download here]ttps://power-bi-desktop.en.softonic.com/download)
  1. For data visualization: For creating interactive dashboards and reports
  2. Data Analysis; Analyse data from variious sources
  3. Data Modelling: create data models using DAX
     
The following were carried out on Microsoft excel
### Data cleaning and processing
  ---
  During data cleaning and processing in excel the following steps were carried out;
  1. Data inspection: To identify missing duplictaes or erroneous data
  2. Duplicate  Removal: Identical records were eliminated
     ![image](https://github.com/user-attachments/assets/968e566c-145f-42ce-825c-f6af9f90be3a)

### Exploratory Data Analysis
  ---
  This involved exploring the retail store data to answer the following questions
  1. What is the total sales by month: The performance of the store monthly.
  2. Total sales by region: To see the amount of sales made in each region.
  3. Total sale by products: To see which product had the most sale.
   ![image](https://github.com/user-attachments/assets/34012f63-2afb-457f-83d0-2b87ec6c6759)

### Data Visualization
---
Using charts and graphs 
![image](https://github.com/user-attachments/assets/c709cab0-65e9-454b-b4ce-1b57f1982fbf)

### Data Analysis
---
On structured query Language. This were we included some lines of codes
- Total sales for each product
```SQL
select PRODUCT, SUM(sales) as TOTAL_SALES 
from [dbo].[LIta CAPSTONE, SALES DATA]
group by product;
```
- Number of sales in each region
```SQL
select Region , count(sales) as SALES_TRANSACTION
from[dbo].[LIta CAPSTONE, SALES DATA]
group by Region
```
other codes







  
