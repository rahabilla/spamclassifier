# Spam vs Ham Email Classifier

This project implements a binary text classification system aimed at distinguishing between spam and legitimate (ham) emails or messages by using traditional machine learning approaches.

## Features

- Preprocesses email text by performing tokenization, removing stopwords, and applying stemming.  
- Converts text into numerical features using TF-IDF vectorization.  
- Trains a Multinomial Naive Bayes classifier on the prepared dataset.  
- Provides an easy-to-use Streamlit web application for interactive message classification.  
- Includes example spam and ham messages for quick testing and demonstration.

## Dataset

The classifier is trained on a publicly available spam dataset containing two main columns:

- `label`: Indicates whether a message is spam or ham.  
- `text`: Contains the content of the email or SMS message.

## Installation

Clone the repository:

Install the necessary dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Usage
Train the Model
Run the training script to preprocess the data, train the classifier, and save both the trained model and the TF-IDF vectorizer:

bash
Copy
Edit
python spam_classifier.py
Run the Streamlit App
Start the interactive web app to classify messages:

bash
Copy
Edit
streamlit run streamlit_app.py
How to Use the App
Enter any email or message text in the input box.

Alternatively, use the sidebar buttons to load sample spam or ham messages.

Click the Classify button to see if the message is spam or ham.

### Dependencies
Python 3.7 or higher

pandas

numpy

scikit-learn

nltk

streamlit

Notes
The classifier performs well on balanced datasets but might occasionally miss some spam messages. You are encouraged to experiment with other algorithms or add features to improve the model’s performance.

License
This project is open source and distributed under the MIT License.
