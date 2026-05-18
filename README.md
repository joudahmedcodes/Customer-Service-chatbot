# Intelligent FAQ Chatbot using NLP & Machine Learning
An NLP-powered chatbot built using Python, TF-IDF vectorization, and Logistic Regression for intent classification. The chatbot preprocesses user input, predicts intent categories, and responds through an interactive Gradio interface.

## Features

- NLP text preprocessing
- Tokenization and stemming
- Stopword removal
- TF-IDF vectorization
- Intent classification using Logistic Regression
- Unknown input detection
- Interactive chatbot GUI using Gradio

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Gradio
- Matplotlib

## Workflow

1. Load and clean dataset
2. Preprocess text
   - Lowercasing
   - Tokenization
   - Stopword removal
   - Stemming
3. Convert text using TF-IDF
4. Train Logistic Regression model
5. Predict user intent
6. Generate chatbot response
7. Display through Gradio interface

## Model Performance

- Model: Logistic Regression
- Vectorizer: TF-IDF
- Accuracy: 96.64%

## Future Improvements

- Deploy as a web application
- Convert model to TensorFlow Lite
- Add speech recognition
- Improve intent detection
- Add deep learning models
- Connect to a database
- Deploy using Flask or FastAPI
- Add multilingual support
