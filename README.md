![titanic png](https://github.com/user-attachments/assets/6e64e515-6519-4c17-94a0-edcac6b2699c)


# Titanic Survival Prediction Using Decision Tree Algorithm

---------------------------------------------------


## **<span style="color:green">Project Description</span>**

The Titanic dataset, sourced from **Kaggle**, is a classic machine learning problem. It challenges us to predict whether a passenger survived or perished during the Titanic shipwreck based on a variety of features such as their age, sex, ticket class, and more. 

In this project, we use the **Decision Tree** algorithm to model the survival outcome of passengers. The model is trained on historical data, and it learns how features like passenger demographics and socio-economic status (e.g., gender, age, ticket class) affected their chances of survival. Our goal is to evaluate how well a decision tree can predict survival and explain its decision-making process.

You can **click the link below** to download the dataset:

[**Click to Download Titanic Dataset**](https://www.kaggle.com/c/titanic/data)

____________________________________________________

## Dataset
The dataset, sourced from Kaggle, consists of the following features:

- `PassengerId`: Unique identifier for each passenger
- `Pclass`: Ticket class (1st, 2nd, or 3rd)
- `Name`: Passenger name
- `Sex`: Gender of the passenger
- `Age`: Age of the passenger
- `SibSp`: Number of siblings/spouses aboard the Titanic
- `Parch`: Number of parents/children aboard the Titanic
- `Ticket`: Ticket number
- `Fare`: Passenger fare
- `Cabin`: Cabin number
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
- `Survived`: Target variable (0 = Did not survive, 1 = Survived)
___________________________________

## **<span style="color:orange">Understanding the Decision Tree Algorithm</span>**

### **1. What is a Decision Tree?**
A **Decision Tree** is a supervised learning algorithm commonly used for **classification** and **regression** tasks. It builds a model by making sequential decisions to split the data based on the most informative features. The tree is made up of nodes (which represent decisions based on feature values), branches (outcomes of decisions), and leaf nodes (final predictions). It is a simple yet powerful algorithm for making human-interpretable decisions.

### **2. How Does It Work?**
- **Root Node**: The top node of the tree where the first split happens based on the most important feature.
- **Internal Nodes**: Each node in the tree represents a decision based on a feature and its value.
- **Leaf Nodes**: The endpoints of the tree, which provide the final prediction (e.g., 'Survived' or 'Did Not Survive').
- **Splitting**: The algorithm splits the data based on criteria like **Gini Impurity** or **Entropy**, selecting the feature that provides the most information.
- **Recursive Splitting**: The tree continues splitting data at each node until stopping conditions are met (e.g., maximum depth, minimum samples at a node).

---

## **<span style="color:purple">Why Use Decision Tree for Titanic Dataset?</span>**

- **Human Interpretability**: Decision Trees allow us to visualize the decision-making process, which is especially useful for interpreting how various factors, such as **age**, **sex**, and **class**, influenced survival on the Titanic.
- **Non-linear Relationships**: The decision tree can handle non-linear relationships between features, such as the interaction between **ticket class** and **age** in determining survival chances.
- **Handling Mixed Data Types**: The Titanic dataset contains both categorical and numerical variables, and Decision Trees are well-suited to handle such mixed data.

---

## **<span style="color:blue">Advantages of Decision Trees</span>**
- **Interpretability**: Each decision in the model is transparent and easy to understand, making it suitable for situations where model explainability is important.
- **No Need for Scaling**: Unlike other algorithms, Decision Trees do not require feature scaling or normalization.
- **Works with Categorical Data**: Decision Trees naturally handle both categorical and continuous data, which is useful for datasets like Titanic.

---

## **<span style="color:red">Limitations of Decision Trees</span>**
- **Overfitting**: Decision Trees tend to overfit, especially when they become deep. This can result in poor generalization to new data. Pruning techniques or using ensemble methods like **Random Forest** can mitigate this issue.
- **High Variance**: Small changes in the training data can lead to drastically different trees, making the model unstable.

---

## **<span style="color:teal">Project Workflow</span>**
1. **Data Preprocessing**: Cleaning and transforming the Titanic dataset (e.g., handling missing values, encoding categorical variables).
2. **Model Training**: Implementing the Decision Tree classifier and training it on the Titanic dataset.
3. **Model Evaluation**: Evaluating the performance of the model using accuracy, precision, recall, and F1-score.
4. **Model Visualization**: Visualizing the decision tree to interpret the decisions made by the model.



## Results
The Decision Tree classifier achieved an accuracy score of `your_accuracy` on the test set. Other key metrics include:

- **Precision**:
- **Recall**: 
- **Confusion Matrix**: 

