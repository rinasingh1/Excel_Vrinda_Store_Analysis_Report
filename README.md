# Excel_Vrinda_Store_Sales_Report
## Project Objective : 
Vrinda store wants to create an annual sales report for 2022. So that, Vrinda can understand their customers and grow more sales in 2023.

## Dataset used
<a href = "https://github.com/rinasingh1/Excel_Vrinda_Store_Analysis_Report/blob/main/Dataset.xlsx">Vrinda Store Dataset</a>

## Question <br>
•	Which month got the highest sales and order ?
<br>
•	Who purchased more, men or women in 2022 ?
<br>
•	What are the different order statuses in 2022 ? 
<br>
•	List top 5 states contributing to the sales?
<br>
•	Relation between age and gender based on number of orders
<br>
•	Which channel is contributing to the maximum sales?
<br>
•	Dashboard Interaction <a href = "https://github.com/rinasingh1/Excel_Vrinda_Store_Analysis_Report/blob/main/Dashboard_Image.png">View Dashboard</a>

## Process
the data is cleaned and processed
<br>
•	Replace function is used - in gender column where 'W' is replaced with 'Women' and 'M' is replaced with 'Men'
<br>
•	IF Condition is used to keep the age in a bucket - column name is Age Group formula =IF(E2>60,"Senior",IF(E1>20,"Adult",IF(E2<=20,"Teenager")))
<br>
•	TEXT function is used - in month column to extract month only the formula =TEXT(H2,"mmm")
<br>
•	PIVOT TABLE and PIVOT CHARTS have been used for analysis and visualization

## Dashboard
![image alt](https://github.com/rinasingh1/Excel_Vrinda_Store_Analysis_Report/blob/3521c5e02f22d81f7c2756ce9eafbb1ec8e1e814/Dashboard_Image.png)

## Project Insight <br>
•	March month got the highest sales and orders
<br>
•	Women are more likely to buy compared to men (~65%)
<br>
•	More than 90% of the products delivered
<br>
•	Maharashtra,Karnatka,and Uttar Pradesh, Telangana and Tamilnadu are the top 5 states (~52%)
<br>
•	Adult age group (30-49 years) is maximum contributor (~50%)
<br>
•	Amazon, Flipkart and Myntra channels are maximum contributors (~80%)

## Conclusion 
to improve Vrinda store sales 
    
    • Target Women customers of age group (30-49 years) living in Maharashtra, Karnatka, Uttar Pradesh, Telangana and Tamilnadu 
      by showing ads/offers/coupons/available on Amazon, Myntra and Flipkart.











  

   
  


