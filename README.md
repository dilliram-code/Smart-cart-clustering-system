# Customer Segmentation Using K-Means Clustering

## Project Overview

This project performs **customer segmentation using K-Means clustering** to identify distinct groups of customers based on their purchasing behavior, income, demographics, and engagement with marketing campaigns.

The objective is to help the **product, marketing, and software teams** better understand customer behavior and design **personalized recommendation systems and targeted marketing strategies**.

---

# Dataset Features Used

The clustering model uses several behavioral and demographic features:

| Feature | Description |
|------|------|
| Income | Customer yearly income |
| Recency | Days since last purchase |
| NumDealsPurchases | Purchases made using deals |
| NumWebPurchases | Purchases made through website |
| NumCatalogPurchases | Purchases through catalog |
| NumStorePurchases | Purchases made in physical stores |
| NumWebVisitsMonth | Monthly website visits |
| Complain | Whether customer complained |
| Response | Whether customer responded to campaign |
| Age | Customer age |
| Customer_tenure_days | Duration as a customer |
| Total_Spending | Total amount spent |
| total_children | Number of children |
| Education levels | Education category |
| Living status | Living with partner or alone |

---

# Clustering Method

Customer segmentation was performed using **K-Means clustering**.

The algorithm grouped customers into **4 clusters** based on similarities in their behavior and demographic characteristics.

Each cluster represents a **distinct customer segment**.

---

# Customer Segments Identified

## Cluster 0 — Budget Family Shoppers

### Characteristics

- Income ≈ **39,680**
- Average spending ≈ **222**
- Moderate store purchases
- High website visits
- Living with partner
- Higher number of children
- Low campaign response rate

### Interpretation

These customers:

- Have lower income
- Are price sensitive
- Frequently browse products online
- Spend moderately
- Likely purchase when discounts are available

### Recommendations

Software and marketing teams should:

- Recommend **discounted products**
- Show **bundle offers**
- Provide **price alerts**
- Display **family-oriented promotions**

Example recommendation features:

- "Best Deals for You"
- "Family Value Bundles"
- Discount notifications

---

## Cluster 1 — Premium High-Spending Customers

### Characteristics

- Income ≈ **72,808**
- Total spending ≈ **1236**
- High catalog and store purchases
- Lower web browsing
- Few children
- Moderate campaign response

### Interpretation

These customers:

- Have strong purchasing power
- Spend frequently
- Already know what they want
- Prefer catalog and store purchasing

They represent **premium customers**.

### Recommendations

The software system should provide:

- **Premium product recommendations**
- **VIP loyalty programs**
- **Exclusive offers**
- **Early access to sales**

Example features:

- VIP membership
- Premium product suggestions
- Loyalty rewards system

---

## Cluster 2 — Low Engagement Browsers

### Characteristics

- Income ≈ **36,960**
- Total spending ≈ **165** (lowest)
- High website visits
- Low purchase activity
- Living mostly alone
- Moderate campaign response

### Interpretation

These customers:

- Browse frequently but rarely buy
- Are price conscious
- May be exploring products without commitment

They are **window shoppers**.

### Recommendations

Software team should focus on **conversion strategies**:

- Recommend **low-cost products**
- Show **best budget deals**
- Use **cart reminders**
- Provide **limited-time offers**

Example features:

- "Products Under $20"
- Budget deals section
- Abandoned cart notifications

---

## Cluster 3 — High Value Loyal Customers

### Characteristics

- Income ≈ **70,722**
- Total spending ≈ **1190**
- Highest web purchases
- High catalog and store purchases
- Highest marketing response rate
- Living alone
- Long customer tenure

### Interpretation

These customers are:

- High income
- High spenders
- Highly responsive to campaigns
- Active online buyers

They represent the **most valuable customer segment**.

### Recommendations

Software teams should prioritize retaining these customers by implementing:

- Personalized recommendation engines
- Upselling strategies
- Smart marketing campaigns

Example features:

- "Recommended for You"
- "Customers Also Bought"
- Personalized email promotions

---

# Strategic Business Insights

Key observations from clustering:

1. **Clusters 1 and 3 generate the majority of revenue.**
2. **Clusters 0 and 2 are price-sensitive customers.**
3. **Cluster 3 shows the highest marketing campaign responsiveness.**
4. **Cluster 2 has high browsing but low purchasing behavior.**

---

# Recommended Product Features

The software team should consider implementing:

### 1. Cluster-Based Recommendation System

Use clustering results to deliver personalized recommendations.

Example pipeline:

---

### 2. Personalized Marketing Campaigns

Different campaigns should be designed for each customer segment.

| Cluster | Marketing Strategy |
|------|------|
| Cluster 0 | Discounts and bundle offers |
| Cluster 1 | Premium product promotions |
| Cluster 2 | Budget deals and conversion incentives |
| Cluster 3 | Loyalty rewards and personalized offers |

---

### 3. Intelligent Recommendation Algorithms

Future improvements can include:

- Collaborative filtering
- Content-based recommendations
- Hybrid recommendation systems

---

# Conclusion

Customer segmentation using K-Means clustering provides valuable insights into customer behavior.

By integrating clustering results into the recommendation system, companies can:

- Improve customer engagement
- Increase conversion rates
- Deliver personalized shopping experiences
- Maximize revenue from high-value customers

This segmentation enables the company to move toward a **data-driven personalized marketing strategy**.
