Project Overview:
This project involves performing Exploratory Data Analysis (EDA) on Play Store app reviews and related datasets to uncover key factors influencing app engagement and success. The analysis focuses on understanding trends, identifying outliers, and deriving actionable insights to improve app performance.

Problem Statement:
The goal is to analyze two datasets:

Play Store Data: 
Contains app details like reviews, ratings, installs, and more.

User Reviews: 
Contains user feedback, sentiment, and sentiment scores.

##Key objectives:

Identify parameters influencing app engagement.

Highlight trends in ratings, installs, and reviews.

Determine factors contributing to app success.

Steps Followed
1. Data Cleaning
Removed duplicate rows based on the App column.

Imputed missing values in columns like Rating and Type using median and mode.

Standardized units for the Size column (all values in MB).

Converted price values to numeric by removing $.

Added calculated columns:
Revenue: Estimated as Installs * Price.

Size_group: Categorized apps into size intervals.

Sentiment Numeric: Mapped sentiments (Positive, Negative, Neutral) to numeric values.

2. Data Visualization
Correlation Heatmap: Analyzed relationships between variables.
Positive correlation between Reviews and Installs.

Slight negative correlation between Price and Installs.

Category Distribution:

Most apps fall under "Family" and "Game" categories.

"Games" and "Tools" are the most competitive.

Content Rating Analysis:
82% of apps are suitable for all age groups (rated "Everyone").

4% are rated "Mature 17+".

Size Group Analysis:
Most apps are in the 1-20 MB range.

Larger apps (>90 MB) tend to have higher popularity (reviews and installs).

3. Insights and Findings
Free apps dominate the Play Store (92%).

Categories like "Games" and "Communication" have the highest installs.

Paid apps generate revenue based on both price and install numbers.

Sentiment analysis reveals 64% positive, 22% negative, and 14% neutral reviews.

Apps with larger sizes (>90 MB) receive higher average reviews.

Tools and Libraries

Python: Primary language for analysis.

Pandas: Data manipulation and cleaning.

NumPy: Numerical computations.

Matplotlib: Data visualization.

Seaborn: Advanced statistical plotting.

How the Project Was Achieved

Data Understanding: Examined datasets for key attributes like Rating, Installs, Reviews, and more.
Preprocessing: Cleaned and standardized data to ensure accuracy and relevance.
Visualization: Used charts and graphs to identify patterns and derive insights.
Analysis: Performed in-depth EDA to understand app performance and user sentiment.
Documentation: Recorded findings and visualizations to communicate results effectively.
Key Visualizations
Correlation heatmaps.

Bar charts for category-wise installs and reviews.

Sentiment distribution pie charts.

Size group distribution histograms.

Conclusion
Through EDA, several actionable insights were derived to aid app developers:

Focus on categories like "Games" and "Tools" for higher visibility.

Optimize app sizes to balance competition and popularity.

Address user concerns highlighted in negative reviews to improve sentiment.

By analyzing the Play Store data, we can better understand user preferences and make data-driven decisions to improve app engagement and success.
