# Master of Science Business Analytics - Capstone - Home Credit Default Risk Prediction

## Business Problem

Many people struggle to get loans due to insufficient or non-existent credit histories. Unfortunately, this population is often taken advantage of by untrustworthy lenders. Home Credit strives to broaden financial inclusion for the unbanked population by providing a positive and safe borrowing experience. To ensure this underserved population has a favorable loan experience, Home Credit uses various alternative data--including telco and transactional information--to predict their clients' repayment abilities.

## Solution 

These notebooks will examine the Home Credit default risk Exploration Data Analysis with data cleaning, explorations, hypothesis questions, and visualizations.

In this EDA, we will use the Application (Train/ Test) dataset and the Bureau dataset to perform the hypothesis test and clean the datasets along with transactional data analysis with the Bureau dataset. Depending on the hypothesis questions, we will also visualize some plots, like whether men or women tend to default more, whether income or credit sum affects the default, and whether the client's region, occupation, and family structure affect the default rate.

Subsequently, we develop predictive models using the cleaned data to assess credit default risk. We focus on the target variable and employ different machine learning models, calculating relevant metrics like accuracy and ROC values.

The objective is to identify the best-performing model based on Kaggle scores. We start with Logistic regression and then explore penalized regression, specifically LASSO, due to collinearity issues. Additionally, we examine Random Forest, XGBoost, and Light XGBoost to assess their effectiveness in predicting credit default risk.

## Contributution

Primary contributor to the project, started the EDA on the data by cleaning and imputing the missing values, exploring the data, and explaining the data with hypothesis testing and visualizations. Careful considerations were made on the hyperparameter tuning by identifying the right combination for each model to achieve optimal predictive accuracy. Understand the business requirements and establish the solutions by providing and interpreting the model confusion matrix. Implemented the Light Gradient Boosting, prepared a notebook write-up, and evaluated the models.

## Business Value



## Challenges

**Missing values** - Dealing with missing values presents a challenge, as the decision between using measures such as mean, median, or mode and treating NAs as a distinct category like 'None' needs careful consideration for each column with missing data.
**Sampling method** - Addressing class imbalance requires careful selection of sampling methods, such as under-sampling or utilizing SMOTE, to enhance the modeling process and ensure a more balanced representation of classes in the dataset.
**Model selection** - The challenge in model selection arises from high correlations between predictors and the risk of multicollinearity. Careful consideration is needed to choose models that can handle these challenges effectively.
**Hyperparameter tuning** - Tuning the hyperparameters for the models so that the dataset fits well with the model and gives us the best results. This involves adjusting parameters to achieve the best fit, and the challenge lies in identifying the right combination for each model to achieve optimal predictive accuracy.

## Lessons Learned


**[EDA Notebook](https://github.com/AbhiramMannam/Capstone-Home-Credit-Default/blob/main/Capstone_Project_EDA_Abhiram.ipynb)**

**[Modeling Notebook](https://github.com/AbhiramMannam/Capstone-Home-Credit-Default/edit/main/README.md#:~:text=Capstone_Project_Modelling)**

**[Presentation](https://github.com/AbhiramMannam/Capstone-Home-Credit-Default/edit/main/README.md#:~:text=Capstone-,Presentation,-.pptx)**

## Link to Presentation
