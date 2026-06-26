# King Empire Wedding Rentals - Advanced SQL Analytics

## Student Information
* *Name:* Ruben A. King
* *Student ID:* 29761/2025
* *Institution:* University of Lay Adventists of Kigali (UNILAK)

---

## Business Scenario
King Empire Wedding Rentals provides high-end event gear (Luxury Tents, Chiavari Chairs, Sound Systems, and Stages) to clients across Kigali. To optimize inventory management and tracking, this system maps relationships across Customers, Inventory Items, and Rental transactions.

---

## Advanced Analytical Insights & Interpretations

### 1. Descriptive Analysis (What Happened?)
* *Insight from Simple CTE:* Our simple CTE revealed that a significant majority of our rental transactions exceeded 150,000 RWF, indicating that our primary revenue stream relies heavily on premium event packages rather than small individual item rentals.
* *Insight from Aggregate Window Functions:* The cumulative running total calculates exactly how our event cash flow grew over our booking timeline, scaling seamlessly up to our peak total revenue.

### 2. Diagnostic Analysis (Why Did It Happen?)
* *Insight from CTE Category Aggregation:* Combining the data showed that our 'Tents' and 'Chairs' inventory categories generated the highest overall revenue because events requiring marquee setups inherently order matching volumes of support items (like 100-500 chairs at once).

### 3. Prescriptive Analysis (What Should We Do Next?)
* *Insight from Window Tiers (NTILE):* By dividing orders into structural spending groups, management can isolate clients in 'Tier 1' (Highest Spenders) to enroll them in a VIP corporate loyalty track. 
* *Insight from Navigation Functions (LAG/LEAD):* Chronological variance tracking allows the booking desk to spot historical trends to predict periods of peak demand during the wedding season, ensuring inventory quantities are fully scaled before bottlenecks happen.
