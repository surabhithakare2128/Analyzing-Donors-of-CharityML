## Analyzing Customers

**Ever thought of analyzing your customers? Specifically, what makes people your potential customers?**

This is exactly what I tried to explore in this project.

Knowing people earning above $50,000 annually are most likely to donate to CharityML, I applied feature importance to discover the most relevant features for predicting if an individual makes at most or above $50,000 

The dataset has been taken from https://archive.ics.uci.edu/ml/datasets/Census+Income

Folllowing steps are carried out to come to a conclusion:
- Exploring data
- Preparing data
- Splittind data into train and test set
- Applying 3 different supervised learning model
- Selecting best model and tuning it
- Applying feature importance
- Concluding

For this problem, I applied AdaBoost, Random Forest and SVM. 
After evaluating every model, I selected AdaBoost which provided an accuracy of 84% because even though AdaBoost Classifier takes slighty more time to train as compared to Random Forest, the difference is trivial. But it overtakes Random Forest and SVC when it comes to Accuracy and F-score. 
So AdaBoost Classifier is the most appropriate model for this data.

Results communicated the driving features are age, #working hours, capital gain, marital status, and education       

Enjoy reading. Happy learning! :)

If you have any doubts or suggestions, please feel free to contact me at st638@njit.edu
