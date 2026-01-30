# Imitating-Fakespot

**Name:** Hiya Modi

**Student ID:** 202301011

**Course:** Deep Learning

---

## Project Overview
This project focuses on applying **Natural Language Processing (NLP)** techniques to analyze e-commerce product reviews. The main goals are:

1. Represent textual reviews numerically using vectorization techniques.  
2. Build machine learning models for classification tasks:  
   - **Product category prediction** (multiclass classification)  
   - **Fake review detection** (binary classification)  
3. Explore patterns in fake reviews using visualization techniques like **Word Clouds**.  

The project demonstrates how textual data can be transformed and utilized for predictive modeling in real-world scenarios.

---

## Dataset
The dataset consists of user reviews from multiple e-commerce product categories. Each review contains:

- **Product Category:** Label indicating the product type.  
- **Review Authenticity:** Label specifying whether the review is **fake** or **genuine**.  

Dataset Source: [https://doi.org/10.1016/j.jretconser.2021.102771](https://doi.org/10.1016/j.jretconser.2021.102771)

---

## Methodology

1. **Text Preprocessing & Vectorization**  
   - Cleaned and normalized review text (removing punctuation, stopwords, etc.)  
   - Converted text into numerical form using **TF-IDF vectorization**  

2. **Product Category Classification**  
   - Trained a **multiclass classifier** on vectorized reviews  
   - Evaluated model using metrics such as accuracy, precision, recall, and F1-score  

3. **Fake Review Detection**  
   - Built a **binary classification model** to detect fake reviews  
   - Analyzed model performance using relevant metrics  

4. **Word Cloud Generation**  
   - Extracted the most influential words in fake reviews  
   - Visualized prominent terms using Word Clouds to identify patterns in fake reviews  

---

## Key Findings
- Vectorized textual reviews can effectively predict product categories and detect fake reviews.  
- Certain words or phrases appear frequently in fake reviews, which can be visually identified through Word Clouds.  
- The project highlights the importance of **text representation** and **feature extraction** in NLP-based classification tasks here.

---

## Conclusion
This project demonstrates how **deep learning and NLP** can be applied to analyze textual data, perform classification, and gain insights into user reviews. It provides practical experience in preprocessing, vectorization, modeling, and result interpretation for real-world datasets.


