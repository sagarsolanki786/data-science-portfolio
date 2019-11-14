# Natural Language Processing - Building a Spam classifier using nltk library in python.
### DataSet used from UCI Machine Learning Repository:
[View the Dataset here](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection).

This dataset contains 5568 text messages along with their label as ham or spam.

Steps used to create this Spam classifier:
1. Import the data and perform feature engineering to create new features such as length of the text message and the percentage of punctuation in the text.
2. Cleaned the data, removed stopwords and punctuation for a better machine learning model creation.
3. Performed text vectorization using Count Vectorizer and TF-IDF Vectorizer.
4. Create and applied Random Forest and Gradient Boosting models.
5. Compared the models using 5 fold cross validation.
5. Created extensive GridSearch for hyperparameter tuning to identify best model parameters for both the models based on Precision, Recall and Accurary of the model.
6. Used [sklearn GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html) to perform hyperparameter tuning and compared the results using cross validation.
7. Compared both the models again using the best parameters based on precision, recall, accuray, fit time and predict time.
