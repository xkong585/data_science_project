# Data Science & Machine Learning Portfolio

This repository is a portfolio of applied data science projects covering experimentation, forecasting, customer segmentation, recommender systems, and business analytics. Each project is built around a real-world business question and includes exploratory analysis, modeling, evaluation, and practical recommendations.

The work highlights my ability to turn messy business data into structured analysis, build statistical and machine learning models, and communicate insights for product, finance, marketing, and operations use cases.

## Portfolio Overview

| Project | Business Question | Methods & Tools | Deliverables |
| --- | --- | --- | --- |
| [A/B Testing](AB%20testing) | Should a product team move the first game gate from level 30 to level 40? | Hypothesis testing, bootstrap analysis, retention analysis, logistic regression | Experiment readout, retention impact, launch recommendation |
| [Cash Flow Forecasting](CashFlow_Forecasting) | How can a financial platform forecast daily purchase and redemption cash flows? | Time-series analysis, feature engineering, cyclic factors, LSTM, model comparison | Forecasting notebook, model methodology, feature analysis |
| [RFM Customer Segmentation](RFM_model) | How can customers be grouped for targeted marketing and lifecycle strategy? | RFM analysis, K-Means, DBSCAN, elbow method, silhouette score | Customer tiers, segment interpretation, marketing recommendations |
| [News Recommender System](Recommender_System) | How can a platform recommend personalized news articles from user click history? | Item-CF, User-CF, LightGBM, DIN, dual-tower recall, ranking metrics | Recommendation pipeline, recall/ranking methods, model notes |
| [Yelp Data Analysis](Yelp_Data_Analysis) | What can reviews, check-ins, and business metadata reveal about local business performance? | EDA, sentiment analysis, network/community analysis, visualization | Business/user insights, analysis framework, decision recommendations |

## Featured Projects

### 1. A/B Testing: Product Experiment Analysis

This project analyzes a Cookie Cats product experiment where the first in-game gate was moved from level 30 to level 40. The analysis focuses on player retention and game activity to determine whether the product change should be launched.

Key work:

- Defined experiment hypotheses and compared control vs. treatment behavior.
- Evaluated 1-day and 7-day retention using statistical testing and bootstrap methods.
- Interpreted product impact in business terms rather than only reporting p-values.
- Produced a recommendation on whether to ship, reject, or continue testing the change.

Project link: [AB testing](AB%20testing)

### 2. Cash Flow Forecasting: Financial Time-Series Modeling

This project forecasts daily purchase and redemption amounts for a financial product similar to Yu'e Bao. The goal is to help financial operations teams anticipate cash inflows and outflows, improve fund allocation, and reduce liquidity risk.

Key work:

- Conducted time-series exploratory analysis on historical transaction behavior.
- Engineered calendar, holiday, weekday, monthly cycle, distance-based, and behavior-based features.
- Compared baseline cyclic-factor forecasting with machine learning and deep learning approaches.
- Documented model assumptions, evaluation logic, and feature selection process.

Project link: [CashFlow_Forecasting](CashFlow_Forecasting)

### 3. RFM Customer Segmentation

This project segments customers using recency, frequency, and monetary value signals. It combines classic RFM scoring with clustering methods to identify customer groups that can support targeted marketing and retention strategy.

Key work:

- Built customer-level RFM features from transactional behavior.
- Applied K-Means clustering and selected cluster counts using elbow and silhouette analysis.
- Compared segmentation outputs against DBSCAN-based clustering.
- Interpreted segments such as best customers, loyal customers, and high-value customers.

Project link: [RFM_model](RFM_model)

### 4. News Recommender System

This project builds a personalized news recommendation framework using user click history and article metadata. It explores multiple recall and ranking methods used in modern recommender systems.

Key work:

- Analyzed large-scale user click logs and article interaction patterns.
- Implemented and documented collaborative filtering approaches, including Item-CF and User-CF.
- Explored ranking and deep recommendation methods such as LightGBM, DIN, YouTube DNN, and dual-tower recall.
- Evaluated recommendations using ranking-oriented metrics such as MRR.

Project link: [Recommender_System](Recommender_System)

### 5. Yelp Data Analysis

This project analyzes Yelp business, review, user, check-in, and tip data to understand customer behavior, business performance, sentiment trends, and local market competition.

Key work:

- Explored business distribution, category popularity, user behavior, and merchant performance.
- Applied sentiment analysis concepts to review data for customer experience insights.
- Discussed network and community detection opportunities for understanding relationships between users and businesses.
- Framed findings from platform, user, and merchant perspectives.

Project link: [Yelp_Data_Analysis](Yelp_Data_Analysis)

## Technical Skills Demonstrated

- Programming: Python, Jupyter Notebook, pandas, NumPy
- Statistics: hypothesis testing, bootstrap analysis, experiment evaluation
- Machine Learning: clustering, classification, ranking, recommendation models
- Time Series: trend analysis, cyclic factors, calendar features, forecasting
- Analytics: EDA, customer segmentation, business insight generation
- Communication: project documentation, model explanation, business recommendation framing

## Repository Structure

```text
data_science_project/
+-- AB testing/
|   +-- A_B_Testing.ipynb
|   +-- README.md
+-- CashFlow_Forecasting/
|   +-- Forecasting_of_fund_inflows_of_financial_products.ipynb
|   +-- readme.md
+-- RFM_model/
|   +-- RFM_customer.ipynb
|   +-- readme.md
+-- Recommender_System/
|   +-- RS_Data_Analysis.ipynb
|   +-- RS_Model.ipynb
|   +-- readme.md
+-- Yelp_Data_Analysis/
|   +-- yelp_data_analysis.ipynb
|   +-- readme.md
+-- README.md
```

## How to Review This Portfolio

For a quick review, start with the project table above and open the README for the project most relevant to your role. For technical depth, review the notebooks inside each project folder.

Recommended starting points:

- Data analyst / product analyst roles: [A/B Testing](AB%20testing), [Yelp Data Analysis](Yelp_Data_Analysis)
- Data scientist roles: [Cash Flow Forecasting](CashFlow_Forecasting), [RFM Customer Segmentation](RFM_model)
- Machine learning / recommendation roles: [News Recommender System](Recommender_System)

## Contact

If you would like to discuss any project in more detail, please reach out through my GitHub profile.
