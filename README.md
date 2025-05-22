# Programming Language Detection from Code Snippets using ML

## Project Overview  
This project generates 250+ synthetic code snippets across several popular programming languages and trains a machine learning classifier to predict the language of any given code snippet. It uses NLP techniques like CountVectorizer combined with logistic regression for effective classification.

---

## Features  
- Automatic generation of diverse, realistic code snippets using randomized templates  
- Multi-language support: Python, C, Java, JavaScript, CSS  
- NLP-based feature extraction with CountVectorizer  
- Logistic Regression classifier for language detection  
- Easily extendable framework for adding more languages and templates  

---

## Dataset  
The dataset consists of 250+ synthetically generated code snippets per language, created using template patterns with random variables such as numbers, colors, and function names to simulate realistic code samples.

---

## Model Training & Evaluation  
- The text data is vectorized using CountVectorizer to extract meaningful features.  
- Logistic Regression is trained on the vectorized snippets to learn language-specific patterns.  
- The model’s accuracy and performance metrics are evaluated on a test set of unseen code snippets.

---

## How It Works  
1. Generate synthetic code snippets for each supported language.  
2. Vectorize snippets with CountVectorizer for NLP feature extraction.  
3. Train the Logistic Regression classifier on the dataset.  
4. Use the trained model to predict the language of new code snippets.

---

# 📧 Contact
Feel free to connect or collaborate: [bhoslesanskar@gmail.com // www.linkedin.com/in/sanskar-bhosle]
