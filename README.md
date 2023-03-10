# <font color=black>**Diabetes Prediction**</font>
This project aims to predict whether a patient has diabetes or not, based on certain diagnostic measurements included in the dataset. The dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases, and consists of several medical predictor variables and one target variable, Outcome.

### <font color=black>**Dataset**</font>
The dataset includes information for females of Pima Indian heritage who are at least 21 years old. Predictor variables include the number of pregnancies, BMI, insulin level, age, and more. The target variable, Outcome, is a binary variable indicating whether or not the patient has diabetes.

### <font color=black>**Analysis**</font>
In this project, I used numpy, pandas, matplotlib, seaborn, and plotly for data manipulation, exploration, and visualization. Before proceeding with the analysis, I checked for missing values in the dataset. I found no missing values in any of the predictor variables.

I analyzed the distribution of each predictor variable. The histogram and KDE plots revealed that BMI, blood pressure, and glucose level variables are approximately normally distributed. However, the insulin level and skin thickness variables are skewed to the right, while the number of pregnancies variable is highly skewed to the right.

I also created KDE plots to see the distribution of each variable based on the diabetes outcome. The KDE plots showed that patients with diabetes had higher BMI, glucose level, and insulin level compared to patients without diabetes. However, there was no strong correlation between the number of pregnancies and the diabetes outcome. I also conducted bivariate and multivariate analysis to explore the relationships between the predictor variables and the target variable. Bivariate analysis involved analyzing the relationship between two variables at a time, while multivariate analysis involved analyzing the relationship between multiple variables simultaneously.

Using seaborn, I created visualizations that helped me understand the relationship between the predictor variables and the target variable. For example, I used kdeplots to visualize the relationship between the number of pregnancies and the diabetes outcome, and a scatterplot matrix to visualize the relationships between multiple predictor variables and the target variable.

For data preprocessing, I used sklearn libraries. I used five different models: Logistic Regression, KNN, Decision Tree, SVM, and Random Forest. Logistic Regression was found to be the best performing model with a test accuracy of 0.78%.

### <font color=black>**Files**</font>
* diabetes.csv: The original dataset
* Diabetes Prediction.ipynb: Jupyter Notebook containing the data analysis and modeling code
* README.md: This file

### <font color=black>**Requirements**</font>
The following libraries are required to run the code:

* numpy
* pandas
* matplotlib
* seaborn
* plotly
* sklearn

### <font color=black>**Usage**</font>
To run the code, run the Diabetes Prediction.ipynb notebook in Jupyter. The notebook contains step-by-step instructions for loading the data, preprocessing the data, training and evaluating the models, and making predictions.

### <font color=black>**Conclusion**</font>
This project demonstrates how to predict diabetes using machine learning techniques. The best performing model was Logistic Regression, which achieved a test accuracy of 0.78%. This model can be used to predict diabetes in new patients based on their diagnostic measurements.

Through visualization and analysis, I identified several important predictor variables for predicting diabetes. BMI, age, and insulin level were found to be strong predictors of diabetes risk. Patients with a higher BMI had a higher likelihood of having diabetes, while patients over 50 years old and with high insulin levels were also at higher risk.

These insights can be used to develop targeted interventions for high-risk patients. For example, healthcare providers could focus on promoting healthy eating and exercise habits for patients with a high BMI, or provide diabetes screening for patients over 50 years old or with high insulin levels.
