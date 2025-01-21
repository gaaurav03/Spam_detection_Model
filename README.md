Spam Detection Classifier

A machine learning-based Spam Detection Classifier built using the Multinomial Naive Bayes algorithm. This project achieves a remarkable 98% accuracy and 1.0 precision, making it highly reliable for detecting spam messages.

Table of Contents

Overview

Features

Dataset

Model

Installation

Usage

Results

Contributing

License

Overview

This project aims to classify SMS messages as Spam or Ham (non-spam) using a text-based classification approach. It leverages data preprocessing techniques and the Multinomial Naive Bayes algorithm to achieve high performance. The implementation follows a structured and modular approach, ideal for learning and production use.

Features

High Accuracy: Achieves 98% accuracy in classifying spam messages.

High Precision: Perfect precision score of 1.0, indicating no false positives.

Data Preprocessing: Includes tokenization, stop word removal, stemming, and more.

Visualization Tools: Displays insights into the dataset through word clouds and plots.

Dataset

The project uses a public dataset containing SMS messages labeled as spam or ham.

The dataset undergoes various cleaning and preprocessing steps to enhance performance.

Model

The model employs Multinomial Naive Bayes, a popular algorithm for text classification tasks.

Key Techniques

Text Preprocessing: Lowercasing, removing punctuation, tokenization, and stemming.

Feature Extraction: Using term frequency-inverse document frequency (TF-IDF).

Training and Validation: Split the dataset into training and testing sets.

Installation

Clone the repository:

git clone https://github.com/yourusername/spam-detection-classifier.git
cd spam-detection-classifier

Install dependencies:

pip install -r requirements.txt

Usage

Load the dataset into the project directory.

Run the script to train the model and evaluate performance:

python train_spam_classifier.py

Use the saved model to classify new messages:

python predict_message.py "Your message here"

Results

Accuracy: 98%

Precision: 1.0

Example Output

Message

Predicted Label

"Win a $1000 gift card now!"

Spam

"Hello, how are you?"

Ham

Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any features or improvements.

License

This project is licensed under the MIT License. See the LICENSE file for more details.
