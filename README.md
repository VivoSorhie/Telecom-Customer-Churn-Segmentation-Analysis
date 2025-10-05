# Project: Finding and Fixing Customer Churn

> **The Bottom Line:** This project builds a system that accurately predicts which customers are about to leave, allowing the business to proactively save them.

---

### The Goal
To spot unhappy customers *before* they cancel their service by finding hidden patterns in telecom data.

---

### Our Approach
Our strategy involved two key steps:
1.  **Customer Segmentation:** We first answered "WHO are our customers?" by using machine learning to sort them into distinct personas.
2.  **Churn Prediction:** We then answered "WHO is going to leave?" by building an "early-warning system" to flag high-risk customers.

---

### Key Findings: The Warning Signs of Churn
Our analysis found three clear red flags:
- **Frustration is the #1 Driver:** A customer making **4 or more service calls** has a **50.7% chance of churning**. This is the critical tipping point.
- **The International Plan is a Problem:** Customers with this plan churn at a rate of **42.2%**, nearly 3x the company average.
- **Voice Mail is a Sign of Loyalty:** Customers with a Voice Mail plan are the most loyal, with a very low churn rate of only **7.4%**.

---

### The Result: A High-Performance Prediction Model
We built a **Random Forest model** that acts as a highly accurate early-warning system.
- **Effectiveness:** It finds **75%** of all customers who are going to churn.
- **Efficiency:** Its predictions are **95%** accurate.

#### The Business Value
The model's biggest strength is its efficiency. It allows for a targeted retention strategy:
> **By contacting just the top 20% of customers flagged by our model, we can reach and save 80% of ALL customers who were going to leave.**

---

### Recommendations
1.  **Deploy the Model:** Generate a daily list of at-risk customers for the retention team.
2.  **Create a "Code Red" Alert:** Immediately escalate any customer making their 4th service call to a senior agent.
3.  **Fix the International Plan:** Launch an urgent review of this product's pricing, quality, and value.
4.  **Reward Loyal Customers:** Nurture the Voice Mail user base and attract more customers like them.

---

### Tech Stack
- **Language:** Python
- **Libraries:** Pandas, Scikit-learn, Seaborn, Matplotlib
