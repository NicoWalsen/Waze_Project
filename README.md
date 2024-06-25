

Waze App Dataset

The waze_app_dataset.csv file contains data collected from the Waze app, providing comprehensive insights into user interactions within the navigation app. This dataset is crucial for understanding and mitigating user churn. Waze, renowned for its free navigation services, fosters a dynamic community of contributors, including map editors, beta testers, and partners, united in the mission to enhance global travel efficiency and safety.

Dataset Contents
The dataset includes the following columns:

label: A unique identifier for the user.
sessions: The total number of sessions the user has had.
drives: The number of drives recorded for the user.
total_sessions: The cumulative number of sessions over a specified period.
n_days_after_onboarding: The number of days since the user completed the onboarding process.
total_navigations_fav1: Total navigations to the user's first favorite location.
total_navigations_fav2: Total navigations to the user's second favorite location.
driven_km_drives: Total kilometers driven in the recorded drives.
duration_minutes_drives: Total duration of drives in minutes.
activity_days: Number of days the user was active on the app.
driving_days: Number of days the user recorded driving activity.
device: Type of device used by the user (e.g., Android, iOS).
Usage
This dataset is ideal for both exploratory data analysis (EDA) and machine learning (ML). It enables the development of accurate models to pinpoint factors contributing to user churn, addressing critical questions such as who, why, and when users churn. These insights empower proactive retention strategies.

Applications are conducted in 'WAZE_PROJECT.ipynb' file:

1)Exploratory Data Analysis (EDA): Identify patterns and trends in user activity and by:
Creating visualizations among features and label.
Exploring methods to get insights.

2)Data Processing
Before using the dataset, some preprocessing steps may be required, such as:
Handling missing or incomplete data.
Encoding categorical variables.
Normalizing numerical features.
Handling class imbalance.

3)Machine Learning Models: Develop predictive models to forecast user churn.

4)Evaluation: Metrics to evaluate model performance and to choose the most accurate.

Further steps
User Retention Analysis: Understand user engagement and retention based on activity and driving patterns.
Personalized Marketing: Tailor marketing strategies to enhance user retention and engagement.
