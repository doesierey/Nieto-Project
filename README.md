# Nieto-Project
TEECE 2 Capstone Project

Lifestyle and Learning – Predicting Student Performance

I. Introduction


This project utilizes a simulated dataset of 1,000 student records sourced from Kaggle. Each record
captures key lifestyle habits—such as study hours, sleep patterns, screen time, diet, and mental health—
and relates them to academic performance, specifically the final exam score. The dataset is ideal for
educational machine learning applications, enabling learners to perform data preprocessing, visualization,
clustering, regression, and classification.

Methods

The project utilizes a comprehensive approach that includes data preprocessing, exploratory data analysis (EDA), clustering, and regression analysis. Initially, the dataset is inspected for missing values and categorical variables are encoded. Feature engineering is performed to create new metrics such as total screen time and study efficiency. Various visualizations, including histograms, scatter plots, and correlation heatmaps, are utilized to explore the data. K-Means clustering is applied to identify student groupings, with the optimal number of clusters determined using the elbow method and silhouette scores. For predictive modeling, three regression techniques—Linear Regression, Decision Tree Regressor, and Random Forest Regressor—are used, with model performance evaluated using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² score.    

Findings    

The analysis reveals that lifestyle factors significantly influence academic performance. Key findings indicate that attendance and study habits are the strongest predictors of success, with the Decision Tree model highlighting attendance-study interaction as the most important feature. The Random Forest model supports this, showing a more balanced importance across multiple factors, including study efficiency and study hours per day. The regression models demonstrate strong predictive capabilities, with Linear Regression achieving an R² score of 0.90, indicating a high level of accuracy in predicting exam scores. Overall, the project underscores the importance of lifestyle habits in shaping academic outcomes and provides valuable insights for students.
