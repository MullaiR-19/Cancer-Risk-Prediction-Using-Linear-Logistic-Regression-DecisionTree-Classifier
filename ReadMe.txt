Cancer Risk Prediction Using Linear, Logistic Regression & DecisionTree Classifier

Predicting cancer risk level is a crucial task in the medical field as early detection and prevention can greatly improve a patient's chances of survival. 

In this project, we aim to predict cancer risk level using two different regression models: Linear Regression and Logistic Regression.

Linear Regression is a statistical model that aims to establish a linear relationship between the independent variables and the dependent variable. 

In the context of cancer risk level prediction, the independent variables may include factors such as age, gender, family history of cancer, lifestyle habits, and environmental factors. 
By analyzing the relationship between these variables and the dependent variable (cancer risk level), we can create a linear regression model that predicts a patient's risk level based on their personal information.

Logistic Regression, on the other hand, is a statistical model used to analyze the relationship between a dependent variable and one or more independent variables. 
In the context of cancer risk level prediction, the dependent variable is binary (cancer or no cancer) and the independent variables are the same as those used in Linear Regression. 
By analyzing the relationship between these variables, we can create a logistic regression model that predicts a patient's likelihood of developing cancer.

Both Linear Regression and Logistic Regression have their own advantages and limitations. 
Linear Regression is best suited for continuous dependent variables, while Logistic Regression is best suited for binary dependent variables.
However, both models can be used to make accurate predictions for cancer risk level based on the patient's personal information.

By making the code available on GitHub, other researchers and medical professionals can use and build upon our work to improve cancer risk level prediction and ultimately improve patient outcomes.

Note: 
In the jupyter notebook file I have started with SVC and KMeans model and both got accuracy of 100% which means the model is overfitting so i decided to use Regression models instred of Classifcation eventhough the out put is 1 or 2 or 3.

Regression working good with this dataset and "Logistric Regression" have high accuracy upto 98% followed by SVR with 92%

Classification algorithams K-Means have <50% acc so the model is failed due to under fitting,
DecissionTree using gini critation with 2 features have 97% of accuracy which can predict LOW(1) and High(3) condtion.
