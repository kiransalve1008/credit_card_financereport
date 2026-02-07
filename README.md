**CREDIT CARD 
WEEKLY STATUS REPORT**

**Import data to SQL Database **

1.Prepapre csv file
2.Create tables in SQL
3.Import csv file into SQL
4. DAX queries:
i.	AgeGroup = SWITCH( TRUE(), 'ccdb cust_detail'[Customer_Age] < 30,"20-30", 'ccdb cust_detail'[Customer_Age] >= 30 && 'ccdb cust_detail'[Customer_Age] < 40,"30-40", 'ccdb cust_detail'[Customer_Age] >= 40 && 'ccdb cust_detail'[Customer_Age] < 50,"40-50", 'ccdb cust_detail'[Customer_Age] >= 50 && 'ccdb cust_detail'[Customer_Age] < 60,"50-60", 'ccdb cust_detail'[Customer_Age] >= 60,"60+", "unknown" )

ii.	IncomeGroup = SWITCH( TRUE(), 'ccdb cust_detail'[Income] < 35000,"Low", 'ccdb cust_detail'[Income] >=35000 && 'ccdb cust_detail'[Income] <70000,"Med", 'ccdb cust_detail'[Income] >= 70000, "High", "unknown" )



**Project Insights – Week 52 (24th Dec)**

WoW change:
•	Revenue decreased by 12.8%
•	Total Transaction Amt & Count increased by 1.62% & 1.62%
•	Customer count increased by 7.2%
Overview YTD:
•	Overall revenue is 55M
•	Total interest is 8M
•	Total transaction amount is 45M
•	Male customers are contributing more in revenue 30M, female 25M
•	Blue & Silver credit card are contributing to 91% of overall transactions
•	TX, NY & CA is contributing to 66%
•	Overall Activation rate is 57.5%
•	Overall Delinquent rate is 6.07%


**Credit card financial dashboard using Power BI:**

•	Developed an interactive dashboard using transaction and customer data from a SQL database, to provide real-time insights.
•	Streamlined data processing & analysis to monitor key performance metrics and trends.
•	Shared actionable insights with stakeholders based on dashboard findings to support decision-making processes.

