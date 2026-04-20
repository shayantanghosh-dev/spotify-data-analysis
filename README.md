# Spotify User Behavior Analysis

## Project Overview
This project analyzes a synthetic dataset that simulates user behavior on a Spotify-like music streaming platform. The dataset contains 5000 user records reflecting user engagement, subscription behavior, and advertisement interaction.

The objective of this project is to derive meaningful insights related to:
- User engagement patterns  
- Subscription behavior and conversion trends  
- User churn and inactivity  
- Marketing effectiveness through advertisements  

This project focuses on building an interactive dashboard using Google Sheets to visualize and analyze user behavior.

---

## Data Source

The dataset used in this project is sourced from Kaggle.

- Platform: Kaggle  
- Dataset Name: Spotify User Behavior and Pattern  
- Dataset Link: https://www.kaggle.com/datasets/sahilislam007/spotify-user-behavior-and-pattern


---

<img alt="image" src="image.png" />






## Dataset Information

- Total Records: 5000  
- Total Columns: 18  
- Data Type: Synthetic (realistic simulation)  
- Domain: Music Streaming / User Analytics  
- Platform Context: Spotify-like environment  
- File Format: CSV  

---

## Data Dictionary

| Column Name | Description | Data Type |
|------------|------------|----------|
| user_id | Unique identifier assigned to each user | Integer |
| country | Country where the user is located | String |
| age | Age of the user | Integer |
| signup_date | Date when the user signed up | Date |
| subscription_type | Type of plan (Free, Premium, Family, Student) | String |
| subscription_status | Indicates whether the subscription is Active or Inactive | String |
| months_inactive | Number of months the user has been inactive | Integer |
| inactive_3_months_flag | 1 = inactive ≥ 3 months, 0 = active/recent | Binary |
| ad_interaction | Indicates whether the user interacted with advertisements | Binary |
| ad_conversion_to_subscription | Indicates whether ad led to subscription conversion | Binary |
| music_suggestion_rating_1_to_5 | Rating given by user to music recommendations (1–5) | Integer |
| avg_listening_hours_per_week | Average weekly listening time in hours | Float |
| favorite_genre | User’s preferred music genre | String |
| most_liked_feature | Feature most liked by the user (e.g., Playlists, Radio, AI DJ) | String |
| desired_future_feature | Feature user wants in the future | String |
| primary_device | Device used for streaming (Mobile, Desktop, Tablet, etc.) | String |
| playlists_created | Number of playlists created by the user | Integer |
| avg_skips_per_day | Average number of songs skipped per day | Float |



## Key Features (Based on Dashboard)

- KPI section displaying total users, total playlists, average age, average listening hours, average music suggestion and average skips per day
- Country-wise playlists created analysis  
- Device usage distribution visualization  
- Average Skips per day in different Countries 
- Inactivity behaviour in various countries analysis
- Average Listening Hours for different age groups
- Average Listening Hours for different music genre 
- Genre popularity insights  
- Most Liked Features  
- Interactive filters (country, subscription status, age, genre, device, most liked feature)

---

## Exploratory Data Analysis (EDA)

### User Distribution
- Users are distributed across multiple countries with relatively balanced participation  
- Certain countries show higher playlist creation and engagement levels  

### Device Usage
- Users access the platform through multiple devices such as mobile, desktop, tablet, and smart systems  
- Mobile and tablet users dominate overall usage  

### Ad Interaction Analysis
- A significant portion of users do not interact with ads  
- Ad engagement shows a declining trend compared to non-interaction  

### Inactivity Analysis
- Among users who go inactive, how long do they stay inactive for    
- Either they are more than 3-months inactive or went inactive recently 

### Churn Analysis
- Majority of users are active  
- A smaller portion of inactive users indicates manageable churn but still requires attention  

### Genre Popularity
- Music preferences are diverse across genres  
- Some genres like Pop, Rock, and Indie have higher user engagement  

### Playlist Behavior
- Playlist creation varies by country  
- High playlist counts indicate stronger user engagement in specific regions  

---

## Key Analytical Questions

- Which countries have the highest user engagement and playlist creation?  
- What devices are most commonly used for music streaming?  
- Which age group has the most listening hours?  
- What percentage of users go inactive and stay inactive for 3months?  
- What is the current churn rate based on inactive users?  
- Which genres are most popular among users?  
- How does user behavior differ across subscription types?  

---

## Use Cases

- User engagement analysis for improving platform experience  
- Churn detection and retention strategy planning  
- Marketing performance evaluation (Ad effectiveness)  
- Subscription conversion optimization  
- Customer segmentation based on behavior and preferences  
- Data visualization and dashboard reporting  

---
## Dashboard
<img alt="image" src="Dashboard.jpg" />



## Disclaimer

This dataset is synthetically generated for educational purposes and does not contain real user data from Spotify. It is designed to simulate realistic behavior patterns for analysis and learning.

---

## Conclusion

This dashboard provides a comprehensive view of user behavior on a music streaming platform. It highlights key insights related to user engagement, subscription patterns, churn, and advertisement effectiveness.

The analysis shows that while most users remain active, there is potential to improve ad engagement and conversion rates. Additionally, understanding user preferences such as genre and device usage can help enhance personalization and overall user experience.

This project demonstrates how data visualization and dashboarding can be effectively used to derive actionable business insights.



