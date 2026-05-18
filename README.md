# Welfare Bot Data Analysis

This is a student data analysis and machine learning project where I analysed simulated wellbeing data using Python and machine learning methods.

# Project Goal

The goal of the project was to explore whether changes in a person’s wellbeing could be identified using data analysis and machine learning.

In the project I analysed wellbeing indicators such as:

* mood
* sleep
* food intake
* hydration
* medication
* social activity
* overall wellbeing

The purpose was not medical diagnosis. The goal was to understand how wellbeing data could help identify possible wellbeing changes, trends, and unusual situations.


# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook


# 1. Exploratory Data Analysis (EDA)

In the EDA phase I explored and visualized the wellbeing dataset.

Main tasks:

* loading and inspecting data
* checking missing values
* analysing correlations
* visualizing wellbeing trends
* comparing wellbeing metrics

Visualizations included:

* correlation heatmap
* wellbeing trend graphs
* risk level distribution
* user wellbeing comparisons

# 2. Data Preprocessing

Before machine learning analysis, I cleaned and prepared the dataset.

Preprocessing included:

* handling missing values
* feature selection
* scaling numerical values using StandardScaler


# 3. Isolation Forest – Anomaly Detection

I used Isolation Forest to identify unusual wellbeing situations from the dataset.

The model helped detect possible anomalies related to:

* low wellbeing
* poor sleep
* low hydration
* low mood
* changes in social activity

I also tested different contamination values and adjusted the model to get more realistic results.


# 4. Linear Regression Analysis

I used linear regression to predict the user’s overall wellbeing (`overall_score`).

The analysis included:

* feature importance analysis
* predicted vs actual comparison
* residual analysis
* social activity vs future wellbeing analysis

The results showed that hydration, sleep, medication, and nutrition were strongly connected to overall wellbeing.


# 5. Risk Level Classification

I also tested classification analysis for predicting wellbeing risk levels.

The analysis included:

* classification model
* confusion matrix visualization
* model evaluation

# 6. Clustering Analysis

I used KMeans clustering to group users with similar wellbeing patterns.

The clustering analysis helped identify:

* more stable wellbeing groups
* lower wellbeing groups
* different behaviour patterns


# 7. User Comparison Analysis

In this phase I compared different users using:

* radar charts
* rolling average wellbeing trends
* average wellbeing metric analysis

The comparison showed that users had clearly different wellbeing profiles and long-term trends.


# Machine Learning Methods Used

The project included both supervised and unsupervised machine learning methods.

Methods used:

* Isolation Forest
* Linear Regression
* Risk Level Classification
* KMeans Clustering

# Ethical Considerations

The project used simulated demo wellbeing data without real personal information.

The goal of the models was not medical diagnosis, but analysing wellbeing changes and possible risk situations.

I also considered that machine learning models can make incorrect predictions, so results should always be interpreted carefully.


# Future Ideas

Possible future improvements:

* real-time wellbeing monitoring
* automatic alerts for risk situations
* personal wellbeing dashboards
* long-term wellbeing tracking

---

# What I Learned

During the project I improved my practical skills especially in:

* data analysis
* preprocessing
* machine learning
* data visualization
* anomaly detection
* interpreting machine learning results

The project also helped me better understand how machine learning can be used in wellbeing analytics.
