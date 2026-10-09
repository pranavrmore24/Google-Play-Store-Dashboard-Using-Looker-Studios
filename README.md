# Project File Link
Link:- https://datastudio.google.com/reporting/73af75c8-ef37-4a36-b6ab-02fb890c801d

# Google Play Store App Insights Dashboard Using Looker Studio

## Project Overview

This project analyzes the Google Play Store dataset to uncover insights related to app performance, user satisfaction, popularity, pricing strategies, app size, and update trends. An interactive Looker Studio Dashboard was developed to transform raw application data into meaningful business insights and support data-driven decision-making.

The dashboard provides a comprehensive view of the Google Play Store ecosystem through multiple analytical perspectives, including ratings analysis, install trends, pricing analysis, and app maintenance patterns.

---

## Objective

The objective of this project is to:

- Analyze the distribution of applications across different categories.
- Evaluate user satisfaction using ratings and reviews.
- Identify the most popular apps and categories based on installs.
- Compare free and paid app monetization strategies.
- Understand the relationship between pricing and user engagement.
- Analyze the impact of app size on installs and ratings.
- Examine app update trends and Android version compatibility.
- Generate actionable business recommendations for developers and businesses.

---

## Tool Used

- Looker Studio
- Google Sheets / Excel
- Data Cleaning & Transformation
- Calculated Fields
- Interactive Dashboard Design

---

## Dataset Features

- App
- Category
- Rating
- Reviews
- Installs
- Type
- Price
- Content Rating
- Genres
- Size
- Last Updated
- Current Version
- Android Version

---

## Data Preparation & Cleaning

### Data Cleaning Steps

- Removed unnecessary missing values.
- Converted Installs column into numeric format.
- Removed special characters from install counts.
- Converted Size column into Size_MB.
- Converted Price field into numeric format.
- Extracted Update Year from Last Updated.
- Standardized data types across fields.

### Feature Engineering

Created the following calculated fields:

- Rating Group
- Rating Sort
- Install Group
- Install Group Sort
- Price Group
- Update Year
- Free Apps Count
- Paid Apps Count
- Total Apps
- Total Reviews

---

## Dashboard Structure

### 1. Executive Overview & Business Performance Analysis

#### KPIs

- Total Apps
- Total Installs
- Average Rating
- Total Reviews
- Free Apps Count
- Paid Apps Count

#### Visualizations

- Top Categories by Number of Apps
- Free vs Paid Apps
- Content Rating Distribution
- App Updates Over Time

#### Key Insights

- Free apps dominate the Google Play Store ecosystem.
- Family and Game categories contain the highest number of applications.
- Most applications target broad audiences.
- App update activity increased significantly in recent years.

---

### 2. Ratings & User Satisfaction Analysis

#### KPIs

- Average Rating
- Apps Rated 4+
- Maximum Rating
- Lowest Rating

#### Visualizations

- Top Categories by Average Rating
- Rating Distribution
- Rating vs Reviews
- Top Rated Apps Table

#### Key Insights

- Average app rating is approximately 4.17.
- Most apps fall within the 4–5 rating range.
- Categories such as Events and Education have the highest ratings.
- Highly reviewed apps generally maintain strong user satisfaction.

---

### 3. Install & Popularity Analysis

#### KPIs

- Total Installs
- Average Installs per App
- Apps Above 1 Million Installs

#### Visualizations

- Top Installed Apps
- Top Categories by Installs
- Install Distribution
- Installs vs Ratings
- Most Installed Apps Table

#### Key Insights

- A small number of apps account for a significant share of total installs.
- Game and Communication categories drive the highest download volumes.
- Popular apps generally maintain positive ratings.
- Install distribution is highly concentrated among top-performing apps.

---

### 4. Pricing & Revenue Analysis

#### KPIs

- Free Apps Count
- Paid Apps Count
- Average Price
- Maximum Price

#### Visualizations

