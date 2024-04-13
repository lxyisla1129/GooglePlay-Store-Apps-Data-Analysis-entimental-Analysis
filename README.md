# GooglePlay-Store-Apps-Data-Analysis-entimental-Analysis

**Project Overview:**
This analytical project delves into the diverse ecosystem of the Google Play Store, exploring various dimensions of mobile applications ranging from app categories and user ratings to installation counts and reviews. Utilizing Python's powerful data manipulation libraries, the project embarks on preprocessing the raw data from the Google Play Store, followed by a structured data analysis that draws insights into user behavior and app trends.

**Data Preprocessing:**
The initial step involved cleansing the datasets, 'googleplaystore.csv' for general app data and 'googleplaystore_user_reviews.csv' for user reviews. The process included:
- Removal of irrelevant columns and rows.
- Treatment of missing values.
- Uniform formatting of categorical data.
- Elimination of duplicates and outliers.

**Sentiment Analysis:**
To augment the project's analytical depth, sentiment analysis on user reviews was conducted using the Natural Language Toolkit (NLTK). This analysis provided a quantifiable measure of the sentiment polarity and subjectivity in user reviews, categorizing them into positive, negative, or neutral sentiments. It played a pivotal role in understanding user satisfaction and pinpointing areas for app improvement.

**Analytical Insights:**
Key analyses were performed, revealing that:
- Family-related and game apps are predominant in the app store.
- A significant concentration of high user ratings indicates general user satisfaction.
- Apps with over 100 million installs do not exhibit considerable variation, indicating a balanced distribution.
- The word cloud analysis emphasized Google's dominance in the app marketplace.

**Technologies Used:**
- Python: pandas, numpy, matplotlib, seaborn, PIL, wordcloud.
- Sentiment Analysis: NLTK.
