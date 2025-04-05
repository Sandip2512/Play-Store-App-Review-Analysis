
<h1 align="center">Play Store App Review Analysis</h1>
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

<p align="center">
  <a href="https://www.almabetter.com/courses/full-stack-data-science">
    <img src="https://img.shields.io/badge/Verified-AlmaBetter-blue" alt="AlmaBetter Badge"/>
  </a>
</p>

<p align="center">
  <img src="https://github.com/Sandip2512/Play-Store-App-Review-Analysis/blob/main/google%20play.gif?raw=true" alt="Google Play Logo" width="300"/>
</p>

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📋 Abstract
This project presents an Exploratory Data Analysis (EDA) of Google Play Store apps and user reviews to understand key trends, user preferences, and app performance. The primary goal is to analyze the available app metadata and user sentiment to provide actionable insights for developers. The study addresses challenges like data inconsistencies, missing values, and limited overlap between datasets. Despite these, valuable patterns were uncovered, such as the dominance of free apps, popular categories, and user behavior around app size and ratings. This analysis lays a foundation for developers to make informed decisions when designing, pricing, and positioning apps in a highly competitive market.


## 💾 Project Files Description
This Project includes 1 colab notebook

Executable Files:
Play Store App Review Analysis - Includes all functions required for clustering operations.
Output:
Google Colab - All the outputs are visible in the provided colab notebook.
Input Files:
Play Store.csv - It contains the basic details of the app like number of user reviews, ratings, etc.
Reviews.csv - It contains the user reviews and its sentiment score for the respective app.
Data Source:
Dataset - Dataset taken from Almabetter
-----------------------------------------------------

## 📖 Introduction:
Google Play Store hosts millions of Android applications across diverse categories. With user reviews, install counts, and app attributes readily available, it becomes essential to analyze this data to gain meaningful insights into user behavior and app performance. This project focuses on performing EDA to identify trends in app ratings, categories, sizes, and user feedback, all of which help developers better understand the market landscape.

## 📦 Contents of the Play Store Data & User Reviews:
The dataset is composed of two main files – one containing app-level information from the Google Play Store, and the other containing user-generated reviews.

1. Play Store Dataset:
This dataset contains metadata for each app, including:
App: Name of the application
Category: Category the app belongs to (e.g., Tools, Games, Finance)
Rating: Average user rating of the app
Reviews: Total number of user reviews
Size: Size of the app (in MB or marked as 'Varies with device')
Installs: Number of times the app has been installed
Type: Free or Paid
Price: Price of the app (if Paid)
Content Rating: Age group suitability
Genres: Genres the app belongs to
Last Updated: Last update date
Current Ver: Current version of the app
Android Ver: Minimum Android version required

2. User Reviews Dataset:
This dataset contains user feedback for apps and includes:
App: Name of the application
Translated_Review: The review text (translated to English)
Sentiment: Label indicating if the review is Positive, Negative, or Neutral
Sentiment_Polarity: A score between -1 (negative) and 1 (positive)
Sentiment_Subjectivity: A score between 0 (objective) and 1 (subjective), indicating how opinion-based the review is

-----------------------------------------------------

## 📋Problem Statements
Understanding app success in the Play Store depends on various factors such as app type, size, pricing, category, and user sentiment. The unstructured nature of reviews and inconsistencies in metadata present challenges for analysis. The objective is to clean, explore, and visualize this data to uncover trends, highlight issues, and identify potential areas for app development.

## 📔 What is Exploratory Data Analysis?
Exploratory data analysis (EDA) is used by data scientists to analyze and investigate data sets for patterns, and anomalies (outliers), and form hypotheses based on our understanding of the dataset and summarize their main characteristics, often employing data visualization methods. It is an important step in any Data Analysis or Data Science project. It helps determine how best to manipulate data sources to get the answers you need.

EDA involves generating summary statistics for numerical data in the dataset and creating various graphical representations to understand the data better and make it more attractive and appealing.

The following are the various steps involved in the EDA process:

## ✅ Steps Involved in the Project:
Understanding the Problem Statement
Defined the goal: to analyze Play Store app data and user reviews for insights into app success and user sentiment.

Importing Libraries and Data
Used libraries like Pandas, NumPy, Matplotlib, and Seaborn. Loaded two datasets:

Play Store Apps Data

User Reviews Data

Data Cleaning

Removed duplicates and irrelevant columns

Handled missing values (e.g., dropped 13.6% NaN reviews)

Standardized data types (e.g., numerical conversions, removing “+”, “M”, “$”)

Data Merging

Merged both datasets on the ‘App’ column

Only 816 apps were common between both datasets

Exploratory Data Analysis (EDA)

Analyzed distributions of installs, ratings, size, price

Category-wise comparison (e.g., free vs. paid apps, most reviewed categories)

Visualized trends using bar plots, pie charts, histograms, and heatmaps

Sentiment Analysis (Basic)

Reviewed available sentiment labels in User Reviews

Couldn’t go deeper due to 42% missing data in review sentiments

Key Insights and Interpretation

Identified top-performing categories, free/paid app patterns, app size impact, etc.

Summarized findings to help developers improve app design and user experience

Conclusion and Future Scope

Concluded with actionable insights

Highlighted scope for future work using ML and deeper sentiment analysis

## 🛠 Challenges Faced:
Major challenge was cleaning and merging two datasets with many NaN and duplicate values.
13.6% of reviews were missing, and 42% of User Reviews contained NaNs, limiting sentiment analysis.
Only 816 apps were common between the two datasets (~10% overlap), restricting deeper correlation studies.
Many features like "Current Version" and "Android Version" remain unexplored and can be studied further.
App size and version may correlate with installs—worth deeper investigation.
ML models were not applied; however, they are identified as potential future work.
Visualizing trends and presenting them clearly was a key part of this analysis.

## 📈 Conclusion
EDA on the Play Store dataset revealed the following key findings:
~92% of apps are free; developers should focus on free apps to increase reach.
~82% of apps are suitable for all age groups.
“Family” is the most competitive category; “Game” and “Communication” dominate in installs.
Categories like Beauty, Parenting, and Events are underdeveloped but show good potential.
Apps over 90MB receive the most reviews, suggesting larger apps may attract more user engagement.
Developers should update apps frequently and optimize size, especially for paid versions.
Game and Family categories have more negative reviews; require careful UX planning.
Helix Jump leads in positive reviews, while Angry Birds Classic leads in negative feedback.
Minecraft is the most successful paid app with over 10M installs and high revenue from purchases.
Finance apps have the highest average installation fee among paid apps.

## 💶 Credits
Contact me for Data Science Project Collaborations

## Connect with me

[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sandip2512)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sandip-salunkhe-6881b5240/)

-----------------------------------------------------

## 📚 References
GeeksforGeeks
Analytics Vidhya
Stackoverflow
Towards data science
Python libraries documentation
Data camp
-----------------------------------------------------

## 📜 Feedback
Play Store App Review Analysis
If you have any feedback, please reach out to us at salunkhesandip2512@gmail.com

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
