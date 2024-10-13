#### Project Overview
This project explores user behavior on the VeloCityX platform, analyzing how various activities—such as real-time chat participation, fan challenges, and sponsorship interactions—impact virtual merchandise purchases. Using data analysis, clustering, and predictive modeling, the project identifies trends, key user segments, and the most influential factors driving engagement and revenue.

#### Objectives
 Data Cleaning & Preparation: Clean and organize the raw data into a usable format. Engineer new features, such as Engagement Score and Purchased Merchandise (binary), to enhance the analysis.
 
 Investigate Trends: Identify which users are most likely to purchase merchandise.Explore correlations between user engagement, sponsorship interactions, and purchases.
 
 Clustering & Predictive Modeling:Use K-Means clustering to segment users. Apply Random Forest, XGBoost, and Neural Networks to predict merchandise purchases.
 
 Visualization Insights: Use correlation heatmaps, scatterplots, feature importance charts, and more to communicate key findings effectively.

#### Dataset
The dataset consists of sample user interaction data from the VeloCityX app, with the following features:
- User ID: Unique identifier for each user.
- Fan Challenges Completed: Number of challenges completed.
- Predictive Accuracy (%): User's accuracy in predicting race outcomes.
- Virtual Merchandise Purchases: Number of merchandise purchases.
- Sponsorship Interactions (Ad Clicks): Number of ad views or clicks.
- Time on Live 360 (mins): Time spent watching race events on Live 360.
- Real-Time Chat Activity (Messages Sent): Number of messages sent during race events.

#### Data Cleaning & Feature Engineering
The raw dataset was well-structured with no missing values or duplicates.

New features were engineered to enrich the analysis:
- Engagement Score: Sum of time on Live 360 and chat activity.
- Purchased Merchandise (binary): A binary indicator of whether a user made a purchase.

#### Investigating Trends
The analysis identified several key trends:
- Users with higher engagement (more active on Live 360 and chat) were more likely to purchase virtual merchandise.
- Participation in fan challenges positively correlated with merchandise purchases.
- Sponsorship interactions (ad clicks) showed a moderate correlation with both purchases and engagement.
- Predictive accuracy in challenges was found to be a key factor driving purchases and user engagement.

#### Predictive Modeling Results
The following machine learning models were applied to predict merchandise purchases:

Logistic Regression: Achieved 85% accuracy. 

Random Forest Model: Achieved 95% accuracy. Key predictors included Engagement Score, Predictive Accuracy, and Sponsorship Interactions.

XGBoost Model: with 95% accuracy and higher recall for identifying purchasers. Fan Challenges Completed and Engagement Score were the most influential features.

Neural Network Model: Captured non-linear relationships, achieving 83% accuracy. Required more training iterations for stable performance.

#### Visualization Insights
Several visualizations were created to communicate the findings effectively:

- Correlation Heatmap: Showed relationships between features, highlighting correlations between engagement and purchases.
- Cluster Scatterplots: Provided clear segmentation of users based on behavior.
- Feature Importance Bar Charts: Identified the most critical predictors of merchandise purchases.
- Confusion Matrix: Evaluated the performance of predictive models by comparing predicted vs. actual outcomes.

#### Conclusion
The VeloX project successfully combined data analysis, clustering, and predictive modeling to uncover valuable insights into user behavior on the VeloCityX platform. The key findings emphasized that:

- High engagement and challenge participation are strong indicators of merchandise purchases.
- Sponsorship interactions play a moderate role in driving engagement and purchases.
- Machine learning models such as Random Forest, XGBoost, and Neural Networks provided robust predictions, with XGBoost delivering the best performance.
