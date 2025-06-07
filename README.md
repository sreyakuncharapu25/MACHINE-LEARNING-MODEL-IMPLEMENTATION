# MACHINE-LEARNING-MODEL-IMPLEMENTATION

*COMPANY* :CODETECH IT SOLUTION

*NAME*: KUNCHARAPU SREYA REDDY

*INTERN NO*: CT06DL136

*DOMAIN*: PYTHON PROGRAMMING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

##📌 Project: Spam Email Detection Using Scikit-Learn

This project focuses on building a spam email detection system using Python and Scikit-Learn, one of the most popular machine learning libraries. The goal is to create a predictive model that can classify whether a given message is spam or not based on its content. Spam messages are one of the major concerns in digital communication, and building an intelligent system to filter them is essential in maintaining productivity, privacy, and security.
In this project, we use a labeled dataset (spam.csv) containing thousands of messages marked as either “spam” or “ham” (not spam). The core idea is to train a Naive Bayes classifier that learns to distinguish between the two classes based on the textual features of the message.
We start with data preprocessing, which includes loading the dataset using Pandas, cleaning and preparing it by removing unwanted columns, and renaming them for clarity. The main columns used are v1 (label) and v2 (message text). Next, we convert the labels into binary format where "spam" becomes 1 and "ham" becomes 0, making it suitable for classification tasks.
Text data is inherently unstructured, so we use TF-IDF (Term Frequency-Inverse Document Frequency) vectorization to convert the text into numerical features. This allows the machine learning model to understand and learn patterns in the messages based on the frequency of words.
After transforming the data, we split it into training and testing sets and train a Multinomial Naive Bayes classifier, which is particularly effective for text classification problems. The trained model is then evaluated using metrics like accuracy, confusion matrix, and classification report, which include precision, recall, and F1-score. The results are promising, typically yielding accuracy over 95%, showing that the model is effective in detecting spam messages.
Once the model is trained and tested, we use Python’s pickle module to serialize and save both the model and the TF-IDF vectorizer so that they can be reused without retraining. A separate prediction script (predict_spam.py) is created to allow users to input a message and receive a simple output: "Spam" or "Not Spam". This script loads the saved model and vectorizer and predicts the result in real-time.
To make the project more user-friendly and visually appealing, we also developed a basic frontend using HTML and CSS. The interface allows users to interact with the spam detection system by typing messages into a chat-style UI and receiving instant classification responses.
This project demonstrates the real-world application of Natural Language Processing (NLP) and machine learning in automating a common and practical task. It also showcases how data preprocessing, feature extraction, model training, and deployment come together in a seamless pipeline.
Overall, the Spam Detection project is a valuable implementation for understanding how to work with text data, build predictive models, and make them accessible through a user interface. It serves as a great learning experience for beginners and a solid base for expanding into more advanced NLP tasks in the future.


##OUTPUT:

![Image](https://github.com/user-attachments/assets/07ea022d-23c1-4a9f-8412-603de25e3b50)



![Image](https://github.com/user-attachments/assets/cc2de7a7-c835-478d-9dfa-3729091b1040)

