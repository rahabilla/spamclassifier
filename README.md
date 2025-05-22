# Spam vs Ham Email Classifier

This project presents a binary text classification system designed to differentiate between spam and legitimate (ham) emails or messages using classic machine learning methods.

## Features

- Performs text preprocessing through tokenization, stopword elimination, and stemming.  
- Utilizes TF-IDF vectorization to transform text into numerical feature vectors.  
- Trains a Multinomial Naive Bayes model for classification.  
- Includes a Streamlit-powered web application for easy and intuitive message classification.  
- Offers sample spam and ham messages for instant testing.

## Dataset

The model is trained using a publicly accessible spam dataset that includes the following columns:

- `label`: Specifies whether a message is spam or ham.  
- `text`: Contains the email or SMS message body.

## Installation

Begin by cloning the repository:

```bash
git clone <repository_url>
cd spam-ham-classifier

