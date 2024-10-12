# NLP - Text Emotion Classification

![emotions](https://github.com/user-attachments/assets/03fa76db-ad8e-4253-870e-833facbad259)  <br>
## Introduction
Emotion detection in text involves recognizing the feelings expressed in written content. This can be tricky since emotions are often conveyed in subtle ways. Natural language processing (NLP) techniques can help analyze the text and identify these emotions. <br>     
The goal of this project is to train machine learning models that uses NLP to accurately detect emotions in text. These models can be useful for tasks like sentiment analysis, customer feedback assessment, and monitoring social media. It will be trained on a dataset of comments (text) labeled with the emotions expressed.
<br>

## Dataset
The data used in this project contains text data labeled with one of three emotions: anger, fear, and joy. The dataset contains a total of 5937 rows.
> Dataset : https://drive.google.com/file/d/1HWczIICsMpaL8EJyu48ZvRFcXx3_pcnb/view?usp=drive_link
  <br><br>

## Project Work flow      
This project involves the following steps:<br>
1. **Preprocessing the text data**: the text data is preprocessed by removing stop words, punctuation and converting all text to lowercase.
2. **Model training**: machine learning models are trained on the extracted features to predict the emotions expressed in the text data. The models used for this project are `Naive Bayes` (MultinomialNB) and `SVM` (LinearSVC)
3. **Model evaluation**: The trained models are evaluated on the test data to measure its accuracy in detecting emotions in text data.        
<br><br>

## Conclusion
The **LinearSVC** achieved an accuracy of 94% and **MultinomialNB** achieved an accuracy of 90% on the data.
