
# Heart Disease Diagnostic Analysis

This project analyses the various attributes like age, sex, cp,trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca	thal, target etcetera to find key metrics and factors affecting the heart disease. Besides, and is intended to assist in better
future preparation.

## Lessons Learned

While building this project on the basis of the objective to analyze the heart disease diagnostic dataset, some potential learnings I went through included Data Preprocessing where I learnt how to handle missing values, duplicates, and outliers in the dataset. 

I also gained experience in performing EDA using Python. Here, I understood the distribution of data, relationships between different variables, identification of patterns and outliers, etc.

In addition, I learnt how to create effective visualizations and dashboards to represent my findings. For this purpose, I used libraries like Matplotlib, Seaborn etcetera.

Some of the potential challenges I faced included understanding Medical Terminology and columns of the dataset as understanding these terms is crucial to interpret the data correctly.


Furthermore, I also faced the challenge of interpreting the results of my analysis carefully, due to the impact of false positives and negatives because this is medical data.

Additionally, deciding which features are important for my analysis was also challenging as it requires a good understanding of the domain and the data.


Moreover, to understand the medical terms like restecg, thalach, oldpeak, and exang, I referred to medical dictionaries or resources available online to understand the medical terms.


Though I did not use any model for the analysis, I know that for this Medical Diagnostics data, a false negative or a person having a disease but diagnosed as not having it is potentially more harmful than a false positive or a person not having a disease but diagnosed as having it. 

Therefore, I might want to choose a model with a higher recall as it measures the ability of a model to find all the relevant cases even if it has a lower precision which measures what proportion of predicted positives is truly positive.

In addition, though I did not used the predictive model in the above case , feature selection was still an important part of my analysis, and I used Univariate Analysis to analyze each feature individually to understand its distribution and its relationship with the target variable. For example, I use box plots to understand the distribution of each feature for each class of the target variable. 

Besides, I also used Correlation Analysis to calculate the correlation between each feature and the target variable. Features with high correlation are generally more important. I also measured the dependency between two variables, and estimate the relevance of each feature with respect to the target variable.

Furthermore, I used the domain knowledge about heart disease to select important features. For example, I know that age and cholesterol levels are important factors in heart disease, and thus focused on these features in my analysis.

Thus, feature selection in this context helped me to identify the features that provide the most useful information about the target variable.


