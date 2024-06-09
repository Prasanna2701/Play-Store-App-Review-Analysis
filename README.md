# Play-Store-App-Review-Analysis
![68747470733a2f2f692e70696e696d672e636f6d2f6f726967696e616c732f36302f61382f62352f36306138623530346131393434393635396163386534316433666238303761342e676966](https://github.com/Prasanna2701/Play-Store-App-Review-Analysis/assets/62757540/22115407-3363-4cdf-88ac-f39a9a7f840b)
# Problem Statement
The goal of this project is to explore and analyze the Google Play Store apps dataset, which includes information such as category, rating, size, and more. Additionally, we will examine a dataset containing customer reviews of Android apps. Our aim is to identify key factors that contribute to app engagement and overall success.

# Features
App Category: The category of the app (e.g., beauty, business, entertainment, education, etc.).
Rating: User rating of the app out of 5.
Reviews: Number of user reviews received.
Size: Memory size required to install the app.
Installs: Number of times the app has been installed.
Type: Indicates if the app is free or paid.
Price: The price of the app.
Content Rating: Intended audience for the app (e.g., teens, mature audience, everyone).
Genres: Sub-category of the app (e.g., Education: Pretend Play).
Last Updated: Date of the most recent update.
Current Ver: Current version of the app.
Android Ver: Oldest version of Android OS supported.

# Summary and Conclusion
Google Play Store is one of the largest and most popular app stores for Android devices globally. With its extensive app collection and rich data, it offers an excellent opportunity to create effective models and identify trends and challenges.

In this EDA project, we utilized two raw datasets from Kaggle: one containing Play Store attributes and the other comprising user reviews. The Play Store dataset includes 13 different attributes, while the reviews dataset provides five additional features for analysis.

To maintain data integrity, we started by performing essential data cleaning steps, such as removing duplicate entries and dropping non-essential null values. Due to a significant number of null values in the rating column (1645), dropping them entirely would have adversely affected our results. Therefore, we replaced these null values with the mode of ratings.

Post data cleaning, we conducted exploratory data analysis to gain a comprehensive understanding of our dataset. This included analyzing the number of installations per category and exploring correlations between app size, Android version, and the number of installs.

We also merged both datasets to uncover correlations between their columns, which yielded fascinating results.

# Key Insights and Conclusions
There is a positive correlation between reviews and installs, while price and rating show a negative correlation.
The "Art and Design" category has the highest number of installs.
Developing apps in the "Family" and "Lifestyle" categories may lead to higher revenue.
Approximately 61% of users have a positive sentiment, while around 15% express negative sentiment.
Free apps make up 92.12% of the dataset, while paid apps constitute 7.81%.
The "Everyone" content rating category dominates, representing 81.80% of all apps.
The most prevalent categories on the Play Store are "Family," "Game," and "Tools."
The "Game" category offers significant opportunities for developers due to its high number of installs.
Popular genres for app downloads include "Tools," "Entertainment," "Education," "Business," and "Medical."
The average app rating on the Play Store is 4.17, indicating a generally satisfactory quality.
Users prefer lightweight apps and may be hesitant to download larger, paid apps.
Apps with a higher number of reviews tend to be downloaded more frequently.
Users tend to leave harsher reviews for paid apps.
A positive correlation exists between installs and ratings.
Developing an app with a high rating requires timely updates and optimal app size.
Creating free apps with a content rating suitable for everyone is advantageous.
This dataset holds immense potential for enhancing business value and making a positive impact. Beyond the specific problem addressed in this project, there are numerous other interesting possibilities to explore through further analysis. By successfully achieving our project objectives and answering our research questions, we have gained valuable insights into the Google Play Store apps ecosystem and its trends.
