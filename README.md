-----
# SpaceX-Project

-----

<img width="1024" height="1536" alt="spacex-rocket" src="https://github.com/user-attachments/assets/592949d9-ec27-4ea1-bfce-48821f7c3b92" />

The project aims to predict the successful landing of the Falcon 9 first stage, a critical factor in SpaceX rocket launches. This prediction bears substantial financial implications, given that SpaceX's reusability of the first stage significantly lowers launch costs compared to other providers. Priced at $62 million per launch, Falcon 9 launches stand in stark contrast to competitors, which can cost upwards of $165 million each.​

Accurately determining the success of the first stage landing is essential for estimating launch costs, especially when competing companies are vying for rocket launch contracts against SpaceX.​

The objective of this project is to analyze data meticulously and predict the outcome of Falcon 9 first stage landings with precision, acknowledging the significant financial ramifications associated with this prediction.​

Throughout the project, predictive modeling and data analysis methodologies were used to predict Falcon 9 first stage landings. This involved;​
- Acquiring and preprocessing relevant data.​
- Performing exploratory data analysis.​
- Employing interactive visual analytics tools to enhance understanding and models.​
- Applying predictive analysis techniques, such as machine learning algorithms.​

-----
## Executive Summary​

-----

- Data collection methodology​
-- Requested via SpaceX REST API and Scrapping historical data from Web (Wikipedia)​
- Performing data wrangling​
-- Cleaning, transforming, and preparing the collected data for analysis, ensuring its quality and suitability for further processing​
- Performing exploratory data analysis (EDA) using visualization and SQL​
- Performing interactive visual analytics using Folium and Plotly Dash​
- Performing predictive analysis using classification models​
-- Logistic Regression, Decision Tree, K-Nearest Neighbors and SVM models are built using scikit learn library, searched for best hyperparameters via GridSearchCV with 10-fold,     tuned with best hyperparameters found and results are evaluated with accuracy score.​
