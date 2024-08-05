# Quick Cart E-Commerce Sales DASHBOARD

### Dashboard Link : 

## Problem Statement

**Problem Statement for Quick Cart E-Commerce Sales Dashboard:**

Quick Cart aims to enhance its business performance and customer satisfaction by addressing seasonal profitability fluctuations, optimizing inventory management, diversifying payment method preferences, and tailoring regional marketing strategies. Despite strong sales in November and January, profitability declines significantly in May and July, indicating a need for strategic intervention. Additionally, while printers and clothes are top-selling categories, there is an opportunity to better manage inventory and target marketing efforts. The predominance of Cash on Delivery (COD) payments at 44% suggests potential for encouraging alternative payment methods. Regional disparities in sales performance, with Maharashtra leading followed by Madhya Pradesh, Uttar Pradesh, and Delhi, highlight the need for optimized marketing and distribution strategies. Insights into top customers like Harivansh, Madhav, and Madan Mohan can be leveraged to design personalized marketing campaigns to boost retention and sales. By addressing these challenges, Quick Cart aims to enhance customer experience, streamline operations, and drive overall profitability.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a 2 csv files i.e "Details" and "Orders".
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Add a new column AOV (Average Order Value): The total amount of products divided by quantity results. It indicates the average revenue per order.
- Step 5 : Stacked Column Chart was created which indicates profits made by the company through E-commerce Sales on the Basis of Month. 
- Step 6 : Stacked Bar Chart was made to show profit earned by sales of particular products .
- Step 7 : Two Donut Charts where made, The first one represented the classification of items sold category wise. The second one tell us about the payment method opted by the coustmers.   
- Step 8 : Stacked Bar Chart was made which represents the states which had highest number sales.

- Step 9 : Stacked Bar Chart was made based on coustmers which have maximum orders. 
- Step 10 : 4 Visiual Cards were which represents :- 

  a)Total Revenue

    b) Total profit

  c) Sum of AOV (Average Order Value )

  d) Sum of Quantity Ordered.

- Step 11 : 2 Slicers were added one in Tile style and another in Dropdown style which represent Data Quater wise and Statewise Respectively.

 
 - Step 18 : The report was then published to Power BI Service.
 
 
![Screenshot 2024-08-05 173150](https://github.com/user-attachments/assets/0db88fe7-3d2b-46dc-91dd-52ab53470e87)

# Snapshot of Dashboard (Power BI Service)
![Screenshot (51)](https://github.com/user-attachments/assets/dc9d7eda-7198-43a7-87ce-450025facddf)



 
 # Report Snapshot (Power BI DESKTOP)

 
![Dashboard_upload](![Screenshot 2024-08-05 160455](https://github.com/user-attachments/assets/2825c124-dd4f-4f9b-bd66-fd60d18e9d58))

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Most profitable month

   a)November -10253

   b)January -9684

   c)Februrary - 8465

   d)March - 7793


           thus, Most profitable month is November.
           
### [2] Least profitable Month

   a)May - -3730

   b) July - -2138

   c)December - -1604
   
   thus, Least profitable month is May.
    
  
  ### [3] Most Profitable Product sold
  
      a) Printers - 8606
      b) Bookcases - 6516
      c) Saree - 4057
      d)Accessories - 3353
      e) Tables - 3139

     thus, Most profitable Product is Printers.

 ### [4] Most sold Product Categories wise 
       a) Clothes - 63%
       b) Electronics - 21%
       c) Furmniture - 17%

                thus, Most Sold Product Category is Clothes. 

 ### [5] Most Preffered Mode of payment
       a) COD - 44%
       b) UPI - 21%
       c) Debit Card - 13%
       d) Credit Card - 12%

                    thus, Most Preffered Mode of payment is COD.  

### [6] State with Most amount of Sales
       a) Maharashtra - 102498
       b) Madhya Pradesh -87463
       c) Uttra Pradesh - 38362
       d) Delhi - 22957

                     thus, State with Most amount of Sales is Maharashtra.

### [7] Maximun order by a customer
        a) Harivansh - 9902
        b) Madhav - 9365
        c) Madan Mohan- 7766
        d) Shiva- 6339

                        thus, Maximun order by a customer is by Harivansh.            
