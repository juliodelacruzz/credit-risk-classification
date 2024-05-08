# credit-risk-classification
Module 20 Challenge UCB Data Analyst Bootcamp 2024

**Credit Risk Analysis Report**
The purpose of this analysis is to provide a model that will identify customers who have good creditworthiness. It is important for creditors to identify who has good and bad credit in order to make just decisions on any transactions they may want to do. The data set provided allows us to create a logistic regression model, categorizing loan risk as binary (0 = healthy, 1 = not healthy) and the rest of the columns as features (income, loan size, interest rate, etc.)

**Why use a logistic regression model?**
Logistic regression performs well when our target, or desired outcome, is binary. Additionally, we want to see how a number of variables, or features, affects that outcome. Considering the nature of our dataset and the situation, logistic regression is a strong choice.

**Classification Report**

- Accuracy: 0.99 | This model is highly accurate, meaning this model has high overall correct predictions

- Precision: 1.00 for healthy | 0.84 for unhealthy | Measures the accuracy of the positive predictions made by the model. A higher precision means fewer false positives. The model performs well for both outcomes.

- Recall: 0.99 for healthy | 0.94 for unhealthy | Measures the model's ability to find all positive instances. A higher recall indicates means false negatives. The model again performs well for both outcomes.

- F1-Score 1.00 for healthy | 0.89 for unhealthy | A measure used to evaluate the performance of binary classification models, especially when the class distribution is uneven. It combines the model's precision and recall into a single metric by taking their harmonic 
 mean. Our model performs well in this aspect as well.

**Summary**

I would recommend this model to the company. This is due to the high levels of accuracy, precision, recall, and F1- scores provided by the classification report. One of the most important things that this model can provide is that it effectively mitigates the chance of a false negative, as seen in it's recall score. This will drastically help the company identify true high risk customers and make their decisions from there.


**Work Flow**

Using class examples, class recordings, and online resources, I was able to complete this module.
