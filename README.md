Social Media Sentiment and Engagement Analysis

Project Overview

This project focuses on analyzing social media data to understand user sentiment, posting patterns, and engagement across different social media platforms.

The analysis is performed using Python libraries such as Pandas and NumPy, along with data visualization techniques.

Project Objectives

- To analyze the number of posts across different social media platforms.
- To identify positive, negative, and neutral sentiments.
- To compare sentiment distribution across platforms.
- To analyze average engagement through likes, shares, and comments.
- To compare engagement between verified and non-verified users.
- To study the relationship between followers count and engagement.
- To analyze country-wise engagement.
- To identify daily and monthly posting trends.

Dataset Information

- Dataset Name: social_media_sentiment_raw.csv
- Original Rows: 2,260
- Columns: 13
- Final Cleaned Rows: 2,216

Dataset Columns

- Post_id
- Timestamp
- Platform
- User
- Followers_count
- Verified
- Text
- Hashtags
- Country
- Likes
- Retweets_shares
- Comments
- Sentiment

Tools and Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

Project Workflow

1. Data Import and Exploration

- Imported the dataset using Pandas.
- Explored the dataset structure, columns, and data types.
- Checked missing values and duplicate records.

2. Data Cleaning and Preprocessing

- Removed duplicate records.
- Handled missing values in the Verified and Country columns.
- Standardized Country and Platform names.
- Identified invalid negative values in Likes.
- Handled outliers in numerical columns using the IQR method and median replacement.
- Verified the cleaned dataset.

Final Dataset Shape: 2,216 rows and 13 columns.

3. Exploratory Data Analysis (EDA)

The following analyses were performed:

1. Identified the number of posts on each social media platform.
2. Identified the number of posts in each sentiment category.
3. Analyzed sentiment distribution across different platforms.
4. Standardized platform names.
5. Analyzed sentiment distribution after standardizing platform names.
6. Compared average engagement across social media platforms.
7. Calculated the percentage distribution of positive, negative, and neutral sentiments.
8. Compared average engagement across sentiment categories.
9. Compared average engagement between verified and non-verified users.
10. Analyzed the relationship between followers count and post engagement.
11. Compared average engagement across different countries.
12. Analyzed the number of posts published over time.
13. Analyzed monthly posting trends across different platforms.

4. Data Visualization

The following 10 chart types were used to visualize the analysis:

1. Bar Chart – Sentiment Distribution
2. Pie Chart – Sentiment Distribution
3. Line Chart – Monthly Posting Trend
4. Scatter Plot – Followers Count vs Likes
5. Histogram – Distribution of Likes
6. Box Plot – Engagement Distribution
7. Stacked Bar Chart – Sentiment Distribution by Platform
8. Donut Chart – Monthly Posting Trend
9. Horizontal Bar Chart – Average Likes by Country
10. Heatmap – Correlation Between Numerical Variables

5. Key Findings

- Positive sentiment posts showed higher average engagement than negative and neutral posts.
- Verified users showed higher average engagement than non-verified users.
- Followers count had a weak positive relationship with likes, shares, and comments.
- TikTok showed higher average engagement among the analyzed platforms.
- Canada recorded the highest average likes among the analyzed countries.
- Daily and monthly posting trends helped identify posting patterns.

Conclusion

This project helped us understand social media sentiment, engagement patterns, and posting trends across different platforms and countries.

The analysis showed that engagement varies according to sentiment, platform, verification status, and country. Data visualization made these patterns easier to understand.

Overall, this project demonstrates how Python and data analysis techniques can be used to explore social media data and gain meaningful insights.

Project Status

Completed
