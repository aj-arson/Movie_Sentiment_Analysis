# Movie Sentiment Analysis
In this project I have used IMDB Movie reviews dataset to train a logistic regression model and predict the sentiment of the review based on the review of the viewer. The dataset is downloaded from the Kaggle website(https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews). I have provided the kaggle link for the data for reference.
In this project I have used Machine Learning Pipeline to do the data preprocessing, tfidf vectorization and finally fitting a Logistic Regression model. Using pipeline in machine learning is time saving and it helps us to automate certain tasks that we do multiple times to achieve our goals. 
I created a custom Preprocessor class and inherited BaseEstimator class and TransformerMixin class, And used transfrom method to perform data cleaning by removing unwated symbols, spaces etc.
Then I created the pipeline with Preprocessor step, then TDIDF vectorization step and finally the model fitting step.
Overall this project gave me basic idea about ML pipelines, NLP techniques and regex.
I was able to get the below accuracies:

# Training Accuracy:
![image](https://github.com/user-attachments/assets/3d6cf353-97f0-4b1e-80f3-24e34871e069)

# Validation Accuracy:
![image](https://github.com/user-attachments/assets/0f534e31-0057-4f25-9d2e-88fef79b6575)

# Testing Accuracy:
![image](https://github.com/user-attachments/assets/0bd03e8e-fc34-423f-b9ec-fd03a57eff2a)

