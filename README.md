Project: Finding and Fixing Customer Churn
Last Updated: October 2025

The Bottom Line: Can we predict which customers are about to leave and save them before it's too late? Yes. This project built a system that does exactly that.
The Problem: Happy Customers Stay, Unhappy Customers Leave
Every time a customer leaves for a competitor, the company loses money. The big question is: can we spot an unhappy customer before they decide to cancel their service?

This project dives into a telecom company's customer data to find the hidden patterns of customer churn.

Our Two-Step Approach
We tackled this problem with a simple, two-part strategy:

First, we answered "WHO are our customers?" We used machine learning to sort the entire customer base into distinct groups or "personas." This helps us understand the different types of customers we have.

Then, we answered "WHO is going to leave?" We built a predictive model that acts as an "early-warning system." It learns the warning signs from past data and then flags current customers who are at high risk of churning in the future.

What We Discovered: The Story in the Data
Our analysis uncovered a very clear story about why customers leave. It's not random; there are specific red flags.

The Biggest Warning Signs of Churn
Frustration is the #1 Driver: The single biggest predictor of a customer leaving is the number of times they call customer service. A customer who calls for help 4 or more times has a 50.7% chance of churning. This is a critical tipping point.

The International Plan is a Problem: Customers who sign up for the International Plan are a major flight risk. They leave at a rate of 42.2%, which is almost three times the company average. Something about this plan—its price, quality, or value—is not working.

Voice Mail is a Sign of Loyalty: On the flip side, customers with a Voice Mail plan are your most loyal. They have a very low churn rate of only 7.4%. These are your stable, happy customers.

The Result: A Highly Accurate Early-Warning System
We built and fine-tuned a Random Forest model that can predict churn with incredible accuracy.

How good is it? Imagine you have a list of all your customers who are going to churn next month. Our model can find 75% of them (high recall) and be 95% sure about its predictions (high precision).

The Real Business Value
The model's biggest strength is its efficiency. This chart proves it:

This Gains Chart shows that by using our model to create a "most wanted" list of at-risk customers, the company can be incredibly efficient:

By contacting just the top 20% of customers flagged by our model, we can reach and have a chance to save 80% of ALL customers who were going to leave.

This means the company can focus its retention efforts where they will have the biggest impact, saving time and money.

The Action Plan: What To Do Next
Based on these findings, the path forward is clear:

Deploy the Model: Start using the model today to generate a daily list of at-risk customers for the retention team to contact.

Create a "Code Red" Alert: Any customer making their 4th service call should be immediately flagged and escalated to a senior support agent to solve their problem.

Fix the International Plan: Launch an urgent review of this product. Find out why it's driving your customers away.

Reward Your Loyal Customers: Recognize that your Voice Mail users are your loyal base. Learn more about them and find ways to keep them happy.

Technologies Used
Python

Libraries: Pandas, Scikit-learn, Seaborn, Matplotlib
