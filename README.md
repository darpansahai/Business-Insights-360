# Business Insights 360
### Problem Statement
Atliq Hardware discuss its business model. It is a consumer goods electronics company having operations in various countries. Their business is growing rapidly and they still rely on excel files for data analytics. Excel files are hard to consume and not effective in generating insights. Also due to the lack of effective analytics the company faced a major loss in Latin America.
This project is done as a part of Codebasics Power BI 2.0 course in Data Analytics Bootcamp 2.0 , link to the course is [here](https://codebasics.io/bootcamps/data-analytics-bootcamp-with-practical-job-assistance). 

### Tech Stack
 •	MYSQL
 
 •	Power BI.
 
 •	DAX Studio (For report optimization).
 
 •	Excel
 
 •	DAX Language
 
 •	Project Charter File

### Power BI Techniques Learnt
 •	What all questions should be asked before starting the project?
 
 •	Transformations using Power Query.
 
 •	Creating Date table using M language.
 
 •	Grouping dimension tables and fact tables separately.
 
 •	Disabling load for the tables that are not needed in the data model.
 
 •	Creating Calculated Columns.
 
 •	DAX Language.

 •	How to set Report Refresh Date.
 
 •	Page Navigations using Buttons.
 
 •	Data Modelling using Star and Snowflake Schema.
 
 •	Applying Conditional Formatting using Background colour and icons.
 
 •	Implementing Bookmarks to switch between two visuals.
 
 •	How to create a separate page for Tooltip.
 
 •	Publishing report onto the Power BI Service.
 
 •	Setting up a personal gateway for auto refresh of data.
 
 •	Dynamic titles based on the applied filters.
 
 •	KPI Indicators.
 
 •	Different types of charts.

### Some DAX Functions () Used

Calculate () – It is used to modify the context of filters.

SUMX () – Performs sum calculation at each row of the table.

DIVIDE () – Used for calculating percentage.

SAMEPERIODLASTYEAR () – Used to perform calculations for same period of the last year.

SUM () – For calculating the total at aggregate level.

BLANK () – To return the blank value.

ISCROSSFILTERED () – Returns True when a specified column or table is cross filtered.

ISFILTERED () – Returns True when a specified column or table is filtered.

MAX () – Used for returning maximum value.

SWITCH () – Evaluates an expression for a list of values and returns one of multiple possible result expressions.

SELECTEDVALUE () – Used to return a value when the context for Column Name has been filtered down to one distinct value only. Otherwise returns an alternate result.

FORMAT () – Converts a value to text in the specified number format.

ISBLANK () - It helps user determine whether or not a cell or a field is empty or contains a blank value.

HASONEVALUE () - Returns TRUE when the context for column Name has been filtered down to one distinct value only. Otherwise is FALSE

### Business Related Terms

•	Net Sales.

•	Gross Margin.

•	Net Profit.

•	Forecast Accuracy.

•	Net Error.

•	Absolute Error.

•	YTD – Year to Date.

•	YTG – Year to Go.

•	COGS – Cost of Goods Sold.

•	LY – Last Year.

•	Fiscal Year.

•	Pre Invoice Deductions.

•	Post Invoice Deductions.

•	Benchmark (Target).

•	Direct.

•	Retailer.

•	Distributor.

### Data Catalog

Dimension Tables: It contains static information about customer, market and products.

Fact Table: It contains data about the transactions.

•	gdb 041:
    
     ○	dim_customer: It contains information about the customers.
     
     ○	dim_market:  It contains information about the market.
     
     ○	dim _product : It contains product information
     
     ○	fact_forecast_monthly:  It contains historical forecast, current forecast at monthly.
     
     ○	fact_sales_monthly: It Contains sales up to date at Monthly level.

  •	gdb 056:

    o	manufacturing_cost: Currency in USD, data at fiscal year level.
    
    o	freight cost: Freight' and 'other costs' is % of Net Sales.
    
    o	post invoice deductions: Currency in USD, data at monthly level.
    
    o	pre invoice deductions: Currency in USD, data at fiscal year level.
    
    o	Gross Price : Currency in USD, data at fiscal year level.

### Data Model

![image](https://github.com/darpansahai/Business-Insights-360/assets/123958866/dbbb0646-0a56-4766-9d3b-ab8b7bd78b89)

### Dashboard Designing

Based on the mock ups received as requirement, the team will start designing the visuals and create measure as and when required.

### Home Page

In Home Page, all the views button will be available. User will land on specific view page by clicking the button

 - Finance View
 - Sales View
 - Marketing View
 - Supply chain View
 - Executive View

### Home Page
![image](https://github.com/darpansahai/Business-Insights-360/assets/123958866/e702f29f-a521-48fa-b773-3f23ba7ae629)

### Finance View
![image](https://github.com/darpansahai/Business-Insights-360/assets/123958866/c9156bc5-72b6-4a8a-b5f5-d134a4958819)

### Sales View
![image](https://github.com/darpansahai/Business-Insights-360/assets/123958866/4cb318d3-76e6-4575-873d-8014c693e12c)

### Marketing View
![image](https://github.com/darpansahai/Business-Insights-360/assets/123958866/b565955c-d23e-49a4-8430-a4ad9a06eae0)

### Supply Chain View
![image](https://github.com/darpansahai/Business-Insights-360/assets/123958866/443ec308-07d1-4a73-8d5e-3ab746f0bd00)

### Executive View
![image](https://github.com/darpansahai/Business-Insights-360/assets/123958866/a4305a57-dcc5-4b94-9382-7549520b7c90)

