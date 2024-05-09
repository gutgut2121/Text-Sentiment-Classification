# Text-Sentiment-Classification

This project focuses on the classification of sentiment on text. The categories of the dataset includes ELECTRONICS, BOOKS, CLOTHING, GROCERY and PATIO, while the sentiments are POSITIVE, NEGATIVE, and NEUTRAL. The workflow of the project involves data exploration, data preparation, model tuning with grid search, evaluating the model using test data, and drawing conclusions based on the confusion matrix.

#### Workflow

Data Exploration: The initial step is to explore the dataset to gain insights into the text sentiment classification problem. This involves loading the dataset and analyzing its structure and features.

Data Loading and Preparation: This includes preprocessing the text data by transforming the text into a numerical representation suitable for machine learning algorithms.

Tuning Model: To achieve optimal performance, the model is tuned using grid search. 

Evaluate Model: The model is evaluated using a separate test dataset and summarized by a confusion matrix. The diagonal elements of the confusion matrix represent the number of correct predictions, providing insights into the model's accuracy for each sentiment category. 

#### Conclusion
Based on the analysis of the confusion matrix, it can be concluded that the text sentiment classification model has performed well. The high number of correct predictions on the diagonal of the confusion matrix indicates that the model has successfully classified the text sentiments across different categories.
