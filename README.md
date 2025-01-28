# Offensive Language Identification SVM Model
Due to its side effects on the users’ mental, emotional, and health states, Offensive or Abusive Language is considered as the most damaging social media activity; which makes it a priority to limit its usage. This project aims to mitigate the spread of offensive language on the internet by developing a **robust Machine Learning Model**.

## Approach
A **Support Vector Machine (SVM) Model** was developed and evaluated to effectively identify offensive language within text data. 
The model leverages the **N-gram** technique for feature extraction, transforming raw text into a numerical representation that highlights key linguistic features. 
This representation is then fed into a **Linear Support Vector Classifier**, which accurately distinguishes between offensive and non-offensive language.

## Dataset and Tools
* A **dataset** of 14,200 annotated English tweets, labeled as Offensive or Not-offensive
* **TF-IDF Vectorizer** to extract the most informative features
* **Pipeline library** to facilitate the sequential nature of the process of extracting features and classifying
* The **Linear Support Vector Classifier** to classify each tweet/text as offensive or not-offensive
