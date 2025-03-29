Spam Email Classifier

Project Overview

This project is a Spam Email Classifier that uses Natural Language Processing (NLP) and Machine Learning to differentiate between spam and non-spam (ham) emails. The model is trained on a dataset of labeled emails and achieves an accuracy of 96.6%.

Dataset

The dataset contains email messages labeled as either:

0 (Ham): Not spam

1 (Spam): Unwanted promotional or fraudulent messages

Dataset Source: Spam.csv

Technologies Used

Python 

Pandas & NumPy for data manipulation

Sklearn (Scikit-learn) for Machine Learning

TfidfVectorizer for text preprocessing

Naive Bayes (MultinomialNB) for classification

Installation & Setup

Initializing the Repository

Clone this repository:

git clone https://github.com/yourusername/spam-email-classifier.git
cd spam-email-classifier

Initialize Git & Add .gitignore:

git init
echo "__pycache__/" >> .gitignore
echo "*.csv" >> .gitignore
git add .
git commit -m "Initial commit"

Installing Dependencies

Install required libraries:

pip install pandas numpy scikit-learn matplotlib seaborn

Running the Script

Run the spam classifier script:

python spam_classifier.py

Project Workflow

Data Preprocessing: Cleaning and transforming text data using TF-IDF Vectorization.

Model Training: Training a Naive Bayes classifier on the dataset.

Evaluation: Checking accuracy, precision, recall, and F1-score.

Prediction: Classifying new email messages as spam or ham.

Model Performance

Accuracy: 96.6%

Precision: 98% (on average)

F1-score: 92%

License

This project is licensed under the MIT License. You are free to use, modify, and distribute this code with proper attribution.

Real-World Applications

Filtering spam emails in email services like Gmail & Outlook.✅ Preventing phishing scams.✅ Automating email categorization in businesses.

Author

Developed by Syed Banafsha 🔗 GitHub: https://github.com/SyedBanafsha/Spam-Email-Classifier.git 🔗 LinkedIn: Syed Banafsha

Feel free to contribute, suggest improvements, or ask questions! 
