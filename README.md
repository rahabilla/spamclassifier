
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

Dependencies
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
