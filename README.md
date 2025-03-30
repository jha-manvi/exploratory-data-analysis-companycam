# exploratory-data-analysis-companycam

# CompanyCam Data Analysis Project

## Overview
This project is a data analysis exercise for CompanyCam, a SaaS platform that helps contractors document and share photos of their work. The goal of this analysis is to assess user engagement, retention, and feature usage to provide actionable recommendations for improving product adoption and user retention.

## Dataset
The dataset consists of three tables:
1. **Users**: Contains user information (`user_id`, `signup_date`, `user_type`, etc.).
2. **Events**: Logs user activity (`event_id`, `user_id`, `event_type`, `event_timestamp`, etc.).
3. **Subscriptions**: Contains user subscription details (`user_id`, `plan_type`, `start_date`, `end_date`, etc.).

## Analysis
### Exploratory Data Analysis (EDA)
- Provided a summary of user engagement.
- Analyzed trends in user activity based on event types.
- Conducted retention analysis to understand user behavior over time.

### Experimentation & A/B Testing Proposal
- Proposed an experiment to improve user engagement through an enhanced onboarding experience.
- Defined key success metrics (retention rate, feature adoption, login frequency).
- Suggested an analysis framework using A/B testing and statistical significance testing.

### SQL Queries
- **Retention Rate Calculation**: Identified retention among users who signed up in the last three months.
- **Top Features Used**: Identified the top three most frequently used features based on event logs.

## Technologies Used
- **Python** (Pandas, Matplotlib) for data analysis and visualization.
- **SQL** for querying and analyzing structured data.
- **Jupyter Notebook** for conducting and presenting the analysis.

## Key Findings & Recommendations
1. Implement an Incentivized Referral Program.
2. Increase Engagement for Free Users to Boost Conversions.
3. Optimize Paid User Retention by Enhancing Subscription Benefits

## How to Run the Analysis
1. Clone the repository:
   ```bash
   git clone <repo-link>
   ```
2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn sqlite3
   ```
3. Run the Jupyter Notebook or Python script to execute the analysis.

## Author
Manvi Jha

---
For any queries, feel free to reach out!

