## 🍘🍜🍣 Campaign Strategy of Online Store 🍣🍜🍘 

- Toko A offers a wide range of products, including fashion, electronics, home living, and more. Every twin date, the company runs a special campaign featuring a major flash sale promotion and free shipping for all transactions.
- The core of the campaign is the Flash Sale, a time-bound promotion where high-demand products are offered at steep discounts (often up to 90%). These are scheduled in "waves" (e.g., 12 AM, 12 PM, and 8 PM) to create a sense of urgency and encourage repeat visits throughout the day.
- Free shipping is the primary "conversion engine." By removing the friction of delivery costs for all transactions, Toko A lowers the barrier to entry for price-sensitive customers, often requiring a "Minimum Spend" of $0 during specific peak hours to drive massive volume.
- To keep users on the app or site longer, the campaign includes Gamification. This involves simple in-app games (e.g., "Tap & Win" or "Daily Check-in") where users earn coins, points, or exclusive vouchers that can be redeemed during the Twin Date event.
- Toko A likely employs Loss Leaders—specific popular items (like iPhones or branded sneakers) sold at or below cost price. While the company may lose money on these specific units, they serve as "hooks" to draw millions of users into the ecosystem who then purchase other, more profitable items on category shop.
- Toko A can utilize 24-hour Live Stream Marathons leading up to and during the twin date. Influencers or shop hosts showcase products in real-time, offering "Live-Only" coupons. This adds a layer of social proof and entertainment (shoppertainment), keeping users engaged during the "lull" periods between flash sale waves.
- Tiered Early Access: Provide high-tier loyalty members with early access to flash sales to reward retention and manage server traffic store.
- Post-Event Retention Loops: Issuing "Bounce-back Vouchers" during the event that are only valid for the following week, ensuring that the spike in traffic translates into long-term shopping habits rather than a one-time visit.
- Real-Time Scarcity & Social Proof: Using live stock trackers (e.g., "90% Sold Out") and "Recent Purchase" pop-ups to create intense FOMO (Fear Of Missing Out), pushing undecided users to complete their checkout immediately.

## 🍘🍜🍣 Problem Goals 🍣🍜🍘 
The goal is to determine which strategy delivered the best results while optimizing the campaign budget, ensuring maximum return on investment.

"Which campaign strategy (A, B, or C) provides the highest revenue and transactions while optimizing costs for the next month?"


## 🍘🍜🍣 Objective 🍣🍜🍘 
To identify the campaign strategy (A, B, or C) that maximizes revenue and transaction volume while minimizing costs, in order to optimize the campaign performance for the upcoming month.


## 🍘🍜🍣 Business Metrics 🍣🍜🍘 
Here is the business metrics below :
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


## 🍘🍜🍣 Campaign Performance Comparison 🍣🍜🍘

TRANSACTIONS AND PRODUCTS SOLD CONSISTENTLY INCREASED
- increased from October to December, despite a slight drop in customers in December.

<img width="114" height="182" alt="image" src="https://github.com/user-attachments/assets/b82b8229-8d50-4903-9d9a-9e91d94bb6e6" />


REVENUE FOLLOWED THE CAMPAIGN BUDGET TREND 
- rising with higher budget and slightly decreasing as the budget dropped.
  
<img width="107" height="189" alt="image" src="https://github.com/user-attachments/assets/06f56743-21db-4ae2-a938-6c895d995403" />


AGGRESSIVE DISCOUNTING EFFECTIVELY BOOSTED SALES 
- showing efficient use of budget even with fewer customers.

<img width="167" height="148" alt="image" src="https://github.com/user-attachments/assets/ee762951-93ea-454e-9a5a-6213a188b078" />



## 🍘🍜🍣 Total Revenue Discount Ratio 🍣🍜🍘
- Solid start with a revenue discount ratio of 53,833, but lower than the other campaigns.
- Slight improvement at 54,924, still trailing behind the 12/12 campaign.
- Highest revenue discount ratio at 58,541, showing the most successful discount strategy.


<img width="340" height="625" alt="image" src="https://github.com/user-attachments/assets/e84fb7a6-4277-4b7a-881d-21a2352dcb83" />


## 🍘🍜🍣  Best Selling Product with Lowest Campaign Budget 🍣🍜🍘
Men’s Fashion is the best-selling product across all campaigns, with the highest revenue recorded and it has a smaller discount compared to other categories.

<img width="416" height="122" alt="image" src="https://github.com/user-attachments/assets/695e59a8-d6d1-469d-a557-86864bc47e8e" />


## 🍘🍜🍣  Highest Ratio Revenue  🍣🍜🍘
Men’s Fashion consistently delivers the best ROI across all campaigns, it’s the most efficient category in terms of profit for every discount spent.

<img width="272" height="272" alt="image" src="https://github.com/user-attachments/assets/be5703f1-87d1-48e5-9699-f50f28f62c7b" />


## 🍘🍜🍣  Hypothesis Testing 🍣🍜🍘
The P-value analysis shows that campaign have significant differences in total revenue. This highlights that campaigns closer to the end of the year (11/11 and 12/12) tend to perform better.

<img width="522" height="133" alt="image" src="https://github.com/user-attachments/assets/a9dbac29-ceac-48b7-9d5d-179d2fbf21c2" />


## 🍘🍜🍣  Overall Insight and Recommendation 🍣🍜🍘
Here is the overall insight and recommendation below :

<img width="517" height="110" alt="image" src="https://github.com/user-attachments/assets/a0371ce2-6191-488e-b778-1a6b25f532ef" />

<img width="355" height="110" alt="image" src="https://github.com/user-attachments/assets/601b07fb-39e6-417b-8395-8dda870b1b5a" />



## 🍘🍜🍣 License 🍣🍜🍘
- Copyright by Diantya Pitaloka
