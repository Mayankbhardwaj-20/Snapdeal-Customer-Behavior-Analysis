# Snapdeal Customer Behavior Analysis
### Market Basket Analysis Using Machine Learning & Exploratory Data Analysis

## Project Overview
This project analyzes customer behavior on an e-commerce platform using **Exploratory Data Analysis (EDA)** and **Machine Learning techniques**. The objective is to understand how customers interact with the platform, identify behavioral patterns, and segment customers based on their shopping habits.

By analyzing purchasing behavior, satisfaction levels, product preferences, and cart abandonment factors, this project generates **actionable insights for improving marketing strategies, product recommendations, and customer retention**.

The analysis combines **rule-based customer segmentation** with **unsupervised machine learning (K-Means clustering)** to identify distinct customer groups.

---

## Business Problem

E-commerce platforms must understand customer behavior to remain competitive. This project addresses several key challenges:

- Identifying different customer segments
- Understanding purchase frequency and product preferences
- Analyzing cart abandonment reasons
- Improving recommendation systems
- Enhancing customer satisfaction and personalization

---

## Project Objectives

- Clean and prepare raw customer behavior data
- Perform exploratory data analysis (EDA)
- Analyze demographic distributions
- Implement rule-based customer segmentation
- Apply K-Means clustering for behavioral grouping
- Identify purchase patterns and product category preferences
- Analyze cart abandonment factors
- Study relationships between recommendations, reviews, and satisfaction
- Create visual dashboards and insights

---

## Dataset Features

| Feature | Description |
|------|------|
| Age | Customer age |
| Gender | Customer gender |
| Purchase_Frequency | High / Medium / Low purchase activity |
| Purchase_Categories | Product categories purchased |
| Cart_Abandonment_Factors | Reasons for incomplete purchases |
| Customer_Reviews_Importance | Importance of reviews in buying decision |
| Shopping_Satisfaction | Customer satisfaction score |
| Recommendation_Helpfulness | Whether recommendations were helpful |
| Rating_Accuracy | Perceived accuracy of product ratings |
| Product_Search_Method | How customers search products |

---

## Project Workflow

Data Cleaning → EDA → Segmentation → Clustering → Analysis → Visualization → Insights


---

## Technologies Used

### Programming Language
- Python

### Development Environment
- Jupyter Notebook

### Python Libraries
- pandas – Data manipulation
- numpy – Numerical computation
- matplotlib – Data visualization
- seaborn – Statistical visualization
- scikit-learn – Machine learning (K-Means clustering)

---

## Key Analysis Performed

### 1. Data Cleaning
- Removed duplicate rows
- Standardized column names
- Handled missing values
- Converted categorical values
- Converted rating columns to numeric format

---

### 2. Exploratory Data Analysis (EDA)

Analyzed:

- Age distribution
- Gender distribution
- Purchase frequency
- Product category popularity
- Product search behavior
- Shopping satisfaction scores
- Cart abandonment factors

Key findings include:

- Electronics and Fashion are the most purchased categories
- Medium purchase frequency dominates the customer base
- Recommendations strongly influence satisfaction

---

### 3. Rule-Based Customer Segmentation

Customers were grouped into three behavioral segments:

| Segment | Criteria |
|------|------|
| Frequent Buyer | High purchase frequency AND satisfaction ≥ 4 |
| Occasional Shopper | Medium purchase frequency |
| At-Risk Customer | Low purchase frequency OR satisfaction < 4 |

Insights from segmentation:

- Frequent buyers show high satisfaction and engagement
- At-risk customers show low interaction with recommendations
- Occasional shoppers represent high conversion potential

---

### 4. K-Means Clustering (Machine Learning)

Unsupervised machine learning was applied to discover natural customer segments.

Features used:

- Shopping_Satisfaction
- Customer_Reviews_Importance
- Recommendation_Helpfulness

Process:

1. Binary encoding of recommendation feature
2. Feature scaling using StandardScaler
3. K-Means clustering with 3 clusters

Outcome:

The algorithm identified distinct behavioral customer groups, enabling deeper insight beyond rule-based segmentation.

---

### 5. Correlation Analysis

A correlation heatmap was generated to study relationships between:

- Shopping Satisfaction
- Recommendation Helpfulness
- Rating Accuracy
- Review Importance

Key insight:

Recommendation systems and customer reviews significantly impact satisfaction levels.

---

## Visualizations Created

The project includes several visual analyses:

- Age Distribution Histogram
- Gender Distribution Bar Chart
- Purchase Frequency Count Plot
- Product Category Distribution
- Product Search Method Pie Chart
- Shopping Satisfaction Distribution
- Correlation Heatmap
- Customer Segment Distribution
- Age Distribution by Segment (Boxplots)
- K-Means Cluster Visualization

---

## Key Insights

- Electronics and Fashion dominate customer purchases
- Medium purchase frequency customers form the largest group
- Customer reviews strongly influence purchase decisions
- Helpful recommendations increase shopping satisfaction
- Three clear customer segments exist with distinct behaviors

---

## Business Applications

The insights from this project can help e-commerce platforms with:

### Targeted Marketing
Create marketing campaigns tailored to specific customer segments.

### Personalization
Improve product recommendation systems based on behavioral clusters.

### Customer Retention
Identify at-risk customers early and deploy retention strategies.

### Cart Abandonment Reduction
Address common abandonment reasons through UX and policy improvements.

---

## Limitations

- Cluster number was predefined (3) rather than optimized
- Additional feature engineering could improve clustering
- No clustering evaluation metrics (Silhouette Score, etc.)
- Dataset lacks time-based behavioral data

---

## Future Improvements

Future versions of this project could include:

- Elbow Method for optimal cluster selection
- Customer churn prediction using supervised learning
- Advanced recommendation systems
- Collaborative filtering models
- Time-series behavior analysis
- Deep learning based personalization

---


