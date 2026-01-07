# **Self-Study Preparation Guide: Supervised Learning Fundamentals**

**⏳ Estimated Prep Time:** 45–60 minutes

Welcome to our flipped-classroom session, where you'll review foundational concepts beforehand to maximize our time for hands-on coding and debugging. This pre-study focuses on mastering three pillars of Supervised Learning: **Linear Regression**, **Logistic Regression**, and **K-Nearest Neighbors (K-NN)**.

By exploring these notebooks now, you will come to class ready to tackle real-world predictive modeling challenges, rather than spending our live time on basic syntax and theory.

## **⚡ Your Self-Study Tasks**

Please complete the following activities before our session.

### **📝 Task 1: Interpreting Linear Regression Models (20 Minutes)**

**Activity:** Open and review the [`part_1_supervised_learning.ipynb`](./notebooks/part_1_supervised_learning.ipynb) notebook. Read through the mathematical foundations (Cost Function, MSE, $R^2$) and compare the implementation styles of **Scikit-Learn** versus **Statsmodels**.

**Focus your attention on these key components:**

1. **The Equation:** How independent variables ($X$) relate to the dependent variable ($Y$).  
2. **Evaluation Metrics:** The difference between Mean Squared Error (MSE) and R-squared ($R^2$).  
3. **Library Comparison:** How `statsmodels` provides detailed statistical summaries compared to the streamlined API of `sklearn`.

### **📝 Task 2: The Logic of Logistic Regression (20 Minutes)**

**Activity:** Review the [`part_2_supervised_learning.ipynb`](./notebooks/part_2_supervised_learning.ipynb) notebook. Focus on how we adapt regression techniques to solve **Classification** problems (predicting categories like 0 or 1).

**Focus your attention on these key components:**

1. **The Sigmoid Function:** How it squashes linear output into a probability between 0 and 1\.  
2. **Odds vs. Probability:** Understanding the math behind the decision boundary.  
3. **Decision Boundary:** Visualizing how the model separates different classes (e.g., the Iris flower types).

**Guiding Questions:**

* Why is a straight line usually a poor choice for predicting a binary outcome (like "Diabetes: Yes/No")? 
* In the code cells, how do we evaluate the performance of a classification model differently than a regression model? (Hint: Look for `accuracy_score`).

### **📝 Task 3: K-Nearest Neighbors (K-NN) and Hyperparameters (20 Minutes)**

**Activity:** Skim through the [`part_3_supervised_learning.ipynb`](./notebooks/part_3_supervised_learning.ipynb) notebook. Observe how K-NN uses distance metrics to make predictions and how it differs from the equation-based models in Tasks 1 and 2\.

**Focus your attention on these key components:**

1. **Distance Metrics:** How Euclidean distance determines "closeness."  
2. **The 'k' Parameter:** The trade-off between a small 'k' (sensitive to noise) and a large 'k' (over-smoothed).  
3. **Regression vs. Classification:** How K-NN handles voting for categories versus averaging for numbers.

## **🙌🏻 Active Engagement Strategies**

To deepen your retention, try one of the following while you review:

* **Concept Comparison:** Sketch a simple table comparing **Linear Regression** vs. **Logistic Regression**. Columns might include: *Target Variable Type (Continuous/Categorical)*, *Key Function (Linear/Sigmoid)*, and *Primary Metric (MSE/Accuracy)*.  
* **Scenario Matching:** Think of a problem in your current workplace. Would you solve it using Regression (predicting a number) or Classification (predicting a category)? Which algorithm from the reading would you try first?

## **📖 Additional Reading Material (Optional)**

* [Introduction to Machine Learning](https://medium.com/data-science/introduction-to-machine-learning-for-beginners-eed6024fdb08)
* [Scikit-Learn User Guide: Supervised Learning](https://scikit-learn.org/stable/supervised_learning.html)

### **🙋🏻‍♂️ See you in the session\!**

