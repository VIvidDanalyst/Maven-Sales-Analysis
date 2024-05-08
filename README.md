## Project Overview
In this project i tends to use advanced analytics techniques to gain valuable insights into the performance of sales in maven tech.
## Data Source 
Data was gotten from @Maven Sales Challenge | Maven Analytics
### DATA E.T.L
The dataset used for this project consist of four csv files 
1. Products - about products
2. Sales Team - about sales teams
3. Account - about clients or company
4. Sales Pipeline - fact table it consist of all transactions 
### Transformation & Load
The data used are mostly clean and needed no stringent transformation 
1. Null Values : Didn't drop null values because it will affect data quality
2. Data Types : Ensured the appropriate data type is used in all the columns 
3. Data Modelling : Ensured that the modelling enables Interactiveness of the report by using star schema modelling.
4. Duplicates : No Duplicates

### KPI's Created 
1. Total Revenue : Sum of close value
2. Total Deals : Total count of opportunity Id
3. Average conversion Duration : created a calculated column by subtracting the engage date from the close date using this syntax '=Duration.from([Close_date]-[Engage_date])'
4. Won : Total deals won
5. Loss : Total deals lost
6. Win Rate : Divided total deals won by total deals 
### Deal Analysis
1. Deals by quarter
2. Deals by deal stage
3. Top 5 agents by total deals 
4. Deals By Location 
5. Deals by Region
### Revenue Analysis 
1. QoQ by revenue
2. Revenue generated by Products
3. Revenue by Region
4. Revenue performance of teams using decomposition tree
## Findings 
There are total of 8800 deals of which 4238 deals where won making 48% of the total deals. The total deals won is slightly below 50% meaning there is need for improvement in the future, hence there should be policies made to ensure improvement in revenue generated and revenue can only be generated if deals are won. I recommend that Location like USA with high number of deals should be targeted to prevent deal loss and ensure deal winning which will in turn generate revenue.

![sales](https://github.com/VIvidDanalyst/Maven-Sales-Analysis/blob/main/Screenshot%202024-05-08%20135050.png)

![