- Free vs Paid Apps
- Price Distribution
- Paid Apps by Category
- Price vs Reviews
- Price vs Ratings

#### Key Insights

- Free apps represent more than 90% of the marketplace.
- Paid apps are concentrated in specific categories.
- Higher prices do not guarantee higher ratings.
- User engagement depends more on app quality than pricing.

---

### 5. App Size & Update Trends Analysis

#### KPIs

- Average App Size (MB)
- Largest App Size (MB)
- Apps Updated in 2018
- Latest Update Year

#### Visualizations

- App Size Distribution
- Average App Size by Category
- Size vs Installs
- Size vs Ratings
- App Updates Over Time
- Android Version Distribution

#### Key Insights

- Entertainment apps tend to have larger sizes.
- App size has minimal impact on ratings and installs.
- Most applications were actively updated in 2018.
- Developers prioritize compatibility with modern Android versions.

---

## Project Workflow

### 1. Data Cleaning

- Removed missing values
- Converted Installs into numeric format
- Converted Size into MB
- Cleaned Price column
- Extracted Update Year
- Created calculated fields

### 2. Basic Analysis (10 Questions)

- Average app rating
- Highest category by app count
- Free vs Paid apps count
- Maximum rating
- Minimum rating
- Total installs
- Content rating distribution
- Average app size
- Maximum app size
- Update year analysis

### 3. Medium Analysis (10 Questions)

- Highest-rated categories
- Most installed categories
- Rating vs Reviews relationship
- Paid apps by category
- Rating group distribution
- Price distribution
- Size vs Ratings
- Size vs Installs
- Largest app categories
- Android version distribution

### 4. Advanced Analysis (5 Questions)

- Price vs Ratings analysis
- Price vs Reviews analysis
- Installs vs Ratings relationship
- Factors contributing to app success
- Strategic recommendations for developers

---

## Key Insights

### User Satisfaction

- Average app rating is approximately 4.17.
- Most applications are rated between 4 and 5 stars.
- Highly reviewed applications generally maintain strong ratings.

### Popularity Trends

- Total installs exceed 75 Billion.
- A small number of applications generate the majority of downloads.
- Game and Communication categories dominate install volume.

### Monetization Analysis

- Free applications dominate the marketplace.
- Paid applications represent less than 10% of total apps.
- Pricing has limited impact on user satisfaction.

### App Maintenance

- Most applications received updates in 2018.
- Frequent updates indicate active developer support.
- Android version compatibility remains a critical factor for app adoption.

---

## Business Impact

### Market Understanding

The dashboard helps stakeholders understand category performance, market demand, and user preferences.

### Product Strategy

Developers can identify successful categories and prioritize features that improve user satisfaction.

### Revenue Optimization

Pricing analysis helps businesses evaluate monetization strategies and market positioning.

### User Experience Improvement

Ratings and reviews provide valuable feedback for continuous product enhancement.

### Competitive Benchmarking

Organizations can compare app performance across categories and identify industry trends.

---

## Conclusion

The Google Play Store App Insights Dashboard successfully transforms raw application data into actionable business intelligence. The analysis reveals that free apps dominate the marketplace, user ratings remain consistently high, install volumes are concentrated among a small number of applications, and pricing has limited influence on user satisfaction.

The project demonstrates the power of data analytics and visualization in understanding user behavior, market trends, and app performance. These insights can support developers, businesses, and decision-makers in improving app quality, optimizing monetization strategies, and driving long-term growth.

---

## Dashboard Pages

### Page 1 – Executive Overview
Business Performance Summary

### Page 2 – Ratings & User Satisfaction Analysis
User Experience Analysis

### Page 3 – Install & Popularity Analysis
App Adoption Trends

### Page 4 – Pricing & Revenue Analysis
Monetization Insights

### Page 5 – App Size & Update Trends Analysis
Maintenance & Optimization Analysis

---

⭐ If you found this project useful, feel free to star the repository and connect with me on LinkedIn.
