## 🍘🍜🍣 Campaign Strategy of Online Store 🍣🍜🍘 

Toko A offers a wide range of products, including fashion, electronics, home living, and more. Every twin date, the company runs a special campaign featuring a major flash sale promotion and free shipping for all transactions.


## 🍘🍜🍣 Problem Goals 🍣🍜🍘 
The goal is to determine which strategy delivered the best results while optimizing the campaign budget, ensuring maximum return on investment.

"Which campaign strategy (A, B, or C) provides the highest revenue and transactions while optimizing costs for the next month?"


## 🍘🍜🍣 Objective 🍣🍜🍘 
To identify the campaign strategy (A, B, or C) that maximizes revenue and transaction volume while minimizing costs, in order to optimize the campaign performance for the upcoming month.


## 🍘🍜🍣 Business Metrics 🍣🍜🍘 
<img width="242" height="265" alt="image" src="https://github.com/user-attachments/assets/69102504-7144-40e5-ae7d-dfa08755e119" />


## 🍘🍜🍣 Data Cleansing 🍣🍜🍘 
After filtering, empty rows were removed and missing values in price, quantity, discount, and status were filled or deemed non-critical based on analysis.

We corrected unusual values in price, discount, and total revenue by converting them to IDR currency format, and standardized customer IDs to a six-digit format.

We identified and removed 5 duplicate rows.


## 🍘🍜🍣 Outliers 🍣🍜🍘
We will remove values in the total revenue column that fall outside the interquartile range (IQR), specifically those below 0 or above 14,107,250 million.
We identified 12 rows exceeding the upper bound, and these rows were subsequently removed.

<img width="194" height="144" alt="image" src="https://github.com/user-attachments/assets/e21e825b-eb1f-484e-a7b9-82f7ce5c59b8" />


## 🍘🍜🍣 Descriptive Statistics 🍣🍜🍘
1) The mean of Total Revenue (4,603,011) is much higher than the median (1,598,332) and mode (1,441,800), showing right skewness due to some very high revenue transactions.

<img width="221" height="272" alt="image" src="https://github.com/user-attachments/assets/486f16c1-a9e4-42eb-89f5-1d3936e419d9" />

2) The mean Quantity (1.28) exceeds the median and mode (both 1), indicating most transactions have low quantities with a few large outliers. 
<img width="199" height="272" alt="image" src="https://github.com/user-attachments/assets/224d0829-cefb-4bab-bbe5-78015487175a" />


3) For Discount, the mean (82,041) is above the median and mode (both 0), meaning most transactions have no discount, but some large discounts raise the average.
<img width="218" height="275" alt="image" src="https://github.com/user-attachments/assets/0ee2b5cd-860f-4471-95a4-7dbe49ce1878" />



## 🍘🍜🍣 License 🍣🍜🍘
- Copyright by Diantya Pitaloka
