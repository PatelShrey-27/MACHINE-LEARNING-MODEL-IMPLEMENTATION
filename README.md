# MACHINE-LEARNING-MODEL-IMPLEMENTATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SHREYKUMAR SANDIPKUMAR PATEL

*INTERN ID*: CT04DL1307

*DOMAIN*: PYTHON PROGAMMING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION*:
              Task 4: Building a Machine Learning Classification Model Using Scikit-learn
For the final task of my internship project, I was asked to develop a machine learning classification model using Python’s scikit-learn library. The goal of this project was to apply the entire machine learning pipeline — from data preprocessing to model training and evaluation — in a real-world scenario. I chose to build a spam detection model, which can automatically classify messages as either “spam” or “ham” (not spam), using a dataset of labeled SMS messages.

Data Preprocessing
The process began with loading and preparing the dataset. I used the "SMS Spam Collection Dataset," a popular dataset consisting of thousands of labeled SMS messages. I read the data using pandas, assigning appropriate column names to make the dataset more understandable.

Next, I carried out text cleaning and preprocessing. Since machine learning algorithms cannot directly interpret text, I applied several techniques to convert raw text into a usable format. This included:

-> Lowercasing all messages

-> Removing punctuation

-> Tokenizing the words

-> Removing stopwords (common words like “and,” “the,” etc.)

-> Applying lemmatization to reduce words to their base forms

These steps are essential in NLP (Natural Language Processing) to ensure consistent and meaningful input for the model.

Feature Extraction
After preprocessing the text data, I used TfidfVectorizer (Term Frequency-Inverse Document Frequency) to convert text into numerical features. This technique assigns weights to words based on their importance in a message compared to the entire dataset. It’s an effective method to represent textual data for classification problems.

Model Building and Training
Once the data was vectorized, I split it into training and testing sets using train_test_split. I chose the Multinomial Naive Bayes classifier, a widely used model for text classification due to its simplicity and effectiveness with word count features. I trained the model on the training dataset and used the test data to evaluate its performance.

Model Evaluation
I evaluated the model using various performance metrics such as:

-> Accuracy: Overall correctness of the model

-> Precision: How many predicted spams were actually spam

-> Recall: How many actual spam messages were correctly identified

-> F1-score: The harmonic mean of precision and recall

*OUTPUT*:

![model output](https://github.com/user-attachments/assets/43ed81e5-ef83-4e5b-b053-44092b2b8dfb)


