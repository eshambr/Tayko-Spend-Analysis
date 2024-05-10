# In-Depth-Analysis-of-Expenditure-Trends-at-Tayko-Software-Using-Logistic-Regression-and-NN-models

# Problem Statement

Tayko Software, a firm specializing in games and educational software, seeks to predict customer spending amounts following a recent catalog revision and mailing, which resulted in 2000 purchases. By analyzing customer data including purchase frequency, last update interval, online order behavior, gender, and residential status, the objective is to develop predictive models using logistic regression and neural networks to accurately forecast the spending amount of purchasing customers.

# Approach

The analysis began with data preparation, selecting and renaming relevant features from Tayko Software’s catalog mailing data. Exploratory data analysis (EDA) included examining categorical variables by calculating and visualizing average spending, and analyzing continuous predictors through scatter plots. Logistic regression and neural network models were developed to predict spending amounts, capturing both linear and complex relationships. Model performance was evaluated using accuracy metrics and visual comparisons of predicted versus actual spending.

# Findings

The analysis revealed a linear relationship between customer spending and purchase frequency, and a decrease in spending with increased days since the last update. Logistic regression and neural network models were developed, with the logistic regression model performing better because of it's RMSE, R Squared and MAE scores. Key predictors of spending included purchase frequency, last update days, online order status, gender, and residential status. These insights suggest targeting frequent buyers, engaging inactive customers, and utilizing predictive models for tailored marketing strategies, with a focus on the superior predictive accuracy of the neural network model. Visualizations provided clear insights to support data-driven decisions and enhanced reporting.
