Real Estate Data Analysis – Key Insights

This project analyzes real estate listings to uncover pricing trends, neighborhood insights, and factors affecting house prices. It combines data cleaning, descriptive statistics, interactive dashboards, and regression analysis for actionable insights.

📂 Dataset

The dataset includes:

Price of each property

Beds, Baths, Sq.Ft

Neighborhood information

All data has been cleaned: blanks, duplicates, and extra spaces removed, and all columns standardized for consistent analysis.

📊 Descriptive Statistics

Price Overview: Mean = $746,259 | Median = $619,000 | Mode = $749,900

Skewness: 5.28 → strong positive skew; most houses clustered at lower prices, luxury homes create a long tail

Kurtosis: 50.29 → extremely leptokurtic, sharp peak and heavy tails indicate multiple outliers

Price Range: $141,900 – $10,000,000 → large variation between cheapest and most expensive homes

🏘️ Neighborhood Insights

Pivot tables summarize average Beds, Baths, Sq.Ft, Price per Sq.Ft, and Average Price per neighborhood

Homes categorized into High / Medium / Low Price groups, most fall in the Medium category

Outliers: Foothills neighborhood shows extremely high prices, skewing averages

📈 Dashboard & Visualizations

Interactive slicers for filtering by price category

Bar plots: Top 10 neighborhoods per category

Pivot table summaries for quick insights

Histogram: Right-skewed price distribution (Non Normal)

Scatter plot: Positive relationship between Sq.Ft and Price, outliers detected

Pie chart: Medium-priced homes represent 58% of the market

📉 Regression Analysis

Dependent Variable: Price

Independent Variables: Beds, Baths, Sq.Ft

R² = 0.44, Adjusted R² = 0.442 → model explains ~44% of price variation

Significance: F = 882.12, p < 0.001
Overall model is significant

Predictor Insights:

Predictor	Coefficient	t-value	p-value	Insight
Sq.Ft	+$245 / sq.ft	24.62	<0.001	Strong positive effect
Bath	+$230k / bath	17.09	<0.001	Highly significant
Beds	-$26k / bed	-2.84	0.0046	Negative due to correlation with Sq.Ft and Bath

Predicted vs Actual: Most points align closely with the diagonal, outliers correspond to extremely expensive homes.

Navigation

Buttons added across all analysis tabs (except Raw Data) for easy navigation between Dashboard, Regression, Pivot Tables, and Charts.

Summary of results

House size and bathrooms strongly predict price, bedrooms alone are less impactful

Medium-priced homes dominate, while luxury outliers widen the price range

Top neighborhoods per price category are easily identifiable

Interactive dashboards and visualizations allow exploration of patterns, trends, and outliers

📚 References

Dataset sourced from Kaggle: https://www.kaggle.com/datasets/reenapinto/housing-price-and-real-estate-2023?resource=download

