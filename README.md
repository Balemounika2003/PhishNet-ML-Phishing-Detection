PHISHNET

## AI-Powered Phishing Detection System
PHISHNET is an intelligent cybersecurity solution designed to identify phishing attacks across multiple
communication channels. By leveraging machine learning algorithms and real-time analysis, the system helps
users detect and avoid potentially harmful websites, emails, and SMS messages before they can cause
damage.

## Features

Core Workflow

Data Collection & Training:
The system utilizes curated datasets containing legitimate and phishing URLs, emails, and SMS messages.
These datasets are preprocessed and used to train machine learning models capable of identifying malicious
patterns.

Threat Detection Engine
PHISHNET analyzes user-provided URLs, email content, and SMS messages using trained machine learning
models. The system evaluates various features and classifies the input as either safe or phishing.

Real-Time Protection
Users receive instant feedback regarding the legitimacy of the submitted content. This helps prevent credential
theft, financial fraud, and unauthorized access caused by phishing attacks.

Platform Features
• URL Phishing Detection
The URL detection module analyzes website links using multiple features such as URL structure,
suspicious keywords, and domain characteristics to identify phishing websites.

• Email Phishing Detection
The email detection module examines email content and identifies suspicious phrases, phishing patterns,
and deceptive messages commonly used by attackers.

• SMS Spam & Phishing Detection
The SMS detection module classifies incoming messages as legitimate or malicious by analyzing spam
keywords and phishing indicators used in smishing attacks.

• Unified Detection Platform
PHISHNET provides a single platform capable of detecting phishing attempts through URLs, Emails, and
SMS messages, making cybersecurity management simple and effective.

• Machine Learning-Based Analysis
The system employs machine learning algorithms to improve detection accuracy and identify patterns that
traditional rule-based systems may fail to recognize.

## Tech Stack

Programming Language
• Python

Machine Learning Libraries
• Scikit-Learn
• Pandas
• NumPy

Algorithms
• Random Forest Classifier
• Gradient Boosting Classifier
• Naive Bayes Classifier

Frontend Technologies
• HTML5
• CSS3

Development Environment
• Jupyter Notebook
• Visual Studio Code

Model Storage
• Pickle (.pkl)
• Joblib (.joblib)

Prerequisites

Before running the project, ensure the following software is installed:
• Python 3.x
• Jupyter Notebook
• Required Python Libraries
• Web Browser

Install required packages:
pip install -r requirements.txt

Installation

1. Clone the repository:
git clone https://github.com/Balemounika2003/PHISHNET.git
2. Navigate to the project directory:
cd PHISHNET
3. Install all dependencies:
pip install -r requirements.txt
4. Start the application:
python feature.py
After launching the application, users can test:
• URL Phishing Detection
• Email Phishing Detection
• SMS Spam Detection
The system instantly predicts whether the provided input is safe or malicious.


Project Structure

PHISHNET/
├── Source Code/
│   └── feature.py                      # Main application logic
│
├── Machine Learning Models/
│   ├── model.pkl                       # Phishing detection model
│   ├── vectorizer.joblib               # URL vectorizer
│   └── sms_vectorizer.joblib           # SMS vectorizer
│
├── Datasets/
│   ├── phishing.csv                    # URL phishing dataset
│   ├── spam.csv                        # Email spam dataset
│   └── sms.csv                         # SMS spam dataset
│
├── Jupyter Notebooks/
│   ├── phishingURL.ipynb               # URL phishing model training
│   └── spamSMS.ipynb                   # SMS spam model training
│
├── Frontend/
│   ├── index.html                      # Home page
│   ├── landing.html                    # Landing page
│   ├── login.html                      # User login page
│   ├── signup.html                     # User registration page
│   ├── emailSpam.html                  # Email phishing detection page
│   ├── spamSMS.html                    # SMS spam detection page
│   ├── contactus.html                  # Contact page
│   ├── style.css                       # Main stylesheet
│   └── styles.css                      # Additional styling
│
├── Assets/
│   ├── attack.jpg                      # Project image
│   ├── contact.jpg                     # Contact page image
│   ├── bg1.png                         # Background image
│   ├── bg5.png                         # Background image
│   └── phishing.png                    # Phishing illustration
│
└── README.md                           # Project documentation

   
## Project Objectives
• Detect phishing websites before users interact with them.
• Identify malicious emails designed to steal sensitive information.
• Detect spam and phishing SMS messages in real time.
• Improve cybersecurity awareness and protection.
• Provide a unified platform for multi-channel phishing detection.

## Results

PHISHNET successfully detects phishing attempts across different communication channels using machine
learning techniques and feature-based analysis.
The system can identify phishing URLs, detect malicious emails, classify SMS messages, and provide real-time
predictions through an easy-to-use web interface.

## Future Enhancements
• Browser Extension Integration
• Real-Time Threat Intelligence Feeds
• Deep Learning-Based Detection Models
• Multi-Language Support
• Mobile Application Development
• Cloud Deployment
