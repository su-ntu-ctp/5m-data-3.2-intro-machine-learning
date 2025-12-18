# **Self-Study Preparation Guide**

**⏳ Estimated Prep Time:** 45–60 minutes

Welcome to our flipped-classroom session, where you'll review foundational concepts beforehand to maximize our time for hands-on coding and debugging. This pre-study focuses on **Supervised Learning**, specifically the mathematical intuition and practical implementation of Linear Regression, Logistic Regression, and K-Nearest Neighbors (K-NN). By mastering these basics now, you will be ready to build predictive models that solve real-world business problems—from forecasting sales to diagnosing medical conditions—during our live workshop.

## ⚡ Your Self-Study Tasks

Please complete the following activities before our session.

### 📝 Task 1: Decoding Linear Regression (20 Minutes)

**Activity:** Open the `supervised_learning_1_lesson.ipynb` notebook. Read the Markdown cells and code examples under the **"Linear Regression"** and **"Scikit-Learn Tutorial"** headers. Pay close attention to how the mathematical equation translates into Python code.

**Guiding Questions:**
* In the equation $Y = \beta_0 + \beta_1X_1 + \epsilon$, what do the coefficients ($\beta$) represent in a real-world context (e.g., predicting house prices)?
* Why do we split the data into `training` and `testing` sets before fitting the model? How does this prevent "overfitting"?
* Review the **Cost Function** section. Why is minimizing the "Mean Squared Error" (MSE) the primary goal during training?

### 📝 Task 2: From Numbers to Categories – Logistic Regression (20 Minutes)

**Activity:** Scroll to the **"Logistic Regression"** section in the notebook. Review how this model differs from linear regression, specifically regarding the **Sigmoid function** and the concept of **Log-Odds**.

**Guiding Questions:**
* Linear regression predicts continuous values (e.g., price). Logistic regression predicts binary classes (0 or 1). How does the **Sigmoid function** act as a bridge between these two concepts?
* Look at the "Statsmodels Tutorial" for the Pima Indians Diabetes dataset. How do you interpret a p-value in the summary table provided by `sm.Logit`?

### 📝 Task 3: The Logic of Neighbors (15 Minutes)

**Activity:** Skim the **"K-Nearest Neighbors (K-NN)"** section. Focus on the visualization of how the algorithm decides a class based on distance metrics.

**Guiding Questions:**
* The text mentions the trade-off in choosing the 'k' value. What happens to the model's sensitivity to noise if 'k' is too small?
* How does the **Euclidean Distance** formula relate to finding the "nearest" data points?

## 🙌🏻 Active Engagement Strategies

To deepen your retention and prepare for our live coding challenges, try one of the following:

* **Scenario Matching:** Look at the three models covered (Linear, Logistic, K-NN). If you were asked to predict *Customer Churn* (Yes/No), which model would you choose? What about predicting *Next Quarter's Revenue*?
* **"Code Commentary":** In the notebook, find the cell where `model.fit(X_train, y_train)` is called. Write a one-sentence explanation of what the computer is actually "learning" at that specific step.
* **Question Generation:** Write down 2 specific questions about *interpreting model performance* (e.g., R-squared or Accuracy Score) to ask during the live Q&A.

## 📖 Additional Reading Material

* [Introduction to Machine Learning](https://medium.com/data-science/introduction-to-machine-learning-for-beginners-eed6024fdb08)
* [Scikit-Learn User Guide: Supervised Learning](https://scikit-learn.org/stable/supervised_learning.html)

### 🙋🏻‍♂️ See you in the session!


