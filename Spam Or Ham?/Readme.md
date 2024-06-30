# SMS Spam Classification

This project demonstrates a machine learning pipeline to classify SMS messages as either 'spam' 🚫 or 'ham' 🥪 (non-spam). The classification model is built using a combination of natural language processing techniques and a Naive Bayes classifier. The goal is to accurately identify and filter out spam messages, improving the user experience by reducing unwanted messages.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Libraries Used](#libraries-used)
4. [Data Preprocessing](#data-preprocessing)
5. [Feature Extraction](#feature-extraction)
6. [Model Training and Evaluation](#model-training-and-evaluation)
7. [Usage](#usage)
8. [Conclusion](#conclusion)

## Introduction

Spam 🚫 messages are a nuisance in our digital communications. This project aims to build a robust SMS spam classifier using machine learning. By processing and analyzing the content of SMS messages, the classifier can distinguish between spam and non-spam 🥪 messages with high accuracy.

## Dataset

The dataset used in this project is the "SMSSpamCollection," which contains 5,575 SMS messages labeled as either 'ham' 🍖 or 'spam' 🚫. The dataset is structured as follows:
- `Label`: The classification label ('ham' 🍖 or 'spam' 🚫)
- `Message`: The content of the SMS message

## Libraries Used

The following libraries are utilized in this project:
- `pandas`: For data manipulation and analysis
- `numpy`: For numerical operations
- `nltk`: For natural language processing tasks
- `scikit-learn`: For building and evaluating the machine learning model

## Data Preprocessing

Data preprocessing involves cleaning and preparing the text data for analysis. This includes:
- Removing punctuation and special characters
- Converting text to lowercase
- Tokenizing the text
- Removing stop words

## Feature Extraction

To convert text data into numerical features, we use:
- **Count Vectorization**: To count the frequency of each word in the messages
- **TF-IDF Vectorization**: To weigh the importance of each word in relation to the entire dataset

## Model Training and Evaluation

The machine learning model is trained using the Naive Bayes classifier. The evaluation metrics used to assess the model’s performance include:
- Accuracy
- Precision
- Recall
- F1 Score

## Usage

To use this project, follow these steps:
1. Clone the repository: `git clone https://github.com/yourusername/sms-spam-classification.git`
2. Navigate to the project directory: `cd sms-spam-classification`
3. Install the required libraries: `pip install -r requirements.txt`
4. Run the main script: `python main.py`

## Conclusion

This SMS spam classification project highlights the power of machine learning and natural language processing in filtering spam 🚫 messages. With accurate classification, users can enjoy a cleaner and more efficient messaging experience.

For further details or contributions, please refer to the [CONTRIBUTING.md](CONTRIBUTING.md) file.

---

*Created with 💙 by [Your Name](https://github.com/yourusername)*
