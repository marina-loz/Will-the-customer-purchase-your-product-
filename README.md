# 🛒 Will the customer purchase your product

## 📝 Objective
This project aims to analyze customer purchasing behavior for an online shopping website, focusing on the busiest months of November and December. The goal is to identify purchase rates for returning and new customers and predict potential sales in a new marketing campaign.

## ❓ Key Questions
- What are the purchase rates for returning and new customers?
- What factors influence purchasing behavior?
- What is the probability of achieving 100 or more sales in a future campaign?

## 📊 Data
- **online_shopping_session_data.csv**: Contains session data with columns like customer type, duration on pages, bounce rates, exit rates, and purchase indicators.

## 🧠 Approach
1. **Purchase Rate Calculation**: Calculated purchase rates for returning and new customers.
2. **Correlation Analysis**: Assessed correlations between different session durations (administrative, informational, product-related).
3. **Probability Estimation**: Estimated the likelihood of achieving a minimum of 100 sales in a marketing campaign based on binomial distribution.

## 📈 Results
- **Returning Customer Purchase Rate**: 19.56%.
- **New Customer Purchase Rate**: 27.34%.
- **Top Correlation**: Between administrative and product-related page duration (0.39).
- **Probability of 100+ Sales**: 90.12% in a new campaign with a 15% increased purchase rate for returning customers.

## 🚀 Conclusion
This analysis helps the marketing team gauge the success of future campaigns by understanding customer behavior and estimating sales probabilities.

## 🛠️ Tools & Libraries
- **pandas**: Data manipulation
- **matplotlib**: Data visualization
- **scipy**: Statistical analysis
