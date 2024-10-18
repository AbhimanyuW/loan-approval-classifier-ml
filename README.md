# Loan Approval Classifier - Machine Learning 

## Project Goal:
The goal of this project is to develop a predictive model for loan approval classification by following a comprehensive data science workflow.
The dataset used in this project is available at: https://www.datacamp.com/datalab/datasets/dataset-python-loans


Here is the list of tasks that we are have followed in this project:

## 1. Data Cleaning and Preprocessing: 
Handling missing values, converting categorical variables into numeric variables, scaling/normalizing the data, and handling any outliers or anomalies in the data. In we have addressed the class imbalance issue by either oversampling the minority class (loans that are not fully paid) or undersampling the majority class (loans that are fully paid).

## 2. Exploratory Data Analysis (EDA):
Exploring the dataset to gain insights into the data, such as distributions of variables, correlations between variables, and identifying any patterns in the data.

## 3. Feature Engineering: 
Creating new features or transforming existing features to improve the predictive power of the model. 

## 4. Model Selection: 
Tried several models, such as decision trees, random forests, logistic regression, or support vector machines (SVM). 

## 5. Model Training and Evaluation: 
Training the selected model on the data and evaluating its performance using various metrics such as accuracy, precision, recall, and F1 score. 

## 6. Hyperparameter Tuning:
Fine-tuning the hyperparameters of the selected model to improve its performance. 

## 7. Creating the web app using Gradio: 
After selecting the best performing model, we have created a web app using Gradio. Due to time constraints, we haven't deployed the web app, but are using localhost.


To deploy your own version of the web app, you can use the "app.py" file, but do make sure that you're using the correct versions of the libraries used in the project.
Once you run the "loan_approval_classifier.ipynb" notebook in an environment of your choice (Google Colab/Jupyter Notebook), you will be able to save the trained model i.e "loan_classifier.joblib", which hasn't been included in this repository due to size limitations. 
Once your server starts running, it should look something like this:

![image](https://github.com/user-attachments/assets/93f70d86-d4c7-426c-86c4-ffc875664549)




Happy training and may your algorithms always converge!



