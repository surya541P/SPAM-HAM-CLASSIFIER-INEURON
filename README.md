# Spam Ham Classifier

Nowadays, most people have access to the Internet, and they cannot survive without Smartphone and computers. They not only use the Internet for fun and entertainment, but they also use it for business, stock marketing, searching, sending e-mails, and so on. Hence, the usage of the Internet is growing rapidly. 

One of the threats for such technology is a spam. Spam has a lot of definitions, as it is considered one of the complex problems in e-mail services. Spam is a junk mail/message, or an unsolicited mail/message. Spam e-mails are also those unwanted, unsolicited e-mails that are not intended for a specific receiver. It is basically an online communication sent to the user without permission. It takes on various forms like adult content, selling products or services, job offers, and so forth. The spam has increased tremendously in the last few years.
 
The good, perfect, and official mails are known as ham. It is also defined as an e-mail that is generally desired.
Today, more than 85% of mails or messages received by users are spam. It costs the sender very little time to send, but most of the costs are paid by the recipient or the service providers rather than by the sender. 

The cost of spam can also be measured in lost human time, lost server time and loss of valuable
mail/messages. The sent mail reserves a quota in the server, and the receiver may have a limited space, causing the server to reject another ham mail because it is out of space. Moreover, the reader may lose a lot of time
in reading unuseful messages. 

The Machine Learning field has a robust, ready-made and alternative way for solving this type of the problem.
We have used the power of Machine Learning and built a classifier, which helping us to classify which message is/are spam or ham depending upon their content. 


# WebApp Link

App link 1: 

https://spamhamprediction.herokuapp.com/

App link 2: 

https://spamhampredictioncicd.herokuapp.com/

Note: In link 2 CI-CD pipeline has been integrated using CircleCI


# Technical Aspects

- Python 3.7 and more
- Important Libraries: sklearn, pandas, numpy, matplotlib & seaborn
- Front-end: HTML, CSS
- Back-end: Flask framework
- IDE: Jupyter Notebook, Pycharm & VSCode
- Database: MongoDB
- Deployment: Heroku
- CI-CD Pipeline: CircleCI
- UnitTest Case: Pytest
- Version Control Sysytem: Git
- Remote Repository: Github
- Containerization: Docker

# How to run this app
Code is written in Python 3.7 and more. If you don't have python installed on your system, click here https://www.python.org/downloads/ to install.

Create virtual environment - conda create -n myenv python=3.7
Activate the environment - conda activate myenv
Install the packages - pip install -r requirements.txt
Run the app - python app.py

# User Interface

#### A very simple UI where text area is provided. In this text area, User need to write their message into this text area and then they can classify their message by clicking on predict button.

# Workflow

## Data Collection
Spam Ham Data Set from UCI Machine Learning Repository.

Link:https://archive.ics.uci.edu/ml/datasets/sms+spam+collection

## Data Cleansing
- Drop unnecessary columns.
- Drop duplicates rows from dataset.
- Rename required columns.
- Encode target column using LabelEncoder.

## Text Preprocessing
- LowerCase
- Tokenization
- Removing Special Characters
- Removing stop words and punctuation
- Stemming

## Model Creation and Evaluation
- Various classification model created. 
- Algorithms used are Naive Bayes, Logistic Regression, DecisionTreeClassifier,RandomForestClassifier, AdaBoostClassifier, Bagging Classifier etc.
- Multinomial naive_bayes classiifer has given good accuracy and precision.
- Model performance evaluated based on accuracy, precision.

## Model Deployment
- Final Model selected is deployed over Heroku cloud environment using WebApp created from Flask framework.

# Author
surya pranav: https://www.linkedin.com/in/suryapranavt/

# Help Me Improve
Hello Reader if you find any bug please consider raising issue I will address them asap.
# SPAM-HAM-CLASSIFIER-INEURON
