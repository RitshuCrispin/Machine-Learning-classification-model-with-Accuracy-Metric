# Machine-Learning-classification-model-with-Accuracy-Metric
Machine Learning classification model that analyzes customer behavior to recommend a telephone service plan. To find the best model, the accuracy metric is calculated in different hyper parameters in the Decision Tree Classifier, Random Forest Classifier and Logistic Regression classification models.

# Project description
Mobile company Megaline is not happy to see that many of its customers are using legacy plans. They want to develop a model that can analyze customer behavior and recommend one of Megaline's new plans: Smart or Ultra.

You have access to behavioral data for subscribers who have already switched to the new plans (from the Statistical Data Analysis course project). For this classification task you must create a model that chooses the correct plan. Since you have already done the step of processing the data, you can jump right into creating the model.

# Target

Develop a model that can analyze customer behavior and recommend one of the new Megaline plans: Smart or Ultra. The model must be as *accurate* as possible. In this project, the *accuracy* threshold is 0.75. We will use the dataset to check *accuracy*.

# Conclusions 
 
1. In the initialization stage of the project, the data delivered was reviewed where it was observed that the data was ready without needing any type of processing to be carried out.
2. Next, the data was prepared by identifying the variables: features and target.
3. After that, the data was segmented into different sets with 3 sizes in order to have 3 datasets: training, validation and testing; The distribution was 0.6, 0.2 and 0.2, respectively.
4. 3 classification models were trained and tested to find the model with the greatest possible accuracy, the test results were as follows:
- Decision trees: 78.85% accuracy.
- Randomness forests: 78.7% accuracy.
- Logistic regression: 69% accuracy.
5. Finally, the model with the greatest accuracy identified was: **Decision trees.**
