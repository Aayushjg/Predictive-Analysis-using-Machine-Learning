# Predictive-Analysis-using-Machine-Learning

COMPANY: CODTECH IT SOLUTIONS

NAME : AAYUSH JANGID

INTERN ID : CT08DG1246

DOMAIN : DATA ANALYSIS

DURATION : 8 WEEKS

MENTOR : NEELA SANTOSH

**For Task 2 of the internship, I worked on performing predictive analysis using machine learning techniques on a dataset simulating the historical Titanic passenger records. The objective of this task was to build a classification model that could predict whether a passenger survived the Titanic disaster based on features such as age, gender, class, fare, number of relatives aboard, and port of embarkation. This task not only enhanced my understanding of supervised machine learning workflows but also gave me hands-on experience with essential concepts like data preprocessing, feature encoding, model training, and evaluation.
To start with, I used a structured dataset named titanic_data.csv, which included passenger attributes such as Pclass, Sex, Age, SibSp, Parch, Fare, Embarked, and the target variable Survived. The target was binary: 1 indicating survival and 0 indicating non-survival. The initial phase involved importing the dataset into a pandas DataFrame and performing exploratory analysis to understand the nature and structure of the data. I then moved on to preprocessing, where I applied label encoding to categorical features such as Sex and Embarked, transforming them into numeric values suitable for machine learning algorithms. Additionally, any irrelevant features (like Name, Ticket, or Cabin) were removed to reduce dimensionality and noise.
Following the data preparation, I split the dataset into features (X) and target labels (y), and further divided it into training and testing sets using an 80/20 ratio. For the modeling part, I employed the Logistic Regression algorithm, which is widely used for binary classification problems. Logistic Regression not only provides a probability-based prediction but is also interpretable and efficient on small to moderately sized datasets. After training the model on the training set, I used it to make predictions on the test set. The performance of the model was evaluated using various metrics including accuracy, confusion matrix, and classification report (which included precision, recall, and F1-score). These metrics allowed me to assess how well the model generalized to unseen data.
Despite the relatively small dataset used for this demonstration (a sample of 10 records), the entire pipeline reflected a real-world supervised learning workflow. In a full-scale deployment, this same pipeline can be adapted to handle thousands of rows or be extended to use more complex models like Random Forest, Support Vector Machines, or even neural networks. Furthermore, I ensured that the code was clean, modular, and well-commented to enhance readability and maintainability.**

*OUTPUT*: <img width="1919" height="654" alt="Image" src="https://github.com/user-attachments/assets/9c213450-5857-40a6-9c1f-e3d48c8d1dc0" />
