# Restaurant Reviews Sentiment Analysis

## 📌 Overview
This project analyzes customer opinions about a restaurant using **Natural Language Processing (NLP)** and **Machine Learning**.  
The goal is to classify reviews as positive or negative and evaluate the model’s performance.

## 🚀 Steps Implemented
### 1. Data Handling
- Imported libraries: **NumPy**, **Pandas**, **Matplotlib**.
- Loaded the dataset of restaurant reviews.

### 2. Text Preprocessing
- Converted all text to lowercase.
- Removed punctuation and special characters.
- Tokenized reviews into words.
- Removed stopwords (common words with little meaning).
- Applied stemming to reduce words to their root form.
- Created a **Bag of Words** representation to transform text into numerical features.

### 3. Model Training
- Used **Naive Bayes classifier (MultinomialNB)** to train on the processed data.
- Split the dataset into training and testing sets.

### 4. Evaluation
- Measured **accuracy** of the model on the test set.
- Displayed performance metrics to evaluate classification results.

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

## 📂 Project Structure
- `Restaurant_Reviews_NLP.ipynb` : Main notebook with preprocessing, model training, and evaluation.
- `README.md` : Documentation file.

## 📈 Results
- The Naive Bayes model achieved good accuracy in classifying restaurant reviews.
- Demonstrated how text preprocessing improves model performance.

---

