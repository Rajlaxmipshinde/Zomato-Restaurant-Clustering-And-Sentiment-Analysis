# Zomato-Restaurant-Clustering-And-Sentiment-Analysis

This project focuses on Zomato, a leading online food delivery platform, utilizing two primary datasets: one detailing restaurant information and the other containing user reviews.

In the initial phase, we conducted thorough data cleaning and preprocessing to prepare the datasets for in-depth analysis. Following this, we performed Exploratory Data Analysis (EDA) on both datasets, which helped us understand their structure and key features.

The core analysis involved applying K-means clustering to categorize similar restaurants and conducting sentiment analysis on user reviews. To visualize the sentiment analysis results, we employed an LDA visualizer. We also compared these findings with supervised methods to gain a deeper understanding of the data.

Overall, this project provides a comprehensive examination of Zomato’s restaurant and review datasets, offering insights through clustering, sentiment analysis, and visualization to support informed decision-making in the food industry.

## Problem Statement
The objective of this project is to analyze and understand the restaurant industry in India using data from Zomato, an Indian restaurant aggregator and food delivery startup. The project focuses on extracting insights from customer reviews, clustering Zomato restaurants into distinct segments, and presenting the findings through visualizations. The analysis covers various aspects, including cuisine types, cost information, and customer reviews. The goal is to help customers discover the best restaurants in their area and support the company in pinpointing opportunities for growth and industry improvement. Additionally, the project aims to perform sentiment analysis and identify influential critics in the industry by examining reviewer metadata.


## Conclusion
* In this project, we implemented a range of data preprocessing techniques to improve the quality of our textual dataset, making it suitable for machine learning applications.

Optimized Clustering: We refined the K-means clustering process by selecting the optimal number of clusters (K=6), which enhanced the Silhouette Score and indicated better cluster separation.

Topic Modeling: Using Latent Dirichlet Allocation (LDA), we identified key topics within the reviews, providing valuable insights into the prevalent themes.

Model Performance: Supervised models, such as Logistic Regression and XGBoost, showed significant improvements in key evaluation metrics following hyperparameter tuning.

Improved Precision: We achieved high precision, crucial for accurately predicting positive sentiment in sentiment analysis, which is vital for businesses interpreting customer feedback.

Enhanced Recall: Our models demonstrated high recall, ensuring effective capture of positive instances, which is essential for applications that must not overlook positive cases.

Balanced F1-Score: We attained a balanced F1-score, offering a good trade-off between precision and recall, beneficial for applications requiring a balance between accuracy and coverage.

ROC AUC Significance: After tuning, the ROC AUC score improved, underscoring the model's effectiveness in distinguishing between positive and negative instances, which is key for classification accuracy.

Model Deployment: We discussed the importance of saving the best-performing model in a deployable format, preparing it for real-world applications.

Future Prospects: We highlighted the potential for live server deployment and emphasized the importance of evaluating the model on unseen data to ensure real-world applicability.

Impact on Business: Our project has the potential to provide businesses with data-driven insights, thereby enhancing their decision-making capabilities.

Data Transformation: From text preprocessing to model selection, our project demonstrates the transformative impact of data science, turning raw data into actionable knowledge.
