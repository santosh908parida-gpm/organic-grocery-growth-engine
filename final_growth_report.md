
# Organic Grocery Growth Engine

## 1. Project Objective

This project analyzes organic product adoption using online grocery order data.  
The goal is to understand how users move from trying organic products to becoming high-value organic buyers, and to design growth experiments that increase organic basket share and repeat organic purchasing.

---

## 2. Dataset Overview

The project uses grocery order data containing:

- Users
- Orders
- Products
- Aisles
- Departments
- Reorder behavior

The raw data was transformed into a user-level growth analytics dataset by tagging organic products and creating user-level metrics such as organic item share, organic order frequency, and organic segment.

---

## 3. Methodology

The project followed this workflow:

1. Loaded raw grocery order and product data
2. Merged products with aisle and department information
3. Combined prior and train order-product data
4. Created a master transaction table
5. Tagged organic products using product names
6. Built user-level organic behavior metrics
7. Created an AARRR-style funnel
8. Segmented users by organic behavior
9. Analyzed product and department opportunities
10. Designed ICE-prioritized growth experiments

---

## 4. AARRR Funnel Findings

The stricter organic adoption funnel was defined as:

| Stage | Definition |
|---|---|
| Acquisition | User has at least 1 grocery order |
| Activation | User bought 2+ organic items |
| Retention | User bought organic in 3+ orders |
| Loyalty | Organic items are 15%+ of basket |
| High-value | 25%+ organic share, 5+ organic orders, 10+ total orders |

### Funnel Results

| Stage | Users | Overall Conversion |
|---|---:|---:|
| Active grocery users | 206,209 | 100.00% |
| Bought 2+ organic items | 181,031 | 87.79% |
| Bought organic in 3+ orders | 166,470 | 80.73% |
| 15%+ organic basket share | 136,075 | 65.99% |
| High-value organic users | 61,585 | 29.87% |

### Key Funnel Insight

The largest leakage occurs before the high-value stage.  
The biggest drop-off is at:

**High-value: 25%+ organic share, 5+ organic orders, 10+ total orders**

This stage loses **74,490 users**, with a drop-off rate of **54.74%**.

This indicates that the primary growth challenge is not first-time organic trial.  
Many users are already buying organic products. The real opportunity is converting loyal organic buyers into high-value organic buyers.

---

## 5. User Segmentation Findings

Users were segmented based on:

- Organic item count
- Organic order count
- Organic basket share
- High-value qualification

The most important growth opportunity is:

**Organic loyal but not high-value users**

This segment contains users who already show meaningful organic buying behavior but have not yet reached high-value organic status.


### Main Opportunity Segment

| Metric | Value |
|---|---:|
| Users | 70,664 |
| User Share | 34.27% |
| Avg Total Orders | 9.43 |
| Avg Organic Items | 27.76 |
| Avg Organic Item Share | 35.22% |

This segment is attractive because these users are already warm.  
They have organic buying behavior, but need basket expansion, category cross-sell, and stronger habit formation to become high-value users.


---

## 6. Product and Category Insights

Product/category analysis focused on the loyal-but-not-high-value segment.

### Key Findings

Top organic products by volume include:

**Bag of Organic Bananas, Organic Baby Spinach, Organic Strawberries, Organic Avocado, Organic Hass Avocado**

High-reorder organic products include:

**Organic Fat-Free Milk, Vitamin D Organic Milk, Organic Low Fat Milk, Organic 2% Reduced Fat Milk, Large Grade AA Organic Eggs**

Top cross-sell opportunity departments include:

**beverages, household, personal care, alcohol, pets**

The analysis shows that organic behavior is concentrated in trusted categories such as produce and dairy/eggs.  
However, growth opportunities exist in adjacent categories where users already buy products but organic penetration is lower.

---

## 7. Growth Strategy

The strategy should shift from:

> Make users try organic

to:

> Make organic a larger part of the user's grocery basket

The recommended strategy is to use trusted organic categories as anchors and expand users into adjacent organic categories.

### Strategic Pillars

1. **Organic Basket Expansion**  
   Recommend organic alternatives in low-penetration categories.

2. **Category Cross-Sell**  
   Move users from organic produce/dairy into organic pantry, snacks, frozen, beverages, and bakery.

3. **Replenishment Nudges**  
   Use high-reorder organic products for reminder and subscription campaigns.

4. **High-Value Upgrade Campaign**  
   Target loyal users close to 25% organic basket share with incentives and bundles.

---

## 8. Growth Experiment Roadmap

The experiments were prioritized using ICE scoring:

ICE = Impact × Confidence × Ease

| Experiment | Target Segment | Primary Metric | ICE Score |
|---|---|---|---:|
| Organic Replenishment Reminder | Users buying high-reorder organic products | Organic reorder rate | 512 |
| Organic Basket Expansion Recommendations | Organic loyal but not high-value users | Organic item share | 504 |
| Organic Alternative Swap Campaign | Organic low-share repeat users | Organic penetration by department | 343 |
| Complete Your Organic Basket Bundle | Organic loyal but not high-value users | Organic items per order | 336 |
| High-Value Organic Upgrade Offer | Organic loyal but not high-value users | Conversion to high-value organic user | 270 |
| Organic Membership / Subscription Pilot | Organic high-value users | Organic order frequency / retention | 144 |


---

## 9. Final Recommendation

The core opportunity is to convert loyal organic buyers into high-value organic buyers.

The first experiment should be:

**Organic Basket Expansion Recommendations**

This experiment targets loyal-but-not-high-value users with personalized organic alternatives in categories they already buy.  
The goal is to increase organic item share from the 15–24% range to 25%+, thereby moving users into the high-value organic segment.

---

## 10. Portfolio Summary

This project demonstrates:

- Product analytics thinking
- AARRR funnel design
- User segmentation
- Behavioral metric engineering
- Organic product adoption analysis
- Growth experiment design
- Business recommendation development

The project converts raw transaction data into a clear Growth PM strategy.

