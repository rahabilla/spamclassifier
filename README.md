Spam vs Ham Email Classifier
This project presents a binary text classification system designed to differentiate between spam and legitimate (ham) emails or messages using classic machine learning methods.

Features
Performs text preprocessing through tokenization, stopword elimination, and stemming.

Utilizes TF-IDF vectorization to transform text into numerical feature vectors.

Trains a Multinomial Naive Bayes model for classification.

Includes a Streamlit-powered web application for easy and intuitive message classification.

Offers sample spam and ham messages for instant testing.

Dataset
The model is trained using a publicly accessible spam dataset that includes the following columns:

label: Specifies whether a message is spam or ham.

text: Contains the email or SMS message body.

Installation
Begin by cloning the repository:

bash
Copy
Edit
git clone <repository_url>
cd spam-ham-classifier
Install the required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Usage
Train the Model
Execute the training script to preprocess the data, train the model, and save both the trained model and TF-IDF vectorizer:

bash
Copy
Edit
python spam_classifier.py
Launch the Streamlit Application
To run the interactive web interface:

bash
Copy
Edit
streamlit run streamlit_app.py
How to Use the App
Input an email or message in the provided text box.

Alternatively, use the sidebar to load example spam or ham messages.

Click on "Classify" to determine whether the message is spam or not.

Dependencies
Python 3.7 or higher

pandas

numpy

scikit-learn

nltk

streamlit

Notes
While the classifier performs effectively on balanced datasets, it may occasionally fail to detect certain spam messages. You are encouraged to enhance the model by trying out alternative algorithms or incorporating additional features.

License
This project is distributed under the MIT License and is open-source.
