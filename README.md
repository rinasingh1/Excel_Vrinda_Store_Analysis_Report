# Excel_Vrinda_Store_Analysis_Report
## Objective : 
Vrinda store wants to create an annual sales report for 2022. So that, Vrinda can understand their customers and grow more sales in 2023.

# steps which have taken to complete the project:

1) data cleaning & processing :

   Replace funtion is used- in gender column 'W' is replaced with 'Women' and 'M' is replaced with 'Men'
   TEXT function is used - in month column to extract month only the formula =TEXT(H2,"mmm")
   IF Condition is used to keep the age in a bucket - column name is Age Group formula =IF(E2>60,"Senior",IF(E1>20,"Adult",IF(E2<=20,"Teenager")))


   2) Pivot Table : To analyse this objective Excel's PIVOT TABLE is used 
      Pivot Charts : For visualization pivot charts are used. 
 
      Using these charts the followings questions visualized:

          1. Compare the sales and order using single chart- Combo Chart is used 

          2. who purchased more men or women in 2022? - Pie Chart is used, and the analysis is "Women are more likely to buy compared to men (~65%)"

          3. what are different order statuses in 2022? - Pie Chart is used, the analysis is "Delivered status is about 92% compared to other order statuses; those are returned (                      (2%),refunded (3%) and cancelled (3%).

          4. List the top 5 states contributing to sales - Bar Chart is used, the analysis is " Maharashtra, Karnatka, Uttar Pradesh, Telangana and Tamilnadu are the top 5 states,                     contributing     (~52%) to the sales 
         
          5.Purchasing status according to Age & Gender - Column Chart is used, the analysis is "The adult age group (30-49 yrs) is the max contributor. (~50%)"
         
          6. which channel contributing to the maximum sale ? - Pie Chart is used, the analysis "Amazon, Myntra and Flipkart channels are the max contributors (~80%)

## Conclusion :  
to improve Vrinda store sales

 • Target Women customers of age group (30-49 yrs) living in Maharashtra Karnatka and Uttar Pradesh, Telangana and Tamilnadu by showing ads/offers/coupons/available on Amazon, Myntra and Flipkart.





