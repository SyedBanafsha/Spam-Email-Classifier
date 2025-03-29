**Spam Email Classifier**
Project Overview:
This project is a **Spam Email Classifier** that uses **Natural Language Processing (NLP) and Machine Learning** to differentiate between spam and non-spam (ham) emails. The model is trained on a dataset of labeled emails and achieves an accuracy of **96.6%**.

**Dataset:**

The dataset contains email messages labeled as either:

**0 (Ham):** Not spam

**1 (Spam):** Unwanted promotional or fraudulent messages

**Dataset Source:** The dataset is stored in the data/spam.csv file in this repository.

**Technologies Used**

**Python** 

**Pandas & NumPy** for data manipulation

**Scikit-learn** for Machine Learning

**TfidfVectorizer** for text preprocessing

**Naive Bayes (MultinomialNB)** for classification

**Installation & Setup:**

Clone this repository:

git clone https://github.com/SyedBanafsha/Spam-Email-Classifier.git
cd Spam-Email-Classifier

**Install required libraries:**

pip install -r requirements.txt

Run the script:

python src/spam_classifier.py

**Project Workflow**

Data Preprocessing: Cleaning and transforming text data using TF-IDF Vectorization.

Model Training: Training a Naive Bayes classifier on the dataset.

Evaluation: Checking accuracy, precision, recall, and F1-score.

Prediction: Classifying new email messages as spam or ham.

**Model Performance**

Accuracy: 96.6%

Precision: 98% (on average)

F1-score: 92%

**Sample Output:**

![Screenshot 2025-03-29 143814](https://github.com/user-attachments/assets/19f691b3-c910-4205-8c22-79f598230710)


**Real-World Applications**

**Filtering spam emails in email services like Gmail & Outlook.**

**Preventing phishing scams.**

**Automating email categorization in businesses.**

Contributing

Contributions are welcome! To contribute:

Fork this repository.

Create a new branch (feature-branch).

Commit your changes.

Push to your branch.

Create a pull request.

**License**

This project is licensed under the MIT License.

**Author**

Developed by Syed Banafsha 🔗 

GitHub: https://github.com/SyedBanafsha/Spam-Email-Classifier.git🔗 

LinkedIn: https://www.linkedin.com/in/syed-banafsha-2492b3283 🔗

Feel free to contribute, suggest improvements, or ask questions!
