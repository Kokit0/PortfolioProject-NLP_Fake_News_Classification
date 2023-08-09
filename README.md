# Fake-News-Classification

![Fake News](image.png)
### Problem Statement: 
We consume news through several mediums throughout the day in our daily routine, but sometimes it becomes difficult to decide which one is fake and which one is authentic. Our job is to create a model which predicts whether a given news is real or fake.

This project discusses the importance and applications of natural language processing (NLP), specifically in the context of classifying fake news. It covers various pre-processing techniques such as tokenization, stemming, and lemmatization, before moving on to vectorization using TF-IDF. The project also demonstrates the use of a class-based approach for model evaluation and prediction.

![WordcloudFakeNewsV3](https://github.com/Kokit0/PortfolioProject-NLP_Fake_News_Classification/assets/86896405/534b21f2-3db5-4c30-91aa-2590d6536343)

### Project Flow:
1. Problem Statement
2. Data Gathering
3. Data Preprocessing : Here we perform some operation on data
   - Tokenization
   - Lower Case
   - Stopwords 
   - Lemmatization / Stemming

5. Vectorization (Convert Text data into the Vector):
   - Bag Of Words (CountVectorizer)
   - TF-IDF

6. Model Building :
   - Model Object Initialization
   - Train and Test Model

7.  Model Evaluation :
      - Accuracy Score
      - Confusition Matrix
      - Classification Report

7. Model Deployment

8. Prediction on Client Data

## Tech Stack Used
1. Python
2. NLP
3. Machine Learning Algorithms

 **SUMMARY**
    
This NLP project aims to perform fake news classification using natural language processing techniques. The main goals and products to be obtained during the process are:
    
1. **Introduction to NLP and its Applications:**
    - Understand the importance of NLP and its applications, including translation, summarization, named entity recognition, speech recognition, relation extraction, and topic segmentation.
    - Recognize the significance of NLP in analyzing unstructured text data, particularly fake news classification.
2. **Data Analysis and Preprocessing:**
    - Read a CSV file containing news data and analyze its structure using the `info()` function.
    - Handle data imbalance in the target column (label) for better classification performance.
    - Preprocess the text data by tokenization, converting text to lowercase, and removing stop words.
3. **Stemming and Lemmatization:**
    - Understand the difference between stemming and lemmatization in NLP.
    - Choose an appropriate technique for the task at hand and implement it to reduce words to their root or lemma form.
4. **Data Vectorization and Model Training:**
    - Vectorize the preprocessed text data using TF-IDF vectorization.
    - Create the target variable (Y label) for the classification model.
    - Split the data into training and testing sets using `train_test_split` from `sklearn.model_selection`.
5. **Model Evaluation:**
    - Evaluate the accuracy of the model on the testing dataset using the `accuracy_score` function.
    - Create an evaluation class to check accuracy on both training and testing datasets.
    - Generate a confusion matrix and classification report to assess the model's performance.
6. **Preprocessing and Prediction Classes:**
    - Develop a preprocessing class to preprocess user input data for classification.
    - Create a prediction class to convert preprocessed data into numeric representations.
    - Utilize TF-IDF to convert the preprocessed data into numeric vectors for input to the classification model.
    
The ultimate outcome of this NLP project is a robust fake news classification model that can accurately differentiate between genuine and fake news articles. The project demonstrates key concepts of NLP, data preprocessing, model evaluation, and encapsulation into reusable classes for easy integration into other applications or systems.
