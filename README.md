# Natural Language Processing (NLP) Tasks 



**Student Name:** Hallig, Siera Q.

**Section:** BSCS 3B - IS

**Subject Code:** CSEL302 

**Course Title:** Introduction in Intelligent Systems


# Introduction to Document Classification (Overview & Importance) 

Document classification is a fundamental task in Natural Language Processing (NLP) that involves automatically categorizing text documents into predefined labels or classes. It helps manage and make sense of large volumes of unstructured text data, such as emails, news articles, or customer reviews. This process plays an essential role in various real-world applications, like spam detection, topic labeling, sentiment analysis, and support ticket routing. By automating classification, organizations can improve efficiency, enhance search capabilities, and deliver more personalized experiences to users.

For the practical implementation, I used the 20 Newsgroups dataset, which contains documents from 20 different online discussion topics. I began by preprocessing the text, removing stopwords and punctuation to clean the data. I then transformed the documents into numerical features using TF-IDF vectorization, capturing the importance of each word relative to each document. A Multinomial Naive Bayes classifier was trained on the processed data, chosen for its simplicity and effectiveness in text-based tasks. After training, the model achieved approximately 67% accuracy on the test data. Evaluation was performed using a classification report and a confusion matrix, helping identify where the model performed well and where improvements could be made, especially in classes with overlapping vocabulary.

## Table of Contents
*   [Code implementation](Code_implementation/Document_Classification.ipynb)
*   [Dataset Used](Dataset/20_newsgroups.tar.gz)
*   [Presentation slides](Presentation/Introduction_to_Document_Classification.pptx)
*   [Video Presentation](Presentation/Introduction_to_Document_Classification_(Video_Presentation).mp4)
