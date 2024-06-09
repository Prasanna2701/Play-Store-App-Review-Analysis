# Play-Store-App-Review-Analysis
![68747470733a2f2f692e70696e696d672e636f6d2f6f726967696e616c732f36302f61382f62352f36306138623530346131393434393635396163386534316433666238303761342e676966](https://github.com/Prasanna2701/Play-Store-App-Review-Analysis/assets/62757540/22115407-3363-4cdf-88ac-f39a9a7f840b)

# Google Play Store Apps Analysis

## Problem Statement
The objective of this project is to explore and analyze the Google Play Store apps dataset, which includes information such as category, rating, size, and more. Additionally, a dataset containing customer reviews of Android apps is provided. The goal is to discover key factors that contribute to app engagement and overall success.

## Features
- **App Category**: The category of the app (e.g., beauty, business, entertainment, education, etc.).
- **Rating**: How users rate the app out of 5, with 1 being the lowest rating and 5 being the highest.
- **Reviews**: The number of user reviews each app has received.
- **Size**: The memory size needed to install the application.
- **Installs**: The number of times each application has been installed by users.
- **Type**: Whether the app is free or a paid app.
- **Price**: The price of the app.
- **Content Rating**: Specifies the intended audience for the app (e.g., for teens, mature audience, everyone).
- **Genres**: The sub-category for each app (e.g., Education: Pretend Play).
- **Last Updated**: The release date of the most recent update for the app.
- **Current Ver**: The app's current version.
- **Android Ver**: The oldest version of Android OS supported by the app.

## Summary and Conclusion
Google Play Store is renowned as one of the largest and most popular Android app stores worldwide. With its extensive collection of apps and a wealth of data, it presents an optimal opportunity for creating effective models and identifying trends and future challenges.

In this exploratory data analysis (EDA) project, we utilized two raw datasets from Kaggle: one containing Play Store attributes and the other consisting of user reviews. The first dataset encompasses 13 different attributes, while the second dataset provides five additional features for data manipulation and analysis.

### Data Cleaning
To ensure data integrity, we began by performing crucial data cleaning steps:
- Removing duplicate entries.
- Dropping non-essential null values.
- Replacing null values in the rating column with the mode of ratings to handle 1645 missing values.

### Exploratory Data Analysis
After cleaning the data, we conducted exploratory data analysis to gain a comprehensive understanding of our dataset. This involved:
- Examining the number of installations for each category.
- Exploring the correlation between app size, Android version, and the number of installs.

### Merging Datasets
We merged both dataframes to discover correlations between the columns of the two datasets, which yielded fascinating results.

### Key Insights
- Positive correlation between reviews and installs, while price and rating exhibit a negative correlation.
- The "Art and Design" category has the highest number of installs.
- Developing apps within the "Family" and "Lifestyle" categories may result in higher revenue.
- Approximately 61% of users have a positive sentiment, while around 15% express negative sentiment.
- Free apps account for 92.12% of the dataset, while paid apps constitute 7.81%.
- The "Everyone" content rating category dominates, representing 81.80% of all apps.
- The most prevalent categories on the Play Store are "Family," "Game," and "Tools."
- The "Game" category presents potential opportunities for developers due to its high number of installs.
- Popular genres for app downloads include "Tools," "Entertainment," "Education," "Business," and "Medical."
- The average rating of apps on the Play Store is 4.17, indicating a satisfactory overall quality.
- Users prefer lightweight apps and may be hesitant to download larger, paid apps.
- Apps reviewed by a larger number of people tend to be downloaded more frequently.
- Users tend to leave harsher reviews for paid apps.
- A positive correlation exists between installs and rating.
- Developing an app with a high rating requires timely updates and optimal app size.
- Developing free apps with a content rating suitable for everyone is beneficial.

### Conclusion
The dataset holds immense potential for improving business value and making a positive impact. It extends beyond the specific problem addressed in this project, with numerous other interesting possibilities waiting to be explored through further analysis. By successfully achieving our project objectives and answering our research questions, we have obtained valuable insights into the Google Play Store apps ecosystem and the trends within.
