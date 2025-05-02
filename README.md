# Student Performance Prediction using Linear Regression
This project focuses on predicting students' Math Scores based on their Reading Scores using a Linear Regression model. It includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and saving the trained model.

### Dataset
The dataset used is from Kaggle and hosted on GitHub:

URL: https://raw.githubusercontent.com/rashida048/Datasets/master/StudentsPerformance.csv

It includes 1000 observations and 8 features:

gender, race/ethnicity, parental level of education, lunch, test preparation course

math score, reading score, writing score

### Project Steps
1. Importing Libraries
Python libraries such as pandas, matplotlib, seaborn, sklearn, and pickle are used.

2. Loading Data
The dataset is loaded using pandas.read_csv() and initial inspection is performed.

3. Exploratory Data Analysis (EDA)
Visualized distributions of scores

Checked for multicollinearity using correlation matrix and VIF

Visualized relationships between features

4. Data Preparation
Selected Reading Score as the feature (X)

Selected Math Score as the target (y)

Split data into training (80%) and testing (20%) sets

5. Model Building
Implemented a Linear Regression model from sklearn

Trained the model on training data

Extracted model coefficients and intercept

6. Model Evaluation
Evaluated the model using MAE and MSE:

Mean Absolute Error (MAE): ~7.28

Mean Squared Error (MSE): ~77.76

### Plotted:

Actual vs Predicted Math Scores

Residuals vs Fitted Values (for homoscedasticity check)

7. Model Serialization
Saved the trained model using Python pickle as linearReg_model.pkl

