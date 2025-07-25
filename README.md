# **"Optimizing Sales & Inventory through Data-Driven Insights"**
Analysis across sales trends, product-level performance, customer behavior, geographic performance, pricing, and return issues.

---

## **1. Sales Trends Analysis**

### Insights:

* **Sales Volume Over Time**: There’s a visible monthly revenue trend with clear peaks during **November–December**, indicating **seasonal demand spikes**, likely due to holiday shopping.
* **Top Products**:

  * *REGENCY CAKESTAND 3 TIER* generated the highest revenue.
  * Other key drivers: **WHITE HANGING HEART T-LIGHT HOLDER**, **JUMBO BAG RED RETROSPOT**, and **PARTY BUNTING**.

### Business Suggestion:

* Prepare **pre-holiday inventory stocking strategies** and **run marketing campaigns** in Q4 to capitalize on the natural uptick.

---

## **2. Customer Behavior Insights**

### Insights:

* **Top Customer (ID: 14646)** alone contributed **\~£279K**, with over 2,000 transactions.
* **Repeat Purchase Rate** is high at **69.97%**, which shows strong customer loyalty.
* **Average Order Value (AOV)** varies significantly. Some customers make frequent small purchases; others make infrequent but high-value orders.
* **RFM Segmentation** reveals a wide range of customer behaviors:

  * *High Recency, High Frequency, High Monetary* = Best customers
  * *Low Recency, Low Frequency* = At-risk or churned customers

### Business Suggestion:

* Run **loyalty programs and personalized email marketing** for high-value repeat customers.
* Use **RFM analysis** to design **customer re-engagement campaigns** for churn-risk segments.

---

## **3. Product-Level Insights**

### Insights:

* Products like *PAPER CRAFT, LITTLE BIRDIE* and *CERAMIC STORAGE JAR* had high return rates.
* Market Basket Analysis identified frequently co-purchased items:

  * *HAND WARMERS (different designs)* and *WHITE HEART T-LIGHT HOLDER* often bought together.

### Business Suggestion:

* Investigate **quality issues or expectation mismatches** on high-return items.
* Use **cross-sell bundling strategies** on frequently co-purchased items during checkout.

---

## **4. Geographic Analysis**

### Insights:

* **UK** leads in revenue (£6.76M), followed by **Netherlands, Ireland, Germany, France**.
* Interestingly, **International orders have higher average revenue per order** than domestic (UK):

  * International: **£34.08** vs UK: **£18.70**

### Business Suggestion:

* Scale **logistics and customer service infrastructure** to support international orders.
* Localize marketing for **top 5 international markets** based on sales growth.

---

## **5. Pricing and Promotions**

### Insights:

* **Negative correlation** between **unit price and quantity sold**: `Spearman = -0.571 (p < 0.001)`, supporting the hypothesis that higher prices lead to fewer purchases.
* Certain price points (e.g., £2.55, £3.39) consistently perform well.
* **Promotions** (based on unit price revenue trends) spike sales but need strategic targeting.

### Business Suggestion:

* Consider **psychological pricing strategies** (e.g., price-ending in .99 or .49) for high-velocity items.
* Use **price sensitivity testing** for new product launches.

---

## **6. Returns and Quality Analysis**

### Insights:

* Products like **REGENCY CAKESTAND 3 TIER**, **Manuals**, and **POSTAGE** have high negative quantities, indicating a return issue.
* **Returns correlate to specific SKUs** suggesting quality/fit/design issues—not random customer behavior.

### Business Suggestion:

* Initiate **product quality audits** for top-return items.
* Add **customer feedback forms** at return time to gather actionable improvement insights.

---

## **7. Statistical Testing Highlights**

| Hypothesis                                     | Outcome                        |
| ---------------------------------------------- | ------------------------------ |
| H1: Higher unit prices reduce quantity sold    |   Supported                    |
| H2: Frequent buyers have higher lifetime value |   Supported (Spearman = 0.794) |
| H3: Specific items cause high return rate      |   Supported                    |
| H4: Holiday months see sales spikes            |   Confirmed via monthly trend  |
| H5: International buyers spend more per order  |   Confirmed (£34 vs £18 avg)   |

---

## **Final Actionable Insight with Business Suggestion**

>  **Actionable Insight**:
> A **small segment of high-frequency international customers** generates disproportionately **higher revenue per transaction**. Their purchase patterns are different and more bundled (as per market basket rules).

>  **Business Suggestion**:
> Launch an **“International Premium Club”** targeting high-LTV overseas customers. Offer:
>
> * **Personalized bundles**
> * **Free/discounted international shipping**
> * **Early access to new collections**
> * **Dedicated support**
>
> This will **retain high-value buyers**, **increase average order value**, and **reduce churn** from your best segments.
