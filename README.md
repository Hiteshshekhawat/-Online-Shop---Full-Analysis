# Online Shop Customer Sales Data

## Sales data collected by an online shop in 2021

About Dataset

Variable description:

Customer_id = unique customer id

Age = customer's age

Gender = 0: Male, 1: Female

Revenue_Total = total sales by customer

N_Purchases = number of purchases to date

Purchase_DATE = date latest purchase, dd.mm.yy

Purchase_VALUE = latest purchase in €

Pay_Method = 0: Digital Wallets, 1: Card, 2: PayPal, 3: Other

Time_Spent = time spent (in sec) on website

Browser = 0: Chrome, 1: Safari, 2: Edge, 3: Other

Newsletter = 0: not subscribed, 1: subscribed

Voucher = 0: not used, 1: used

#### Programming Language: python

#### Libraries used: numpy, pandas, matplotlib, seaborn

#### Notebook: google colab

#### Data source: kaggle dataset


## Objective

Clean & analyse raw data.

Gain usefull insights throrugh the data analysis process.

Visualize the Gained insights through python.
## Links:

Colab link : https://colab.research.google.com/drive/1kehStMEirrzIDNq8Q9db1WA8nHfKE93q?usp=sharing

Dataset : KAggle dataset - "Online Shop Customer Sales Data"

https://drive.google.com/file/d/10XO2Gdd0tvpypYRTC-a-iAmVgpdJgLGe/view?usp=sharing




## About dataset


Total number of rows and columns : 

(65796, 12)

    ### No null values.

    ### No duplicated values.

    ### Change the datatypes (to_datetime,astype)

    ### We just use z - score to exclude outliers from the dataset
##  Data exploration section.

Performed EDA and tried to answer these questions below:

      1. Total number of customer according to their Genders.

      2. Number of purchases to the date.

      3. Monthly count of sales.

      4. Mode of payment by customers in percentages.

      5. Different type of Browser use by customers while ordering product.

      6. Number and Percentage of customers who has subscribed or Not subscribed newspaper.

      7. Number and Percentages of customers who use vouchers while ordering.

      8. Comparison between Revenue Total and Purchase total.

      9. Total revenue with respect to Browser.

     10. Total Revenue with respect to Gender.

     11. Total revenue with repect to age of top 10 customers.

     12. Total Revenue with respect to mode of payment used by customers.

     13. Number of purchases according to Gender.

     14. Number of purchases made by customers according to months.

     15. Number of purchases made by customers in year 2021 -22.

     16. Maximum and Minimum aged customer with respect to Gender.
## Visualisation

Mainly performed using Matplotlib and Seaborn library and the following graph and plots had been used:

    Bar Plot.

    Count Plot.

    Pie Chart.

    Histplot.
    
## Summary 

The most important details in this text are that the maximum payment method is by card with 30%, while the minimum payment method is with cash or something. The maximum browser used by customers is Chrome 63.95%, followed by Safari 19.95%, edge 5.15%, and other browsers. The maximum number of customers who haven't subscribed to the newspaper is 84.91%, while 15.09% had subscribed. 74.98% of customers didn't use vouchers in their orders, while 25.02% used a voucher. Most of the booking is done in Chrome browser, followed by Safari, edge, and other browsers.

Most of the customers are female, with 67.05% followed by 32.95

