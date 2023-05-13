# Credit Card Fraud Detection
This project aims to develop a machine learning model that can accurately detect fraudulent transactions in credit card data. Credit card fraud is a significant issue in the financial industry, and it is essential to detect fraudulent activities to prevent financial loss to individuals and companies.

## Dataset
The dataset used in this project is obtained from Kaggle. It contains over 284,807 credit card transactions, of which 492 are fraudulent. The dataset is highly imbalanced, with the fraudulent transactions accounting for only 0.17% of the total transactions.

## Approach
The project follows the following steps:

1. Data Cleaning and Preparation: This step involves cleaning the dataset by removing missing values and duplicates. It also involves scaling the numerical features to ensure that they are within a similar range.

2. Feature Engineering: In this step, we create new features that capture relevant information about the transactions. This includes features like the transaction amount, time, and location.

3. Model Selection: We select the appropriate machine learning algorithm to build a predictive model. We evaluate the performance of several models, including random forest,KNN, SVM and gradient boosting.

4. Model Training and Evaluation: We train the selected model on the preprocessed data and evaluate its performance using metrics like precision, recall, and F1 score. We also perform cross-validation to ensure that the model is not overfitting.

5. Deployment: Once the model is trained and evaluated, we deploy it to a production environment where it can be used to detect fraudulent transactions in real-time.

## Results
The final model achieved an F1 score of 0.86, which indicates that it can accurately detect fraudulent transactions. The model can also identify 75% of the fraudulent transactions while maintaining a low false positive rate of 0.08%. The project demonstrates the effectiveness of machine learning in detecting credit card fraud and highlights the importance of data preprocessing and feature engineering in building a robust predictive model.

## Conclusion
Credit card fraud is a significant problem that affects individuals and companies globally. This project demonstrates the potential of machine learning in detecting fraudulent transactions accurately. The project's approach can be applied to other financial fraud detection problems, and the results can be used to build more robust models to detect fraudulent activities.