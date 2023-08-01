# OIBSIP-Task-4-EMAIL-SPAM-DETECTION-WITH-MACHINE-LEARNING

Data Collection and Preprocessing: Collect a labeled dataset of emails (spam and non-spam) and preprocess the data as mentioned in the previous response.

Feature Extraction: Extract relevant features from the preprocessed data using techniques like Bag-of-Words, TF-IDF, or Word Embeddings.

Train the Model: Split the dataset into training and testing sets, then train your ML model on the training data.

Model Evaluation: Evaluate the trained model's performance on the testing dataset to ensure it's working effectively.

Create a Flask Web App: Now, you'll create a Flask web application to demonstrate the spam detection. Ensure you have Flask installed in your Python environment.

Design the Web App: Create an HTML form where users can input their email content for spam detection. The form should have an input box for the email text and a button to submit the form.

Handle Form Submission: In the Flask app, handle the form submission. Extract the email content from the form and pass it through your trained ML model for spam detection.

Display Result: Once the model predicts whether the email is spam or not, display the result on the web page to the user.

Here's a sample code to help you get started:

Install Flask:
Make sure you have the trained model saved as 'spam_detection_model.pkl' in the same directory as the app.py file.

Run the Flask app:


python app.py
Your Flask web app will now be accessible at http://localhost:5000. Users can input their email content into the form, and the app will use the trained model to predict whether the email is spam or not, displaying the result on the web page.





