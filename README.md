
# Online Food Delivery Prediction Application:

An Application to predict whether a customer will Order food online.
## Description:

The application can predict whether the customer will order food online.
The Model will analyse the parameters provided by user and predict whether customer will order food again.

## Detailed Description:

## DataSets:

**Datasets:**
- Input Features:
- Age: The age of the customer
- Gender: The Gender of customer
- Marital Status: marital status of the customer
- Occupation: occupation of the customer
- Monthly Income: monthly income of the customer
- Educational Qualification: educational qualification of the customer
- Family Size: family size of the customer
- Latitude & Longitude: latitude and longitude of the location of the customer
- Pin Code: pin code of the residence of the customer
- Feedback: Feedback of the last order (Positive or Negative)
**Output Feature:**
- Output: did the customer order again (Output)
## Methods Used:
- Exploratory Data Analysis (EDA)
- Data Collection
- Data Cleaning
- Feature Engineering
- Modelling
- Render application online
## Technologies used
- Python
- Machine Learning
- Pandas, matplotlib, plotly
- seaborn, Google Colab
- flask, flasgger
## ML Algorithms Used
- RandomForestClassifier
- LogisticRegression
- AdaBoostClassifier
- KNeighborsClassifier
- GaussianNB
## Performance Evaluation

Below are the evaluation metrics used for calculating the Performance of model:
- Confusion Matrix
- Accuracy Score
- ROC Accuracy Score

## Conclusion

We select the best model for prediction the output, based on model performance for the datasets provided.

## Application

Once we select the best model, we use FLASK to host the application.
The application takes various input from user and predicts whether the customer will order food again.
