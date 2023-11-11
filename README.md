# Credit_DefaulterPrediction
Overview
This project aims to predict credit defaulters using machine learning techniques. The model is trained on historical data containing information about customers and their credit-related behaviors to identify patterns indicative of potential default.

Table of Contents
Background
Data
Modeling
Requirements
Usage
Results
Contributing
Background
Predicting credit defaulters is crucial for financial institutions to assess and manage the risk associated with lending. 
This project leverages machine learning algorithms to analyze historical data and build a predictive model for identifying customers who are likely to default on 
credit obligations.


Target Variable: Default Status (1 for defaulter, 0 for non-defaulter)
The data is split into training and testing sets to train and evaluate the model's performance.

Modeling
The project employs various machine learning algorithms, such as Logistic Regression, Random Forest, and Gradient Boosting, to build and train the predictive model. Evaluation metrics, including ROC-AUC, precision, recall, and accuracy, are used to assess the model's performance.

Requirements
Python 3.7
Required Python packages are listed in the requirements.txt file.
Install the dependencies using:

bash
Copy code
pip install -r requirements.txt
Usage
Clone the repository:
bash
Copy code
git clone https://github.com/Jyoti200/credit-defaulter-prediction.git
cd credit-defaulter-prediction
Install the required dependencies.

Run the Jupyter notebooks or Python scripts in the src directory to train the model and make predictions.

Results
The model's performance on the test set is as follows:

ROC-AUC: 0.80
Precision: 0.75
Recall: 0.70
Accuracy: 0.78
These results indicate the model's ability to distinguish between defaulters and non-defaulters.

Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.






