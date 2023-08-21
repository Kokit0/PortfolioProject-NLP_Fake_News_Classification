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

---

## Wrapping Up
Congratulations, we've reached the end of this iteration of the project! I hope you've found this exploration into "NLP and Fake News Classification" as fascinating and rewarding as I have. While we're closing this chapter for now, I'm excited to share with you my plans for the future of this project.

### What's Next?
In the near future, I'm committed to taking this project to the next level. Here's a sneak peek at what's on the horizon:

### Expanding Visual Materials
I have exciting plans to incorporate more captivating visualizations and graphs to make the insights even more accessible and engaging. Data storytelling is a powerful way to convey complex ideas, and I'm eager to explore this avenue further.

### Version 4.0 and Beyond
As technology and techniques evolve, so will this project. I'm already brainstorming ideas for a Version 4.0 that will dive even deeper into "NLP and Fake News Classification". From refining algorithms to exploring new datasets, there's always more to uncover.

### Missed Opportunities
During this project, I encountered some intriguing avenues that I didn't have the chance to fully explore. As I move forward, I'll be keeping these alternative paths in mind for future iterations:

- Opportunity 1: I noticed that I could have exposed the dataset in a more graphic manner, showcasing its composition and possibly evaluating its completeness. However, given that the source was predefined, I had to decide between sticking to what was available or handcrafting it myself. Since the purpose of this project was to demonstrate a working model with a sound methodology, I couldn't delve deeper. This is an area I'm excited to revisit.

- Opportunity 2: While analyzing other approaches out there, I came across more streamlined methods that are more efficient and have reusability for other datasets, along with graphical outputs that better expose patterns. At the moment of developing this project, I had limited understanding of what it would become until I could gather everything and outline the workflow. Exploring these efficient techniques warrants further investigation and learning from my own experiences.

I believe that these aren't missed opportunities but rather different paths. I'm proud of the direction I took and the fair share I explored, reflecting the growth and evolution of my understanding.

### Stay Engaged!
I invite you to keep an eye out for updates to this project. Feel free to follow me on [Medium](https://medium.com/@jorge.amaya.s) or on my soon-to-be-updated [GetOnBoard](https://www.getonbrd.com/p/jorge-amaya-s) for notifications about new releases and announcements. Your feedback and suggestions are invaluable, and I'm excited to continue this journey together.

Thank you for joining me on this adventure. Until next time!



*Happy Data Torturing!,*

**Jorge 'Kokke' Amaya**


---

