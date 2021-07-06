### Amazon.com-Employee-Access-Challenge

Kaggle competition predicting an employee's access needs, given his/her job role.
Competition Link: https://www.kaggle.com/c/amazon-employee-access-challenge/

#### Problem statement
> When an employee at any company starts work, they first need to obtain the computer access necessary to fulfill their role. This access may allow an employee to read/manipulate resources through various applications or web portals. It is assumed that employees fulfilling the functions of a given role will access the same or similar resources. It is often the case that employees figure out the access they need as they encounter roadblocks during their daily work (e.g. not able to log into a reporting portal). A knowledgeable supervisor then takes time to manually grant the needed access in order to overcome access obstacles. As employees move throughout a company, this access discovery/recovery cycle wastes a nontrivial amount of time and money.

>There is a considerable amount of data regarding an employee’s role within an organization and the resources to which they have access. Given the data related to current employees and their provisioned access, models can be built that automatically determine access privileges as employees enter and leave roles within a company. These auto-access models seek to minimize the human involvement required to grant or revoke employee access.

#### Project Details
- Exploratory data analysis and visualization
- Preprocessing with encoding categorical features
- dealing with imbalanced data using SMOTE
- Feature engineering and creating more features
- Evaluating the models using ROC Curve
- Finding the best parameters using GridSearchCV

#### Models
The models are trained with:
- KNeighborsClassifier
- Support Vector Machine
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classification

The best model XGBoost has achieved **95,25%** accuracy on the test set and auc roc score equals **0.77**.