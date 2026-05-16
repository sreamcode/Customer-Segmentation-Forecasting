Customer Segmentation & Sales Forecasting
Segmented 793 customers using K-Means clustering and 
forecasted 3-month sales trends using time-series modelling.

Tools Used
Python | Pandas | Scikit-learn | Matplotlib | Seaborn | Statsmodels

What I Did
- Grouped 793 customers into 4 segments based on buying behaviour
- Found 191 at-risk customers losing money due to high discounts
- Identified 58 VIP customers generating highest profit
- Forecasted next 3 months of sales using Exponential Smoothing

Key Results
| Segment | Customers | Avg Sales | Avg Profit |
|---------|-----------|-----------|------------|
| VIP | 58 | $9,379 | $2,235 |
| At-Risk | 191 | $1,591 | -$100 |
| Mid-Tier | 264 | $3,649 | $340 |
| Low Value | 280 | $1,736 | $308 |

Dataset
Superstore Sales Dataset — 9,994 rows | Source: Kaggle

How to Run
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
